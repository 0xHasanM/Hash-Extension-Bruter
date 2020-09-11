# Hash-Extender-Bruter
Hash-Extender-Bruter is a tool in python to bruteforce Hash-extender length and send back cookie to website

## Table of Contents
* [Features](#Features)
* [Installation](#Installation)
* [Usage](#Usage)

## Features
1.auto detect hashes type and check if they are vulnerable
2.send the new generated signatures to website and exclude results that contains words in resfilter option

## Installation
1.```sh git clone https://github.com/0xMohammed/Hash-Extender-Bruter.git```
2.```sh cd Hash-Extender-Bruter```
3.```sh mv ./hash-extender /usr/bin```
4.```sh pip3 install -r requirements.txt```
5.```sh chmod +x ./Hash-Extender-bruter.py```

## Usage
1.```sh -h : show help menu```
2.```sh -d : the original data i.e. user=demo```
3.```sh -s : signature (hash)```
4.```sh -a : data to add i.e. user=admin```
5.```sh -r : bad word i.e. 'wrong signature'```
![Alt Text](https://github.com/0xMohammed/Hash-Extender-Bruter/blob/master/Images/Peek%202020-09-11%2018-45.gif)

##Refrences
[Length_extension_attack](https://en.wikipedia.org/wiki/Length_extension_attack)
[SHA1 length extension attack on the Secure Filesystem](https://www.youtube.com/watch?v=6QQ4kgDWQ9w)
[MD5 length extension and Blind SQL Injection - BruCON CTF part 3](https://www.youtube.com/watch?v=sMla6_4Z-CQ)
