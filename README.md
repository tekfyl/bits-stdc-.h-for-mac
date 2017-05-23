# bits-stdc-.h-for-mac

bits/stdc++ is a GNU GCC extension, whereas OS X uses the clang compiler. However, you can still make it work by manually creating the header file.

## Steps
* Inside the directory /usr/local/include/ 
* Create a directory named bits (mkdir bits)
* Create stdc++.h file (touch stdc++.h or vim stdc++.h)
* Paste the contents of the stdc+.h file here

Now it should compile as expected

I have also included "using namespace std;" in this file.
So, from now on you dont need to write it everytime you create a cpp file.
