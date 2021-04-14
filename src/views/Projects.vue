<template>
	<div>
		<section class="hero is-medium is-primary is-bold">
			<div class="hero-body">
				<div class="container">
					<h1 class="title is-2">
						Projects I have built
					</h1>
				</div>
			</div>
		</section>
			<section class="section">
			<div class="columns is-multiline">
		<div>
			
			<div class="uihead">
				
				<strong>UI DESIGNS</strong>
			</div>
<div class="post-card grid-container">



	<div class="grid-item">
		<a href="https://xd.adobe.com/view/5feb857f-f35c-4c3e-6a70-ac0ef5ad5ce2-29da/">
		<div class="card">
			<div class="card-image">
				<figure class="image is-square">
					<img src="../assets/WEMA.png" alt="Placeholder image" >
				</figure>
			</div>
			<div class="card-content">
				<div class="media">
					<div class="media-content">
						<p class="title is-4">Wema Bank UI</p>
					</div>
				</div>
				<div class="content">
					<p>UI Design</p>
					<button class="button is-fullwidth">View Project</button>
				</div>
			</div>
		</div>
		</a>
		</div>


		<div class="grid-item">
		<a href="https://xd.adobe.com/view/4c8b0341-c158-42a4-493b-3c88d7d6b52a-3aba/">
		<div class="card">
			<div class="card-image">
				<figure class="image is-square">
					<img src="../assets/vue-logo.png" alt="Placeholder image" >
				</figure>
			</div>
			<div class="card-content">
				<div class="media">
					<div class="media-content">
						<p class="title is-4">Portfolio App</p>
					</div>
				</div>
				<div class="content">
					<p>UI Design</p>
					<button class="button is-fullwidth">View Project</button>
				</div>
				
			</div>
		</div>
		</a>
		</div>



		<div class="grid-item">
		<a href="https://xd.adobe.com/view/36a3e2aa-f52d-4e27-644b-ec9843145ced-4092/">
		<div class="card">
			<div class="card-image">
				<figure class="image is-square">
					<img src="../assets/MICSERAH.jpg" alt="Placeholder image" >
				</figure>
			</div>
			<div class="card-content">
				<div class="media">
					<div class="media-content">
						<p class="title is-4">Micserah Watches</p>
					</div>
				</div>
				<div class="content">
					<p>UI Design</p>
					<button class="button is-fullwidth">View Project</button>
				</div>
				
			</div>
		</div>
		</a>
		</div>

		
		<div class="grid-item">
		<a href="https://xd.adobe.com/view/a335215a-375d-43cd-6016-04f23411227f-d504/">
		<div class="card">
			<div class="card-image">
				<figure class="image is-square">
					<img src="../assets/medihub.png" alt="Placeholder image">
				</figure>
			</div>
			<div class="card-content">
				<div class="media">
					<div class="media-content">
						<p class="title is-4">MediHub App</p>
					</div>
				</div>
				<div class="content">
					<p>UI Design</p>
					<button class="button is-fullwidth">View Project</button>
				</div>
				
			</div>
		</div>
		</a>
		</div>

		<div class="grid-item">
		<a href="https://xd.adobe.com/view/ee7c734e-1f18-474a-5103-d52ad73691a9-984d/">
		<div class="card">
			<div class="card-image">
				<figure class="image is-square">
					<img src="../assets/URANHIVE.jpg" alt="Placeholder image">
				</figure>
			</div>
			<div class="card-content">
				<div class="media">
					<div class="media-content">
						<p class="title is-4">Urban Hive</p>
					</div>
				</div>
				<div class="content">
					<p>UI Design</p>
					<button class="button is-fullwidth">View Project</button>
				</div>
				
			</div>
		</div>
		</a>
		</div>

<div class="grid-item">
		<a href="https://xd.adobe.com/view/b0058bc1-b7ff-45b3-54a5-3e52a4573ea5-c634/">
		<div class="card">
			<div class="card-image">
				<figure class="image is-square">
					<img src="../assets/weather.png" alt="Placeholder image" >
				</figure>
			</div>
			<div class="card-content">
				<div class="media">
					<div class="media-content">
						<p class="title is-4">Weather App</p>
					</div>
				</div>
				<div class="content">
					<p>UI Design</p>
					<button class="button is-fullwidth">View Project</button>
				</div>
				
			</div>
		</div>
		</a>
		</div>
	</div></div>
				
			</div>
		</section>
		<section class="section">
			<div class="uihead">
				<strong>INTERIOR DESIGNS</strong>
			</div>
			<div class="grid-container">
				<div class="grid-item">
			<div class="card">
<img class="imag" v-for="(image, i) in inte" v-bind:key="i" :src="image" @click="onClick(i)">
			<vue-gallery-slideshow :images="inte" :index="indexi" @close="indexi= null"></vue-gallery-slideshow>	
			</div>
	</div></div>
		</section>
 
		<section class="section">
			<div class="uihead">
				<strong>EVENT PLANNING</strong>
			</div>
			<div class="grid-container">
				<div class="grid-item">
			<div class="card">
<img class="imag" v-for="(image, e) in event" v-bind:key="e" :src="image" @click="oClick(e)">
			<vue-gallery-slideshow :images="event" :index="indexe" @close="indexe= null"></vue-gallery-slideshow>	
			</div>
	</div></div>
		</section>

 <section class="section">
			<div class="uihead">
				<strong>BUILDING DESIGNS</strong>
			</div>
			<div class="grid-container">
				<div class="grid-item">
			<div class="card">
<img class="imag" v-for="(image, b) in building" v-bind:key="b" :src="image"  @click="nClick(b)">
			<vue-gallery-slideshow :images="building" :index="indexb" @close="indexb = null"></vue-gallery-slideshow>	
			</div>
	</div></div>
		</section>

	

	</div>
</template>

<script>
	import VueGallerySlideshow from 'vue-gallery-slideshow'
		export default {
		name: "projects",
		components:{
VueGallerySlideshow,
		},
		
methods: {
    onClick(i) {
	this.indexi = i;
	},
	oClick(e){
	this.indexe=e;
	},

	nClick(b){
	this.indexb=b;
	}
  },
		data(){
			return{
				inte:[
				
require("@/assets/interior1.png"),

require("@/assets/interior2.png"),

require("@/assets/interior3.png"),

require("@/assets/interior4.png"),

require("@/assets/interior5.png"),


				],

				event:[
			

require("@/assets/event1.png"),

require("@/assets/event2.png"),

require("@/assets/event3.png"),

				],

				building:[
					require("@/assets/build1.png"),

require("@/assets/build2.png"),

require("@/assets/build3.png"),

require("@/assets/build4.png"),

require("@/assets/build5.png"),
require("@/assets/build6.png"),
require("@/assets/build7.png"),
				],

				indexi: null,
				indexe:null,
				indexb:null
				// b:null,
				// e:null
			}
		}
	};

</script>

<style type="text/css">


.grid-item{
	padding: 20px;
	display: block;

}
.imag {
  width: 300px;
  height: 300px;
  background-size: contain;
  cursor: pointer;
  margin: 10px;
  border-radius: 3px;
  padding: 20px
}

.uihead{
margin-left: auto;
font-size: 20px;
text-align: center
};

@media (min-width: 900px) {
	.uihead{
		flex: auto;
font-size: 50px;
text-align: center;

	}
	
} 
.grid-container{
	display: grid;
	grid-template-columns:auto;
	grid-template-rows: auto;
	padding: 10px;
	width: auto;
}

@media (min-width: 700px) {
	.grid-container{
		display: grid;
		width: auto;
grid-template-columns: repeat(3,auto);
	}	
}

@media (min-width: 900px) {
	.grid-container{
		display: grid;
		width: auto;
grid-template-columns: repeat(6,auto);
	
	}
}
</style>
