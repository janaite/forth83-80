# Forth F83 _by Laxen & Perry_

## Description

A public domain implementation of FORTH-83 version 2.0 for CP/M-80 made by Henry Laxen and Michael Perry

Here we have all contents of archive "f83v2-80.ark" (MD5: 8c5017e406add5aa0dcd9e99a2514bc2)

This archive is available from from [Forth Interest Group _FIG_ site, Public Domain Forths section](http://www.forth.org/eforth.html) 
and from [Retroarchive.org, forth-83](http://www.retroarchive.org/cpm/cdrom/CPM/FORTH-83)

References:
[1](http://www.forth.org/library/eforth_SOC/eforth_SOC_source/f83/f83v2-80.ark)
[2](http://www.retroarchive.org/cpm/cdrom/CPM/FORTH-83/F83V2-80.ARK)

## Archive information

Archive File = F83V2-80.ARK

Name         | Length |Disk | Method  |Ver|Stored |Saved|  Date   |Time  |CRC 
-------------|--------|-----|---------|---|-------|-----|---------|------|----
-READ   .ME  |   1792 | 32k |Crunched |8  |  1022 |43%  |5 Feb 87 |8:50p |98F7
BASIC   .BLK |  18432 | 32k |Crunched |8  |  3216 |83%  |5 Feb 87 |8:26p |5304
CLOCK   .BLK |  12288 | 32k |Crunched |8  |  2295 |82%  |5 Feb 87 |8:26p |5C0D
CPU8080 .BLK |  41984 | 64k |Crunched |8  |  7281 |83%  |5 Feb 87 |8:26p |AC67
EXPAND80.BLK |   5120 | 32k |Crunched |8  |  1792 |65%  |5 Feb 87 |8:26p |B566
EXTEND80.BLK |  30720 | 32k |Crunched |8  |  6471 |79%  |5 Feb 87 |8:26p |4B10
F83-FIXS.TXT |   5120 | 32k |Crunched |8  |  3023 |41%  |5 Feb 87 |8:26p |369B
F83     .COM |  24448 | 32k |Crunched |8  | 21197 |14%  |5 Feb 87 |8:20p |446B
HUFFMAN .BLK |  43008 | 64k |Crunched |8  |  9464 |78%  |5 Feb 87 |8:26p |5492
KERNEL80.BLK | 190592 |192k |Crunched |8  | 48606 |75%  |5 Feb 87 |8:27p |FDEB
META80  .BLK |  49280 | 64k |Crunched |8  | 10121 |80%  |5 Feb 87 |8:27p |A3AE
README  .80  |  18048 | 32k |Crunched |8  | 10364 |43%  |5 Feb 87 |8:27p |6B5A
UTILITY .BLK | 112640 |128k |Crunched |8  | 29838 |74%  |5 Feb 87 |8:27p |4BD5
-------------|--------|-----|---------|---|-------|-----|---------|------|----
Total     13 | 553472 |768k |         |   |154690 |73%  |         |      |1D45

## Original "README"

F83V2-80.ARK contains F83.COM, a public domain implementation of 
FORTH-83 version 2.0 for CP/M-80 that is ready to run.  It also 
contains source files.

These files are identical to those distributed in F83V2-80.LBR.  They 
have now been put into this ARK to take advantage of the more efficient 
file compression methods available.

The original Laxen-Perry distribution had these files squeezed with a 
program that took hours (!) to run to unsqueeze. 

The VIEW word expects certain source blocks to be on drive A: and 
certain source files to be on drive B:.  If you have a hard disk 
system, you can  follow the directions in README.80 to recompile your 
system with all of the source blocks on your hard disk and the VIEW 
file numbers will be set up correctly. 

Here are the files in this ARK:

- FILE:  F83     .COM         The FORTH system compiled.
- FILE:  README  .1ST         This file
- FILE:  README  .80          Original F83 instructions
- FILE:  F83-FIXS.TXT         Changes from F83 v.1.0

These "blocks" are the F83 sources

- FILE:  KERNEL80.BLK         Kernel source
- FILE:  META80  .BLK         Metacompiler source
- FILE:  CPU8080 .BLK         8080 dependent code
- FILE:  EXTEND80.BLK         Extensions source
- FILE:  UTILITY .BLK         The UTILITY source 

These blocks are applications

- FILE:  HUFFMAN .BLK         A VERY slow compression program
- FILE:  CLOCK   .BLK         Source for a calendar example
- FILE:  EXPAND80.BLK         Original source to expand .HUF
- FILE:  BASIC   .BLK         BASIC compiler in F83

--Keith Petersen, W8SDZ  5-Feb-87
