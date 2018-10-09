# [Redirects](https://www.ibm.com/developerworks/library/l-lpic1-103-4/index.html)

heres an exerpt from an article explaining the '>' & '>>' symbols.

>Redirecting output
>There are two ways to redirect output to a file:

>n>
>redirects output from file descriptor n to a file. You must have write authority to the file. If the file does not exist, it is created. If it does exist, the existing contents are usually lost without any warning.


>n>>
>also redirects output from file descriptor n to a file. Again, you must have write authority to the file. If the file does not exist, it is created. If it does exist, the output is appended to the existing file.


>The n in n> or n>> refers to the file descriptor. If it omitted, then standard output (file descriptor 1) is assumed. Listing 3 illustrates using redirection to separate the standard output and standard error from the ls command using files you created earlier in your lpi103-4 directory. It also illustrates appending output to existing files.
