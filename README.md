# Master Async/Await With This Real World Example
## Currency Converter Tutorial
In this tutorial, we will build simple, but educational and useful application that is going to improve your overall knowledge of Async/Await. 

The program will take in currency code we want to convert from and currency code we want to convert to, as well as the amount of money, afterwards, the program will output correct exchange rate based on the data from the API’s.

In this application we’re going receive data from two asynchronous sources:
1. Currency Layer — https://currencylayer.com  —  You’ll need to sign up for free so you can use API Access Key. This API will provide us with data needed to calculate exchange rate between currencies.
2. Rest Countries — http://restcountries.eu/  —  This API will give us information about where can we use the currency we just converted our money to.

For starters, create a new directory and run npm init, skip through all the steps and install axios by typing npm i --save axios. Create a new file called currency-converter.js.

Firstly, require axios by typing: const axios = require(‘axios’);
