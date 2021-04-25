# python 20210425
## 3rd
    arr="96028 64634 90265 94205 39894 92797 40344 86568 84897 9062 11007 42670 12116 77477 89875 73861 40636 69768 36098 27424 99319 61332 52341 56201 92637 14511 23102 50781 20131 86219 16469 16654 39291 4952 50242 22044 77842 4497 44260 59080 85250 44082 58804 69952 63988 70636 67058 77109 54130 53647 42396 89756 41194 30240 80693 4011 46293 38741 48388 9427 16423 17777 51716 47410 32187 25995 85285 65480 7974 7803 36451 15707 19815 69730 75307 69451 34990 3289 44694 7276 32712 30352 38554 87795 75248 99558 52795 44572 56307 26990 47342 2397 2761 89173 69788 11166 18730 31812 13923 66268"
arr=arr.split(' ')
for i in arr:
	i=int(i)
MySort=[0,0,0]
count=0
while (MySort[2]==0):
	MyMaX=arr[0]
	for i in arr:
		if (i>=MyMaX)and(i!=MySort[0])and(i!=MySort[1]): 
			MyMaX=i
	MySort[count]=MyMaX
	count+=1
print(MySort[2])

## count
    from pwn import *

    ip="140.110.112.22"
    port=2403
    r=remote(ip,port)
    for i in range(1,101):
        r.recvuntil("?")
        r.sendline(str(i))
    r.interactive() 

## hello world
![image](https://github.com/eweakagay/python20210425/blob/main/unnamed.png)

## base64
    https://www.base64decode.org/

## ascii
    http://www.unit-conversion.info/texttools/ascii/

## base32
    https://cryptii.com/pipes/base32

## morse code
    https://morsecode.world/international/translator.html

## 第一堂base64編碼
    https://www.base64decode.org/

