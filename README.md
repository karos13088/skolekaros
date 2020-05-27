<html>
<head>
<style>
  body {
  font-family: 'Poppins', sans-serif;
  font-size: 1.8rem;
  font-weight: 0;
  line-height: 1.4;
  color: var(--main-white);
}
body {margin:400;}
 
 
.navbar {
  overflow: hidden;
  background-color: rgba(0, 0, 0, 0.5);
  position: fixed;
  top: 0;
  width: 100%;
  text-align: center;
}
 
.navbar a {
  float: left;
  display: block;
  color: #000000;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;
}
 
.navbar a:hover {
  background: #ddd;
  color: black;
}
 
.main {
  padding: 16px;
  margin-top: 30px;
  height: 1500px; /* Used in this example to enable scrolling */
 
}
li {
  border-right: 1px solid #bbb;
}
 
li:last-child {
  border-right: none;
}
.project-tile {
  text-align: center;
  background-color: lightcoral;
  font-size: 20px;
 
}
#projects {
background-color: lightcoral;
text-align: center;
font-size: 20px;
}
#about {
  background-color: rgb(0, 204, 255);
  text-align: center;
  font-size: 20px;
    }
 
.welcome-section {
  font-size: 3rem;
  font-weight: 200;
  font-style: italic;
  color: var(--main-red);
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  width: 100%;
  height: 100vh;
  background-color: #000;
  background-image: linear-gradient(62deg, #3a3d40 0%, #181719 100%);
}
h1 {
  font-size: 6rem;
}
.fa {
  padding: 20px;
  font-size: 30px;
  width: 50px;
  text-align: center;
  text-decoration: none;
  margin-bottom: 2cm;
}
.fa:hover {
  opacity: 0.7;
}
.fa-facebook {
  background: #3B5998;
  color: white;
}
 
.profile-link {
  text-align: center;
}
.fa-twitter {
  background: #55ACEE;
  color: white;
}
.fa-youtube {
  background: #bb0000;
  color: white;
}
.fa-instagram {
  background: #125688;
  color: white;
}
.fa-github {
  background: #4b4b4b;
  color: white;
}
#contact{
font-size: 3rem;
font-weight: 200;
font-style: italic;
color: var(--main-red);
display: flex;
flex-direction: column;
justify-content: center;
align-items: center;
width: 100%;
height: 100vh;
background-color: #000;
background-image: linear-gradient(62deg, #3a3d40 0%, #181719 100%);
}
</style>
</head>

<body>
  <div class="navbar">
        <a href="#welcome-section">Home</a>
        <a href="#projects">projects</a>
        <a href="#contact">Contact</a>
      </div>
 
<div class="welcome-section">    
    <section section id="welcome-section">
        <h1>Hi I am Karos!</h1>
        <p>I am a programmer!</p>
</div>
  
<section section id="projects">
    <h2 class >Projects</h2>
 
    <div class="project-tile">
        <a href="https://www.youtube.com/watch?v=L76qCr0t32c">
        <h3> Hover robot</h3>
        </a>
        <p>Here is a robot that I've made at school, I've made it so it avoids obstacles that comes infront of him. In a sense it avoids crashes.</p>
        there is another video put it got Deleted
    </div>
 
    <div class="project-tile">
        <h3> KarosCut (app)</h3>
        <p>KarosCut is an app I made in order to help people that has a bad PC or actually just make opening websites easier. <br>
        I'm not done with it, but I think that it will be an open-source project. </p>
         project is not done yet
 
        <div class="project-tile">
            <h3> 3D printed phone holder</h3>
            <p>I've also 3D printed a phone holder for myself. This was when I was an apprentice. It worked and it's simple and creative <br>
            Sadly I can't find a picture of it. I've lost the main base so can't take a picture of it now either. </p>
    </div>
 
</section>
 
<section section id="contact">
<div class="profile-link">
    <h3> Contact me here:</h3>
<a href="https://www.snapchat.com/add/karos1308" target ="_blank" class="fa fa-snapchat"></a>
<a href="https://twitter.com/explore" target ="_blank" class="fa fa-twitter"></a>
<a href="https://www.instagram.com/karos1308.a/" target ="_blank" class="fa fa-instagram"></a>
<a href="https://www.youtube.com/channel/UC0iwfdu_maQeCAdMVQYibNA?view_as=subscriber" target ="_blank" class="fa fa-youtube"></a>
<a href="https://github.com/Karos13088" target ="_blank" class="fa fa-github"></a>
 
</div>
</section>

</body>
</html>
