<template>
<header>
    <h1>Jero Tya</h1>
    
            <ul>
                <li><a href="contact.html">Contact</a></li>
                <li><a href="gallery.html">Gallery</a></li>
                <li><a href="blog.html">Blog</a></li>
            </ul>
</header>
</template>

<style>

main {
	max-width: 100vw;

}


header h1 {
color: #e7b706;
font-weight: 300;
text-transform: uppercase;
font-size: 64px;
transition: .4s;
margin: 1vw; 
padding: 0;
}

/*----------------------------------------*/
/*		     ✨ NAVIGATION ✨		 	  */
/*----------------------------------------*/

ul {
	padding-bottom: 75%;
}

 li {
	display: inline-block;
	margin: 2vw;
	
}

li a:link,
	li a:visited {
	border-bottom: 2px solid rgb(253, 216, 216);
	border-top: 1px solid rgb(250, 247, 247);
	background-color:#000;
	opacity: .7;
	border-radius: 10px; 
	padding: 5px;
	transition: .6s;
	font-size: 22px;
	text-transform: uppercase;
	}

li a:hover,
li a:active {
	border-bottom: 2px solid rgb(253, 216, 216);
	background-color:#000;
	opacity: 1;
	border-radius: 10px; 
	padding: 5px;
	transition: .6s;
}

/*----------------------------------------*/
/*		     ✨ RESPONSIVE ✨		 	  */
/*----------------------------------------*/

/*@media(max-width: 700px) {
	
	ul {
		list-style: none;
		padding-bottom: 80%;
		padding-left: 0;
	}
	
	 li {
		display: inline-block;
		padding: 10px;
		font-size: 10px;
	
	}
	
	li a:link,
	li a:visited {
	border-bottom: 2px solid rgb(253, 216, 216);
	border-top: 1px solid rgb(250, 247, 247);
	background-color:#000;
	opacity: 1;
	border-radius: 10px; 
	padding: 5px;
	transition: .6s;
	font-size: 16px;
	text-transform: uppercase;
}

	li a:hover,
	li a:active {
	opacity: .6;
	border-radius: 10px; 
	padding: 5px;
	transition: .6s;
	color:black;
}

	header {
			max-width: 100vw;
			height: auto;
			display: block;
		}
	
	header h1 {
		font-size: 46px;
		text-transform: uppercase;
		margin: 0;
	
	}}*/
</style>