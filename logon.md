# LOGON

The factory is hiding things from all of its users. Can you login as logon and find what they've been looking at? `https://2019shell1.picoctf.com/problem/47307/` ([link](https://2019shell1.picoctf.com/problem/47307/)) or http://2019shell1.picoctf.com:47307
## SOLUTION

 

 - By opening the link given you are redirected to a website which require login credentials.
 - Enter any Username and Password
 - Now Use inspect element feature in your browser and go to storage section
 - There you can see the username and password you entered and admin cookie.
 ![alt text](https://user-images.githubusercontent.com/44405294/66729358-8791ce80-ee68-11e9-962f-acca2c9af218.png)
 - Change value of admin from **False** to **True**
 ![alt text](https://user-images.githubusercontent.com/44405294/66729361-89f42880-ee68-11e9-9461-eceeb00b3b21.png)
 
 **Flag**:
![alt text](https://user-images.githubusercontent.com/44405294/66729364-8cef1900-ee68-11e9-855b-52a28df9af55.png)
