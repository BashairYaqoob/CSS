after you have done the basic html code, go in the head section and under the title, use link and href to connect html with css file
<link rel="stylesheet" href="style.css">

firstly in html, we have added a small text in between the paragraph texts.
to style it open p with curly braces in css and:

color, fontsize

we can do the same in html sheet using style and p. the precendence would of the last line read by compiler

----->style can be applied in 3 ways:
-> .css document
-> by using <style> ---code-----</style> 
-> in line css
------------------------------------------------------------------------------
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
    <style>
        p{
            color: bisque;
        }
    </style>
</head>
<body>
<p style="background-color: blue;">I'm learning</p>    
</body>
</html>
---------------------------------------------


