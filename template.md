---
title: How to create user in linux
description: "In linux, you can quickly create a new user through adduser"
date: August 21 2022
---
## Introduction
In linux, you can quickly create a new user with `adduser`
## Command Line
Change the password of the user `cmdhelp`
```linux
sudo adduser cmdhelp
```
## Parameter
| parameter | Introduction                                                               |
| --------- | -------------------------------------------------------------------------- |
| sudo   |execute a command as another user|
| adduser   |Add user.|
###  operation result
```
[sudo] password for root: 
Changing password for user cmdhelp.
New password: 
BAD PASSWORD: The password is shorter than 8 characters
Retype new password: 
passwd: all authentication tokens updated successfully.
```
### Notice

If the password is less than 8 digits, you can continue to enter it for the second time.
