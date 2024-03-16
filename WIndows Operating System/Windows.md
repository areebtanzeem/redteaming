#  Windows File System

## NTFS (New Technology File System)

### Format

The NTFS contains 4 major parts which includes
1. Boot Sector: Here all the boot code resides for loading the OS and getting everything kind of working
2. Master File Table: It is a table that keeps the record of every file in the NTFS system
 Structure of MFT
    |MFT|
    |---|
    |Copy of MFT|
    |14 Default Records|
    |File Record|
    |Directory Record|
    |File Record|
    |Directory Record|

   
4. File System Data: It contains the actual text of file or image data etc
5. MFT Copy: It is the copy of Master File Table
