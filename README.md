<!DOCTYPE html>
<html>

<head>
 <meta charset="UTF-8">
 <meta name="viewport" content="width=device-width, initial-scale=1">
 <title></title>
 <style>
 *{
  margin: 0;
  padding: 0;
  box-sizing:border-box;
 }
  body{
   display:flex;
   align-items: center;
   justify-content: center;
   min-height: 100vh;
   
  }
  .container{
   position: relative;
  display:flex;
   align-items: center;
   justify-content: center;
  }
  .container .card{
   position: relative;
   
   width:440px; 
   height:350px;
   display:flex;
   margin: 20px;
   justify-content: flex-start;
   align-items: center;
   background: linear-gradient(30deg,#1a2f3f,#7094ce);
  }
  .container .card img{
   position:absolute;
   bottom:0;
   height: 400px;
   left: 50%;
   transform: translateX(-50%);
   transition: 0.5s;
   }
  .container .card:hover img{
   left: 73%;
   height: 500px;
  }
  .container .card .content {
   position:relative;
   left:20%; 
   width:50%;
   padding:20px 20px 20px 40px;
   transition: 0.5s;
   opacity: 0;
   visibility: hidden;
  }
  .container .card:hover .content{
   left:1%;
   opacity: 1;
   visibility: visible;
   
  }
  .container .card .content h2{
   color:#fff;
   text-transform: uppercase;
   font-size: 2.2em;
   line-height: 1em;
  } 
  .container .card .content p{
   color:#fff;
  }
 .container .card .content a{
  position: relative;
  display: inline-block;
  color: #111;
  background:#fff; 
  padding: 10px 20px;
  margin-top:10px;
  text-decoration: none;
  font-weight: 100;
 } 
   
 @media screen and (max-width:770px){
  .container{
   display:flex;
   align-items: center;
   justify-content:center;
   flex-direction:column ;
  }
  
  .container .card{
   position: relative;
   
   width:400px; 
   height:330px;
   display:flex;
   flex-direction: column;
   margin: 20px;
   justify-content:center;
   align-items: center;
   background: linear-gradient(30deg,#1a2f3f,#7094ce);
  }
  .container .card img{
   width: 
   height:;
  }
 }
 </style>
</head>

<body>

 <div class="container">
  <div class="card">
   <div class="content">
    <h2>Nathan drake</h2>
    <p>Lomes is a not so a program to get a good time for a while on a program that we have a program for </p>
    <a href="#">Read more</a>
   </div>
   <img src="nathan.png">
  </div>
   <div class="card">
   <div class="content">
    <h2>sam drake</h2>
    <p>Lomes is a not so a program to get a good time for a while on a program that we have a program for </p>
    <a href="#">Read more</a>
   </div>
   <img src="sam.png">
   </div>
</div>
</body>

</html>