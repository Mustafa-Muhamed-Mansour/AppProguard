# Why do we use a ProGuard or R8 ???

## 1- shrinking --> I meaning a less code or in this application version if found codes not used didn't upload with aab or apk.
## 2- Optimization --> I meaning if I write a big function, the proguard abbreviates this function so a size in aab or apk low also a higher performance.
## 3- Obfuscation --> I meaning encryption, the code becomes not understood.

before add Proguard
<img src = "" width = "200" height = "400">
size app before adding " Proguard "
<img src = "" width = "200" height = "400">
after add Proguard
<img src = "" width = "200" height = "400"> 
size app after adding " Proguard "
<img src = "" width = "200" height = "400">
annotation in Proguard to save the thing (1)
<img src = "" width = "200" height = "400">
annotation in Proguard to save the thing (2)
<img src = "" width = "200" height = "400">
inside a " proguard-rules.pro " you write rules your own, ex:- inside the white box
<img src = "" width = "200" height = "400">
inside a " proguard-rules.pro " you write rules your own, ex. other:- inside the white box and don't forget a documentation Proguard inside the red box
<img src = "" width = "200" height = "400">
