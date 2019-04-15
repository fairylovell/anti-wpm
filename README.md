# anti-wpm

## What is it?

* A class which protects code from external editing variables with programs such as Cheat Engine is

## How it works?

* it creates two variables with the same value and moves one of them through different positions in the RAM (simply said) which makes finding it much harder
* it compares values for differences

## How to use it?

* basically, you can use it exactly like any other 'normal' variable

```c++
int x = 0; // creates 'normal' - unprotected variable
pvar<int> y = 0; // creates protected variable
```

* you can use operations like ```y = 2 + x``` but, there are several operators which are not overloaded (i.e. y++)

## Can I use it as it is?

* It depends. I made it ~1 year ago *(I had got the idea sooner)* just to be sure that it is possible to make something like that, therefore, I didn't put much time into it. I have made small changes in the recent past in order to make it readable and compatible with every type of variable but as I mentioned, some of the operators were not overloaded. One can live without it and another one may be mad about it. Although it is not completed foundations were laid down.