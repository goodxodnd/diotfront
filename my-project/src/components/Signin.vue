<template>
<div class="container">
    <div class="row">
        <div class="col-md-1"></div>
        <div class="col-md-5">
          <div class="box01">
            <div class="box01-text">Welcome to diot</div>
            <div class="box01-subtext">sldkfnsldkf nlskdnfklsd sdlkfnsldkfs <br>sdkjfsdf skdjfnsdkj sdkjfnssz fsdsasd<br>
            sfsdfsdlkdnfsf sdlfknsdfk sdflksndfk<br> sdkjfskdjf sdfjs sdkjf. </div>
            <b-button variant="light" class="know-more">Know More</b-button>
          </div>
        </div>
        <div class="col-md-5">
          <div class="box02">
            <div class="box02-text">Sign In</div>
            <div class="box02-signin">
              <input class="id" type="text" placeholder="Enter DID Numer"/>
              <br>
              <input class="password" type="password" placeholder="Enter Password"/>
            </div>
            <b-button variant="light" class="signin">S I G N  I N</b-button></div>
          <div class="question">
            <a href="/signup.vue">Sign up here</a>
          </div>
        </div>
        <div class="col-md-1"></div>
    </div>
</div>
</template>

<script>
</script>

<style>
.box01 {
background-color: #3d6098;
position: relative;
top:145px;
width:475px;
height:500px;
border-top-left-radius:50px;
border-bottom-left-radius:50px;
}
.box01-text {
position: relative;
top: 130px;
left: 85px;
font-size: 30px;
font-weight: bold;
color: white;
}
.box01-subtext {
position: relative;
top: 150px;
left: 85px;
font-size: 15px;
color: white;
}
.know-more {
font-weight: bold;
font-size: 15px;
width: 110px;
height: 35px;
position: relative;
top: 190px;
left: 85px;
}

.box02 {
background-color: #E7E7E7;
position: relative;
top:145px;
width:475px;
height:500px;
border-top-right-radius:50px;
border-bottom-right-radius:50px;
}
.box02-text {
font-size: 40px;
font-weight: bold;
position: relative;
top: 70px;
left: 160px;
}
.box02-signin{
font-size: 20px;
}
.id {
width: 250px;
height: 45px;
position: relative;
top: 100px;
left: 110px;
}
.password {
width: 250px;
height: 45px;
position: relative;
top: 130px;
left: 110px;
}
.signin {
width: 250px;
height:50px;
position: relative;
top:170px;
left:110px;
font-size: 27px;
font-weight: bold;
background-color:#3d6098;
color: white;
}


</style>
