# CSCI 1250 – Data Lab: Working with Arrays and Lists

## Introduction
This lab will reinforce topics covered in the lectures about working with simple collections, primarily **arrays** and **lists**.

***

## Part 0: Setup

1.  Create a new C# **console project**, being sure to use **“.Net”** and not **“.Net Framework”**. The version of .Net used must be at least **version 8**.

***

## Part 1: Finding an Average

1.  Create a **Method** called `GetAverage`, that accepts an **array of integers** as its parameter, and returns a **double**.
2.  Use a **for-loop** to determine the **sum total** of the array of integers.
3.  Divide the total by the number of elements in the array to determine the average value.
    3.1. **Hint**: Research the **`.Length`** property of arrays.
4.  The method should return the average value of the integers as a **double** so that the average can contain fractional values.
5.  Inside of your main method, create a simple array of integers using **`{1,2,3}`**-style notation.
6.  Use your `GetAverage` method to determine and display the average of that array.

***

## Part 2: Getting an Array from a User

1.  Inside of your main method, do the following:
2. Prompt the user for the **number of integers** they would like to enter.
3. Create a **new array of integers** of that size.
4.  Using a **for-loop**, prompt the user for each number individually, and store them into the array that you just created.
5. Once they have entered all of the numbers, use your **`GetAverage`** method from **Part 1** to display the average value of the user’s input.

***

## Part 3: Reverse an Array

1.  Create a new array of integers of any size.
2.  Display the array in **reverse order**.
3.  **Hint**: Remember that merely printing an array method will result in the array’s data type being printed. Research **`string.Join()`**;

***

## Part 4: Minimum, Maximum, and Mean

1.  Create a new array of integers of any size.
2.  Research how you can **sort the array**.
    2.1. **Hint**: You should not need to implement your own sorting algorithm.
3.  Once the array is sorted, display the **minimum**.
    3.1. Leave a **comment** describing how you know that is the minimum value.
4.  Once the array is sorted, display the **maximum**.
    4.1. Leave a **comment** describing how you know that is the maximum value.
5.  Once the array is sorted, display the **mean** (average).
    5.1. Leave a **comment** describing how you know that is the mean.

***

## Part 5: Histogram

1.  Prompt the user to enter exactly **5 values from 1 to 10**.
    1.1. **Hint**: Continue using a similar technique to one of the methods outlined in **Part 2**.
2.  Display a **histogram** using **asterisks**. Look into string creation, or go number-by-number up to 10.
    2.1. **Example**:
        *Input*: `3 7 4 1 5`
        *Output*:
        ```
        ***
        *******
        ****
        *
        *****
        ```

***

## Part 6: FileIO

1.  Determine if a **“names.txt”** file exists in your executable’s directory.
    1.1. **Hint**: Research the **`File.Exist`** method.
2.  If the file exists, then **read all the lines** from the file and display them to the console.
3.  If the file does not exist…
4.  Create a **new list of strings**.
5.  Prompt the user to add any names to the list (separated by **commas**).
6.  Create a **foreach loop** to add each name entered into the console to the list (research **`.Split()`** method).
7.  **Write the list out** to the **“names.txt”** file.

***

## Submission

Zip up all of your code. Be sure to include the following:
* All **.cs** files
* All **.csv** files
* All **.csproj** files
* Any **.sln** files if your editor generated one or more for you.

Submit your zipped file to the dropbox.

If you do not know how to zip up a folder or group of files, follow the appropriate guide below:
* Windows 10 - [https://www.howtogeek.com/668409/how-to-zip-and-unzip-files-on-windows-10/](https://www.howtogeek.com/668409/how-to-zip-and-unzip-files-on-windows-10/)
* Windows 11 - [https://www.howtogeek.com/749206/how-to-zip-and-unzip-files-on-windows-11/](https://www.howtogeek.com/749206/how-to-zip-and-unzip-files-on-windows-11/)
* MacOS - [https://www.howtogeek.com/672240/how-to-zip-and-unzip-files-and-folders-on-mac/](https://www.howtogeek.com/672240/how-to-zip-and-unzip-files-and-folders-on-mac/)
* Linux (most common distributions) - [https://www.howtogeek.com/414082/how-to-zip-or-unzip-files-from-the-linux-terminal/](https://www.howtogeek.com/414082/how-to-zip-or-unzip-files-from-the-linux-terminal/)

Occasionally, D2L will reject your submission because it thinks it is a virus. Double check to ensure your work was successfully submitted to the dropbox. If your submission is rejected by D2L, you can delete the folders **"obj"** and **"bin"**. They are unnecessary. These folders are where the executable versions of your program are stored. Deleting them is enough to satisfy D2L.

*Original lab by Professor Jacob Gillenwater, ETSU Dept. of Computing*
