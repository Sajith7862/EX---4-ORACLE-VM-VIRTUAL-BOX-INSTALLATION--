# Ex.3 Virtualization: Installation and Configuration of Oracle VirtualBox & Kali Linux, and Execution of Linux Commands

# Name : Mohamed Hameem Sajith J
# Reg : 212223240090

## Aim:
To set up a virtualized environment using Oracle VirtualBox, install Kali Linux as a guest OS, and execute fundamental Linux commands.

## 3.a) Installation and Configuration of Oracle VirtualBox

## Aim:
To install and configure Oracle VM VirtualBox.

## Pre-requisites:

* Machine with Internet access
* Minimum 4 GB RAM
* Sufficient storage space

## Steps:
1. Download Oracle VM VirtualBox:

    * Visit Oracle VirtualBox Official Site
    * Download installer for your OS (Windows/macOS/Linux).
2. Install Oracle VM VirtualBox (Example: Windows):

    * Launch Installer → Allow Changes → Click Next.
    * Choose Installation Options → Click Next.
    * Accept Network Interface Warning → Click Yes.
    * Click Install.
    * Finish Installation and Launch VirtualBox.
3. Configure VirtualBox:

    * Open VirtualBox.
    * Click New → Name VM → Select Type (Linux/Windows) and Version.
    * Allocate:
        * Minimum 2 GB RAM
        * Create Virtual Hard Disk (20 GB recommended).
    * Start Virtual Machine and provide ISO to install OS.

## Result:
Thus, Oracle VM VirtualBox was installed successfully.

## 3.b) Installation and Configuration of Kali Linux

## Aim:
To install and configure Kali Linux in Oracle VirtualBox.

## Pre-requisites:
* Oracle VM VirtualBox Installed
* 4 GB RAM and 20 GB Storage Minimum
* Kali Linux ISO image

## Steps:
1. Download Kali Linux ISO:

    * Visit Kali Linux Official Site
    * Download 64-bit ISO (Installer version).
2. Create a New Virtual Machine:

    * Open VirtualBox → Click New.
    * Name: "Kali Linux" → Type: Linux → Version: Debian (64-bit).
3. Allocate Memory:

    * Minimum 2 GB RAM (recommended 4 GB).
4. Create Virtual Hard Disk:

    * Select VDI (VirtualBox Disk Image).
    * Choose Dynamically allocated.
    * Set Disk size to 20 GB or more.
5. Configure ISO Image:

    * Settings → Storage → Controller: IDE → Empty CD → Choose Disk File → Select Kali Linux ISO.
6. Start Installation:

    * Boot Virtual Machine → Choose Graphical Install.
    * Set Language, Region, Keyboard.
    * Configure Network → Set Hostname (e.g., kali).
    * Set root password.
    * Disk Partitioning: Use entire disk → All files in one partition.
    * Install System → Install GRUB Bootloader → Finish Installation.
7. Login to Kali Linux:

    * Use root credentials.
8. (Optional) Install Guest Additions:

    * Devices → Insert Guest Additions CD Image → Follow steps inside Kali.

## Snapshots:
AWS Account Creation Snapshot

Snapshot 1: Installing Oracle VirtualBox
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/3ec3ad0f-a83b-4bff-b08c-d4355a2ff1c4" />

Snapshot 3: Kali Running in VirtualBox

<img width="1920" height="945" alt="image" src="https://github.com/user-attachments/assets/9fc131e0-5cc1-4642-b0a8-88f9c74f77dd" />

## Result:
Thus, Kali Linux guest OS was installed and configured successfully.

## 3.c) Execution of Linux Commands in Kali

## About Linux:
* Open-source operating system.
* Kernel manages communication between hardware and software.
* Commands are case-sensitive.

## Linux Commands:
1. ls Command
    
    The ls command is used to display a list of content of a directory.

### Syntax:
```
ls
```
<img width="1186" height="161" alt="image" src="https://github.com/user-attachments/assets/f6b9dea1-cc21-4346-a925-77410f05774f" />

2. pwd Command

    The pwd command is used to display the location of the current working directory.

### Syntax: 
```
pwd
```
<img width="714" height="239" alt="image" src="https://github.com/user-attachments/assets/f50bac10-aff8-4ff8-8782-06f4dfe786a1" />

3. mkdir Command

    The mkdir command is used to create a new directory under any directory.

### Syntax: 
```
mkdir <directory_name>
```
<img width="482" height="104" alt="image" src="https://github.com/user-attachments/assets/7983dfa1-de2d-40e6-9bd4-c2cc8249c682" />

4. rmdir Command

    The rmdir command is used to delete a directory.

### Syntax: 
```
rmdir <directory_name>
```
<img width="398" height="97" alt="image" src="https://github.com/user-attachments/assets/8432a33a-a35e-45cf-a661-f2c201482719" />

5. cd Command
The cd command is used to change the current directory

### Syntax: 
```
cd <directory_name>
```
<img width="431" height="111" alt="image" src="https://github.com/user-attachments/assets/1a0f61b4-4e5c-420b-a575-f1c085db22bd" />

6. cat Command

    The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content ofthe file, copy the content of one file to another file, and more.

### Syntax: 
```
cat [options] [file_name]
```
<img width="556" height="172" alt="image" src="https://github.com/user-attachments/assets/8d45960f-d6f2-4c65-8c0f-390fc3f2a574" />

<img width="490" height="161" alt="image" src="https://github.com/user-attachments/assets/b10d6a3b-6bc5-4180-9073-ddc31f8b671c" />

7. cp Command

    The cp command is used to copy a file or directory.
### Syntax: 
```
cp [source] [destination]
```
<img width="441" height="99" alt="image" src="https://github.com/user-attachments/assets/02f5355f-0d67-4025-983d-cd430e51a78e" />

<img width="482" height="170" alt="image" src="https://github.com/user-attachments/assets/07264be9-be70-481d-b424-63de1e3dcdb6" />



8. mv Command

    The mv command is used to move a file or a directory form one location to another location.

### Syntax: 
```
mv [source] [destination]
```
<img width="395" height="92" alt="image" src="https://github.com/user-attachments/assets/72b47c7c-9f87-437c-89b6-a3f1d9cc200f" />

<img width="415" height="89" alt="image" src="https://github.com/user-attachments/assets/f5a9c269-fd8b-4878-8bd8-1a0e1449c3a1" />

9. touch Command

    Create empty file.

### Syntax: 
```
touch [filename]
```
<img width="493" height="109" alt="image" src="https://github.com/user-attachments/assets/4006ee6a-6023-4015-9f4b-5df93c94102a" />

10. vi Command

    Edit file contents using editor.

### Syntax: 
```
vi [filename]
```
<img width="423" height="98" alt="image" src="https://github.com/user-attachments/assets/16f3f232-da4e-452e-834f-d99333152d4f" />

## Result:
Thus, various Linux commands were executed successfully in Kali Linux virtual machine.


