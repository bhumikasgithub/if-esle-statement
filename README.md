<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <title>JS</title>
    </head>
    <body>
        <h3>demo on if statement</h3>
    <script>
        //checking the given number is eve or odd
        let n = prompt("enter number")
        if(n%2===0)
    {
       document.write(n+ "is Even number"); 
    } else{
    document.write(n+ "is Odd number");
    }
       </script>
    </body>
</html>

//if esle if statment
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <title>JS</title>
    </head>
    <body>
        <h3>demo on if statement</h3>
    <script>
        // finding biggest of two numbers
        let x = +prompt("enter first number")
        let y = +prompt("enter second number")
        if(x>y)
           document.write("First number is Big"); 
        else if(y>x)
           document.write("Second number is Big");
        else
           document.write("both are same");
       </script>
    </body>
</html>

//switch demo program

<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <title>JS</title>
    </head>
    <body>
        <h3>demo on switch statement</h3>
    
    <script>
    
        let n =  +prompt("enter number b/w 1 to 7")
       switch(n)
       {
        case 1:document.write("Monday");
        break;
        case 2:document.write("Tuesday");
        break;
        case 3:document.write("wednsday");
        break;
        case 4:document.write("Thursday");
        break;
        case 5:document.write("Friday");
        break;
        case 6:document.write("sutarday");
        break;
        case 7:document.write("sunday");
        break;
        default:documdnt.write("Wrong Value");
       }
       </script>
    </body>
</html>

