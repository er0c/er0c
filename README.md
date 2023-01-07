
  <!DOCTYPE html>
<html>
<head>
<link href="https://fonts.googleapis.com/css2?family=Indie+Flower&display=swap" rel="stylesheet">

  <style>
@keyframes scroll{
  0%{bakground-position: 0,0 ;}
  100%{background-position: 100vw,0 ;}
}

@keyframes bob{
0%{top:0px;}
10%{top:50px;}
20%{top:0px;}
30%{top:50px;}
40%{top:0px;}
50%{top:50px;}
60%{top:0px;}
70%{top:50px;}
80%{top:0px;}
90%{top:50px;}
100%{top:0px;}
}
    body {
      background-image: url("clouds.jpg");
      background-size: cover;
      bakground-repeat: repeat-x;
      animation: scroll 20s linear infinite; 
		}

    img {
      position: relative;
			display: flex;
			margin: 0 auto;
      height:300px; width:450px;
      padding: 25px 25px;
      animation-name: bob;
      animation-duration: 20s;
      animation-iteration-count: infinite;
      animation-timing-function: cubic-bezier(0,0,0,0);
      /* animation: bob 20s linear infinte; */
		}

		.form {
      size: 70px;
			text-align: center;
      border-width: 10px;
      padding: 25px 25px;
  
		}

    h1{
      font-family: 'Indie Flower', cursive;
      text-align: center; 
      font-size: 70px ;
      padding: 25px,0;
    }
    #Password{
         display: inline-block;
        height: 25px;
        width: 200px;
        border-radius: 100px;
        border-color: (rgb(118, 118, 118), rgb(195, 195, 195));

    }

    #Enter{ 
        display: inline-block;
        height: 25px;
        width: 100px;
        border-radius: 100px;
        border-color: (rgb(118, 118, 118), rgb(195, 195, 195));
    }

    h2{
      text-align: center;
      font-family: 'Yanone Kaffeesatz', sans-serif;

    }
	</style>
</head>
<body>


	<h1>Rawrsuron</h1>
  <img title="rawrr" src="iamdrago.png" >

	<div class="form">
	  <h2>Please Login</h2>
    <input id="Password" placeholder="Password">
    <button id="Enter">Enter</button>
	</div>
<script>
		document.getElementById('Enter').onclick = () => {
			document.getElementById('Password').value = "";
			alert('WRONG, BEGONE');
      window.top.close();
		};
    
	</script>

</body>
</html>

<h1 align="center">Hello World, I'm Eric Nguyen</h1>
<h3 align="center">I am a aspiring software developer.</h3>

#### Breif Introduction -
  I am a First-Year at Lehigh University majoring in Computer Science and Business. I live in Philadelphia, PA and I plan on performing resserach on Artifiical Intelligence, Machine Learning, and Virtual Reality to someday be a Pioneer in the new era of technology.
 

-  I’m currently learning **Unity**

-  How to reach me: **eric.nguyen103@gmail.com**

-  My experiences: [https://docs.google.com/document/d/1RTIhrj-gZ9ySD76MsM4GCo7XFhOVRsRCOJNBTUpmNKQ/edit?usp=sharing](Resume)

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://linkedin.com/in/ericnguyen2022" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="ericnguyen2022" height="30" width="40" /></a>
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> </a> <a href="https://www.figma.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" alt="figma" width="40" height="40"/> </a> <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a> <a href="https://www.java.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> <a href="https://unrealengine.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/kenangundogan/fontisto/036b7eca71aab1bef8e6a0518f7329f13ed62f6b/icons/svg/brand/unreal-engine.svg" alt="unreal" width="40" height="40"/> </a> </p>
