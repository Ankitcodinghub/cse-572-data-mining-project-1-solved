# cse-572-data-mining-project-1-solved
**TO GET THIS SOLUTION VISIT:** [CSE 572 Data mining Project 1 Solved](https://www.ankitcodinghub.com/product/cse-572-data-mining-project-1-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;46945&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;4&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (4 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE 572 Data mining Project 1 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (4 votes)    </div>
    </div>
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
&nbsp;

Some facts about the data:

Each cell array is an array of time series each of which can have varying lengths.

Each subject has multiple such time series but the total number of time series data for each subject may vary.

You have data from 5 subjects

The insulin input may not be every 5 mins hence the insulin time series length may vary significantly

The time stamp which has the highest insulin delivery is the time at which the meal was logged.

<strong>Tasks:</strong>

<ol>
<li>Extract 4 different types of time series features from only the CGM data cell array and CGM timestamp cell array (10 points each) total 40</li>
<li>For each time series explain why you chose such feature (5 points each) total 20</li>
<li>Show values of each of the features and argue that your intuition in step b is validated or disproved? (5 points each ) total 20</li>
<li>Create a feature matrix where each row is a collection of features from each time series. SO if there are 75 time series and your feature length after concatenation of the 4 types of featues is 17 then the feature matrix size will be 75 X 17 (10 points)</li>
<li>Provide this feature matrix to PCA and derive the new feature matrix. Chose the top 5 features and plot them for each time series. (5 points)</li>
<li>For each feature in the top 5 argue why it is chosen as a top five feature in PCA? (3 points each) total 15</li>
</ol>
&nbsp;
