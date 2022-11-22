<script setup>

defineProps({
  msg_h1: {
	type: String
  },
	msg_h2:  { 
	type: String }, 
  msg_p_1: {
	type: String
  },
  msg_p_2: {
	type: String
  },
  phoneNumber: {
	type: String
  }
 })
</script>

<template>
<section class="card" data-aos="fadeIn">
    <slot name="image"></slot>       
	<div>
                <h1> {{ msg_h1 }}</h1>
                <h2>{{ msg_h2 }}</h2>
                <p>{{ msg_p_1 }}</p>
				<p>{{ msg_p_2 }}</p>
				<p>{{ phoneNumber }}</p>
				<slot name="blog"></slot>
            </div>
        </section>
</template>

<style scoped>

/*----------------------------------------*/
/*		     ✨  CARD	✨		 		  */
/*----------------------------------------*/

.card {
	max-width: 100%;
	background: #ecf0f0;
	margin: 20px 0;
	border-radius: 1rem;
	border: solid 2px #76645f;
	
}
.card h1 {
	margin-bottom: 1rem;
	color: #fff;
	font-size: 24px;
	background-color: rgb(109, 114, 109);
	border-radius: .5rem;
	padding: 7px 10px;
	width: fit-content;
	border: solid 1px #fff;
	line-height: 2.2rem;
}
.card h2 {
color:#fff;
background-color: rgb(202, 175, 202);
border-radius: .8rem;
padding-left: 1rem;
border: solid 1px #fff;
font-size: 24px;
margin-bottom: 16px;
width: fit-content;
padding: 5px 10px;
line-height: 2.2rem;
}

.card p {
	line-height: 2.2rem;
    font-size: 16px;
	font-weight: 300;
	letter-spacing: .2px;
	color: #000;
	padding: 3px;
}
.card > div {
	padding: 2rem;
}


/*----------------------------------------*/
/*		     ✨ RESPONSIVE ✨		 	  */
/*----------------------------------------*/

/*@media(max-width: 1000px) {
.card {
		width: 94vw; 
		display: block;
		border-radius: 1rem;
		align-self: center;
		justify-content: center;
		margin: 10px auto;
		}

	.card p {
		line-height: 2.2rem;
		font-size: 16px;
		letter-spacing: .2px;
	}
	.card h3 {
		font-size: 1.2rem;
		margin-bottom: .5rem;
		padding: .7rem;
	}
	
	.card h2 {
		font-size: 1.2rem;
		margin: 0;
		padding: 4px;
	}
	
		.card img {
			width: 80vw;
			height: auto;
			margin: auto;
		}}*/
</style>

