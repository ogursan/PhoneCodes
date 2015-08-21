# Phone Helper
Simple helper formatting phone numbers

## Usage
In order to use the PhoneHeler, first you have to install it via composer:
`composer require ogursan/phone-helper`

Then you should create new instance of helper:
`$phoneHelper = new Ogursan\PhoneHelper();`

And now you can format your phone numbers:
`var_dump($phoneHelper->phone('+79051234567')); // will return +7(905)123-45-67`
