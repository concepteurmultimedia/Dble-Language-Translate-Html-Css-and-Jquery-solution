style.css : 
```
  html, body, div, ul, li, img, h1, h2, h3 , h4, h5, p {
    box-sizing: border-box;
    padding:0;
    margin:0;
    margin-block-start: 0;
    margin-block-end: 0;
    margin-inline-start: 0;
    margin-inline-end: 0;
    user-select: none;
    pointer-events: auto;
    cursor: default;
  }
  html ul#language{
    width : 50px;
    height:50px;
    top:00px;
    left:50px;
    position :fixed;
    display:block;
    list-style-type:none;
    background-color:rgb(255,255,255);
  }
  html ul#language li#french{
    width:30px;
    height:20px;
    text-indent:-999999999999999999999999999999999999999999999999px;
    background:url("../img/lang/fr.png") no-repeat center center;
    background-size: cover;
    transition:all 0.5s ease;
    position:absolute;
    position:absolute;
    top:13px;
    left:10px;
    display:block;
  }
  html ul#language li#english{
    width:30px;
    height:20px;
    text-indent:-999999999999999999999999999999999999999999999999px;
    background:url("../img/lang/en.png") no-repeat center center;
    background-size: cover;
    transition:all 0.5s ease;
    position:absolute;
    top:13px;
    left:10px;
    display:block;
  }
  html ul#nav{
    margin-top:5%;
    margin-left:5%;
    list-style-type:none;
  }
  html ul#nav li a:hover
  {
    line-height:50px;
    font-size:45px;
    cursor:pointer;
    transition:all 0.5s ease;
  }
  html ul#nav li a{
    text-transform:uppercase;
    text-decoration:none;
    color:rgb(0,0,0);
    transition:all 0.5s ease;
  }
  html p{
    position:absolute;
    top:38%;
    left:35%;
    width:45%;
    margin:auto;
  }
```





Fr.css :
```
.fr{
	display:block !important;
}
.en{
	display:none !important;
}
#english {
	margin-top:0px !important;
	cursor:pointer;
	transition: all 0.5s ease;
}
#french{
	margin-top:-350px !important;
	transition: all 0.5s ease;
}
