<template>  <section class="card-story">
    <div id="clock">
        loading ...
    </div>  
</section>
</template>
<script>
import moment from '../../moment'
import $ from '../../jQuery'

function update() {
$('#clock').html(moment().format('dddd, MMMM Do YYYY h:mm:ss A'));
} setInterval(update, 1000);
</script>
