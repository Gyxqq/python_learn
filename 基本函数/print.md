# print()
## print(value, ..., sep=' ', end='\n', file=sys.stdout, flush=False)
- sep 为输出元素之间的间隔字符，如设置sep='#',则输出会以#间隔  
- end 为输出结尾的字符，'\n'表示结尾输出换行符，如改为end=''则不会输出任何字符 
 - file 一个流，在默认情况下是sys.stdout即标准输入输出流，会将结果打印到屏幕，也可以是一个文件流 
- flush 是否强制刷新输出流，可为True 或者 False 

## e.g.:
```python
print(1,2,3,sep='0',end='#') 

print("2342","234",sep='\t',end='') 
````
[点击这里试一试](https://gyxqq-crispy-bassoon-979qvpq9jgpcpxg6.github.dev/)