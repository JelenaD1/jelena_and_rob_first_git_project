# My 4 Favorite Ruby Methods
### zero? 
Returns a true boolean if the Float returns 0. Otherwise, it returns false.
```
0.0.zero? #=> true
3.829.zero? #=> false

```
### next_year
This method is called on Ruby Date object and it returns that date one year in the future.
```
Date.new(2014, 8, 9).next_year
```

### .nil?
This method can be called on any Ruby Object and returns a boolean if that object is nill or not.
```
"string".nill?
```

### include?
This method can be called on any Ruby Object and returns true if there is an eniviroment variable with that given name. 
```
ENV.replace('foo' => '0', 'bar' => '1')
```

