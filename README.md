strman-java
------

A Java string manipulation library without any dependencies. It is inspired by [dleitee/strman](https://github.com/dleitee/strman).


## Available Functions

* [append](https://github.com/shekhargulati/strman-java)
* [appendArray](https://github.com/shekhargulati/strman-java)


## append(value, strings...)

This method will append `strings` to the `value`.

```java
import static strman.Strman.append;
String title = "s";
String result = append(title, "tr","m","an");
// result = "strman"
```


## appendArray(value, strings)

This method will append all the values in `strings` array to the `value`.

```
import static strman.Strman.appendArray;
String title = "s";
String result = appendArray(title, new String[]{"tr","m","an"});
// result = "strman"
```