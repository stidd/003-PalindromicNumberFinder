# Problem Guide

## CountHi 

Create a variable to count the number of times the String "hi" appears

```
int count = 0;
```

Iterate across the String parameter but be careful to not traverse out of bounds!

{% code title="Main.java" %}
```java
for(int i = 0; i < str.length()-1; i++){
}
```
{% endcode %}

Consecutively look at two characters at a time using substring and test for equality using the .equals\( \) method

```java
if(str.substring(i, i+2).equals("hi")){
    count++;
}
```

{% hint style="warning" %}
Never test for String equality in Java with "==". The "==" operator does not test for a reference types content but rather will test memory location. 
{% endhint %}

Return the count

```java
return count;
```

Congratulations! 🎊 

