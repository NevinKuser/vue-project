<template>
<div>
<form 
name="contact" 
method="POST" 
data-netlify="true" type="html/css">

  <input value="contact" name="form-name" type="hidden" />

  <p>
   <input type="text" name="name" placeholder="Name" />   
  </p>
  <p>
    <input type="email" name="email" placeholder="Email" />
  </p>
  <p>
  <input type="text" name="country" placeholder="Nationality" />
  </p>
  <p>
    <textarea name="message" placeholder="Message"></textarea>
  </p>
  <p>
    <button class="btn" type="submit">Send</button>
  </p>
</form>
<h3>We usually reply to messages within a day.</h3>

<a href="https://www.instagram.com/tya_priestess_of_bali/">
<img src="../../resources/logo/ig.png" alt="instagram logo"></a>
</div>
</template>

<style scoped>
h3 { font-size: 20px; font-family: inter; margin-top: 20px;}

img { height: 25vh; width: auto; }
/*----------------------------------------*/
/*		     ✨ CONTACT	✨		 		  */
/*----------------------------------------*/

::placeholder {
color: rgb(102, 125, 107);
opacity: .6; 
}

div {
  text-align: center;
  margin-right: auto;
  margin-left: auto;
}

input, textarea {
  padding: 2px;
  width: 300px;
  margin: 10px;
  border-radius: 4px;
  font-size: 16px;
  color: #000;
  border: 1.5px solid #1e272e;
  background-color: #bdc1bb;
  
}

textarea {
  height: 150px;
}
.btn {
	background: #000;
	color: #0be881;
	padding: 0.6rem 1.8rem;
  cursor: pointer;
	border-radius: 1.5rem;
	font: 'Lato'; 
	font-size: 1.7rem;
	border: 2px, green;
}

.btn:hover {
	opacity: 0.8;
	background: #d3d8db;
	transition: 2s;
	color: rgba(red, black, gold);
}

</style>