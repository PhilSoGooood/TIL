# list_sort_and_sorted

> list에서 정렬 방법 중 sort와 sorted의 차이



### 1. sort

```python
list_name.sort()
# 기존의 리스트를 아예 바꾸어 버림. 따라서 print(list_name)하는 경우 정렬된 리스트가 출력된다.
```



### 2. sorted

```python
sorted(list_name)
# 기존 리스트를 변경하지 않은채 정렬된 리스트를 보여줌. 따라서 정렬된 리스트를 사용하고자 하는 경우 별도의 변수에 할당해주어야 한다. 
new_list = sorted(old_list)
```

