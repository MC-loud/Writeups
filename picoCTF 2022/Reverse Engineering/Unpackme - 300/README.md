# unpackme

For this challenge, we are given a single file named unpackme-upx. We can unpack it using upx.
![unpacking using upx](./file.png)

We can now open the file using ghidra and look at the main function.</br>
![opening with ghidra](./ghidra.png)

The main function appears to be a simple if/else statement. If the input's value is 0xb83cb, we will receive the flag.</br>
Inputting the decimal equivalent, 745635, gives us the flag.</br>

![retrieving the flag](./flag.png)
