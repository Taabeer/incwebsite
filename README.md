<!DOCTYPE html>

<style>



html {

    box-sizing: border-box;

  }

body {

    background: #fff;
    padding: 0;
    margin: 0;
    /* font-family: "Montserrat", sans-serif; */
    font-family: 'Source Sans Pro', sans-serif;
}

.header {

    display: block;

    margin: 0 auto;

    width: 100%;

    max-width: 100%;

    box-shadow: none;

    background-color: #4665f0;

    position: fixed;

    height: 60px!important;

    overflow: hidden;

    z-index: 10;

}

/*.main {

    margin: 0 auto;

    display: block;

    height: 100%;

    margin-top: 60px;

}

.mainInner{

    display: table;

    height: 100%;

    width: 100%;

    text-align: center;

}

.mainInner div{

    display:table-cell;

    vertical-align: middle;

    font-size: 3em;

    font-weight: bold;

    letter-spacing: 1.25px;

}*/

#sidebarMenu {

    height: 100%;

    position: fixed;

    left: 0;

    width: 250px;

    margin-top: 60px;

    transform: translateX(-250px);

    transition: transform 250ms ease-in-out;

    background: linear-gradient(180deg, #4665f0 0%, #58b974 100%);

}

.sidebarMenuInner{

    margin:0;

    padding:0;

    border-top: 1px solid rgba(255, 255, 255, 0.10);

}

.sidebarMenuInner li{

    list-style: none;

    color: #fff;

    text-transform: uppercase;

    font-weight: bold;

    padding: 20px;

    cursor: pointer;

    border-bottom: 1px solid rgba(255, 255, 255, 0.10);

}

.sidebarMenuInner li span{

    display: block;

    font-size: 14px;

    color: rgba(255, 255, 255, 0.50);

}

.sidebarMenuInner li a{

    color: #fff;

    text-transform: uppercase;

    font-weight: bold;

    cursor: pointer;

    text-decoration: none;

}

input[type="checkbox"]:checked ~ #sidebarMenu {

    transform: translateX(0);

}

 

input[type=checkbox] {

    transition: all 0.3s;

    box-sizing: border-box;

    display: none;

}

.sidebarIconToggle {

    transition: all 0.3s;

    box-sizing: border-box;

    cursor: pointer;

    position: fixed;

    z-index: 99;

    height: 100%;

    width: 100%;

    top: 22px;

    left: 15px;

    height: 22px;

    width: 22px;

}

.spinner {

    transition: all 0.3s;

    box-sizing: border-box;

    position: absolute;

    height: 3px;

    width: 100%;

    background-color: #fff;

}

.horizontal {

    transition: all 0.3s;

    box-sizing: border-box;

    position: relative;

    float: left;

    margin-top: 3px;

}

.diagonal.part-1 {

    position: relative;

    transition: all 0.3s;

    box-sizing: border-box;

    float: left;

}

.diagonal.part-2 {

    transition: all 0.3s;

    box-sizing: border-box;

    position: relative;

    float: left;

    margin-top: 3px;

}

input[type=checkbox]:checked ~ .sidebarIconToggle > .horizontal {

    transition: all 0.3s;

    box-sizing: border-box;

    opacity: 0;

}

input[type=checkbox]:checked ~ .sidebarIconToggle > .diagonal.part-1 {

    transition: all 0.3s;

    box-sizing: border-box;

    transform: rotate(135deg);

    margin-top: 8px;

}

input[type=checkbox]:checked ~ .sidebarIconToggle > .diagonal.part-2 {

    transition: all 0.3s;

    box-sizing: border-box;

    transform: rotate(-135deg);

    margin-top: -9px;

}




































*, *:before, *:after {

    box-sizing: inherit;

  }

 

  .column {

    float: left;

    width: 33.3%;

    margin-bottom: 16px;

    padding: 0 8px;

  }

 

  .card {

    box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);

    margin: 8px;

  }

 

  .about-section {

    padding: 50px;

    text-align: center;


    color: black;

  }

 

  .container {

    padding: 0 16px;

  }

 

  .container::after, .row::after {

    content: "";

    clear: both;

    display: table;

  }

 

  .title {

    color: grey;

  }

 

 

 

  @media screen and (max-width: 650px) {

    .column {

      width: 100%;

      display: block;

    }

  }



















</style>




<div class="header"></div>

  <input type="checkbox" class="openSidebarMenu" id="openSidebarMenu">

  <label for="openSidebarMenu" class="sidebarIconToggle">

    <div class="spinner diagonal part-1"></div>

    <div class="spinner horizontal"></div>

    <div class="spinner diagonal part-2"></div>

  </label>

  <div id="sidebarMenu">

    <ul class="sidebarMenuInner">

      <li><a href="./home.html" target="blank">Home</a></li>
      <li><a href="./namejarfinal.html" target="_blank">The Name Jar</a></li>
      <li><a href="./emmanuelsdreamfinal.html" target="_blank">Emmanuel's Dream</a></li>
      <li><a href="./sulwefinal.html" target="_blank">Sulwe</a></li>
      <li><a href="./ilovemyhairfinal.html" target="_blank">I Love My Hair</a></li>
      <li><a href="./Allthewaystobesmartfinal.html" target="_blank">All The Ways To Be Smart</a></li>
      <li><a href="./about.html" target="blank">About Us<span>Meet the team</span></a></li>

    </ul>

  </div>
  <div class="about-section">


    <body style="background-color: #eef8eb;">
        <center>
<img src="./A student-led initiative at the british international school, abu dhabi.png">
        </center>        </center>
        

  
    <center><h2>About Us</h2></center>
    <div class="container">
      <h2 class="title">
        <span class="title-word title-word-1">Equality</span>
        <span class="title-word title-word-2">&ensp;Diversity</span>
        <span class="title-word title-word-3">&ensp;Inclusion </span>
      </h2>
    </div>
   
          <p>The inclusivity club aims to educate others about the importance of equality, equity, and anti-racism through the formation of lesson plans. As a club, we have created 20 lesson plans that are utilized in our school???s moral education classes from Year 7 to Year 11. Each lesson is adapted to account for the differences within these year groups. Topics we have covered include eurocentric beauty standards, microaggressions, and the harms of ???colour-blind??? racism. The club aims to foster a culture in which stereotyping, microaggressions, and ???casual??? racism are no longer tolerated. The club also aims to move away from being complacent in injustice and instead actively speaking up and standing up for minorities. We understand that in a broader context, we can???t systemically undo the inequalities that are embedded into the foundations of society. However, we can still make an impact through supporting marginalized groups, reducing microaggressions, providing a comfortable environment for students, and hopefully, we can also encourage students in our community to, in the future, advocate for policies that do work to systemically eradicate these issues. Here at the inclusivity club, we believe in the domino effect. We believe that one person standing up for inequality can give others the courage to do so as well and hence the positivity of our impact can ripple into the wider global community.</p>          
        
    
    <style>

          .title-word {
      animation: color-animation 4s linear infinite;
    }
    
    .title-word-1 {
        font-size: 30px;
        font-style: italic;
       
      --color-1: #c65d5d;
      --color-2: #D89B66;
      --color-3: #b7b253;
    }
    
    .title-word-2 {
        font-size: 30px;
        font-style: italic;
      --color-1: #b7b253;
      --color-2: #c65d5d;
      --color-3: #D89B66;
    }
    
    .title-word-3 {
        font-size: 30px;
        font-style: italic;
      --color-1: #D89B66;
      --color-2: #b7b253;
      --color-3: #c65d5d;
    }
    @keyframes color-animation {
      0%    {color: var(--color-1)}
      32%   {color: var(--color-1)}
      33%   {color: var(--color-2)}
      65%   {color: var(--color-2)}
      66%   {color: var(--color-3)}
      99%   {color: var(--color-3)}
      100%  {color: var(--color-1)}
    }
    .title {
  font-family: "Montserrat", sans-serif;
  font-weight: 800;
  /* font-size: 8.5vw; */
  text-transform: uppercase;
}
h2{
  font-size: 50px;
  color: #7c795d;
  text-transform: none;
  font-style: italic;
  font-weight:lighter;
  font-family: 'Trocchi', serif;

}
    
    </style>
  </div>
  
  <center><h2>Our Aim</h2></center>
  <center>
  <div class="container">
    <h2 class="title">
      <span class="title-word title-word-1">Engage</span>
      <span class="title-word title-word-2">&ensp;Educate</span>
      <span class="title-word title-word-3">&ensp;Empower </span>
    </h2>
  </div>
</center>
  <p style="text-align:center;">This website includes five interactive lessons aimed at primary students from Year 1 to Year 6. Each lesson plan is based on
 a book with a main character of colour. We aim to make young students of colour feel included and represented in the media they consume. Positive representation of minorities in media has shown to also reduce stereotypes of the marginalized group presented and to generally boost the self-esteem of the people of colour who consume it-particularly youth.
 We hope that these lesson plans can help them feel confident and to help celebrate diversity and that our differences are our strength, not our weakness! The books we have included are I Love My Hair by Natasha Tarpley, Emmanuel's Dream by Laurie Ann Thompson, Sulwe by Lupita Nyong'o, The Name Jar by Yangsook Choi, and All the Ways to be Smart by Davina Bell. The books cover a range of topics, ranging from embracing your natural hair to dealing with your name being pronounced wrong. We hope that the children using our lesson plans can learn to treat everyone with respect and kindness, including themselves! Our lesson plans aim to encourage these children to be empathetic, caring, and thoughtful individuals to foster a more inclusive school community. 
Through having these lessons accessible through this website, we hope that this enables our reach to spread beyond the British International School, Abu Dhabi.</p>          
 
                  
  <!-- <h2 style="text-align:center">Our Aim</h2> -->

 
