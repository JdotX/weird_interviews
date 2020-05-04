# Python Interview Questions

## 1. Mutable and immutable types. 

In python everything is an object. There are two types of objects, namely mutable and immutable ones. The two types differs when being assigned a new value. Mutable types executes the operation on the original memory addresses directly. Immutable types will be re-assigned with a new address, while the contents of original address is not affected. 

```python
a = 1
b = a # share same address
b = 2 # Assign address of 2 to b, doesn't affect a

a = [1]
b = a # share same address
b.append(2) # Append on original 
```

I have a video explaining the concept in Chinese: https://www.bilibili.com/video/BV1EV411o7jC/
