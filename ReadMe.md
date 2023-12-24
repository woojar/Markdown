# This project is an basic example of a TCP and UDP client and server

## Introduction

Socket programming is a way of connecting two nodes on a network to communicate with each other. One socket(node) listens on a particular port at an IP, while the other socket reaches out to the other to form a connection. Server forms the listener socket while client reaches out to the server.

The difference between TCP socket and UDP socket is that TCP is connection oriented and UDP is connectionless. For the using TCP, you need to establish a connection first then you can send data, while for UDP you can send data first and then establish a connection.

## TCP socket programming in c++

In this project, we have implemented a TCP client and server using c++. The client sends a message to the server and the server responds back with the same message. As a summary, we can divide 3 steps when we use tcp socket server in c++

- Create a socket
- Bind the socket
- Listen for connections

## UDP socket programming in c++

In this project, we have implemented a UDP client and server using c++. The client sends a message to the server and the server responds back with the same message. As a summary, we can divide 3 steps when we use udp socket in c++

- Create a socket
- Bind the socket
- Send and receive data

# Introduction to markdown

Markdown is a lightweight markup language with plain-text-formatting syntax. Its design allows it to be converted to many output formats, but the original tool by the same name only supports HTML. Markdown is often used to format readme files, for writing messages in online discussion forums, and to create rich text using a plain text editor.

## paragraph in markdown

header 
# header 1
## header 2
### header 3
#### header 4
##### header 5
###### header 6

## Emphasis

*italic*
**bold**
***bold and italic***
~~strikethrough~~
~~hello, c++ world~~

## Lists

### unordered list

- item 1
- item 2
- item 3
    - item 3.1
    - item 3.2
- item 4

- item 5
    - item 5.1
    - item 5.2
    - item 5.3
- item 6
- 你好
    - 你好1

### ordered list

1. item 1
2. item 2
3. item 3
    1. item 3.1
    2. item 3.2
4. item 4



## Links

[link to google](https://www.google.com)

[link to woojar](https://woojar.com)

## Images

![image of cat](https://cdn.pixabay.com/photo/2016/02/10/16/37/cat-1192026_960_720.jpg) 

## Code blocks

```python
def add(x, y):
    return x + y
```

```c++
#include <iostream>
using namespace std;

int main() {
    cout << "Hello, world!" << endl;
    return 0;
}
```
```
test a code block
```

## Tables

| Name | Age | Gender |
|------|-----|--------|
| John | 25  | Male   |
| Jane | 23  | Female |
| Bob  | 31  | Male   |

|team name|DM     |SM     |SM     |scores|total|
|---------|-------|-------|-------|------|-----|
|team1    |1      |  2    |3     |  4    |  **=SUM(B2:E2)**  |


## Quotes

> quote 1
>
> quote 2
>
> quote 3

## Horizontal Rule

---

## Youtube Videos

[![youtube video](https://img.youtube.com/vi/9bZkp7q19f0/0.jpg)](https://www.youtube.com/watch?v=9bZkp7q19f0)


[this is a link](https://woojar.com)

## quote
> quote 1
>

## horizontal rule
---
