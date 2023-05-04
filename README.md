Download Link: https://assignmentchef.com/product/solved-cse-572-data-mining-project-1
<br>
<h1></h1>

<h1>This is an individual project</h1>




<strong>Input: </strong>Five cell arrays:

<ol start="2">

 <li>The first cell array has tissue glucose levels every 5 mins for 2.5 hrs during a lunch meal</li>

</ol>

The data starts from 30 mins before meal intake an continues up to 2 hrs after the start of meal consumption

There are several such time series for one subject.

<ol>

 <li>The second cell array has time stamps of each time series in the first cell array</li>

 <li>The third cell array has insulin basal infusion input time series at different times during the 2.5 hr time interval</li>

 <li>The fourth cell array has time stamps for each basal or bolus insulin delivery time series.</li>

 <li>The fifth cell array has insulin bolus infusion input time series at different times during the 2.5 hr time interval</li>

</ol>




Some facts about the data:

Each cell array is an array of time series each of which can have varying lengths.

Each subject has multiple such time series but the total number of time series data for each subject may vary.

You have data from 5 subjects

The insulin input may not be every 5 mins hence the insulin time series length may vary significantly

The time stamp which has the highest insulin delivery is the time at which the meal was logged.

<strong>Tasks:</strong>

<ol>

 <li>Extract 4 different types of time series features from only the CGM data cell array and CGM timestamp cell array</li>

 <li>For each time series explain why you chose such feature</li>

 <li>Show values of each of the features and argue that your intuition in step b is validated or disproved?</li>

 <li>Create a feature matrix where each row is a collection of features from each time series. SO if there are 75 time series and your feature length after concatenation of the 4 types of features is 17 then the feature matrix size will be 75 X 17 (Provide this feature matrix to PCA and derive the new feature matrix. Chose the top 5 features and plot them for each time series.</li>

 <li>For each feature in the top 5 argue why it is3a chosen as a top five feature in PCA?</li>

</ol>


