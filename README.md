# format
A simple formatting library.

Some examples of use are the following. Bear in mind all the functionality is in the `format` namespace.

Here is the first basic usage.

```C++
format::format("Hello, you are {} years old", 42);
```
Which outputs:
```C++
Hello, you are 42 years old
```
You do not have to use additional variables, you can just pass things to print and it will print them:
```C++
format::format("Hello");
```
You can pass as many arguements as you want:
```C++
format::format("Hello {} you are {} years old. You live on planet {} which is in the {}.", "Robert", 42, "Earth", "Milky Way");
```
Which has the following output:
```C++
Hello Robert you are 42 years old. You live on planet Earth which is in the Milk Way.
```
