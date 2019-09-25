Java Conditional IF/Else
===================================

Example Application: Conditional: IF/ELSE

## Simple conditional IF and ELSE
```java
int value = 1;
if (value == 1) {
	// TODO
	System.out.println("Value is 1");

} else {
	// TODO
	System.out.println("Value is not 1");

}
```

## IF conditional with multiple ELSE
```java
int value = 1;
if (value < 1) {
	// TODO
	System.out.println("Value is less than 1");

} else if (value == 1) {
	// TODO
	System.out.println("Value is 1");

} else if (value == 2) {
	// TODO
	System.out.println("Value is 2");

} else if (value > 2) {
	// TODO
	System.out.println("Value is greater than 2");

}
```

## IF with Boolean	
```java
boolean bVal = true;

if (bVal) {
	// TODO
	System.out.println("TRUE");

} else {
	// TODO
	System.out.println("FALSE");

}
```

## IF with "!".		
```java
boolean bVal = true;
if (!bVal) {
	// TODO
	System.out.println("TRUE");
} else {
	// TODO
	System.out.println("FALSE");
}
```


## IF String Equals.
```java
String sVal = "wwww.google.com";
if (sVal.equals("wwww.google.com")) {
	// TODO
}
```

## IF String Equals Ignore Case Sensitive.
```java
String sVal = "wwww.google.com";
if (sVal.equalsIgnoreCase("WWW.GOOGLE.COM")) {
	// TODO
}
```

## IF String starts with the specified prefix.
```java
String sVal = "wwww.google.com";
if (sVal.startsWith("www")) {
	// TODO
}
```

## IF String end with the specified prefix.
```java
String sVal = "wwww.google.com";
if (sVal.endsWith(".com")) {
	// TODO
}
```

## IF String using &&
```java
String sVal = "wwww.google.com";
if (sVal.startsWith("www") && sVal.endsWith(".com")) {
	// TODO
}
```

## IF String using ||
```java
String sVal = "wwww.google.com";
if (sVal.startsWith("www") || sVal.endsWith(".com")) {
	// TODO
}
```

## IF String is Empty value.
```java
String sVal = "wwww.google.com";
if (sVal.isEmpty()) {
	// TODO
}
```

## If conditional (ternary) 

#### Sintax conditional (ternary)
> condition ? exprIfTrue : exprIfFalse

```java
boolean bVal = true;
String value = "This boolean is: "+ (bVal==true?"True":"False");
```

## Some links for more in depth learning

* [JAVA PRINT](https://github.com/fefong/java_print);
* [JAVA SWITCH CASE](https://github.com/fefong/java_switch);
* [JAVA IF/ELSE](https://github.com/fefong/java_ifElse);
* [JAVA ARITHMETIC](https://github.com/fefong/java_calculator);
* [JAVA](https://github.com/search?q=fefong%2Fjava)

