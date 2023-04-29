
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="view point content=" "width=device_width,initial-scale=1.0">
        <meta http-equiv="X-UA-Compatible" content="ie=edge">
        <title>Educo</title> 
        <link rel="stylesheet" href="style.css">

    </head>
    <body background="computer.jpg"  background-size: 250ch;
    background-position: 250ch;
>
        <font size="2" face="verdana"
        <form action="results.html" method="GET">
            
            <div>
                <label for="name">Name </label>
                <input type="text" name="name" id="name" placeholder="username" required>
            </div>
            <div>
                <label for="email">Email</label>
                <input type="email" name="email" id="email" placeholder="mail" required>  
            </div>
            <div>
                <label for="age"> Age</label>
                <input type="number" name="age" id="age" min="1" max="200" step="1">
            </div>
            <div>
                <label for="date"> Birthdate</label>
                <input type="date" name="date" id="date" min="1975/01/01">
            </div>
            <div>
                Gender
                <div>
                    <label for="male"> Male</label>
                    <input type="radio" name="gender" id="Male>"
                </div>
                <div>
                    <label for="Female"> Female</label>
                    <input type="radio" name="gender" id="Female>"
                </div>
            </div>
            <div>
                Course Name
                <div>
                <label for="web designing"> Web designing</label>
                <input type="checkbox" name="web designing" id="web designing">
                </div>
                <div>
                <label for="video editing"> Video Editing</label>
                <input type="checkbox" name="Video Editing" id="Video Editing">
                <div>
                <div>
                    <label for="Programmimg"> Programmimg</label>
                    <input type="checkbox" name="Programming" id="Programming">
                    <div>
                </div>
                <label>Password</label>
                <input type="password" name="password" placeholder="password" required>
            </div>
            <div class="box"></div>
            <div id="div1"></div>
            <button class="btn">click mw</button>
            </div>
            <button type="reset"> Reset</button>
            <button type="submit"> Submit</button>
            </div>
        </font>
        </form>
    </body>
</html>
