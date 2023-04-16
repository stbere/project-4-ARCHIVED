# US Housing Forecast & Prediction

View our final project for Group 3 in [Github Pages](https://stbere.github.io/project-4/) or directly on [Github](https://stbere.github.io/project-4/)!



<img src="https://github.com/stbere/project-4/blob/main/images/forecast-fortress.PNG">



<!DOCTYPE html>
<html>

<head>
  <title>&#128200; Home Value Predictions &#128200;</title>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <!--I wanted a specific font. The link below helped me. We can change it later-->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link rel="stylesheet" href="style.css">

  <link href="https://fonts.googleapis.com/css2?family=Libre+Barcode+128+Text&display=swap" rel="stylesheet">

</head>

<body>
<div class="header">
  <img src="https://github.com/stbere/project-4/blob/main/images/forecast-fortress.PNG?raw=true" alt="Website Banner" style="width:100%; max-width:1000px; height:auto;">
</div>
</br>
 <div class="image-container">
	<img src="https://cdn.pixabay.com/photo/2017/10/26/17/51/under-construction-2891888__480.jpg">
</div>
</br>
</br>
<div class="text-container">
	<h1>
    <p>Our first Machine Learning example yielded low accuracy over a large, unfiltered dataset</p>
    </h1>
</div>
</br>
<style>
    /* Center align the iframe element */
    iframe {
        display: block;
        margin: 0 auto;
    }
</style>
<iframe src="https://giphy.com/embed/WeuiU5wFZQuV7HA7om" align="center" width="480" height="434" frameBorder="0" allowFullScreen></iframe><p>
<br>
<div class="text-container">
    This was our first attempt at home value forecasting. It is a linear regression model
	attempting to predict home values from a fhfa.gov public dataset. The model uses a target
	variable of 'NoteAmount' (the amount the bank has loaned to an individual in our dataset), and independent variables of
	'TotalyMonthlyIncomeAmount' and 'LTVRatioPercentage' (loan-to-value ratio -- think equity)
</div>
<style>
    .button-container {
        text-align: center;
    }
</style>
      <div class="button-container">
        <button onclick="window.open('https://github.com/stbere/project-4/blob/main/fhfa-ml-loan-amount-predictions.ipynb')">Python Script for Linear Regression model</button>
      </div>
<br>	  
<div class="half-page-line"></div>
<br>
<br>
<div class="text-container">
	<h2>
	<p>Our second Linear Regression Machine Learning example improved, but only slightly</p>
	</h2>
</div>
<style>
    /* Center align the iframe element */
    iframe {
        display: block;
        margin: 0 auto;
    }
</style>
<iframe src="https://giphy.com/embed/XhcRBmGgsIpqoMvIF0" width="480" height="386" align="center" frameBorder="0" class="giphy-embed" allowFullScreen align="center"></iframe><p>
<br>
	<div class="text-container">
		This model had a low accuracy but taught us how to finetune our parameters.
		The current model is only 10% accurate with an R-squared value of 0.10
		This particular linear regression model is attempting to predict home values in
		Tulsa, OK based on data from the years 2000 to 2023
</div>
<style>
    .button-container {
        text-align: center;
    }
</style>
	<div class="button-container">
		<button onclick="window.open('https://github.com/stbere/project-4/blob/main/zillowhomevalues-oklahoma.ipynb')">Python Script for 2nd Linear Regression model</button>
	</div>
<br>	  
<div class="half-page-line"></div>
<br>
<br>
<div class="text-container">
	<h2>
    <p>Our third Machine Learning example, this time we used the Random Forest Regressor </p>
	</h2>
</div>
<style>
    /* Center align the iframe element */
    iframe {
        display: block;
        margin: 0 auto;
    }
</style>
<iframe src="https://giphy.com/embed/LHr9FHHD048Py7osBx" width="480" height="432" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p>
<br>
<style>
    .button-container {
        text-align: center;
    }
</style>
<div class="text-container">
    For this model, we achieved a Mean Absolute Error (MAE) of 80015.92 which means, on average, the predictions made
	by the Random Forest Regressor are off by about $80,016 in terms of the approved loan amount by a traditional bank.
	So according to this model, if the actual value of a loan is $200K, then the prediction made by this model for that
	amount might be around $280K
</div>
	<div class="button-container">
		<button onclick="window.open('https://github.com/stbere/project-4/blob/main/fhfagov-sklean_rfr.ipynb')">Python Script for 3rd ML Model</button>
	</div>
<br>	  
<div class="half-page-line"></div>
<br>
<br>
<div class="text-container">
	<h2>
    <p>Our Fourth Machine Learning example, this time we used the Polynomial features for a Linear Regression model.</p>
	</h2>
</div>
<style>
    /* Center align the iframe element */
    iframe {
        display: block;
        margin: 0 auto;
    }
</style>
<iframe src="https://giphy.com/embed/FVaBzBtU7dEoZYR4Ao" width="480" height="434" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p>
<br>
<div class="text-container">
    Our final model uses a polynomial features for our linear regression model.
	This model gives us 76% accuracy when predicting home values in Tulsa, OK based on:
	1) Bedrooms, 2) Bathrooms, 3) Square Footage of house & 4) Year Built
	It is using a RapidAPI function to acquire the dataset.
</div>
<style>
    .button-container {
        text-align: center;
    }
</style>
	<div class="button-container">
		<button onclick="window.open('https://github.com/stbere/project-4/blob/main/polynomial-model-ml.ipynb')">Python Script for 4th ML Model</button>
	</div>
<br>	  
<div class="half-page-line"></div>
<br>
<br>
<br>
      <div class="rss-feed">
        <h2>News Feed</h2>
        <h3>What are people saying about the US Housing Market? How do we help determine our predictions *outside* of our data? The news, of course!</h3>

        <!-- I used xml here bc it is easier to read in this case-->

  <!-- Add the scrollbox wrapper here -->
  <div style="height: 450px; overflow: auto;">
    <div id="rss-feed">
      <ul id="feed-list"></ul>
    </div>
  </div>

              <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>

              <script>
                $(document).ready(function () {
                  $.ajax({
                    url: "https://rss.app/feeds/tK90yxtx7qZdZ9V5.xml",
                    dataType: "xml",
                    success: function (data) {
                      var $xml = $(data);
                      var items = [];
                      $xml.find("item").each(function () {
                        var $this = $(this);
                        var title = $this.find("title").text();
                        var link = $this.find("link").text();
                        var imgSrc = $this.find("media\\:content, content").first().attr("url");
                        var imgHtml = '';
                        if (typeof imgSrc !== 'undefined') {
                          imgHtml = '<img src="' + imgSrc + '" class="feed-item-image" width="300">';
                        }
                        items.push("<li class='feed-item'><a href='" + link + "' class='feed-item-content'>" + imgHtml + '<br>' + "<div class='feed-item-text'>" + title + "</div></a></li>");
                      });
                      $("#feed-list").html(items.join(""));
                    }
                  });
                });
              </script>
</div>
<br>
<br>
<br>
      <div class="text-box">
        <p>Cited/Referenced Sources:</p>
        RapidAPI -
        FHFA.gov -
        Zillow.com - 
		Rss.app
        <p>Copyright &copy; 2023</p>
      </div>

<script>
    console.log("Steve: Front-end HTML and ML Models. Operational assistance & research:");
</script>
	  
</body>

</html>



***Strictly for fictional project-use only***</br>
[Contribution guidelines for this project](https://www.fhfa.gov/DataTools/Downloads/Pages/Public-Use-Databases.aspx)

