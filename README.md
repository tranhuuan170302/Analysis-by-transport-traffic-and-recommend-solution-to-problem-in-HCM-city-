# Analysis by transport traffic and recommend solution to problem in HCM city
------------------
<p>Identify vehicle behavior in every moments of date or week and using model machine learning to predict state traffic congestion in the future with Python.</p>


## OverView
<p>The dataset was collected from the research group of HCM university of technology. it's talking about state traffic congestion by time, street segment, and type of street. The dataset includes 4 file data (node, segment, segment_status, street). When analyzing the dataset, we merge all files. so it has 90481 rows and 15 columns.</p>
<p>We'll analyzing the dataset to collect insights of time traffic congestion, states traffic congestion where does it take place, and based on segment length of street.</p>
<p>While analyzing processing data, We need data preprocessing include: Convert data type, data standardization.</p>

## Purpose
<p>In this project, we want show solution to slove this problem.</p>
<ul>
  <li>Short-term: During peak hours, the red light signal at the intersections and junctions will change to the yellow light signal. Arrange traffic controllers to control there.</li>
  <li>Long-term: Change the time frame between people going to work and going to school. Encourage commuters to travel by train or bus. Residential evacuation...</li>
</ul>

## Model predict.
<p>Model using linear regression to evaluate. Model show result not good, so we can't using model to predict traffic congestion state in the future.</p>
