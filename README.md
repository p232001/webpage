<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="web.css">
</head>
<body>
    <div id="one">
        <h3>Sensive</h3>
        <h5>Home</h5>
        <h5>Archive</h5>
        <h5>Category</h5>
        <h5>Pages</h5>
        <h5>Contact</h5>
    </div>
    <div id="two">
        <div id="three">
            <h3>Tours & Travels</h3>
            <h2>Amazing Places on earth</h2>
        </div>
    </div>
    <div id="four">
        <div id="overlay"></div>
        <div id="five"></div>
        <div id="six"></div>
        <div id="seven"></div>
        <h2>Newyork fashion week's contined the evolution</h2>
    </div>
</body>
</html>
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
html,body{
    width: 100%;
    height: 100%;
}
#one{
    width: 100%;
    height: 40px;
    background-color: rgb(255, 255, 255);
    display: flex;
    justify-content: space-evenly;
    align-items: center;
}
#one h5{
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    color: rgba(0, 0, 0, 0.815);
}
#one h3{
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    color: rgba(0, 0, 0, 0.815);
}
#two{
    width: 100%;
    height: 100%;
    background-image: url(https://images.unsplash.com/photo-1501785888041-af3ef285b470?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1650&q=80);
    display: flex;
}
#three{
    width: 100%;
    height: 100%;
    background-color: rgba(0, 0, 0, 0.555);
}
#three h2{
    color: white;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    font-size: 40px;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
}
#three h3{
    color: white;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    font-size: 26px;
    position: absolute;
    top: 45%;
    left: 50%;
    transform: translate(-50%, -50%);
}
#four{
    width: 100%;
    height: 100%;
    color: white;
    display: flex;
    justify-content: space-evenly;
    margin-top: 70px;
    position: relative;
}

#five
{
    width: 400px;
    height: 400px;
    background-image: url(https://images.unsplash.com/photo-1565493383251-d3a136e92e6c?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1050&q=80);
    background-position: center;
    background-size: cover;
}
#six
{
    width: 400px;
    height: 400px;
    background-image: url(https://images.unsplash.com/photo-1499894245346-c90612441beb?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1050&q=80);
    background-position: center;
    background-size: cover;
}
#seven
{
    width: 400px;
    height: 400px;
    background-image: url(https://images.unsplash.com/photo-1528311365813-a4039b392fb6?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=634&q=80);
    background-position: center;
    background-size: cover;
}

#four h2{
    color: rgb(10, 10, 10);
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    font-weight: 100;
    font-size: 50px;
    position: absolute;
    top: 60%;
    left: 55%;
    transform: translate(-50%, -50%);
    width: 70%;
}
