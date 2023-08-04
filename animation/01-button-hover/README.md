<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hover button</title>
    <link rel="stylesheet" href="style.css"/>
</head>
<body>
    <div>
        <button>Transition</button>
    </div>
</body>
</html>


div {
    width: 100px;
    height: 100px;
    align-items: center;
    font-family: Arial, sans-serif;
    margin : 500px auto;
    transition-duration: 0.2s;

}



button {
    border-radius: 8px;
    border: none;
    background-color: #2563eb;
    color: white;
    font-size: 18px;
    padding: 16px 24px;
    text-align: center;

    
}
button:hover {
  
    cursor: pointer;
    transform: scale(1.50);
    
}




