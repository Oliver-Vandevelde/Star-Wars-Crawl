# Star-Wars-Crawl
.texte{
    position:absolute;
    top:-3500px;
    bottom:0;
    left:0;
    right:0;
    overflow:hidden;
    font-size:30px;
    text-align:center;
    font-family:sans-serif;
}
.texte>div{
    padding-top:3500px;
    animation:autoscroll 1000s linear;
}
html:after{
    content:'';
    position:absolute;
    top:0;
    bottom:0;
    left:0;
    right:0;
    background:linear-gradient(top,rgba(0,0,0,1),rgba(0,0,0,0) 100%);
    background:linear-gradient(to bottom,rgba(0,0,0,1),rgba(0,0,0,0) 100%);
    pointer-events:none;
}

body{
    
    position:absolute;
    top:0;
    bottom:0;
    left:0;
    right:0;
    transform-origin:50% 100%;
    transform:perspective(300px) rotateX(20deg);
}
html{
    color:yellow;
    background:black;
}
@keyframes autoscroll{
    to{
        margin-top:-50000px;
    }    
} cheat.