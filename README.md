/* Basic reset and styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Arial', sans-serif;
    line-height: 1.6;
    background-color: #f4f4f4;
    color: #333;
}

.container {
    max-width: 960px;
    margin: 0 auto;
    padding: 0 20px;
}

header {
    background: #333;
    color: #fff;
    padding: 40px 0;
    text-align: center;
    border-bottom: 5px solid #4CAF50;
}

header .profile-pic {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    margin-bottom: 20px;
    border: 5px solid #4CAF50;
}

header h1 {
    font-size: 2.5em;
    margin-bottom: 10px;
}

header p {
    font-size: 1.2em;
    margin-bottom: 20px;
}

header .skills, header .experience {
    margin-bottom: 20px;
    text-align: left;
}

header .skills ul, header .experience ul {
    list-style-type: none;
}

header .skills ul li, header .experience ul li {
    background: #4CAF50;
    color: #fff;
    padding: 10px;
    margin-bottom: 10px;
    border-radius: 5px;
}

section {
    padding: 40px 0;
    background: #fff;
}

section#projects {
    background: #f9f9f9;
}

section h2 {
    text-align: center;
    margin-bottom: 40px;
    font-size: 2.5em;
    color: #333;
    text-transform: uppercase;
    letter-spacing: 1px;
}

.project {
    background: #fff;
    padding: 20px;
    margin-bottom: 20px;
    border-radius: 5px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    transition: transform 0.3s ease, box-shadow 0.3s ease;
    text-align: center;
}

.project:hover {
    transform: translateY(-10px);
    box-shadow: 0 5px 15px rgba(0,0,0,0.2);
}

.project img {
    max-width: 100%;
    border-radius: 5px;
}

.project h3 {
    font-size: 1.8em;
    margin-bottom: 0.5em;
    color: #4CAF50;
}

.project p {
    font-size: 1.2em;
    color: #666;
    margin-bottom: 20px;
}

.project a {
    display: inline-block;
    background: #4CAF50;
    color: #fff;
    padding: 10px 20px;
    text-decoration: none;
    border-radius: 3px;
    transition: background 0.3s ease;
}

.project a:hover {
    background: #45a049;
}

footer {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 20px 0;
    border-top: 5px solid #4CAF50;
}

footer p {
    margin: 0;
    font-size: 1em;
}
