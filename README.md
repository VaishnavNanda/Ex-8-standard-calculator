# Design of a Standard Calculator

## AIM:

To design a web application for a standard calculator.

## DESIGN STEPS:

### Step 1:
Clone the github repository and create Django admin interface.

### Step 2:
Change settings.py file to allow request from all hosts.

### Step 3:
Use CSS for creating attractive colors.

### Step 4:
Write JavaScript program for implementing five different operations.

### Step 5:
Validate the HTML and CSS code.

### Step 6:
Publish the website in the given URL.

## PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>SEC Demo on Calculator</title>
        <style>
        table{
            border: 10px solid maroon;
            margin-left: auto;
            margin-right: auto;
        }
        input[type="text"]{
            border: 5px solid goldenrod;
            padding: 20px 30px;
            font-size: 24px;
            font-weight: bold;
            border-radius: 2px;
        }


        input[type="button"]{
            width: 100%;
            padding: 20px 40px;
            background-color:salmon;
            border-radius: 2px;
        }
        </style>
    </head>
    <body>
        <form name="form1" onload="result.value=''">
            <h1 style="text-align: center;color:red;">Simple Calculator</h1>
        <table id="calc">
            <tr>
                <td colspan="4">
                    <input type="text" id="result">
                </td>
            </tr>
            <tr>
                <td><input type="button" value="1" onclick="result.value+='1'"></td>
                <td><input type="button" value="2" onclick="result.value+='2'"></td>
                <td><input type="button" value="3" onclick="result.value+='3'"></td>
                <td><input type="button" value="+" onclick="result.value+='+'"></td>
            </tr>
            <tr>
                <td><input type="button" value="4" onclick="result.value+='4'"></td>
                <td><input type="button" value="5" onclick="result.value+='5'"></td>
                <td><input type="button" value="6" onclick="result.value+='6'"></td>
                <td><input type="button" value="-" onclick="result.value+='-'"></td>
            </tr>
            <tr>
                <td><input type="button" value="7" onclick="result.value+='7'"></td>
                <td><input type="button" value="8" onclick="result.value+='8'"></td>
                <td><input type="button" value="9" onclick="result.value+='9'"></td>
                <td><input type="button" value="*" onclick="result.value+='*'"></td>
            </tr>
            <tr>
                <td><input type="button" value="/" onclick="result.value+='/'"></td>
                <td><input type="button" value="0" onclick="result.value+='0'"></td>
                <td><input type="button" value="." onclick="result.value+='.'"></td>
                <td><input type="button" value="=" onclick="result.value=eval(result.value)"></td>
            </tr>
            <tr>
                <td colspan="4">
                    <input type="button" value="C" id="clear" onclick="result.value=''">
                </td>
            </tr>
        </table>
        </form>
    </body>
</html>
```

## OUTPUT:
![calc](https://user-images.githubusercontent.com/118707051/215272933-c1f118d7-fb0a-491f-8961-7a7c8c9f4957.jpg)

## HTML VALIDATOR:
![validationcalc](https://user-images.githubusercontent.com/118707051/215272940-58890096-d955-468d-aec1-0b7859de0ed8.jpg)

## RESULT:
Thus a web application for standard calculator is designed.
