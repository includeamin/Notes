# Notes
my Notes
## UWP Accessing Documents Library
https://www.pmichaels.net/2016/11/11/uwp-accessing-documents-library/
## Enable XPT2046 touch screen contorller windows 10 IOT
https://www.hackster.io/dotMorten/windowsiottouch-44af19

## check element existing in MongoDB collection C#
```
   var userWithSamePhoneNumber = users.Find(user => user.PhoneNummer.Equals(phoneNumber)).CountDocuments();
   if (userWithSamePhoneNumber > 0)
     {
      throw new Exception("User with this PhoneNumber address is exist");
     }
```
