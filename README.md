迴圈


for迴圈
```java=
for(int i =5,k=1 ; i < 5 && k >1 ; i++,k++ ){
    System.out.println(i+":"+k);
}
```
while迴圈
```java=
int i = 1;
        
while(i <= 10){
   System.out.print(i+" ");
        i++;
 }
   System.out.println();
```
do while迴圈 條件不成立會執行一次
```java=
int x = 0;
        
 do{
   System.out.print(x+" ");
    x--;
}while(x >=1);
```
印出 0

```java=
int x = 10;
 while(x < 9){
    System.out.println("While");
     }
        
 do{
    System.out.println("do while");
}while(x <9);
```
印出 do while

while 迴圈 製作9x9表
```java=
int i =1;
        
while(i <=9){
int k =2;
while(k <=9){
    System.out.printf("%d*%d=%2d ",i,k,i*k);
    k++;
        }
    i++;
    System.out.println();
        }
```