### main
```
int main()
    make an int array with 9 values
    print "Before:"
    call printValue with the array
    make int x = 3 and int y = 5
    print x and y
    call swap with the address of x and the address of y
    print x and y again
    call sort with the array
    print "After:"
    call printValues with the array
    return 0
```

### swap
```
void swap(int*a, int*b)
    take two int pointer parameters
    make a temporary integer called temp
    copy the value at a to temp
    copy the value at b to a
    copy temp to b
    return temp to b
```

### sort
```
void sort(int*)
    take an int pointer representing the array
    make int i and int j
    for i from 0 up to MAX
        for j from 0 up to MAX -1
            if the number at j is bigger than the number at j + 1
                call swap with the address of j and the address of j + 1
                cal printValues with the array
    return void
```
