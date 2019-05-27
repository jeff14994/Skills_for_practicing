# Linux Practice
#### 1080314
***
# 1. Linux基本輸入輸出
## Cat
> cat > myfile.txt
>>用鍵盤輸入的資料匯處存入myfile.txt

> cat > myfile.txt < test.txt
>>從test.txt匯入資料

> cat > myfile.txt << eof
>>若輸入的關鍵字是eof時停止輸入資料

## Grep

- -n 代表顯示line

- ＄PATH —>執行檔搜尋的路徑
- 刪除前後
1. ctrl u —>向前全刪
2. ctrl k —>向後全刪
3. ctrl + a —> 到最前面
4. ctrl + e —>到最後MM面M

# 2. Bash Script
> shebang
1. #! /bin/bash
2. #! /bin/less —> 可以直接使用該程式執行此script

## 系統變數
- $1 —>回傳第一個參數
- $@ —>回傳所有參數
- $# —>回傳參數個數
## 設定變數
- a=“abc"

## 顯示變數
- echo **$** a
## 測試
test $a
[ 空格**變數**空格**判斷式**空格**變數**空格]

- echo $? —> 0 (表示a存在非空字串)  —>1(表存在空字串)
- 速記：有字串：0; 沒字串：1 
- 小白：0表 yes(圈圈)
- [ 12 -eq 13]
## 比較
- 字串
- 整數
- file
- 多個判斷式

**多個判斷式：** 
1. 且：expression -a expression
2. 或：expression -o expression

