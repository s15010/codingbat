#codingbat

##warmup-1

###sleep_in 

weekdayがfalseのときまたvacationがtrueのときにtrueをかえして
それ以外はfalseをかえす

```
　　　def sleep_in(weekday, vacation):
  　　　　if not weekday or vacation:
    　　　　return True
 　　　　 else:
   　　　　　return False
```

###monkey_trouble

asmileとbsmileが両方ともtrueまたは両方ともfalseのときはtrueをかえし
それ以外はfalseをかえす

```
　　def monkey_trouble(a_smile, b_smile):
  　　if a_smile and b_smile:
   　　 return True
  　　if not a_smile and not b_smile:
    　　return True
　　  return False
```


###sum_double

aとbの値が同じの時はaとの合計の２倍をかえして
それ以外の時は合計かえす

```
　　def sum_double(a, b):
   　　sum = a + b
   　　if a == b:
     　　sum = sum * 2
   　　return sum
　　
```

###diff21

２１とnの差分を絶対値でかえす、nが２１以上の時は差分２倍をかえす

```
def diff21(n):
  if n <= 21:
    return 21 - n
  else:
    return (n - 21) * 2

```

###parrot_trouble

hourが7未満か20以上なおかつtakingがtrueの時に
trueをかえしてそれ以外はfalseをかえす

```
　　def parrot_trouble(talking, hour):
　　　return (talking and (hour < 7 or hour > 20))
```
###makes10

aとbの合計が10,またはaが10もしくはbが10の時
にtrueをかえしそれ以外はfalseをかえす

```
　　def makes10(a, b):
  　　　 return (a == 10 or b == 10 or a+b == 10
```

###near_hundred

100または200との差分の絶対値が10以下の場合は
trueをかえしそれ以外はfalseをかえす

```
　　def near_hundred(n):
  　　　return ((abs(100 - n) <= 10) or (abs(200 - n) <= 10))
```

###pos_neg
###not_string
###missing_char
###front_back

















