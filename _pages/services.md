---
layout: default
permalink: /services/
---
<style>
#myBtn {
  display: none; /* Hidden by default */
  position: fixed; /* Fixed/sticky position */
  bottom: 20px; /* Place the button at the bottom of the page */
  right: 30px; /* Place the button 30px from the right */
  z-index: 99; /* Make sure it does not overlap */
  border: none; /* Remove borders */
  outline: none; /* Remove outline */
  background-color: #0086d6; /* Set a background color */
  color: #ffffff; /* Text color */
  cursor: pointer; /* Add a mouse pointer on hover */
  padding: 15px; /* Some padding */
  border-radius: 10px; /* Rounded corners */
  font-size: 18px; /* Increase font size */
}

#myBtn:hover {
  background-color: #555; /* Add a dark-grey background on hover */
}

* {
  box-sizing: border-box;
}

/* Float four columns side by side */
.column {
  display: table-cell;
  float: left;
  width: 33%;
  padding: 0 10px;
  display: flex;
}

/* Remove extra left and right margins, due to padding in columns */
.row {
  margin: 0 -5px;
  flex: 1; 
  width: 100%;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* Style the counter cards */
.card {
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2); /* this adds the "card" effect */
  padding: 16px;
  text-align: center;
  color: white;
  background-color: #0086d6;
  flex: 1;
}

/* Responsive columns - one column layout (vertical) on small screens */
@media screen and (max-width: 600px) {
  .column {
    width: 100%;
    display: block;
    margin-bottom: 20px;
  }
}
</style>

## We are <span style="color: #0086d6;">Feynic</span> Technology <button onclick="topFunction()" id="myBtn" title="Go to top">▲ Top</button>

***[fɛynic]*** *adj.* Using simple explanation methods.

***
	
## <a name="investors"></a><span style="color: #0086d6;">For Investors</span>

<div class="row">
	<div class="column">
		<div class="card">
			<h4>Seed Advice</h4>
		</div>
	</div>

	<div class="column">
		<div class="card">
			<h4>Market Insights</h4>
		</div>
	</div>
</div>

<div class="row">
	<div class="column">
		<div class="card">
			<img src="/assets/img/Seed.png">
			<br>
			<p>Translating research</p>
			<p>Identifying high growth potential</p>
			<p>Locating adjacent investments to the existing portfolio</p>
		</div>
	</div>
	
	<div class="column">
		<div class="card">
			<img src="/assets/img/Market_Insights.png">
			<br>
			<p>Example text</p>
		</div>
	</div>
</div>

***
	
## <a name="founders"></a><span style="color: #0086d6;">For Founders</span>

<div class="row">
	<div class="column">
		<div class="card">
			<h4>Advisory Services</h4>
		</div>
	</div>

	<div class="column">
		<div class="card">
			<h4>Seed Funding</h4>
		</div>
	</div>
	
	<div class="column">
		<div class="card">
			<h4>Training & Development</h4>
		</div>
	</div>
</div>

<div class="row">
	<div class="column">
		<div class="card">
			<img src="/assets/img/Advisory.png">
			<br>
			<p>Value proposition</p>
			<p>Commercialisation strategy</p>
			<p>Exit strategy planning</p>
		</div>
	</div>
	
	<div class="column">
		<div class="card">
			<img src="/assets/img/Seed.png">
			<br>
			<p>Some text</p>
			<p>Some text</p>
		</div>
	</div>
	
	<div class="column">
		<div class="card">
			<img src="/assets/img/Training.png">
			<br>
			<p>Ideation & Innovation Workshops</p>
			<p>Startup frameworks</p>
			<p>Minimum viable product development</p>
			<p>Specialism training</p>
			<p>Mentoring</p>
		</div>
	</div>
</div>

***

## <a name="institutions"></a><span style="color: #0086d6;">For Institutions</span>

<div class="row">
	<div class="column">
		<div class="card">
			<h4>Advisory Services</h4>
		</div>
	</div>

	<div class="column">
		<div class="card">
			<h4>Financial Assistance</h4>
		</div>
	</div>
	
	<div class="column">
		<div class="card">
			<h4>Professional Services</h4>
		</div>
	</div>			
</div>

<div class="row">
	<div class="column">
		<div class="card">
			<img src="/assets/img/Advisory.png">
			<br>
			<p>Ecosystem design, development and delivery</p>
			<p>Cluster strategy</p>
		</div>
	</div>

	<div class="column">
		<div class="card">
			<img src="/assets/img/Finance.png">
			<br>
			<p>Achieving commercial intent support</p>
			<p>Negotiation of consortium financing</p>
			<p>Identification of alternative funding options</p>
		</div>
	</div>
	
	<div class="column">
		<div class="card">
			<img src="/assets/img/Professional.png">
			<br>
			<p>Post-launch support for accelerator participants</p>
			<p>Commercial direction for research</p>
			<p>Training course design</p>
			<p>Insights into international partnership opportunities</p>
		</div>
	</div>			
</div>

<script>
//Get the button:
mybutton = document.getElementById("myBtn");

// When the user scrolls down 20px from the top of the document, show the button
window.onscroll = function() {scrollFunction()};

function scrollFunction() {
  if (document.body.scrollTop > 20 || document.documentElement.scrollTop > 20) {
    mybutton.style.display = "block";
  } else {
    mybutton.style.display = "none";
  }
}

// When the user clicks on the button, scroll to the top of the document
function topFunction() {
  document.body.scrollTop = 0; // For Safari
  document.documentElement.scrollTop = 0; // For Chrome, Firefox, IE and Opera
}
</script>