# from-stdin

As we go through jq adventure, you will receive JSON strings from stdin, and output them to stdout. This exercise is to make sure you know how to do that before we get further into the lessons.

Your program will get the following input.

```input
{
    "message": "welcome to jq adventure!"
}
```

and the test expects the following output.

```output
{
    "message": "welcome to jq adventure!"
}
```

Use `jq '.'` to print JSON to the console from stdin.
