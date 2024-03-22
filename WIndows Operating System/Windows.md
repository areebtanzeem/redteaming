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

# Windows Internal 

## UAC

User Account Control provides a temporary administrative rights during the single time it is being run. It helps mitigate viruses and malwares. below is the attached picture.

![image](https://github.com/areebtanzeem/redteaming/assets/38752820/347dbd36-cd75-48e4-adea-0d133936a157)

### Working of UAC

![image](https://github.com/areebtanzeem/redteaming/assets/38752820/7cfcab9a-7f0f-43be-8c0c-41871aa846d8)

Shell Execute is a Windows API call which will create a process.
Then it will send the process information to Application info service and it check if ActiveX is installed
ActiveX is a software framework from Microsoft (MSFT) that allows applications to share functionality and data with one another through web browsers, regardless of what programming language they're written in.

## Permissions



