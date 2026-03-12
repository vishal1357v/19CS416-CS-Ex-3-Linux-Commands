# CC-LAB-3-Linux Commands Study
### NAME: VISHAL P
### REG. NO.: 212224230306

## Introduction to Linux

**Linux** is an open-source operating system, and its kernel is the heart of the OS, facilitating communication between hardware and software. One of the key advantages of Linux is its customizability; developers can modify the Linux kernel to create their own tailored operating systems.

## Linux Commands

Linux commands are executed in the terminal, which is case-sensitive. This guide covers some basic and advanced commands used in Linux.

### 1. `ls` Command

The `ls` command is used to display a list of contents in a directory.

**Syntax:** 
```bash
ls
```

**Output:**

<img width="219" alt="image" src="https://github.com/user-attachments/assets/0c0a657c-97f4-4e73-a483-e5e828390b14">


### 2. `pwd` Command

The `pwd` command displays the location of the current working directory.

**Syntax:**
```bash
pwd
```

**Output:**

<img width="319" alt="image" src="https://github.com/user-attachments/assets/7e3be958-92f4-46da-aa96-333f6986b51e">


### 3. `mkdir` Command

The `mkdir` command is used to create a new directory.

**Syntax:**
```bash
mkdir <directory_name>
```

**Output:**

<img width="305" alt="image" src="https://github.com/user-attachments/assets/0b3a994f-dc6d-43e3-8933-65ee3d852a31">


### 4. `rmdir` Command

The `rmdir` command is used to delete a directory.

**Syntax:**
```bash
rmdir <directory_name>
```

**Output:**

<img width="301" alt="image" src="https://github.com/user-attachments/assets/4c0b13ed-8331-4ad2-a180-a315cb9b0926">


### 5. `cd` Command

The `cd` command is used to change the current directory.

**Syntax:**
```bash
cd <directory_name>
```

**Output:**

<img width="299" alt="image" src="https://github.com/user-attachments/assets/b0f678b8-b00b-4ac0-9e40-cbaf9b5a4d2c">


### 6. `cat` Command

The `cat` command is used to create, display, and concatenate files.

**Syntax:**
```bash
cat [OPTION]... [FILE]...
```

**Output:**

<img width="304" alt="image" src="https://github.com/user-attachments/assets/3e2759c2-9e2b-4e1e-8325-787f9dcbd755">


### 7. `cp` Command

The `cp` command is used to copy files or directories.

**Syntax:**
```bash
cp <source_file> <destination_file>
```

**Output:**

<img width="314" alt="image" src="https://github.com/user-attachments/assets/1851692d-2d1a-4974-8181-3b40cbd696ba">


## 8. `gedit` Command

`gedit` is a general-purpose text editor used to create and edit text files.

**Syntax:**
```bash
gedit <file_name>
gedit filename.txt 
```

### Output:
![image](https://github.com/user-attachments/assets/d16fe2e2-f203-467a-a256-9a279889ae51)


## 9. `su` Command

The `su` command provides administrative access to another user.

**Syntax:**
```bash
su <username>
su root
```

### Output:
![image](https://github.com/user-attachments/assets/da3d9bab-1f43-4fd2-936d-cd5d208eb605)


## 10. `mv` Command

The `mv` command is used to move a file or directory from one location to another.

**Syntax:**
```bash
mv <file_name> <directory_path>
mv filename.txt cloud2

```
### Output:
![image](https://github.com/user-attachments/assets/a18d0a45-75ba-456a-8dfb-8e96b44bd105)


## 11. `rename` Command

The `rename` command is used to rename files.

**Syntax:**
```bash
rename oldfile.txt newfile.txt
```

### Output:
![image](https://github.com/user-attachments/assets/749822e3-c9dc-431f-b573-cf200afa24ac)


## 12. `head` Command

The `head` command displays the first 10 lines of a file.

**Syntax:**
```bash
head <file_name>
head filename.txt 
```

### Output:
![image](https://github.com/user-attachments/assets/f4dbcef7-ff80-436a-8a47-83f63f8e1e70)


## 13. `tail` Command

The `tail` command displays the last 10 lines of a file.

**Syntax:**
```bash
tail <file_name>
tail filename.txt 
```
### Output:
![image](https://github.com/user-attachments/assets/bd496d57-44d8-4b7e-8305-e2359d5fc121)


## 14. `id` Command

The `id` command displays the user ID (UID) and group ID (GID).

**Syntax:**
```bash
id
```

### Output:
![image](https://github.com/user-attachments/assets/ad42807e-d328-4d8d-97e3-fb18dd632c9f)


### 15. `grep` Command

The `grep` command is used to search for a pattern within files.

**Syntax:**
```bash
command | grep <search_word>
```

### Output:
![image](https://github.com/user-attachments/assets/aad161ad-1d4d-4252-b154-22fcd6944ff2)


## 16. `tr` Command

The `tr` command is used to translate or delete characters.

**Syntax:**
```bash
command | tr <old> <new>
echo "hello world" | tr 'a-z' 'A-Z'
echo "banana" | tr -d 'a'
echo "one two three" | tr ' ' '\n'
```

### Output:
![image](https://github.com/user-attachments/assets/4801f8d1-9221-4969-810d-f945155db023)


## 17. `chmod` Command

The `chmod` command is used to change the access mode (permissions) of a file.

**Syntax:**
```bash
chmod <options> <permissions> <file_name>
chmod 755 file1
```

### Output:
![image](https://github.com/user-attachments/assets/965bfe60-371a-4ccc-99ea-ecfae690308e)


## 18. `tar` Command

The `tar` command is used to create or extract archive files.

**Syntax:**
```bash
tar [options] [archive-file] [files_to_archive]
tar -cvf archive.tar file1 file2
```

### Output:
![image](https://github.com/user-attachments/assets/bf37f2b2-e877-4db2-96ad-94a8dd21c776)


## 19. `chown` Command

The `chown` command is used to change the ownership of a file.

**Syntax:**
```bash
chown <owner_name> <file_name>
chown bharathi:root file1
```

### Output:
![image](https://github.com/user-attachments/assets/1a2e9440-d1e7-41b7-91d9-bcf5baf6e6c3)


## 20. `make` Command

The `make` command is used to build and maintain groups of programs.

**Syntax:**
```bash
make [-f makefile] [options] [targets]
nano Makefile
make
make clean
```

### Output:
![image](https://github.com/user-attachments/assets/bbb8e1d8-2649-4945-b75a-8fa3f720e9c3)


## 21. `ifconfig` Command

The `ifconfig` command is used to configure network interfaces.

**Syntax:**
```bash
ifconfig [options] [interface]
```

### Output:
![image](https://github.com/user-attachments/assets/2f4044fd-18f2-412f-9c12-b8b04a09a808)


## 22. `chmod 777` Command

The `chmod 777` command gives read, write, and execute permissions to the owner, group, and others.

**Syntax:**
```bash
chmod 777 <file_name>
chmod 777 filename.txt 
```

### Output:
![image](https://github.com/user-attachments/assets/3c34e47b-a812-43d7-bfbc-3aab505114c9)


## 23. `host` Command

The `host` command is used to display the IP address for a given domain name.

**Syntax:**
```bash
host <domain_name> or <ip_address>
host www.amazon.com

```

### Output:
![image](https://github.com/user-attachments/assets/a551b58b-26cd-4056-bc7f-38d0b531d21e)


## 24. `gzip` Command

The `gzip` command is used to compress files, replacing the original file with a compressed one with a `.gz` extension.

**Syntax:**
```bash
gzip filename.txt
gzip -d filename.txt.gz
gzip -k filename.txt
gzip -l filename.txt.gz  
```

### Output:
![image](https://github.com/user-attachments/assets/761d6bed-dd17-43b9-805f-124dfd9b66b8)


## 25. `sort` Command

The `sort` command is used to sort the contents of a file alphabetically.

**Syntax:**
```bash
sort <file_name>
sort filename.txt
```

### Output:
![image](https://github.com/user-attachments/assets/539348b5-92c8-4a67-bdff-c848d2754c11)


## 26. `cal` Command

The `cal` command displays the current month's calendar with the current date highlighted.

**Syntax:**
```bash
cal
```

### Output:
![image](https://github.com/user-attachments/assets/de1082c8-49d7-4fc6-b64a-2446c3abad56)


## 27. `clear` Command

The `clear` command clears the terminal screen.

**Syntax:**
```bash
clear
```

### Output:
![image](https://github.com/user-attachments/assets/bb7a7e1f-ae07-4e6c-91b8-5ec792fe6402)


## 28. `mail` Command

The `mail` command is used to send emails from the command line.

**Syntax:**
```bash
mail
```

### Output:
![image](https://github.com/user-attachments/assets/db5cad74-8a0f-452f-bbd8-67ce911afbd0)


## 29. `df` Command

The `df` command displays the disk space usage of file systems.

**Syntax:**
```bash
df
```

### Output:
![image](https://github.com/user-attachments/assets/8d3b62c0-5558-4162-a2cd-ea07d45701d7)


## 30. `find` Command

The `find` command is used to search for files in a directory hierarchy.

**Syntax:**
```bash
find <directory> -name <file_name>
find /etc -name "passwd"
```

### Output:
![image](https://github.com/user-attachments/assets/74844dc1-0c8a-45d3-ac0d-93da990187ca)


## Result :
Linux commands are executed in the linux terminal successfully.
