## Test Yourself

Have a go at the questions below to see how well you've understood the project.

1. Which of the following extensions contains the code blocks needed to play drum sounds?
![scratch extensions](images/extensions.png)
<html lang="en">
<head>
<meta charset="utf-8">
<title>jQuery Show Hide Elements Using Checkboxes</title>
<style type="text/css">
    .box{
        color: #fff;
        padding: 20px;
        display: none;
        margin-top: 20px;
    }
    .A{ background: #228B22; }
    .B{ background: #ff0000; }
    .C{ background: #ff0000; }
    .D{ background: #ff0000; }
    label{ margin-right: 15px; }
</style>
<script src="https://code.jquery.com/jquery-1.12.4.min.js"></script>
<script type="text/javascript">
$(document).ready(function(){
    $('input[type="checkbox"]').click(function(){
        var inputValue = $(this).attr("value");
        $("." + inputValue).toggle();
    });
});
</script>
</head>
<body>
    <div>
        <label><input type="checkbox" name="colorCheckbox" value="A"> A</label>
        <label><input type="checkbox" name="colorCheckbox" value="B"> B</label>
        <label><input type="checkbox" name="colorCheckbox" value="C"> C</label>
        <label><input type="checkbox" name="colorCheckbox" value="D"> D</label>
    </div>
    <div class="A box">Well done, that is the correct extension</div>
    <div class="B box">Try again, this extension lets you draw on the stage</div>
    <div class="C box">Try again, this extension lets you use the computer's camera</div>
    <div class="D box">Try again, this extension can get your computer to talk</div>
</body>
</html>
2. Which of the following scripts would play a `Hand Clap` when the spacebar is pressed?

A.
```blocks3
when [x v] key pressed
play drum [(8) Hand Clap v] for (0.25) beats
```
B.
```blocks3
when [space v] key pressed
play drum [(8) Hand Clap v] for (0.25) beats
```
C.
```blocks3
when [space v] key pressed
play drum [(5) Open Hi-Hat v] for (0.25) beats
```
D.
```blocks3
when this sprite clicked
play drum [(8) Hand Clap v] for (0.25) beats
```
<html lang="en">
<head>
<meta charset="utf-8">
<title>jQuery Show Hide Elements Using Checkboxes</title>
<style type="text/css">
    .box{
        color: #fff;
        padding: 20px;
        display: none;
        margin-top: 20px;
    }
    .A{ background: #ff0000; }
    .B{ background: #228B22; }
    .C{ background: #ff0000; }
    .D{ background: #ff0000; }
    label{ margin-right: 15px; }
</style>
<script src="https://code.jquery.com/jquery-1.12.4.min.js"></script>
<script type="text/javascript">
$(document).ready(function(){
    $('input[type="checkbox"]').click(function(){
        var inputValue = $(this).attr("value");
        $("." + inputValue).toggle();
    });
});
</script>
</head>
<body>
    <div>
        <label><input type="checkbox" name="colorCheckbox" value="A"> A</label>
        <label><input type="checkbox" name="colorCheckbox" value="B"> B</label>
        <label><input type="checkbox" name="colorCheckbox" value="C"> C</label>
        <label><input type="checkbox" name="colorCheckbox" value="D"> D</label>
    </div>
    <div class="A box">Try again, this script works when the x key is pressed</div>
    <div class="B box">Well done, this script plays a hand clap when space is pressed</div>
    <div class="C box">Try again, this script plays the Hi Hat</div>
    <div class="D box">Try again, this script works when the sprite is clicked</div>
</body>
</html>

3. Which of the following scripts would change the costume of a sprite when it has been clicked on?

A.
```blocks3
when this sprite clicked
switch costume to (costume2 v)
```
B.
```blocks3
when flag clicked
show
```
C.
```blocks3
when this sprite clicked
show
```
D.
```blocks3
when I receive [change costume v]
switch costume to [costume2 v]
```
<html lang="en">
<head>
<meta charset="utf-8">
<title>jQuery Show Hide Elements Using Checkboxes</title>
<style type="text/css">
    .box{
        color: #fff;
        padding: 20px;
        display: none;
        margin-top: 20px;
    }
    .A{ background: #228B22; }
    .B{ background: #ff0000; }
    .C{ background: #ff0000; }
    .D{ background: #ff0000; }
    label{ margin-right: 15px; }
</style>
<script src="https://code.jquery.com/jquery-1.12.4.min.js"></script>
<script type="text/javascript">
$(document).ready(function(){
    $('input[type="checkbox"]').click(function(){
        var inputValue = $(this).attr("value");
        $("." + inputValue).toggle();
    });
});
</script>
</head>
<body>
    <div>
        <label><input type="checkbox" name="colorCheckbox" value="A"> A</label>
        <label><input type="checkbox" name="colorCheckbox" value="B"> B</label>
        <label><input type="checkbox" name="colorCheckbox" value="C"> C</label>
        <label><input type="checkbox" name="colorCheckbox" value="D"> D</label>
    </div>
    <div class="A box">Well done, this script changes the costume when the sprite is clicked </div>
    <div class="B box">Try again, this script changes costume when the green flag is clicked</div>
    <div class="C box">Try again, this script shows a hidden sprite when it is clicked</div>
    <div class="D box">Try again, this script switches the costume when it receives a broadcast</div>
</body>
</html>
