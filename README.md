
#html code
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <link rel="stylesheet" href="Task1.css" />
  </head>
  <body>
    <h1>Make your Diwali more Happier</h1>
    <h1 id="head">Join DeliveriWalaa</h1>
    <h2>Come join to us!</h2>
    <p id="one">We guarantee you a grate work experience with us !</p>
    <div class="jackport">
    <h4>The below are the perks you get here :</h4>
  </div>
    <div class="heading">
            <h3>supportive company culture</h3>
            <h3>open communicatison and feedback</h3>
            <h3>work life balance and flexibility</h3>
            <h3>growth and advancement opportunities</h3>
    </div>

    <img
      src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRlneVbu8Wz1UP4d4OwPYUXB91x9QW0ruyp-w&s"
    />
    <img 
    src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR7oGniXz4816BJf4d9YGgXhyGFDfxIOFOuaQ&s"
    />
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSYHg5TWumV2HNkDSAwHpieN6hMwTXjnO6LzQ&s"/>
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSsC2UDXKpchcZD4NDivp67ogBgyz6HufTv8Q&s"/>
    <br>
    <br>
    <h2>The Work Culture at our Company :</h2>
    
    <div class=" inline-features"> 
      <h3 id="first">Diversity & Inclusion</h3>
      <h3 id="second">Structured Hierarchy </h3>
      
      
      <h3 id="third">Focus on Work-Life Balance</h3>
      <h3 id="fourth">Clear Growth Pathways</h3>
    </div>
    <br>
    <br>
    
    <div class="sales-heading">
    <h2>The given below are the sales data at our company:</h2>
  </div>
    <div class ="center-image">
      
    <img src="https://usenotioncms.com/proxy/block/f32eb35c-f17d-4e15-a0c7-667868458d33%2Fc61fd6f4-21d0-4ad4-9e8f-093b487b9925%2FScreenshot_2022-10-14_at_12.07.15_AM.png" alt="centered imagess">
  </div>
  </body>
</html>

h1{
    text-align: center;
    border-radius: 10cm;
    background-size: 10cm;
    color: black;
}
#head{
    color: chocolate;
    text-align: center;
}
h2{
    text-align: center;
    
}
#one{
    text-align: center;
    font-weight: 900;
}
img{
    
    height:5cm;
    width: 7.5cm;
    border:2px solid black;
    margin:2px;
}

.heading{
    display:flex;
    justify-content: space-around;
    align-items: center;
     
}
h3{
    margin:0;
    text-align: center;
    flex:1;
}
.inline-features{
   align-items: center;
   display: flex;
   gap:0.5rem;
}
.inline-features{
    margin:0;
}
.inline-features h3:not(:last-child)::after{
    content:" <=> ";
    margin-left: 0.4rem;
    margin-right: 0.4rem;
    color:#555;
}
#first{
    position: relative;
  left: 5%; 
}
#second{
    position: relative;
  left: 10%; 
   
}

#third{
    position: relative;
  left: 15%; 
}
#fourth{
    position: relative;
  left: 20%; 
}
.sales-heading {
    color: black;
    align-items: center;
  }
.center-image {
    display: flex;
    justify-content: center;
    text-align: center;
    height: 50vh;
  }
  .jackport{
    text-align: center;
    color: cadetblue;
  }
  .center-image img {
    width: 800px;  
    height: 400px;  
    object-fit: cover;  
  }
