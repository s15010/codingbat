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
###parrot_trouble
###makes10
###near_hundred
    
