# ce295-hw-4-forecasting-residential-electricity-power-consumption-solved
**TO GET THIS SOLUTION VISIT:** [CE295 HW 4-Forecasting Residential Electricity Power Consumption Solved](https://www.ankitcodinghub.com/product/ce295-hw-4-forecasting-residential-electricity-power-consumption-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;95663&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CE295 HW 4-Forecasting Residential Electricity Power Consumption Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (1 vote)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
&nbsp;

You have been hired as a Building Energy Data Scientist. Congratulations! What an exciting new op- portunity! In your first job assignment, you must construct algorithms to forecast residential electricity consumption with data and machine learning (ML). The assignment is organized in a tutorial fashion, thereby allowing you to practice ML on a relevant real-world energy system example.

Reading

[Optional] Read “Gated Ensemble Learning Method for Demand-Side Electricity Load Forecasting” first authored by Eric Burger, available at this URL.

Background

Several years ago we collected Green Button Data &lt;http://www.greenbuttondata.org/&gt; from the CE 295 students. This data includes hourly electricity consumption from over 20 residences in the East Bay. The data has been (mostly) cleansed for your convenience including (i) aligning time-stamps, (ii) filling-in missing data, and (iii) organizing it into an easily readable format.

Problem 1: Exploratory Data Analysis

Download the data file HW4_Train_Data.csv. Load the CSV data into Matlab or Python

<ol>
<li>(a) &nbsp;Create a bar plot of the average hourly energy consumption [kWh] for each building. Make the x-axis the building index number. Make the y-axis the average hourly energy consumption. In red, super impose error bars on your bars that indicate the standard deviation of hourly energy consumption. Provide this plot in your report.</li>
<li>(b) &nbsp;Which building has abnormally high variance? Do any buildings have moments of NEGATIVE power consumption? If so, then we will remove this building from our analysis. This building likely in- stalled solar during the year and the smart meter data aggregates power consumption and solar power generation, so it’s un-usable for this homework.</li>
<li>(c) &nbsp;Re-organize your energy data set into a 4-D array. In order, the dimensions correspond to (i) building index, (ii) week-of-year, (iii) day-of-week, and (iv) hour-of-day. For each element in the 4-D vector, store the normalized energy. That is, divide kWh by the maximum hourly energy consumption for that building.
Normalize the energy for each building. That is, divide kWh by the maximum hourly energy consump- tion for that building. In industry and academia, we sometimes refer to these normalized building electricity consumption trajectories as “load shapes”. Now, generate the following plots:

• In seven separate figures (one for each day-of-week), plot the hourly energy consumption load shapes vs. hour (x-axis) for each building – all super-imposed.
</li>
</ol>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
• In each of the seven figures, plot the average hourly energy consumption in a thick black line.

How to do this? In Matlab, you can re-organize your energy data set into a 4-D array. In order, the dimensions can correspond to (i) building index, (ii) week-of-year, (iii) day-of-week, and (iv) hour-of- day. For each element in the 4-D vector, store the normalized energy. In Python, you can create a DataFrame with the Pandas library, where the first three columns are week-of-year, day-of-week, and hour-of-day. The next columns would be normalized energy for all the buildings. Then you can use the groupby function in Pandas to help you generate the plots.

Provide the seven plots in your report. They should look similar to Fig. 1 below. Comment on any observations you might have.

Figure 1: Example of plot you must produce for Problem 1(c).

Problem 2: Average Model

In this problem, we design an extremely simple forecasting model that is often effective. We call it the “Average Model”. The average model forecasts the building power to be the average value from historical data at the HoD and DoW. Mathematically:

7 24

Pˆavg(k)=􏰉􏰉P ̄ij ·Uij(k) (1) i=1 j=1

where

• P ̄ ∈ R7×24 is the average value from historical data, for each (DoW, HoD) pair.

• U(k) ∈ {0,1}7×24. All elements are zero, except the one element which corresponds to (DoW,HoD) at time step k. For example,

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
– if k corresponds to 12am on Sunday, then U1,1(k) = 1.

– if k corresponds to 3am on Monday, then U2,4(k) = 1.

– if k corresponds to 11pm on Saturday, then U7,23(k) = 1.

Answer the following questions.

</div>
<div class="column">
Spring 2019 Professor Scott Moura

</div>
</div>
<div class="layoutArea">
<div class="column">
<ol>
<li>(a) &nbsp;Download test data file HW4_Test_Data.csv. Load the CSV data into Matlab or Python. The test data includes one week of normalized hourly load for Sunday Sept 7, 2014 00:00 – Saturday Sept 13, 2014 23:00. Generate seven plots (one for each DoW) which visualize HoD (x-axis) and the normalized hourly energy for the Test Data and Average Model.</li>
<li>(b) &nbsp;Compute the mean absolute error (MAE)
1 􏰉m

|P(k)−Pˆ(k)| (2) for each DoW and the entire week. Provide these error metrics in your report. Which DoW has the

largest and smallest MAE?
</li>
</ol>
Problem 3: Autoregressive with eXogeneous Inputs Model (ARX)

In this problem, we will design a forecasting model based on the Autoregressive with eXogenous inputs model (ARX). We consider the ARX model given by:

L

Pˆarx(k)=􏰉αl ·P(k−l)+Pˆavg(k) (3)

l=1

where Pˆ(k) is the normalized hourly energy consumption we aim to forecast in the target hour. The inputs include the previous hourly energy consumption: P (k − 1), P (k − 2), · · · , P (k − L). We will also consider an exogenous term corresponding to the average power: Pˆavg(k). Consequently, the autoregressive terms adjust the average model based upon temporally local power, over a short retrospective horizon. In total, we must fit L parameters. Answer the following questions.

<ol>
<li>(a) &nbsp;Write the ARX model in linear-in-the-parameters form: Y = Φθ as described in the video lectures. Define the vector Y and matrix Φ.</li>
<li>(b) &nbsp;Formulate a least squares optimization problem to find the optimal parameters αl, l = 1, 2, · · · L which fit your data. Write down the objective function. Define your notation. Is this a convex program? Why?</li>
<li>(c) &nbsp;Solve your optimization problem with L = 3. In your report, give the optimal values of α1⋆, α2⋆, α3⋆.</li>
<li>(d) &nbsp;Test your ARX model on the test data set. Generate seven plots (one for each DoW) which visualize HoD (x-axis) and the normalized hourly energy for the Test Data, the Average Model, and the ARX model. Report the MAE for each DoW, and the entire week.
&nbsp;
</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
MAE = m

</div>
<div class="column">
i=1

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
Problem 4: Neural Network Model

Next, we consider a neural network (NN) model, and more specifically a single neuron model. As detailed below, the NN model is just a nonlinear function with many parameters (a.k.a. “weights” in the jargon of ML). Our NN model is simply: Pˆnn(k) = fnn(x;θ)+Pˆavg(k) where the NN makes adjustments to the power forecast relative to the mean.

</div>
</div>
<div class="layoutArea">
<div class="column">
(a) Consider the least squares error:

</div>
</div>
<div class="layoutArea">
<div class="column">
mmm

</div>
</div>
<div class="layoutArea">
<div class="column">
1􏰉 2 1􏰉􏰌 (i)

</div>
<div class="column">
T

</div>
<div class="column">
(i) 􏰍2 )

</div>
<div class="column">
1􏰉􏰌 (i)

</div>
<div class="column">
(6)

</div>
</div>
<div class="layoutArea">
<div class="column">
J=2 δi =2 i=1

</div>
<div class="column">
y

</div>
<div class="column">
−y(w x

</div>
<div class="column">
=2

</div>
<div class="column">
y

</div>
</div>
<div class="layoutArea">
<div class="column">
i=1

Our objective is to fit neural network weights w to the example training data,

</div>
</div>
<div class="layoutArea">
<div class="column">
x(i) =[P(k−1),P(k−2),P(k−3)]T, y(i) =P(k)−P ̄TU(k)

where training example index (i) = 1,2,··· ,m corresponds to time index k = 4,5,··· ,K. We do this

by solving a nonlinear least squares optimization problem:

minimize J = 1 􏰉m 􏰌y(i) − tanh(wT x(i))􏰍2 (8)

2

i=1

which is a nonlinear program because the output y is nonlinear w.r.t. weights w. What are the

optimization variables?

<ol start="2">
<li>(b) &nbsp;A simple fitting/optimization algorithm is called “gradient descent”:
wk+1 = wk − γ · ∂J 􏰀wk􏰁 (9) ∂w

where superscript (·)k represents the iterations. Armed with the gradient descent method, our next goal is to compute the gradient in (9). Use chain rule to expand ∂J/∂w, as done in the lecture videos. After expanding with chain rule, then express each term analytically.
</li>
<li>(c) &nbsp;Implement the gradient descent algorithm yourself. Select an initial guess of w0 = 0 ∈ R3. Use a small step size/learning rate, such as γ = 10−3 or 10−4. Perform at least three steps of gradient descent. In
Page 4 of 5
</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
3

z = 􏰉wlxl=wTx (4) l=1

</div>
</div>
<div class="layoutArea">
<div class="column">
y =

</div>
<div class="column">
f(z) = tanh(z)

T (i) 􏰍2 −tanh(w x )

</div>
<div class="column">
(5)

</div>
</div>
<div class="layoutArea">
<div class="column">
i=1

</div>
</div>
<div class="layoutArea">
<div class="column">
(7)

your report, give the final values of w1⋆, w2⋆, w3⋆.

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
(d) Test your NN model on the test data set. Generate seven plots (one for each DoW) which visualize HoD (x-axis) and the normalized hourly energy for the Test Data, the Average Model, the ARX model, and the NN model. Report the MAE for each DoW, and the entire week.

Interesting Remarks

• Stochastic gradient descent (SDG) is a popular alternative to the gradient descent algorithm in (9) in ML. In gradient descent, we update weights by computing the gradient with ALL training examples. This can be a computationally heavy task. In SDG, we update a weights based on a RANDOM SUBSET (e.g. 10%) of training examples within each iteration. This is computationally lighter, since we significantly reduce the number of forward propagations and backward propagations through the neural network.

Deliverables

Submit the following on bCourses. Be sure that the function files are named exactly as specified (including spelling and case). Please do NOT zip files.

LASTNAME_FIRSTNAME_HW4.PDF

LASTNAME_FIRSTNAME_HW4.xyz which contains your respective Matlab or Python files, i.e. xyz ∈ {m, ipynb}.

</div>
</div>
<div class="layoutArea">
<div class="column">
&nbsp;

</div>
</div>
</div>
