This project consists in creating your own library with some of mostknown functions, such as, strlen, strcpy, memcpy, and others...

## Clone

```bash
git clone https://github.com/pemiguel-dca/Libft.git
```
When you have cloned the repo, you just need to run ```make``` inside of the 'src' directory.

## Libft

You'll see after running ```make``` that a 'libft.a' file was created, that file is the library itself, to use it you add a flag when compiling, here's an example:

```bash
cc main.c -L. libft.a
```
