<template>
     <section data-aos="fadeIn">
            <ul>
                <li><img src="resources/img/incense_burning.jpg" alt="Balinese prayer offering"></li>
                <li><img src="resources/img/TyaNevin_Sebatu.jpg" alt="Praying"></li>
                <li><img src="resources/img/Tya_offerings4.jpg" alt="Balinese spiritual tools"></li>
                <li><img src="resources/img/B1.jpg" alt="Balinese bells"></li>
                <li><img src="resources/img/Tya_sebatu_morning_light.jpg" alt="Sebatu"></li>
                <li><img src="resources/img/Tya_statue.jpg" alt="East Bali"></li>
                <li><img src="resources/img/trekking2.jpg" alt="Trekking in Bali"></li>
                <li><img src="resources/img/ulu/3.jpeg" alt="Uluwatu cliffs"></li>
            </ul>
        </section>
</template>

<style scoped>

ul {
list-style: none;
width: 100%;
float: left;
padding: 0;
margin: 2px;
border: 2px solid lime;
background-color: rgb(118, 112, 112);
}

 li {
	display: block;
	float: left;
	width: 25%;
    content: fill;
	margin: 0;
	padding: 0;
	overflow:hidden;
	background-color: ;
}

 img {
	opacity: 0.7;
	width: 100%;
	height: auto;
	transform: scale(1.15);
	transition: transform 0.5s, opacity 0.5s;
	margin: 0;
	padding: 0;
        overflow: hidden;
	background-color: #000;
}

img:hover {
	opacity: 1;
	transform: scale(1.03);
}

/*----------------------------------------*/
/*		     ✨ RESPONSIVE ✨		 	  */
/*----------------------------------------*/

/*@media(max-width: 1124px) {

ul {
list-style: none;
width: 100vw;
padding: 0;
}

    li {
	display: grid;
    grid-template-columns: 1fr;
    grid-area: 0;
	width: 48vw;
	margin: 0;
    overflow: hidden;
}

 img {
	opacity: 0.7;
	width: 100%;
	height: auto;
	transform: scale(1.15);
	transition: transform 0.5s, opacity 0.5s;
	margin: 0;
	padding: 0;
    overflow: hidden;
	background-color: #000;
}

img:hover {
	opacity: 1;
	transform: scale(1.03);
}

}*/
</style>