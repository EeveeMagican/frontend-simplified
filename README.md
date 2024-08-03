https://frontendsimplified.com/
paid $27 to learn how to code in a simplified manner for frontend developers, working with HTML/CSS and simple coding like Javascript.... eventually. (that's later on in the lessons).
Followed the video step by step, including examples of folders being moved and needing to reconnect them. these are the 3 pages left when all is said and done:

In order:
index.html
dashboard.html
login.html

This is utilizing Visual Studio Code (google search, install for your computer type)
Extentions purposefully used:  
  Live Server | Mithril Emmet | Prettier - Code Format



<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE-edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1>Auto save is turned on </h1>
    <h1> H1 text </h1>
        </p> Lorem ipsum dolor sit amet consectetur, adipisicing elit. Recusandae quibusdam tenetur dolores iure porro eaque odit quaerat nulla excepturi cumque voluptatibus possimus quae, sequi nobis dolorem veniam quo maiores minima?
     </p>
    <h2> H2 text </h2>
    <h3> H3 text </h3>
    <h4> H4 text </h4>
    <h5> H5 text </h5>
    <h6> H6 text </h6>
    <a href="https://discord.gg/frontend" target="_blank"> Discord Server</a>
    <p>this creates the link in a new page</p>
    <a href="/html_pages/dashboard.html">Dashboard</a>
</body>
</html>




<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE-edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <nav>
        Logo
        <button><a href="/html_pages/index.html">Home</a></button>
    </nav>
    <main>
        <section>
            <h1> To do list</h1>
            <p> Lets get this stuff done by EOY.</p>
            <img src="../assets/dashboard/unnamed.jpg" alt="picture">
            <ul>
                <li> Land $100k job</li>
                <li> Finish Frontend Simplified</li>
                <li> Network with other people in the discord server</li>
            </ul>
        </section>
        <section>
            <h1> Land $100k job></h1>
            <ol>
                <li> Finish Frontend Simplified </li>
                <li> Study for interviews</li>
                <li> Apply to jobs </li>
            </ol>
        </section>
    </main>
    <footer>
        Copyright terms & conditions
    </footer>
</body>
</html>




<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE-edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1>Login</h1>
    <form>
        <hr>
            <label for="">Email</label>
            <input type="email" />
        </hr>
        <hr>
            <label for="">Password</label>
            <input type="password" />
        </hr>
        <hr>
            <label for="">Age</label>
            <input type="number" />
        </hr>
        <hr>
            <label for="">Date</label>
            <input type="date" />
        </hr>
        <hr>
            <label for=""> Extra Information</label>
            <textarea rows="10">enter text here...</textarea>
        </hr>
    </form>
    <div>
        <span></span>
    </div>
        <button>Submit</button>
    </form>
</body>
</html>


