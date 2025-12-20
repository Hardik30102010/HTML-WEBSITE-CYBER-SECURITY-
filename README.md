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
       <button onclick="showpage('cyberlaws')">LEARN<br>ABOUT<br>CYBER LAWS IN INDIA</button> <button onclick="showpage('')"></button> 
       <br><hr><br>
       <button onclick="showpage('phishing')" >LEARN <br> ABOUT <br>PHISHING</button> <button onclick="showpage('')">LAERN<BR>ABOUT<BR>SOMETHING</button>
       <br><br><br><hr><br><br>
       
       <h3><B>MADE BY<BR>HARDIK AWANA <BR> CLASS-8C </B></h3>
       <BR><BR><BR>
      
      </DIV>

<div id="cyberlaws" class="page"> 
<h1><B>CYBER LAWS IN INDIA</B></h1>
  <BR><BR><BR><HR><BR><BR>
  <P><B>Information Technology Act, 2000 (IT Act): </B>
    <br>The foundational law, enabling e-commerce, recognizing electronic records/signatures, and establishing offenses. 
    <br><br>
<b>IT (Amendment) Act, 2008: </b><br>Expanded the IT Act, introducing new offenses (like publishing private images) and increasing penalties. 
    <br><br>
<b>Indian Penal Code (IPC):</b><br> Sections of the IPC (e.g., cheating, forgery, defamation) are applied to cybercrimes. 
    <br><br>
<b>IT Rules, 2011 (and subsequent) : </b><br>Detailed rules for implementing the IT Act, covering intermediaries, digital signatures, etc. 
    <br><br>
<b>Digital Personal Data Protection Act, 2023 (DPDP Act):</b><br> Focuses specifically on processing personal data, balancing individual privacy with data fiduciary needs. 
    <br><br>
<b>National Cyber Security Framework (NCSF):</b><br> Outlines national strategies for cybersecurity. </P>
    <br><br><br><hr><br><br><br>
<h2><b>Core Concepts & Offences under IT Act, 2000/2008</b></h2>
  <br><br><hr><br><br>
<p><b>Legal Recognition:</b>
  <br>
  Validates electronic records, digital signatures, and e-governance. 
  <br>
<b>Cyber Crimes & Penalties:-</b>
  <br><br>
  <ul>
<li><b>Tampering/Hacking (Sec 66):</b> Unauthorized access/damage to computer systems. </li>
<li><b>Identity Theft (Sec 66C):</b> Fraudulent use of IDs. 
Cheating by Impersonation (Sec 66D): Using communication devices for fraud. </li>
<li><b>Publishing Private/Obscene Content (Sec 66E/67): </b>Violating privacy or posting explicit material. </li>
<li><b>Offensive Messages (Sec 66A - struck down by Supreme Court): </b>Intended to cause annoyance.</li>
  </ul>
  <br><br><br>
<b>Data Protection: Addresses data security and breach notification.</b>
</p>
  <br><br><br><br><br>
</div>
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
