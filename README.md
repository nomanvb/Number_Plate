# Number_Plate_CSharp
This C# Project used http://app.cogedg.com:4555/api/ free API  to detect and read vehicle number plate. Currently it can detect and read Bangladeshi vehicle number plate.
This system only works with Retro-Reflective Number Plate issued by Bangladesh Road Transport Authority. 

![test result](https://user-images.githubusercontent.com/15852967/35750172-085c2a6a-084c-11e8-9005-cdb76e3461b9.jpg)

The API returns number plate information and accuracy in JSON format shown below.
```JSON
{
NumberPlate:XXXX XXXX XX-XXXX,
Accuracy:xx.xx
}
```
