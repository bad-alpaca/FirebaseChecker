# FirebaseChecker
A python script to take a list of firebasio.com URLs and check for possible permission misconfiguration.

The script adds /.json to end of url and checks what the status code code is, if it returns a 200 there is a good chance the firebase do not have proper permission configuration. 

![usage example](https://user-images.githubusercontent.com/108617127/219955248-1a7b6b78-81c8-4dcb-ac2f-f1d954c217c8.png)
