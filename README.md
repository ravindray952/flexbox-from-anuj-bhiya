# flexbox-from-anuj-bhiya  and vishal rajput    but pdna hai apko from vishal rajput
link : freecodecamp  https://www.freecodecamp.org/news/flexbox-the-ultimate-css-flex-cheatsheet/


8 times div created with 12345  with box

 .container>box*8{box-$} 

 <div class="container">
        <div class="box">box-1</div>
        <div class="box">box-2</div>
        <div class="box">box-3</div>
        <div class="box">box-4</div>
        <div class="box">box-5</div>
        <div class="box">box-6</div>
        <div class="box">box-7</div>
        <div class="box">box-8</div>
      </div>

/
html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>flexbox</title>
     <link rel="stylesheet" href="style.css"> 
</head>
<body>
      <div class="container">
        <div class="box" id="box-1">box-1</div>
        <div class="box" id="box-2">box-2</div>
        <div class="box" id="box-3">box-3</div>
        <div class="box" id="box-4">box-4</div>
        <div class="box" id="box-5">box-5</div>
        <div class="box" id="box-6">box-6</div>
        <div class="box" id="box-7">box-7</div>
        <div class="box" id="box-8">box-8</div>
      </div> 
</body>
</html>



css






*{
    box-sizing: border-box;
}
.container{
    height: 400px;
    border: 2px solid red;
    display: flex;  
    /* flex-direction: column-reverse; */
    /* flex-wrap: wrap-reverse; */
     
    /* row-gap: 10px; */
     flex-flow: row;
    /* justify-content: space-around;   */
    /* justify-content: space-between; */
    /* justify-content: flex-start; */
    /* justify-content: flex-end; */
    justify-content: center;
    align-items: center;
    align-content: space-evenly;

       
} 

.box{
    border: 2px solid green;
    width: 80px;
    flex-basis: 25%;
} 

#box-1 {
    /* order: 1;
    flex-grow: 1;
    flex-shrink: 2; */
    flex-basis: 200px;
}

 #box-3 {
   flex: 0 0 200px;     
   align-self: self-start;
}

#box-4 {
    /* flex-shrink: 3; */
}

