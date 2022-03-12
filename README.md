t=int(input())
```python
for aaa in range(t):
    a,b=map(int,input().split())
    if a>b:
        if (a-b)%2==0:
            print(1)
        else:
            print("2")
    elif a<b:
        if (b-a)%2!=0:
            print("1")
        else:
            print("2")
    else:
        print("0")# Add-Odd-or-Subtract-Even
```
