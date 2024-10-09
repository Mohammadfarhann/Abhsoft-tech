<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Web Page with Table</title>
    <style>
      body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #333;
    color: #fff;
}

nav {
    display: flex;
    justify-content: center;
    padding: 1rem 0;
}

ul {
    list-style: none;
    padding: 0;
}

li {
    margin: 0 15px;
}

a {
    text-decoration: none;
    color: white;
    transition: color 0.3s;
}

a:hover {
    color: #ffa500; /* Change color on hover */
}

main {
    text-align: center;
    padding: 2rem;
}

table {
    width: 80%;
    margin: 20px auto;
    border-collapse: collapse;
    background-color: #fff;
}

th, td {
    border: 1px solid #ddd;
    padding: 10px;
    text-align: left;
}

th {
    background-color: #333;
    color: white;
}

tr:hover {
    background-color: #f1f1f1; /* Highlight row on hover */
}
    </style>
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <h1>Welcome to Our Website</h1>
        <p>This is a simple web page with a navigation bar and a data table.</p>
        
        
