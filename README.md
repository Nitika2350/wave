# wave
<html>
     <head>
         <style>
             body{
                 background:blue;
                 display:flex;
                 align-items:center;
                 justify-content:center;
                 min-height:100vh;
                 margin:0px;
                 padding:2px;
             }
             div{
                 position:relative;
                 display:flex;
                 justify-content: center;
                 align-items: center;
             }
             span{
                 position:absolute;
                 display:block;
                 box-shadow:0px 30px 1px aqua;
                 border-radius: 50%;
                 border:5px solid red;
                 }
             span:nth-child(1){
                 height:10px;
                 width:10px;
                 animation: one 4s linear infinite;
             }
             @Keyframes one{
                 0%{
                     height:0px;width:0px;opacity:1;}
                 100%{height:400px;width:400px;opacity:0;}
                 }
             }
             span:nth-child(2){
                 height:50px;
                 width:50px;
                 animation:two 4s linear infinite;
                 animation-delay:.5s;
             }
             @keyframes two{
                 0%{height:0px;width:0px;opacity:1;}
                 100%{height:400px;width:400px;opacity:0;}
             }
             span:nth-child(3){
                 height:100px;
                 width:100;
                 animation:three 4s linear infinite;
                 animation-delay:1s;
             }
             @keyframes three{
                 0%{height:0px;width:0px;opacity:1;}
                 100%{height:400px;width:400px;opacity:0;}
             }
             span:nth-child(4){
                 height:150px;
                 width:150px;
                 animation:four 4s linear infinite;
                 animation-delay:1.5s;
             }
             @keyframes four{
                 0%{height:0px;width:0px;opacity:1;}
                 100%{height:400px;width:400px;opacity:0;}
             }
             span:nth-child(5){
                 height:200px;
                 width:200px;
                 animation:five 4s linear infinite;
                 animation-delay:2s;
             }
             @keyframes five{
                 0%{height:0px;width:0px;opacity:1;}
                 100%{height:400px;width:400px;opacity:0;}
             }
             span:nth-child(6){
                 height:250px;
                 width:250px;
                 animation:six 4s linear infinite;
                 animation-delay:2.5s;
             }
             @keyframes six{
                 0%{height:0px;width:0px;opacity:1;}
                 100%{height:400px;width:400px;opacity: 0;}
             }
             span:nth-child(7){
                 height:300px;
                 width:300px;
                 animation:seven 4s linear infinite;
                 animation-delay:3s;
             }
             @keyframes seven{
                 0%{height:0px;width:0px;opacity:1;}
                 100%{height:400px;width:400px;opacity:0;}
             }
             span:nth-child(8){
                 height:350px;
                 width:350px;
                 animation:eight 4s linear infinite ;
                 animation-delay:3.5s;
             }
             @keyframes eight{
                 0%{height:0px;width:0px;opacity:1;}
                 100%{height:400px;width:400px; opacity;0;}
             }
         </style>
    </head>
    <body>
        <h1 style="color:yellow;text-align: left;">WAVE</h1>
        <div>
         <span></span>  
        <span></span>   
        <span></span>   
        <span></span>
        <span></span>    
        <span></span>   
         <span></span>
        <span></span> 
        <span></span>
        <span style="border-color:aqua"></span>
        </div>
         </body>
</html>
