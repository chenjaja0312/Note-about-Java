# Note-about-Java
### DataTypeVariable 資料型態 
1. 整數 : byte (-128-127), short (-32768-32768), **int** (-2147483648-2147483647), long (-9223372036854775808-9223372036854775808)  
2. 浮點數 : float (到小數點下7位), **double** (到小數點下15位)  
3. 布林值 : boolean (true/false)  
4. 字元 : char ('')  
5. 字串 : String("")  

### 變數 (儲存資料的名稱 取有意義的)
steps:
- 宣告變數
   - 語法: 資料型態 變數名稱 (e.x. int x) 
- 指定資料(把資料放進變數裡)
   - 宣告變數、同時指定資料 int x=3; (資料型態 變數名稱=資料)  
   - 先宣告變數、再指定資料 double y; (資料型態 變數名稱)
     y=3.5 (變數名稱=資料)
- 使用變數(代替資料)  
   - 印出資料 System.out.println(任意資料);  

### DataTypeConversion 資料型態轉換
1. 範圍: double>float>long>int>short>byte
- 小->大: 自動轉換
- 大->小: error
2. 字串-> 數字
- 轉成int型態: Integer.parseInt("字串")
- 轉成long型態: Long.parseLong("字串")
3. 數字-> 字串
- String.valueOf(數字)

### Operator 運算符號
1. 算術 (注意資料型態)
  +-*/、取餘數:% (int、double)
2. 指定
  = += -= *= /= %=
3. 比較 (結果: T/F)
  大小 > < >= <=
是否相等 == !=
5. 單元(針對單一資料做操作)
  ++(加一) --(減一)  !(布林值反轉)
6. 邏輯(結果: T/F)
  &&(且) ||(或: 有一個true就T)
7. 位元
  暫不討論
  
  



