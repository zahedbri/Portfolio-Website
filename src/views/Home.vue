<template>
  <div class="home">
		<div class="container-fluid">
			<div class="text-center">
				<img src="@/assets/img/profile-nitin.png" width=200 class="profile-pic">
				<h1 style="font-weight:500">Nitin Agarwal</h1>
			  <h4>Full Stack Developer</h4>
        <button class="btn" data-toggle="modal" data-target="#myModal">View Resume</button> | <a class="btn" href="@/assets/resume/NitinAgarwal_resume.pdf" style="color: inherit;" download>Download Resume</a>
        <h5>Currently working as full stack developer with fundamental knowledge and hands-on experience AWS Serverless technology, DynamoDB, MongoDb, NodeJS and Vue.js.</h5>
			      <div class="row text-center" style="margin-bottom:2%">
		    			<div class="col-xs-12">
		    				<img src="@/assets/img/techlogos/aws.png" class="techlogo" width="100">
		    				<img src="@/assets/img/techlogos/node.png" class="techlogo" width="100">
		    				<img src="@/assets/img/techlogos/stripe.svg" class="techlogo" width="100">
		    				<img src="@/assets/img/techlogos/MongoDB.png" class="techlogo" width="100">
                <img src="@/assets/img/techlogos/DynamoDB.png" class="techlogo" width="100">
		    				<img src="@/assets/img/techlogos/Vue.png" class="techlogo" width="30">
                <img src="@/assets/img/techlogos/pusher.png" class="techlogo" height="30">
                <img src="@/assets/img/techlogos/github.png" class="techlogo" width="30">
                <img src="@/assets/img/tool-logos/git.png" class="techlogo" width="90">
                <img src="@/assets/img/techlogos/bootstrap.png" class="techlogo" width="100">
		    			</div>
		    		</div>
			</div>
			<div class="row row-grey">
			    <div class="col-sm-8 col-sm-offset-2">
			    	<div class="row work-item-row">
			    		<div class="col-lg-8">
			    			<img src="@/assets/img/willu.png" class="img-responsive center-block">
			    		</div>
			    		<div class="col-lg-4">
			    			<h2><a href="#" target="blank">Willu</a></h2>
			    			<p>A web, android, ios application that gives you a better way to have direct and more meaningful conversations with the people that matter to you.</p>
			    			<h4>Technology</h4>
			    			<p>Willu is built using Vuejs for web, Swift for ios and Kotline for android, with a aws serverless backend for handling API requests. Payments are handled via Stripe, DynamoDB provides the database solution for this project</p>
			    		</div>
		    		</div>
		    		<div class="row text-center">
		    			<div class="col-xs-12">
		    				<img src="@/assets/img/techlogos/Vue.png" class="techlogo" width="30">
                <img src="@/assets/img/techlogos/twilio.png" class="techlogo" width="100">
		    				<img src="@/assets/img/techlogos/node.png" class="techlogo" width="100">
                <img src="@/assets/img/techlogos/DynamoDB.png" class="techlogo" width="100">
		    				<img src="@/assets/img/techlogos/stripe.svg" class="techlogo" width="100">
		    				<img src="@/assets/img/techlogos/aws.png" class="techlogo" width="100">
		    			</div>
		    		</div>
					</div>
			</div>
			<div class="row row-footer text-center">
				<div class="col">
  				<div style="margin:50px;">
  					<h3 style="margin:50px 0 15px">I'm available for work, get in touch</h3>
				  	<a href="mailto:agarwalnitin192@gmail.com">
				  		agarwalnitin192@gmail.com
				  	</a>
				  </div>
				</div>
			</div>
      <div id="myModal" class="modal fade" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true">
        <div class="modal-dialog">
                  <img src="@/assets/resume/NitinAgarwal_resume.jpg" class="img-responsive">
        </div>
      </div>
		</div>
  </div>
</template>
<script>
export default {
  name: 'home',
}
</script>
<style>
img {
  margin: 5px;
}
</style>
