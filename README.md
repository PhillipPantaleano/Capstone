Capstone
========

School Capstone project (Nicks Powerwashing)
 This is my First Repository
 Here is a web site I made for my capstone project for my web design class
 
 this is the CSS code:
 body			{ background-image: linear-gradient(to top, #000000, #333399); 
			background-repeat: no-repeat; 
			background-color: #000000; }

header		{ background-color: #99ccff; 
			text-align: center; height: 50px;
			border-bottom: 4px solid #ff0033; 
			background-image: url(headerop.jpg);}

nav 			{ font-weight: bold;
			width: 200px;
			float: left; margin-top: 50px;
			text-align: center; }   
nav ul 		{ list-style-type: none;
			padding-left: 0px;
			font-size: 1.2em; }
nav li		{ padding: 20px 0px 20px 0px; }
nav a 		{ text-decoration: none; }
nav a:link 	{ color: #000000; }
nav a:visited { color: #333399; }
nav a:hover 	{ color: white; }

ul			{ list-style-type: none; }

ol			{ list-style-type: disc; }

#wrap		{ width: 70%; margin: auto;
			min-width: 900px; 
			box-shadow: 5px 5px 5px #ffffff; 
			border-bottom-right-radius: 90px;
			border-bottom-left-radius: 90px; 
			background-color: #99ccff;}

#content	{ padding: 1px 0px 0px 0px;
			margin-left: 200px;
			background-color: #99ccff; }

footer		{ background-color: #99ccff; 
			padding: 10px; 
			text-align: center;
			border-bottom-right-radius: 90px;
			border-bottom-left-radius: 90px; 
			border-top: 4px solid #ff0033;}

.align		{ text-align: center; }

table			{ border: 2px solid #000000; width: 80%; background-color: white; 
			margin-bottom: 10px; margin-top: 10px; }
th			{ padding: 2px; border: 2px solid #000000; text-align: center; }
td			{ padding: 2px; border: 2px solid #000000; text-align: center; }

fieldset	{ display: block; width: 300px; margin-bottom: 15px; }
input 	{ display: block; margin-bottom: 10px; }
label		{ float: left; display: block; padding-right: 15px;  }
textarea 	{ display: block; margin-bottom: 15px; }
select	{ display: block; margin-bottom: 15px; }

#gallery 	{  height: 300px; position: relative; }
#gallery ul 	{ width: 500px; list-style-type: none; margin-bottom: 200px; }
#gallery li 	{ display: inline; float: left; padding: 10px; }
#gallery img {  float: none; border-style: none; }
#gallery a 	{ text-decoration: none;
             font-style: italic;  
             color: #000000; }
#gallery span { position: absolute;
                left: -1000px;
               opacity: 0;
             -webkit-transition:  opacity 3s ease-in-out;
              -moz-transition:   opacity 3s ease-in-out;
              -o-transition:  opacity 3s ease-in-out;
              transition:  opacity 3s ease-in-out; }
#gallery a:hover span { position: absolute; top: 16px; left: 320px; opacity: 1; }	
figure 		{ position: absolute; left: 580px; text-align: center; }

p			{width: 800px; }

Here is the Home Page:

<!DOCTYPE html>
<html lang="eng">
<head>
<!--[if lt IE 9]>
<script src="http://html5shim.googlecode.com/svn/trunk/html5.js">
</script>
<![endif]-->
<title>Nick's Powerwashing, Cement Seal and Deck Staining</title>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0"> 
<link rel="stylesheet" href="css.css" type="text/css";>
<script type="text/javascript">
function alertUser(msg) {alert(msg); }
</script>
</head>

<body onload="alertUser('Use the code SlickNick to get 15% off of your purchase!')">
<div id="wrap">
<header>
<h1>Nick's Powerwashing</h1>
</header>

	<nav>
		<ul>
			<li><a href="index.html">Home Page</a></li>
			<li><a href="info.html">Informational</a></li>
			<li><a href="sources.html">Sources</a></li>
			<li><a href="contact.html">Contact</a></li>
	</nav>
	
	

	<div id="content">
		<h2>Welcome</h2>
		<p>Nicks Powerwashing is a small family operated business tailored to offer 
		high-quality, moderately priced services using only the best products
		available. We strive to put our customers, community and the environment
		first. Our goal is to be a leader in our area of expertise by using new
		technology and other innovations to deliver our services with as much
		information and professionalism as possible.</p>
		<div class="align">
		<img src="badwalk.jpg" height="250px" width="200px">
		<img src="badsteps.gif" height="250px" width="250px">
		<img src="b4nafter.jpg" height="250px" width="600px">
		</div>
	</div>
<footer>
		<ul>
			<li><a href="index.html">Home Page</a></li>
			<li><a href="info.html">Informational</a></li>
			<li><a href="sources.html">Sources</a></li>
			<li><a href="contact.html">Contact</a></li>
		</ul>
</footer>
</div>
</body>
</html>

Here is the Info page:

<!DOCTYPE html>
<html lang="eng">
<head>
<!--[if lt IE 9]>
<script src="http://html5shim.googlecode.com/svn/trunk/html5.js">
</script>
<![endif]-->
<title>Nick's Powerwashing, Cement Seal and Deck Staining</title>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0"> 
<link rel="stylesheet" href="css.css" type="text/css";>
</head>

<body>
<div id="wrap">
<header>
<h1>Nick's Powerwashing</h1>
</header>
	
	<nav>
		<ul>
			<li><a href="index.html">Home Page</a></li>
			<li><a href="info.html">Informational</a></li>
			<li><a href="sources.html">Sources</a></li>
			<li><a href="contact.html">Contact</a></li>
	</nav>
	
	<div id="content">
	<h1>Content: </h1>
		<ol>
			<li><a href="#history">History</a></li>
			<li><a href="#powerwashing">Powerwashing</a></li>
			<li><a href="#deck">Deck Staining</a></li>
			<li><a href="#seal">Cement Sealing</a></li>
			<li><a href="#estimate">Rough Estimates</a></li>
		</ol>
		<div id="history">
		<h2>History</h2>
		<p>Nicks Powerwashing is a small family operated business tailored to offer
		high-quality, moderately priced services using only the best products
		available. We strive to put our customers, community and the environment
		first. Our goal is to be a leader in our area of expertise by using new
		technology and other innovations to deliver our services with as much
		information and professionalism as possible.</p>
		</div>
		<div id="powerwashing">
		<h2>Powerwashing</h2>
		<p>Power washing otherwise known as pressure washing, is an essential tool when 
		dealing with staining decks or sealing cement. Power washing opens up the pores 
		of the wood on decks and cleans off all the algae, dirt and other grime. This is 
		typically done the day before a deck is scheduled to be stained and takes no time 
		at all. The same goes for cement, there are microscopic "holes" in the cement 
		where water becomes trapped and soaks into the cement, slowly breaking it down 
		and weakening it over time. Power washing cement allows for a clean surface for 
		the chemicals to adhere to properly. 
		<a href="http://en.wikipedia.org/wiki/Pressure_washer"> Wikipedia</a> has a more 
		detailed explanation of what power washing entails, check it out if you have any 
		other questions. Our company has a fifty gallon water tank that we have hooked 
		up to our power washer which sits on our trailer. Our power washer has a gas motor 
		and can dish out 1600 psi. We also have a variety of wands including a two story 
		magic wand for easy access to larger houses. We also have a buffer disk that is 
		primarily used for driveways, garages and walkways.</p>
		</div>
		<div id="deck">
		<h2>Deck Staining</h2>
		<p>There are a few rules and steps essential in deck staining. The first and most 
		important rule is to clean the deck first. Taking away the algae, dirt and loose 
		pieces from the previous stain will allow the pours to open up and soak in the stain 
		you will be applying, allowing for longer longevity for your deck. This is always 
		done the day before we stain your deck to ensure that the deck is dry and free of 
		any water puddles. The other rule is just as important as the first, which is, weather. 
		Weather plays such a big role when it comes down to the staining day, if the forecast 
		calls for rain, then we cannot stain that day. Staining your deck requires 24-48 hours 
		of rain free weather, to ensure that the stain soaks in the wood. There are many stains 
		out there however there are only 3 types of stain; water based, oil based and gel. 
		There’s a lot of information about wood stains at 
		<a href="http://en.wikipedia.org/wiki/Wood_stain">Wikipedia</a> but that might be a 
		little confusing. Water base is thicker, takes a short amount of time to dry, has no 
		flammable or harmful vapors and is environmentally friendly. Oil based stains dry much 
		faster and does not require such a heavy coating and you get a smoother coat. They 
		also show more of the natural wood grain than the water and gel base stains. Gel based 
		stains are not used as often but still has its advantages. This is more of a thicker 
		paste like substance and works more like paint, not allowing any grain to show through. 
		Our first step when we arrive is to tape off the surrounding area with painters tape 
		and plastic, so everything around your deck is protected. After that we get our supplies 
		ready and clear the deck off if there’s anything on it. After we stain the deck we will 
		take all the tape and plastic down, if there’s any we can’t reach we will come back the next day.</p>
		</div>
		<div id="seal">
		<h2>Concrete Sealing</h2>
		<p>Sealing your walkway, driveway or patio is something that is extremely important in 
		extending the life and look of your cement. Sealing your cement every five years will 
		prevent stains from decaying leaves, tire marks, oil spills, and other hazardous outside
		forces. This also prevents water from soaking into your cement and slowly breaking it down
		making it weaker and more prone to cracks. The process is done in one day and takes roughly
		24 hours to cure and dry properly, so no walking, driving or putting any furniture on the 
		finished area. We start by power washing the area first to assure that there is no mold, dirt
		or loose particles to get in the way of the sealant we are using. After it dries we then sweep 
		anything else off and start applying the sealant. We apply it by spray, being careful not to 
		create any heavy spots or puddles. We tape the area off so no one else can walk on it and just
		wait 24 hours before driving on it.</p>
		</div>
		<div id="estimate">
		<table border="1">
		<tr>
			<th>Powerwahsing</th>
			<th>Deck Staining</th>
			<th>Cement Sealing</th>
		</tr>
		<tr>
			<td>Ranch - $250.00</td>
			<td>Small 100ft x 100ft - $400.00</td>
			<td>Walkways - $200.00</td>
		</tr>
		<tr>
			<td>2 Story House - $400.00</td>
			<td>Medium 500ft x 500ft - $850.00</td>
			<td>Small Driveways - $300.00</td>
		</tr>
		<tr>
			<td>2 Story House and Garage - $450.00</td>
			<td>Large 1000ft x 100ft - $1200.00</td>
			<td>Large Driveways - $700.00</td>
		</tr>
		</table>
		</div>
	</div>
<footer>
		<ul>
			<li><a href="index.html">Home Page</a></li>
			<li><a href="info.html">Informational</a></li>
			<li><a href="sources.html">Sources</a></li>
			<li><a href="contact.html">Contact</a></li>
		</ul>
</footer>
</div>
</body>
</html>

Here is the Sources page:

<!DOCTYPE html>
<html lang="eng">
<head>
<!--[if lt IE 9]>
<script src="http://html5shim.googlecode.com/svn/trunk/html5.js">
</script>
<![endif]-->
<title>Nick's Powerwashing, Cement Seal and Deck Staining</title>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0"> 
<link rel="stylesheet" href="css.css" type="text/css";>
</head>

<body>
<div id="wrap">
<header>
<h1>Nick's Powerwashing</h1>
</header>

	<nav>
		<ul>
			<li><a href="index.html">Home Page</a></li>
			<li><a href="info.html">Informational</a></li>
			<li><a href="sources.html">Sources</a></li>
			<li><a href="contact.html">Contact</a></li>
	</nav>

	<div id="content">
		<h2>Sherwin Williams</h2>
		<p>Nicks Powerwashing is a small family operated business tailored to offer 
		high-quality, moderately priced services using only the best products
		available. We strive to put our customers, community and the environment
		first. Our goal is to be a leader in our area of expertise by using new
		technology and other innovations to deliver our services with as much
		information and professionalism as possible.</p>
		<h2>Heres some tips and how-to's from Lowes</h2>
		<iframe src="http://www.youtube.com/embed/CSXZ-fOzd9I" width="500px" height="500px">
			<a href="http://www.youtube.com/embed/CSXZ-fOzd9I">YouTube Video</a>
		</iframe>
		
		<div id="gallery">
		<h2>Here are some great pictures of what we do!</h2>
			<figure>
				<img src="closeup.jpg" width="200px" height="150px">
			</figure>
			<ul>
				<li><a href="closeup.jpg"><img src="closeup.jpg" width="100px" height="75">
				<span><img src="closeup.jpg" width="200px" height="150px" alt="Cement Sealer Closeup"></span></a></li>
			
				<li><a href="closeup1.jpg"><img src="closeup1.jpg" width="100px" height="75">
				<span><img src="closeup1.jpg" width="200px" height="150px" alt="Water on cement after sealed"></span></a></li>
			
				<li><a href="seal1.jpg"><img src="seal1.jpg" width="100px" height="75">
				<span><img src="seal1.jpg" width="200px" height="150px" alt="Driveway after a seal"></span></a></li>
			
				<li><a href="deckstain1.jpg"><img src="deckstain1.jpg" width="100px" height="75">
				<span><img src="deckstain1.jpg" width="200px" height="150px" alt="Rails of a deck getting stained"></span></a></li>
				
				<li><a href="deckstain2.jpg"><img src="deckstain2.jpg" width="100px" height="75">
				<span><img src="deckstain2.jpg" width="200px" height="150px" alt="Deck half done"></span></a></li>
				
				<li><a href="deckstain4.jpg"><img src="deckstain4.jpg" width="100px" height="75">
				<span><img src="deckstain4.jpg" width="200px" height="150px" alt="Deck split for compare"></span></a></li>
				
				<li><a href="deckstain3.jpg"><img src="deckstain3.jpg" width="100px" height="75">
				<span><img src="deckstain3.jpg" width="200px" height="150px" alt="Even small decks!"></span></a></li>
			</ul>
		</div>
		
		
	</div>
<footer>
		<ul>
			<li><a href="index.html">Home Page</a></li>
			<li><a href="info.html">Informational</a></li>
			<li><a href="sources.html">Sources</a></li>
			<li><a href="contact.html">Contact</a></li>
		</ul>
</footer>
</div>
</body>
</html>

And here is the Contacts Page:

<!DOCTYPE html>
<html lang="eng">
<head>
<!--[if lt IE 9]>
<script src="http://html5shim.googlecode.com/svn/trunk/html5.js">
</script>
<![endif]-->
<title>Nick's Powerwashing, Cement Seal and Deck Staining</title>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0"> 
<link rel="stylesheet" href="css.css" type="text/css";>
<!--
function validateForm() 
{ 
if( info.myEmail.value == "" )  
	{
	alert("Please enter an e-mail address."); return false;}
		else {end if return true}
if( info.myLName.value == "" )  
	{
	alert("Please enter an e-mail address."); return false;}
		else {end if return true}
if( info.myArrival.value == "" )  
	{
	alert("Please enter an e-mail address."); return false;}
		else {end if return true}
if( info.myGuests.value == "" )  
	{
	alert("Please enter an e-mail address."); return false;}
		else {end if return true}
}
// -->
</head>

<body>
<div id="wrap">
<header>
<h1>Nick's Powerwashing</h1>
</header>

	<nav>
		<ul>
			<li><a href="index.html">Home Page</a></li>
			<li><a href="info.html">Informational</a></li>
			<li><a href="sources.html">Sources</a></li>
			<li><a href="contact.html">Contact</a></li>
	</nav>
	
	

	<div id="content">
		<h2>Contact us here!</h2>
		<h4>Fill out the required fields and we'll get back to you.</h4>
		<form name="info" method="post" id="info" action="http://webdevbasics.net/scripts/demo.php"
		onsubmit="return(validateForm());">
	
		<label for="myFName">*First Name: </label><input type="text" name="myFName" id="myFName" required="required">
		<label for="myLName">*Last Name: </label><input type="text" name="myLName" id="myLName" required="required">
		<label for="myPhone">*Phone: </label><input type="tel" name="myPhone" id="myPhone" maxlength="12" required="required">
		<label for="myArrival">*Address: </label><input type="date" name="myArrival" id="myArrival" required="required">
		<label for="myArrival">*City: </label><input type="date" name="myArrival" id="myArrival" required="required">
		<label for="state">*State: </label>
		<select name="state" id="state" required="required"> <option>Select State</option>
			<option>Alabama</option><option>Alaska</option><option>Arizona</option><option>Arkansas</option><option>California</option><option>Colorado</option>
			<option>Connecticut</option><option>Delaware</option><option>Florida</option><option>Georgia</option><option>Hawaii</option><option>Idaho</option>
			<option>Illinois</option><option>Indiana</option><option>Iowa</option><option>Kansas</option><option>Kentucky</option><option>Louisiana</option>
			<option>Maine</option><option>Maryland</option><option>Massachusetts</option><option>Michigan</option><option>Minnesota</option><option>Mississippi</option>
			<option>Missouri</option><option>Montana</option><option>Nebraska</option><option>Nevada</option><option>New Hampshire</option><option>New Jersey</option>
			<option>New Mexico</option><option>New York</option><option>North Carolina</option><option>North Dakota</option><option>Ohio</option><option>Oklahoma</option>
			<option>Oregon</option><option>Pennsylvania</option><option>Rhode Island</option><option>South Carolina</option><option>South Dakota</option><option>Tennessee</option>
			<option>Texas</option><option>Utah</option><option>Vermont</option><option>Virginia</option><option>Washington</option><option>West Virginia</option>
			<option>Wisconsin</option><option>Wyoming</option>
		</select>
		<label for="myArrival">*Four Digit Zip Code: </label><input type="date" name="myArrival" id="myArrival" required="required">
		<label for="myEmail">E-mail: </label><input type="text" name="myEmail" id="myEmail" size="40">
		
		<label for="myComments">*Comments: </label><br><textarea type="text" name="myComments" id="myComments"
		rows="2" cols="32" required="required"></textarea>
		<input type="image" src="submit.gif" alt="submit">
		</form>
	</div>
<footer>
		<ul>
			<li><a href="index.html">Home Page</a></li>
			<li><a href="info.html">Informational</a></li>
			<li><a href="sources.html">Sources</a></li>
			<li><a href="contact.html">Contact</a></li>
		</ul>
</footer>
</div>
</body>
</html>
