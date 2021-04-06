# covid-sh
A simple BASH script to get the latest information about covid-19 in your country, the data extracted by this script is taken from this 
Covid-19 [site](https://ftp.worldometers.info/coronavirus/)

  ![image](https://user-images.githubusercontent.com/76466992/113694409-4ea38480-9702-11eb-91a6-9a756b4e703f.png) 

<h1> Getting Started </h1>

1.) Download the script from the [releases page](https://github.com/Thanatoslayer6/covid-sh/releases)

2.) After downloading the file change the permissions of the file to make it executable by typing, then execute it

>  chmod +x covid-sh

Execute it
>  ./covid-sh

<h1> Optional </h1>

Add the file to your $PATH or /usr/bin/ then add it into your .bashrc... 

Change the country variable inside the script by using your favorite text editor and then type your own country

To know the proper syntax for country names just look at the end part of the url from this [site](https://ftp.worldometers.info/coronavirus/)

<h1> Example </h1>

When you search your country by using this [site](https://ftp.worldometers.info/coronavirus/) just look at the end of the URL of the site then add that name to the variable inside the script...

For instance if my country is Canada I just add rename canada to the Bash script

https://ftp.worldometers.info/coronavirus/country/**canada**/

>#!/bin/bash
>
>country=~~us~~**canada**
>
>...
>
>..
>
>.

