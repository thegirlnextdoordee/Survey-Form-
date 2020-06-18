# Survey-Form-

<!DOCTYPE html>
<html>
  <head>
    <title> Survey form of sparkles Jewelries </title>
    <link href="https://fonts.googleapis.com/css2?family=Knewave&display=swap" rel="stylesheet">
    
  </head>
  <body>
    <style>
      
      body {
       font-family: 'knewave';
       color: white;
      
        background-image: url(https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcRSiBJNpe_29SicLyx0KQJDCeEyTIEQV6DFIW5m37gWu2EyUstS&usqp=CAU);
      }
    
   #title {
     text-align: center;
     font-size: 60px;
     line-height: 1.3;
      }
      #description {
      text-align: center;  
        line-height: 1 !important;
        font-size: 45px;
      }
      #survey-form {
        line-height: 2.5;
       font-size: 30px; 
      }
      #name {
height: 80px;
        width: 900px;
        font-size: 30px;
      }
      #email {
       height: 80px;
        width: 900px;
        font-size: 30px;
      }
      #number {
        height: 80px;
        width: 900px;
        font-size: 30px;
      }
      #name-label {
       font-size: 50px !important;
        
      }
      #email-label {
       font-size: 50px !important;
      }
      #number-label {
       font-size: 50px !important;
      }
      #dropdown {
       font-size: 20px !important;
       width: auto;
       
      }
      #submit {
       height: 100px;
        width: 500px;
        background-color: purple;
        font-size: 40px;
        line-height: 2;
      }
      label {
       display: block;
        font-size: 30px;
       
      }
      #comment {
        font-size: 30px;
        height: 200px;
        width: 600px;
        line-height: 2;
      }
      #true {
        line-height: 2.5;
      }
      p {
      font-size: 50px;
      }
      #main {
        line-height: 0.8 !important;
      }
      #more {
        line-height: 2.5 !important;
        font-size: 30px !important;
      }
      
       
        
      
    </style>
    <main>
      <div id="main">
      <h1 id="title"> SPARKLES JEWELRIES FASHIONISTAS <br> SURVEY FORM </h1>
        <p id="description"> Thank you for taking the time to help  us improve the platform  </p>
      </div>
      
      
      <form action="idvictor.14@gmail.com" id="survey-form">
        
        
        
        <div>
          <label id="name-label" for="name"> Name
          </label> 
        <input id="name" type="text"required placeholder="Enter your name">
          
       
        
        
          <label id="email-label" for="email"> Email
          </label>
        <input id="email" type="email"required placeholder="Enter your Email">
          
        
        
        
          <label id="number-label" for="number"> Telephone
          </label>
        <input id="number"  type="number"required min="11" max="11" maxlength="11" placeholder="Enter your Tel">
          
        </div>
        
        <div>
        <p> Which option best describes your role? </p>
        </div>
        
        <div>
         <dropdown id="dropdown" style="zoom:5;">
        <select>
          <option value="" selected disabled hidden> Select role </option>
          <option value="Fulltime"> Fulltime </option>
          <option value="part-time"> Part-time </option>
          <option value="unemployed"> Unemployed </option>
          <option value="student"> Student </option>
          <option value="prefer not to say"> Prefer not to say </option>
          <option value="other"> Other </option>
         </select>
         </dropdown>
          </div>
        
        <div>
        <p> Would you recommend Sparkles Jewelries Fashionistas? </p>
        </div>
        
        <div>
          <label for="definitely">
          </label>
        </div>
        
        <div>
            <input id="definitely" value="definitely" type="radio" name="recommendation" checked style="zoom:2;">Definitely 
         
          <label for="maybe">
          </label>
            <input id="maybe" value="maybe" type="radio" name="recommendation" style="zoom:2;"> Maybe 
          
          <label for="not sure">
          </label>
            <input id="not sure" value="not sure" type="radio" name="recommendation" style="zoom:2;"> Not sure
          
       </div>
         
        <div>
          <p> What would you like to see improved on?<br>
            (check all that is involved) </p>
        </div>
        
          <div>
            <label for="wedding bands">
          </label>
              <input id="wedding bands" value="wedding bands" type="checkbox" name="improvement" style="zoom:2;"> Wedding Bands
            
            <label for="wrist watches">
          </label>
              <input id="wrist watches" value="wrist watches" type="checkbox" name="improvement" style="zoom:2;"> Wrist Watches 
            
            <label for="necklaces">
          </label>
              <input id="necklaces" value="necklaces" type="checkbox" name="improvement" style="zoom:2;"> Necklaces 
            
            <label for="bracelets">
          </label>
              <input id="bracelets" value="bracelets" type="checkbox" name="improvement" style="zoom:2;"> Bracelets 
            
            <label for="bangles">
          </label>
              <input id="bangles" value="bangles" type="checkbox" name="improvement" style="zoom:2;"> Bangles 
            
            <label for="earrings">
          </label>
              <input id="earrings" value="earrings" type="checkbox" name="improvement" style="zoom:2;"> Earrings 
            
            <label for="perfumes">
          </label>
              <input id="perfumes" value="perfumes" type="checkbox" name="improvement" style="zoom:2;"> Perfumes
            
            <label for="brooches">
          </label>
              <input id="brooches" value="brooches" type="checkbox" name="improvement" style="zoom:2;"> Brooches 
            
            <label for="others">
          </label>
              <input id="others" value="others" type="checkbox" name="improvement" style="zoom:2;"> Others
            
              </div>
          <div>
          <p> Any comments or suggestions? </p>
            <textarea id="comment" name="comment" form="survey-form"> Enter your comment
            </textarea>
          </div>
            
          <div>
            <button id="submit" value="submit" type="submit"> Submit </button>
          </div>
         
          </form>
      
        </main>
  </body>
    <script src="https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js"> </script>
</html>
      
