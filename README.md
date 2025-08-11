# CODING-SAMURAI-INTERNSHIP-TASK-2
it is a 2 task 

<!DOCTYPE html>
<html lang="en">
<head>
 
    <title>Document</title>
</head>
<link
    href="https://cdn.jsdelivr.net/npm/remixicon@4.5.0/fonts/remixicon.css"
    rel="stylesheet"
/>
<link rel="stylesheet" href="i.css">
<body>
    <div class="main">
     <div class="nav">
        <h2>Logo</h2>
        <div  class="nav-part2">
            <h4>Store</h4>
            <h4>Courses</h4>
            <h4>Career</h4>
            <h4>Blog</h4>
            <h4>Account</h4>
            <button>Sign IN</button>
            <i class="ri-menu-3-fill"></i>
        </div>
     </div>
     <div class="content">
        <div class="left">
            <h1>This is a  <span>landing page</span>
                 and it is very helpful for starting.</h1>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Consectetur, laudantium? Architecto nobis quibusdam, obcaecati consectetur ad quis cumque assumenda ex!</p>
        <button>Explore Now</button>
        </div>

        <div class="right">
<img src="https://tse3.mm.bing.net/th/id/OIP.qNfq_R68u7XK7m8Hf3yNjQHaHX?r=0&rs=1&pid=ImgDetMain&o=7&rm=3" alt="">
        </div>
     </div>
    </div>
   


    <script src="i.js"></script>
</body>
</html>

*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html,body{
    height: 100%;
    width: 100%;
}

.main{
    width: 100%;
    height: 100%;
    position: relative;
}

.nav{
    width: 100%;
    height: 100px;
   border-bottom: 2px solid #dadada;
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 0 5vw;
}

.nav-part2{
    display: flex;
   gap: 4vw;
   align-items: center;
}

.nav h2{
    font-size: 2vw;
    font-weight: 700;
}

.nav h4{
    font-size: 1.2vw;
}


.nav i{
    font-size: 2vw;
    font-weight: 900;
    display: none;
}

.content{
    height: calc(100% - 100px);
    width: 100%;
   position: relative;
     display: flex;
}

.left{
    height: 100%;
    width: 55%;
    padding: 5vw 4vw;
}
.left h1{
 font-size: 4.5vw;
 line-height: 4.4vw;
}
.left h1 span{
    color: lightgreen;
}
.left p{
    font-size: 1.2vw;
    color: #555;
    font-weight: 600;
    width: 80%;
    margin-top: 2vw;
    margin-bottom: 4vw;
}

.right{
    height: 100%;
    width: 45%;
    
}

button{
font-size: 1vw;
padding: 1vw 2vw;
background-color: lightgreen;
color: white;
border: none;
border-radius: 5px;
font-weight: 700;
}

.right img {
    height: 100%;
    width: 100%;
   
}







@media (max-width:600px) {
.nav{
padding: 0 5vw;
height: 60px;
}
.nav h2{
    font-size: 6vw;
}
nav h4{
    font-size: 4vw;
    display: none;
}
.nav i{
    display: block;
    font-size: 6vw;
}

.nav button{
    display: none;
}
.content{
    height: calc(100% - 60px);
flex-direction: column;
}
.left{
    width: 100%;
    height: 50%;
    padding: 4vw 6vw;
}
.right{
    width: 100%;
    height: 50%;
}
.left h1 {
    font-size: 10vw;
    line-height: 11vw;
}
.left p{
    font-size: 3vw;
    width: 90%;
    margin-top: 5vw;
    margin-bottom: 6vw;
}
.content button{
    padding: 3vw 6vw;
    border-radius: 5px;
    font-size: 3vw;
    font-weight: 600;
}
}


