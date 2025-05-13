* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: sans-serif;
}

#header {
    background-color: #0e3b66;
    display: flex;
    align-items: center;
    justify-content:center;
    padding: 10px;
    gap: 16px;
     /* logo আর h1 এর মাঝে ফাঁকা */
    width: 100%;
}

#header img {
    width: 20%;
    height:20%;
    flex-shrink: 0;
    margin-left:3%;
}

#header h1 {
    font-size: clamp(10px, 3vw, 480px);
    color: #ffffff;
    line-height: 1.2;
    flex: 1;
    align-items: center;
    justify-content:center;
    margin-right:10%;
}
li{
    item-algin:right;
    list-style-type:none;
    
    
}
a{
    text-decoration:none;
    font-size:5px;               
               text-decoration:none;
               color:white;
               text-align:center;
}
#welcome{
    height: auto;
    width: 100%;
    margin-top:0%;
    
}
#about-us-p{
    margin-right: 50%;
    font-size:clamp(6px,2vw,200px);
}
#h2-about{
    font-size:3vw;
}
