# 0x41haz Challenge



- So after downloading the file, let's run a file command to see what type binarie it is.it's"ELF 64-bit MSB" and i don't understand this "*unknown arch 0x3e00*(SYSV)".
![Source](https://github.com/b3ng0x/THM-easy-reverse/blob/main/1.png?raw=true)
- So let's google it and i find this good site "https://pentester.blog/?p=247"
- After reading it we need to change the 6th bit from 2 to 1 and I use hexedit for that




![Source](https://github.com/b3ng0x/THM-easy-reverse/blob/main/2.png?raw=true)

### Solution
- Now we can use radare2 analyzing this binarie.

![Source](https://github.com/b3ng0x/THM-easy-reverse/blob/main/3.png?raw=true)

- I see that is check the length of the input if is equal to 13
and after he check the pass provided from the three variable var_16h,var_eh,var_ah

![Source](https://github.com/b3ng0x/THM-easy-reverse/blob/main/4.png?raw=true)
