You may created ul and li with their "id" and put the onclick function for language Fr/En :

### Tips for Fr/En language : index.html
Put a class="fr" or class="en" attribut on ours elements in page
```Html
<ul id="language">
	<li id="french" onclick="langFrench()">français</li>
	<li id="english" onclick="langEnglish()">anglais</li>
</ul>
```


### Tips for Fr/En function : language.js
```Js
function langFrench(){
	$( "#french" ).on( "click", function() {
		$("#language").attr("href", "./css/Fr.css");
	} );
	}
function langEnglish() {
	$( "#english" ).on( "click", function() {
		$("#language").attr("href", "./css/En.css"); 			
	} );
}



### You create style.css for generic index elements and ul language of our design : 
```Css
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
```CSS
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
```
### En.css :
```Css
.fr{
	display:none !important;
}
.en{
	display:block !important;
}
#english {
	margin-top:-350px !important;
	transition : all 0.5s ease !important;
}
#french{
	margin-top:0px;
	cursor :pointer;
	transition : all 0.5s ease !important;
	cursor:pointer;
}
```
