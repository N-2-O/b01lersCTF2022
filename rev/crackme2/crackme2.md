# crackme2

> Time for some basic algebra...

Disassemble the file using `objdump -d crackme_2 > crackme2.asm`. The file uses a check function to compare an input string with the passphrase hidden in the code. Looking at the check function, it checks each character of the input string, some involve operations, some are hardcoded. For example, the fifth character is compared with `(0x70 - 0x3c)`.

![crackme2](https://github.com/N-2-O/b01lersCTF2022/blob/main/rev/crackme2/crackme2.png)

The flag is `bctf{4lg3br4!}`.
