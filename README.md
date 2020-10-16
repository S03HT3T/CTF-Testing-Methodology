# **CTF-Testing-Methodology**

## 1. Always check source code.(Yes I mean ALWAYS!!!)
 - ***Look carefully the source code and check all of css file,js file***

## 2. Check robots.txt .

## 3. Check useragents.

## 4. You should bruteforce the directory.(use gobuster or ffuf)
 - ***find common directory(eg- admin.php,login.php)***

## 5. Find search box or parameter which you can control.
 - ***If you found search box,you can test common attacing methods(eg- sql injection,ssti,xss cookie stealing)***
 - ***else you found parameter , you can test other methons(eg - lfi,rfi,rce)***

## 6. Try to understand challenge's website processes.
 - ***should find what technology the challenge's website used.***
 - ***intercept all requests of challenge's webiste and look carefully each requests and responce.(such as - data,header,url,cookie)***

## 7. If the challenge give you login panel.
 - ***At first you should try login byass***
