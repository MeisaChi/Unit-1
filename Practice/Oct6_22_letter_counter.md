# Practice

```.py
def count_letter(message:str,letter:str)->int:
    count=0
    for i in range(len(message)):
        if message[i]==letter:
            count += 1
        else:
            pass
    return count
test1 = count_letter(message="hello",letter="e")
print(test1)
test2 = count_letter("apple","p")
print(test2)
```

![](https://github.com/MeisaChi/Unit-1/blob/main/Screenshots/Practice10-06-22.png)
