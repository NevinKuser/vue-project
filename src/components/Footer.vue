<template>
<footer>
        <img src="../assets/logo.svg" alt="Vue logo">
        <p>✨ Copyright &copy; 2022 by Jero Mangku Istri Tya.<br> All rights reserved.</p>
    </footer>
</template>

<style scoped>
footer {
	height: 100px;
	max-width: 100%;
	background-image: linear-gradient(#080808, #7f8c8d, #080808);
    overflow: hidden;
    border: 2px solid lime;
    background-repeat: no-repeat;
}

footer img {
	height: 70px;
	width: auto;
	float: left;
    margin: 15px;
    padding-left: 20px;
}

footer p {
	color: #fff;
	font-size: 12px;
    text-align: center;
    padding: 24px;
}

/*----------------------------------------*/
/*		     ✨ RESPONSIVE ✨		 	  */
/*----------------------------------------*/

/*@media(max-width: 1000px) {
footer {
 width: 100vw;
 height: 80px;
}
footer p {
	font-size: 16px;
    padding-top: 16px;
    padding-bottom: 16px;
    padding-right: 16px;
}

footer img {
	height: 50px;
    margin: 15px;
}
}*/
</style>