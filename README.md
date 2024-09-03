You may created ul and li with their "id" and put the onclick function for language Fr/En :

### Tips for Fr/En language

```
<ul id="language">
	<li id="french" onclick="langFrench()">français</li>
	<li id="english" onclick="langEnglish()">anglais</li>
</ul>
```




### You create style.css for generic index elements and ul language of our design : 
```
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
```



### You can create two .css one for Fr and other for En 

### Fr.css :
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
