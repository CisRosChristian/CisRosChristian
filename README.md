
<p align="center">
<style>
	    $bg: #10111F;
    $barsize: 15px;


.hr {
    
    width: 100%;
    height: 1px;
    display: block;
    position: relative;
    margin-bottom: 0em;
    padding: 2em 0;

    &:after,
    &:before {

        content: "";
        position: absolute;

        width: 100%;
        height: 1px;
        bottom: 50%;
        left: 0;

    }

    &:before {

        background: linear-gradient( 90deg, $bg 0%, $bg 50%, transparent 50%, transparent 100% );
        background-size: $barsize;
        background-position: center;
        z-index: 1;

    }

    &:after {

        transition: opacity 0.3s ease, animation 0.3s ease;

        background: linear-gradient(
            to right, 
            #62efab 5%, 
            #F2EA7D 15%, 
            #F2EA7D 25%, 
            #FF8797 35%, 
            #FF8797 45%, 
            #e1a4f4 55%, 
            #e1a4f4 65%, 
            #82fff4 75%, 
            #82fff4 85%, 
            #62efab 95%);

        background-size: 200%;
        background-position: 0%;
        animation: bar 15s linear infinite;

    }

    @keyframes bar {

        0% { background-position: 0%; }
        100% { background-position: 200%; }

    }
    
}




.hr.anim {
    &:before {
        background: linear-gradient( 
            90deg, 
            $bg 0%, $bg 5%, 
            transparent 5%, transparent 10%, 
            $bg 10%, $bg 15%, 
            transparent 15%, transparent 20%, 
            $bg 20%, $bg 25%,
            transparent 25%, transparent 30%,
            $bg 30%, $bg 35%, 
            transparent 35%, transparent 40%, 
            $bg 40%, $bg 45%, 
            transparent 45%, transparent 50%, 
            $bg 50%, $bg 55%,
            transparent 55%, transparent 60%,
            $bg 60%, $bg 65%,
            transparent 65%, transparent 70%, 
            $bg 70%, $bg 75%, 
            transparent 75%, transparent 80%, 
            $bg 80%, $bg 85%,
            transparent 85%, transparent 90%,
            $bg 90%, $bg 95%, 
            transparent 95%, transparent 100% );

        background-size: $barsize * 10;
        background-position: center;
        z-index: 1;
        
        animation: bar 120s linear infinite;
        
    }
    
    &:hover {
        &:before {
            animation-duration: 20s;
        }
        &:after {
            animation-duration: 2s;
        }
    }
}





body {
    
    background: $bg;
    padding: 4em;
    font-family: Lato;
    font-weight: 100;
    color: #696B89;
    text-indent: 1em;
    line-height: 1;
    
}

h1,h2 {
    line-height: 1;
    margin-bottom: -0.5em;
}

h2 {
    margin-top: 5em;
}

@import url(https://fonts.googleapis.com/css?family=Lato:100);
</style>
<h1>Hola&nbsp;&nbsp;&nbsp;&nbsp;&lt;&gt;&nbsp;&nbsp;</h1>
    
<b class="hr"></b>
</p>
<p align="left"> 
<img src="https://komarev.com/ghpvc/?username=Mahdiiye&color=brightgreen" alt="watching_count" />
 </p>
	
## <picture><img src = "https://github.com/7oSkaaa/7oSkaaa/blob/main/Images/about_me.gif?raw=true" width = 30px></picture> **About Me**

<picture> <img align="right" src="https://mir-s3-cdn-cf.behance.net/project_modules/disp/601014116770475.6068beff4640a.gif" width = 400px></picture>
 <p align="left">
  <img src="https://img.shields.io/badge/Focus-Backend%20Development-dodgerblue" />
  <img src="https://img.shields.io/badge/Languages-English-dodgerblue" />
</p>

I'm Cisneros Christian Ivan, and I'm currently following my own path in the game development scene. I'm specialized in game mechanics coding, where I'm always trying to give the best experience to the users, having in mind the different opportunities a project has to make the experience more enjoyable. Likewise, I'm open-minded about learning new languages and technologies in order to improve my knowledge and be able to enroll in different areas. That's why I'm always looking for new people to work with; no matter if it is in projects or something more complex, I appreciate any opportunity to learn from others and help each other to improve, sharing experiences, knowledge and even having the chance to meet more of each one and build up a community where we are always connected. 

<br>

## <img src="https://img.shields.io/badge/Itch.io-FA5C5C?style=for-the-badge&logo=itchdotio&logoColor=white" width ="50"><b> Projects</b>

## <img src="https://media2.giphy.com/media/QssGEmpkyEOhBCb7e1/giphy.gif?cid=ecf05e47a0n3gi1bfqntqmob8g9aid1oyj2wr3ds3mg700bl&rid=giphy.gif" width ="25"><b> Skills</b>

<p align="center">

- **Languages**:
    
     <img src="https://user-images.githubusercontent.com/64439609/212555599-9b7ae14f-093a-41bf-8cb8-3cdefd418636.png" width="40" height="40" alt="C#"/>
	 <img src="https://skillicons.dev/icons?i=java&perline=12" width="40" height="40" alt="Java"/>
	 <img src="https://skillicons.dev/icons?i=py&perline=12"  width="40" height="40"/>
	
- **Softwares and Tools**:

	<img src="https://img.shields.io/badge/Unity-100000?style=for-the-badge&logo=unity&logoColor=white" width="40" height="40" alt="Unity"/>
  	<img src="https://user-images.githubusercontent.com/64439609/212556685-de9a7c04-31b0-43b6-af39-7c82ac13b321.png" width="40" height="40" alt="Git"/>
    <img src="https://user-images.githubusercontent.com/64439609/212556741-81407849-82c8-4926-854f-820e8a644375.png" width="40" height="40" alt="Github"/>
    <img src="https://user-images.githubusercontent.com/64439609/212556802-77a65ec1-aa71-4272-b603-1a57d1914678.png" width="40" height="40" alt="Visual Studio"/>
	<img src="https://skillicons.dev/icons?i=eclipse&perline=12"  width="40" height="40" alt="Eclipse"/>

- **Front-End Development**:

   <img src="https://skillicons.dev/icons?i=angular&perline=12"  width="40" height="40" alt="Angular"/>	
   <img src="https://user-images.githubusercontent.com/64439609/212556407-f122dc0e-901c-4df7-960f-29a3b52c5349.png" width="40" height="40" alt="HTML" />
   <img src="https://user-images.githubusercontent.com/64439609/212556203-47a51702-fec1-4275-bafb-6afdea15b092.png" width="40" height="40" alt="CSS" />
   <img src="https://user-images.githubusercontent.com/64439609/212556085-e6f8391a-6f25-43d5-8bfe-818167047cfb.png" width="40" height="40" alt="JS"/>
 

<br>
</p>


## <img src="https://media.giphy.com/media/iY8CRBdQXODJSCERIr/giphy.gif" width="35"><b> Github Stats </b>
<br>

<div align="center">

![](https://github-readme-stats.vercel.app/api?username=Mahdiiye&theme=dracula&hide_border=false&include_all_commits=true&count_private=true)<br/>
![](https://github-readme-streak-stats.herokuapp.com/?user=Mahdiiye&theme=dracula&hide_border=false)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=Mahdiiye&theme=dracula&hide_border=false&include_all_commits=true&count_private=true&layout=compact)
	
</a>
</div>



-----

<h3 align="center" >Contact info 🤝 </h3>

<p align="center">

 <div align="center"  class="icons-social" style="margin-left: 10px;">
        <a   target="_blank" href="https://www.linkedin.com/in/">
			<img src="https://img.icons8.com/doodle/40/000000/linkedin--v2.png" style="margin-left: 10px;" ></a>
        <a style="margin-left: 10px;" target="_blank" href="">
		<img src="https://img.icons8.com/doodle/40/000000/github--v1.png"></a>
           <a style="margin-left: 10px;" target="_blank" href="https://">
		<img src="https://img.icons8.com/doodle/2x/gmail-new.png" style=" width:35px; height:43px;"></a>
		<a style="margin-left: 10px;" target="_blank" href="">
				<img src="https://img.icons8.com/external-tal-revivo-color-tal-revivo/40/000000/external-stack-overflow-is-a-question-and-answer-site-for-professional-logo-color-tal-revivo.png"></a>
		<a style="margin-left: 5px;" target="_blank" href="">
					<img src="https://img.icons8.com/ultraviolet/2x/resume.png" style=" width:37px; height:40px;"></a>
      </div>

</p>


	

</div>


------
[Mahdiiye](https://github.com/Mahdiiye)
Last Edited on: 19/01/2023
