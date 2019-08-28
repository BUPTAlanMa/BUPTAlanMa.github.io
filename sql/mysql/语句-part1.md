------
[hackerrank](https://www.hackerrank.com/domains/sql)
- 查询ID为偶数的且不重复的city名称，从STATION表
```
SELECT DISTINCT CITY FROM STATION WHERE MOD(ID, 2) = 0 
```
