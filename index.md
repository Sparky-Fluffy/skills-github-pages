---
title: Welcome to my blog
---

Some text here for example.

```c
#include <stdio.h>
#include <fcntl.h>
#include <unistd.h>

int main(void)
{
  int fd = 0;

  fd = open("file.txt", O_RDONLY, 0750);
  if (fd == -1)
  {
    perror("fd");
    return 1;
  }
  close(fd);
  return 0;
}
```
