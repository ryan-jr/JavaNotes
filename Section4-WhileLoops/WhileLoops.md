# KByte Java Lectures

## Section 4 - While Loops

### Lesson 1 - 0-9

```
construct a while loop that outputs 0-9
```

```java

// commenting for while loops

int i = 0;

while ( i <= 9 ) {
    
    println(i);
    i++;
    
}

```

***

### Lesson 2 - 0-20 by 2

```
construct a while loop that prints the numbers 0 to 20 by steps of 2

```

```java 
// comment for while loop by 2

int i = 0;

while( i <= 20 ) {
    
    println( i );
    i += 2;
    
}
```

***

### Lesson 3 - -30 to 30 by 3

```
Write a while loop that prints the numbers from -30 to 30 by steps of 3 
```

```java

// commenting for while loop by steps of 3

int i = -30;

while ( i <= 30 ) {
    
    println( i );
    i += 3;
    
}

```

***

### Lesson 4 - 10 to -10

```
Write a while loop that prints the numbers from 10 to -10
```

```java
int i = 10;

while ( i >= -10 ) {
    
    println( i );
    i -= 1;
    
}
```

***

### Lesson 5 - 2 to 1024

```
Write a while loop that goes from 2 to 1024 where each number is double the previous one. Example: 2,4,8,16,32,64,...024 
```

```java

int i = 2;

while ( i <= 1024 ) {
    
    println( i );
    i *= 2;
    
}

```

***

### Lesson 6 - 1024 to 2

```
Write a while loop that goes from 1024 to 2 where each number is the half of the previous one. Example: 1024,512,256,...2 

```

```java

int i = 1024;

while ( i >= 2 ) {
    
    println( i );
    i = i / 2;
    
}

```

***

### Lesson 7 - 0 to 9 on one line

```
Write a while loop that prints the numbers from 0 to 9 in one line using print. Include a space after each number. Example: 0 1 2 3 4 5 6 7 8 9 . 
```

```java
int i = 0;

while ( i <= 9 ) {
    
    print(i);
    print( " " );
    i++;
    
}

```


***

### Lesson 8 - 1 to 10 then 10 to 1
```

```

```java
int i = 1;
while(i <= 10) {
    print(i+" ");
    i++;
}
println("");
int j = 10;
while(j >= 1) {
    print(j+" ");
    j--;
}
println("");
```

### Lesson 9 - Num Digits
```
Write a program that given a number int n = nextInt() it outputs the number of digits in n. For example, if n is 123, print 3. 


```

```java
int n = nextInt();
int counter = 1;

while ( n > 1 ) {
    
    
    if ( n / 10 >= 1 ) {
        
        counter = counter + 1;
    }
    
    n = n / 10;
    
}
println( counter );


```


***

### Lesson 10 - Print digits

```
write a loop that given a number n, outputs the digits in reverse order.  
EX: 123 // 321
```

```java
int n = nextInt();

while(n > 0) {
    
    println( n % 10 );
    n /= 10;
    
}
```