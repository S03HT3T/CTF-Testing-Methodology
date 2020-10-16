# **CTF-Testing-Methodology**

## 1. Always check source code.(Yes I mean ALWAYS!!!)
 - ***Look carefully the source code and check all of css file,js file***

## 2. Check robots.txt .

## 3. Check useragents.
 - ***If you need to bruteforce useragents,[use this](https://github.com/JackStouffer/Violent-Python/blob/master/wordlist/fuzzdb/Discovery/PredictableRes/UserAgents.fuzz.txt)***

## 4. You should bruteforce the directory.(use gobuster or ffuf)
 - ***find common directory(eg- admin.php,login.php)***

## 5. Find search box or parameter which you can control.
 - ***If you found search box,you can test common attacing methods(eg- sql injection,SSTI,xss cookie stealing)***
 - ***else you found parameter , you can test other methods(eg - LFI,RFI,RCE)***

## 6. Try to understand challenge's website processes.
 - ***should find what technology the challenge's website used.***
 - ***intercept all requests of challenge's website and look carefully each requests and responce.(such as - data,header,url,cookie)***

## 7. If the challenge give you login panel.
 - ***At first try to login with some weak password(eg-admin:admin,admin:pass) and you should try login byass([use this](https://github.com/S03HT3T/CTF-Testing-Methodology/blob/main/adminbypass.txt))***
 - ***And second intercept the login requests and try to understand how login request check credentials.***
 - ***And third you should check cookie and play with cookie(eg - base64,jwt,flask session).***

### 8. Try with some common methods.
 - ***I mean dig,git,etc...***
