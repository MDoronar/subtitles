# Subtitles
Subtitles


curl https://yt-dl.org/downloads/2016.03.27/youtube-dl -o
/home/fede/bin/youtube-dl

chmod a+rx bin/youtube-dl



#!/bin/bash

# Pointers in C: https://www.youtube.com/playlist?list=PL2_aWCzGMAwLZp6LMUKI3cc7pgGsasm2_

for URI in "https://www.youtube.com/watch?v=h-HBipu_1P0" "https://www.youtube.com/watch?v=X1DcpcgSUXw" "https://www.youtube.com/watch?v=JTttg85xsbo" "https://www.youtube.com/watch?v=d3kd5KbGB48" "https://www.youtube.com/watch?v=LW8Rfh6TzGg" "https://www.youtube.com/watch?v=ASVB8KAFypk" "https://www.youtube.com/watch?v=CpjVucvAc3g" "https://www.youtube.com/watch?v=Bf8a6IC1dE8" "https://www.youtube.com/watch?v=vFZTxvUoZSU" "https://www.youtube.com/watch?v=sHcnvZA2u88" "https://www.youtube.com/watch?v=_j5lhHWkbnQ" "https://www.youtube.com/watch?v=xDVC3wKjS64" "https://www.youtube.com/watch?v=E8Yh4dw6Diw" "https://www.youtube.com/watch?v=ynYtgGUNelE" "https://www.youtube.com/watch?v=sxTFSDAZM8s" "https://www.youtube.com/watch?v=F2nrej6Kjww" 
do
    bin/youtube-dl --verbose --all-subs --sub-format srt --skip-download $URI
done


31/3 4h
1/4 3h
2/4 1h
4/4 4h
5/4 1h
6/4 1h
9/4 3h
13/4 2h
18/4 1h
19/4 2h
24/4 1h
25/4 1h
28/4 2h
29/4 3h

		
Working with pointers
Pointer types, pointer arithmetic, void pointers
Pointers to Pointers in C/C++
Pointers as function arguments - call by reference
Pointers and arrays
Arrays as function arguments
Character arrays and pointers - part 1
Character arrays and pointers - part 2
Pointers and 2-D arrays
Pointers and multidimensional arrays
Pointers and dynamic memory - stack vs heap
Dynamic memory allocation in C - malloc calloc realloc free
Pointers as function returns in C/C++
Function Pointers in C / C++
Function pointers and callbacks
Memory leak in C/C++
