## Markdown preview

When opening Markdown files in text editor you can interactively render the content (`Right Mouse Button` -> `Show Markdown Preview`).

## Embeded code

Tripple backticks with the name of the programming language following will create a block of code with proper syntax syntax highlighting. 

```python

print("Hi there")
print("How is it going?")
```

Several languages (Python, R, C/C++, Julia) are supported:

```c

#include <stdio.h>

int main() {
    printf("Hi there\n");
    return 0;
}
```

## Code execution

Source code included in Markdown files can be run in the interactive console (`Right Mouse Button` -> `Create Console for Editor`) but pressing `Shift` + `Enter` while cursor is over the block of code.

```python
name = input("Hi! What is your name?")
```

You can run blocks one by one as they appear in the text:

```python
print("Hello, " + name + ". You're looking well today.")
```
