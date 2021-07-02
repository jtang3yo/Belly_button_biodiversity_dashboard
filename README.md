Bellybutton Biodiversity Dashboard 

Overview

  Roza has a partially completed dashboard that she needs to finish. She has a completed panel for demographic information and now needs to visualize the bacterial data for each volunteer.Specifically, her volunteers should be able to identify the top 10 bacterial species in their belly buttons. That way, if Improbable Beef identifies a species as a candidate to manufacture synthetic beef, Roza's volunteers will be able to identify whether that species is found in their navel.
  
	Initial dashboard:
initial dashboard<img width="615" alt="initial dashboard" src="https://user-images.githubusercontent.com/82353749/124327512-07d4f780-db56-11eb-900d-e3252da27104.png">

	
	1. Deliverable 1: Create a Horizontal Bar Chart
	* Create buildChart()function use d3.json("samples.json").then() to load external json file, use filter()method on array to get samples array; 
	* Create a variable that filters the samples for the object with the desired sample number.
    filteredSample = sampleArray.filter(sampleObj => sampleObj.id == sample);
	* Use slice() method to filter the top 10 OTU with otu_ids 
otu and yticks variables <img width="699" alt="otu and yticks variables " src="https://user-images.githubusercontent.com/82353749/124330108-c09d3580-db5a-11eb-8743-e60d193fecbd.png">

barchart<img width="573" alt="barchart" src="https://user-images.githubusercontent.com/82353749/124330716-00b0e800-db5c-11eb-9917-95d781b708bb.png">

	2. Deliverable 2: Create a Bubble Chart: refactored the code to plot bubble chart
bubblechart<img width="547" alt="bubblechart" src="https://user-images.githubusercontent.com/82353749/124331109-c431bc00-db5c-11eb-8782-464164c76111.png">

	3. Deliverable 3: Create a Gauge Chart: refactor the code to iterrate metadata object with filter() method to return wfreq element, and plot gauge chart.
gaugechart<img width="821" alt="gaugechart" src="https://user-images.githubusercontent.com/82353749/124331524-5a65e200-db5d-11eb-8f24-1c6f1c44cd0a.png">

	4. Deliverable 4: Customize the Dashboard
	Created style.css with customization css code with color, font, styling refactoring.
css customize<img width="578" alt="css customize" src="https://user-images.githubusercontent.com/82353749/124331747-dc560b00-db5d-11eb-9bfa-79aa669f248c.png">

	Bellybutton Biodiversity Dashboard page: 
page1<img width="1440" alt="page1" src="https://user-images.githubusercontent.com/82353749/124332897-ae25fa80-db60-11eb-8fe1-04d551fc524b.png">
  	Update interactive filter: 
interactive filter<img width="1440" alt="interactive filter" src="https://user-images.githubusercontent.com/82353749/124332925-c0079d80-db60-11eb-9aca-4ffe685ad585.png">

Visit interactive data: 
https://jtang3yo.github.io/Belly_button_biodiversity_dashboard/challenge/index.html

-- JavaScript, D3.js, Plotly, Bootstrap, CSS and HTML 
