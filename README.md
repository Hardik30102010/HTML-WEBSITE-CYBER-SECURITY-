<!---HTML-WEBSITE-CYBER-SECURITY-Complete this--->

<HTML>
  <HEAD>
    <TITLE> CYBER SECURITY WEBSITE CLASS 8C CSET </TITLE>
    <STYLE>
      body{
        background-color: #1a1a2e;
        text-allngment: center;
        color: #ffffff;
        font-family: Arial, sans-serif;
      
    
      }
         .page { 
      display: none;
      text-align: center;
      min-height: 100vh;
      padding-top: 50px;
    }
    .active { display: block; }
    button { 
      margin: 10px; 
      padding: 10px 20px; 
      font-size: 18px; 
      cursor: pointer; 
      border-radius: 10px; 
      border: solid 2px #8800ff ; 
      background-color: #4b3ca7; 
      color: white; 
      transition: transform 0.2s; 
    }
      button { 
       margin: 10px; 
       padding: 10px 20px; 
       font-size: 18px; 
       cursor: pointer; 
       border-radius: 10px; 
       border: solid 2px #8800ff ; 
       background-color: #4b3ca7; 
       color: white; 
       transition: transform 0.2s; 
    }
    button:hover { 
       border:solid 3px #ff00ee;
       transform: scale(1.1);
    }
    hr {
      border: none; 
      border-top: 2px solid #fff; 
      width: 100%; 
    }
    A:LINK, A:VISITED {
     COLOR: #0000FF
    TEXT-DECORATION: UNDERLINE;
    FONT–WEIGHT: normal;
}

A:HOVER, A:ACTIVE {
  COLOR: #cc0cf7
  FONT–WEIGHT: BOLD;
  }
  h3:hover{

transform: rotate(360deg); 
    transition: 5s;
}
h1:hover{

transform: rotateY(360deg); 
    transition: 5s;
}
    </STYLE>
  </HEAD>
   <BODY>
     <DIV id="home" class="page active">
       <H1> <B>WELCOME</B></H1>
       <br><br><br>
       <p>cybersecurity is the practice of protecting your digital life—such as your computers, smartphones, and online accounts—from hackers who want to steal, change, or break your information. </p>
         <br><br><br><br>
       <button onclick="showpage()"></button> <button onclick="showpage()"></button> 
       <br><hr><br>
       <button onclick="showpage(phishing)" >LEARN <br> ABOUT <br>PHISHING</button> <button onclick="showpage()">LAERN<BR>ABOUT<BR>SOMETHING</button>
       <br><br><br><hr><br><br>
       
       <h3><B>MADE BY<BR>HARDIK AWANA <BR> CLASS-8C </B></h3>
       <BR><BR><BR>
      
      </DIV>


<div id="phishing" class="page">
  
</div>
     <SCRIPT>
     function showpage(id) {
    document.querySelectorAll('.page').forEach(p => p.classList.remove('active'));
    document.getElementById(id).classList.add('active');
  }
     </SCRIPT>
   </BODY>
</HTML>
