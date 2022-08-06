<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Outfit&display=swap" rel="stylesheet">
    <title>QRCODE</title>
    <style>
        body
    {
        background-color: hsl(212, 45%, 89%);
        font-family: Outfit;
    }
    div.container
    {
        background-color: hsl(0, 0%, 100%);
        width: 370px;
    height: 551px;
    position: fixed;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    border-radius: 12px;
    text-align: center;
    
    }
    .image>img
    {
        margin: 17px 9px 9px 9px;
    width: 340px;
    border-radius: 15px;
    }
    .text
    {
        font-size: 15px;
        margin: 5px 59px;
    }
    .text>h2
    {
        font-weight: 700;
  
    }
    .text>p
    {
       color: hsl(220, 15%, 55%);
       font-weight: 400;

    }
    @media (max-width:375px) {
        div.container
        {
            width: 300px;
            height: 491px;
        }
        .image>img
        {
width: 270px;
        }
        .text
        {
            margin: 2px 29px;
        }
        
    }
    </style>
</head>
<body>
   <div class="container">
    <div class="image">
<img src="/image-qr-code.png">
    </div>
    <div class="text">
        <h2>Improve your front-end skills by building projects</h2>
        <p>Scan the QR to visit Frontend Mentor and take your coding skills to next level.</p>
    </div>
   </div>

</body>
</html>
