<script setup>

defineProps({
  msg_h1: {
	type: String
  },
	msg_h2:  { 
	type: String }, 
  msg_p_1: {
	type: String
  }
 })
</script>

<template>
<section class="card-story" data-aos="fadeIn">
    <slot name="image"></slot>       
	<div>
                <h1> {{ msg_h1 }}</h1>
                <h2>{{ msg_h2 }}</h2>
                <p>{{ msg_p_1 }}</p>
            </div>
        </section>
</template>

<style scoped>

/*----------------------------------------*/
/*		     ✨  CARD	✨		 		  */
/*----------------------------------------*/

.card-story {
	max-width: 100%;
	display: grid;
	grid-template-columns: 1;
	background: #ecf0f0;
	margin: 20px 0;
	border-radius: 1rem;
	align-self: center;
	border: solid 2px #76645f;
	
}
.card-story h1 {
	margin-bottom: 1rem;
	color: #000;
	font-size: 24px;
	background-color: limegreen;
	border-radius: .5rem;
	padding: 7px 10px;
	width: fit-content;
	border: solid 2px #76645f;
}
.card-story h2 {
color:#fff;
background-color:rgb(49, 24, 24);
border-radius: .8rem;
padding: 5px 10px;
border: solid 2px #76645f;
font-size: 24px;
margin-bottom: 16px;
}

.card-story p {
	line-height: 2.2rem;
    font-size: 16px;
	font-weight: 300;
	letter-spacing: .2px;
	color: #000;
	line-break:normal;
	padding: 16px;
	border-left: solid 2px #c20eb6;
	border-right: solid 2px #c20eb6;
}
.card-story img {
	height: auto;
	width: 30%;
	border-radius: 2rem;
	padding: 1.5rem;
}
.card-story > div {
	padding: 2rem;
}

/*----------------------------------------*/
/*		     ✨ RESPONSIVE ✨		 	  */
/*----------------------------------------*/
/*@media(max-width: 700px) {
.card-story {
		width: 100%; 
		display: block;
		grid-template-columns: 1;
		grid-gap: 2rem;
		margin: 20px auto;
		border-radius: 1rem;
		align-self: center;
		}

	.card-story p {
		line-height: 1.4rem;
		font-size: 16px;
		letter-spacing: .2px;
	}
	.card-story h3 {
		font-size: 1.2rem;
		margin-bottom: .5rem;
		padding: .7rem;
	}
	
	.card-story h2 {
		font-size: 1.2rem;
		margin: 0;
		padding: 4px;
	}
	
		.card-story img {
			width: 80vw;
			height: auto;
			margin: auto;
		}}*/
</style>
