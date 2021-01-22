<template>
<div style="margin-left:18%">
<div class="body">
<div class="story-container">
  <ul>
    <li class="has-story">
      <div class="story">
        <img src="https://hips.hearstapps.com/hmg-prod.s3.amazonaws.com/images/dog-puppy-on-garden-royalty-free-image-1586966191.jpg?crop=1.00xw:0.669xh;0,0.190xh&resize=1200:*" alt="">
      </div>
      <span>John Doe</span>
    </li>
    <li class="has-story">
      <div class="story">
        <img src="https://hips.hearstapps.com/hmg-prod.s3.amazonaws.com/images/dog-puppy-on-garden-royalty-free-image-1586966191.jpg?crop=1.00xw:0.669xh;0,0.190xh&resize=1200:*" alt="">
      </div>
      <span>Kaushik</span>
    </li>
  </ul>
</div>
</div>
<div class="f-card">
  <div class="header">
    <div class="options"><i class="fa fa-chevron-down"></i></div>
    <img class="co-logo" src="https://media-exp1.licdn.com/dms/image/C5603AQFAEp71UBdvGw/profile-displayphoto-shrink_200_200/0/1588193352025?e=1616630400&v=beta&t=KJw0EDKa-8Y55n97h-jpV14UEdRR6f4Ws6YLL9eugnw" />
    <div class="co-name"><a href="https://www.facebook.com/kaushik.kumar.31105">Kaushik</a></div>
    <div class="time"><a href="#">2hrs</a> · <i class="fa fa-globe"></i></div>
  </div>
  <div class="content">
    <p>Height is optional, if no height is specified the image will be a square.Example: <a class="" href="http://placehold.it/300">http://placehold.it/300</a> See More</p>
  </div>

  <div class="reference">
    <img class="reference-thumb" src="http://placehold.it/476x249" />
    <!-- <div class="reference-content">
      <div class="reference-title">A quick and simple image placeholder service. | PLACEHOLDER.it</div>
      <div class="reference-subtitle">How does it work? Just put your image size after our URL and you'll get a placeholder.</div>
      <div class="reference-font">placeholder.it</div>
    </div> -->
  </div>
  <div class="social">
    <div class="social-content"></div>
    <div class="social-buttons">
      <span><i class="fa fa-thumbs-up"></i>Like</span>
      <span><i class="fa fa-comment"></i>Comment</span>
      <span><i class="fa fa-share"></i>Share</span></div>
  </div>
</div>
<div class="w3-container">
  <div class="w3-card-4" style="width:30%">
    <h3 class="Ad">Advertisment</h3>
    <img src="https://hips.hearstapps.com/hmg-prod.s3.amazonaws.com/images/dog-puppy-on-garden-royalty-free-image-1586966191.jpg?crop=1.00xw:0.669xh;0,0.190xh&resize=1200:*" alt="Alps" style="width:100%">
    <div class="w3-container w3-center">
      <p>The Italian / Austrian Alps</p>
    </div>
  </div>
</div>
</div>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'Home',
  components: {
  }
}

</script>

<style scoped>
.classFromParent {
  margin: 10px 0px 0px;
}
*{
  margin: 0px;
  padding: 0px;
  box-sizing: border-box;
}
.body{
  font-family: sans-serif;
  background: #f5a376;
  height: 5%;
}
img{
  pointer-events: none;
}
.story-container ul{
  list-style-type: none;
  user-select: none;
  display: flex;
  overflow-y: auto;
  padding: 20px 0;
}
.story-container ul li{
  padding: 0 10px;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;

}
.story-container ul li:first-child{
  padding-left: 20px;

}
.story-container ul li:last-child{
  padding-right:  20px;
}
.story-container ul li .story{
  width: 75px;
  height: 75px;
  border-radius: 50%;
  background: rgba(225, 225, 225, .75);
  padding: 1px;
  position: relative;
}
.story-container ul li .has-story .story{
  background: linear-gradient(45deg, #f5a376 0%, #f95e49 25%,#f5a376 50%);
}
.story-container ul li .story img{
  padding: 4px;
  background: currentColor;
  border-radius: 50%;
  width: 100%;
  height: 100%;
}
*, *:before, *:after {
    -webkit-box-sizing: border-box;
       -moz-box-sizing: border-box;
            box-sizing: border-box;
}

body {
  background-color:#e9ebee;
}

.f-card {
  background-color:white;
  border: 50px;
  width:640px;
  border: 1px solid #d0d1d5;
  border-radius:3px;
  margin: auto;
  margin-bottom:10px;
  margin-left: 40px;
  margin-top: 10px;
  padding: 12px;
  box-shadow: 0 0 5px rgba(0, 0, 0, .30); /* Not original, just a test */
  float: left;
}

.header {
  margin-bottom:17px;
}

.co-logo {
  /*display:block;*/
  float:left;
  margin-right:8px;
  width:40px;
  height:40px;
}

.co-name > a {
  font-family: Helvetica;
  font-size:14px;
  font-weight: bold;
  line-height: 1.38;
  color: #365899;
  text-decoration:none;
  margin-bottom:2px;
}

.co-name > a:hover {
  text-decoration:underline;
}

.time {
  font-family: Helvetica;
  font-size:12px;
  color: #90949c;
}

.time > a {
  color: #90949c;
  text-decoration:none;
}

.time > a:hover {
  text-decoration:underline;
}

.options {
  font-family: Helvetica;
  font-size:12px;
  color: #e5e5e5;
  float:right;
}

.options:hover {
  color: black; /* Fallback */
  color: rgba(0, 0, 0, .30);
}

.content {
  clear:both;
  font-family: Helvetica, sans-serif;
  font-size:14px;
  line-height: 1.38;
}

.reference {
  width:476px;
}
.reference-thumb {
  display:block;
  width:600px;
  height:300px;
  position: relative;
}

.reference-content {
  border: 2px solid black;
  border: 2px solid rgba(0, 0, 0, .1);
  border-top: 0;
  padding: 10px 12px 10px 12px;
  width: 500px;
}

.reference:hover .reference-content {
  border-color: black; /* Fallback */
  border-color: rgba(0, 0, 0, .15);
}

.reference-title {
  font-family: Georgia;
  font-size: 18px;
  font-weight: 500;
  line-height: 22px;
  margin-bottom:5px;
}

.reference-subtitle {
  font-family: Helvetica;
  font-size:12px;
  line-height: 16px;
}

.reference-font {
  color: #90949c;
  font-family: Helvetica;
  font-size: 11px;
  line-height: 11px;
  text-transform: uppercase;
  padding-top:9px;
}

.social {
  margin-top:12px;
}
.social-buttons {
  color: #7f7f7f;
  font-family: Helvetica;
  font-size: 12px;
  font-weight:bold;
  line-height:14px;
  border-top:1px solid #e5e5e5;
  padding-top:4px;
}

.social-buttons span {
  font-size: 12px;
  margin-right:20px;
  padding:4px 4px 4px 0;
}

.social-buttons span:hover {
  text-decoration:underline;
  cursor:pointer;
}

.social-buttons span i {
  padding-right:4px;
}
.w3-card-4{
  float:right;
  width: 50px;
  height: 60%;
  position: absolute;
  border: 2px;
  margin: 40px;
  margin-top: 10px;
}
.w3-container{
  float: left;
}
</style>
