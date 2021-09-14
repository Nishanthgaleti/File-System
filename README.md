---------------------READ ME------------------

File system is of 128 KB, once created you can have 5 options 

1) create
2) delete
3) read
4) write
5) list out all the files in the filesystem


compilation :- g++ filesystem.cpp -o fs

how to run :- ./fs


after running above command, you are going to ask to pick from below two options, 
1) creating a new FILESYSTEM
2) Continue with already existed FILESYSTEM if exists


Below constraints are implemented in the filesystem :-

1) FILENAME must be unique

2) FILESIZE must be less than or equal to 8

3) Number of files at maximum in the filesystem must be 16

4) when all 15 files are at maximum strength i.e., all are having size 8. then total blocks occupied = 120, and one block for super block, so total occupied blocks = 120+1 = 121, so we are currently having only 7 blocks at max for 16th file.

5) after deleting the file, all block contents which are present in that file are going to be erased.
