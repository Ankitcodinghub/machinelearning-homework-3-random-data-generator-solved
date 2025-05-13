# machinelearning-homework-3-random-data-generator-solved
**TO GET THIS SOLUTION VISIT:** [MachineLearning Homework 3-Random Data Generator Solved](https://www.ankitcodinghub.com/product/machinelearning-homework-3-random-data-generator-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;92069&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;MachineLearning Homework 3-Random Data Generator Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="section">
<div class="layoutArea">
<div class="column">
1. Random Data Generator

a. Univariate gaussian data generator Input

Expectation value or mean:

Variance:

Output: A data point from HINT

Generating values from normal distribution

You have to handcraft your geneartor based on one of the approaches given in the hyperlink.

You can use uniform distribution function (Numpy)

b. Polynomial basis linear model data generator

is a vector

Input: (basis number),

e.g. ,

Output: (a number) Internal constraint

is uniformly distributed.

2. Sequential Estimator

Sequential estimate the mean and variance

Data is given from the univariate gaussian data generator (1.a).

Input: as in (1.a) Function:

Call (1.a) to get a new data point from

Use sequential estimation to find the current estimates to and

</div>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="section">
<div class="layoutArea">
<div class="column">
Repeat steps above until the estimates converge.

Output: Print the new data point and the current estimiates of and in each iteration.

Notes

You should derive the recursive function of mean and variance based on the sequential esitmation.

Hint: Online algorithm

Sample input &amp; output ( for reference only )

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
1 2 3 4 5 6 7 8 9

<pre>10
11
12
13
14
15
16
17
18
19
20
21
22
23
24
25
</pre>
</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
<pre>Data point source function: N(3.0, 5.0)
</pre>
<pre>Add data point: 3.234685454257290
Mean = 3.408993960833291   Variance = 0.030383455464755956
Add data point: 0.519242879651157
Mean = 2.445743600439247   Variance = 1.875958150575018
Add data point: 1.347113997201991
Mean = 2.171086199629932   Variance = 1.633278676389248
Add data point: 8.979491998496083
Mean = 3.532767359403163   Variance = 8.723325264636875
Add data point: 3.603448448693051
Mean = 3.544547540951477   Variance = 7.270131583917285
Add data point: 4.127197937610908
Mean = 3.627783311902824   Variance = 6.273110519038578
Add data point: 4.992735798186870
Mean = 3.798402372688330   Variance = 5.692747751482052
</pre>
…

<pre>Add data point: 4.233592159021013
Mean = 2.961576104513964   Variance = 5.045715437349161
Add data point: 3.529990930040463
Mean = 2.961883688294010   Variance = 5.043159812425648
Add data point: 1.125210345431449
Mean = 2.960890354955524   Variance = 5.042255747918937
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
3. Baysian Linear regression

Input

The precision (i.e., b) for initial prior

All other required inputs for the polynomial basis linear model geneartor (1.b) Function

Call (1.b) to generate one data point

Update the prior, and calculate the parameters of predictive distribution Repeat steps above until the posterior probability converges.

Output

Print the new data point and the current paramters for posterior and predictive distribution.

</div>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="section">
<div class="layoutArea">
<div class="column">
After probability converged, do the visualization

Ground truth function (from linear model generator) Final predict result

At the time that have seen 10 data points

At the time that have seen 50 data points

Note

Except ground truth, you have to draw those data points which you have seen before

Draw a black line to represent the mean of function at each point Draw two red lines to represent the variance of function at each point

In other words, distance between red line and mean is ONE variance Hint: Online learning

Sample input &amp; output (for reference only) 1. b=1,n=4,a=1,w=[1,2,3,4]

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
1 2 3 4 5 6 7 8 9

<pre>10
11
12
13
14
15
16
17
18
19
20
21
22
23
24
25
26
27
28
29
</pre>
</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
<pre>Add data point (-0.64152, 0.19039):
</pre>
<pre>Postirior mean:
   0.0718294547
  -0.0460797888
   0.0295609502
  -0.0189638408
</pre>
<pre>Posterior variance:
   0.6227289276,   0.2420256620,  -0.1552634839,   0.0996041049
   0.2420256620,   0.8447365161,   0.0996041049,  -0.0638976884
</pre>
<pre>  -0.1552634839,   0.0996041049,   0.9361023116,   0.0409914289
   0.0996041049,  -0.0638976884,   0.0409914289,   0.9737033172
</pre>
<pre>Predictive distribution ~ N(0.00000, 2.65061)
--------------------------------------------------
Add data point (0.07122, 1.63175):
</pre>
<pre>Postirior mean:
   0.6736864869
   0.2388980107
  -0.1054659080
   0.0710615952
</pre>
<pre>Posterior variance:
   0.3765992302,   0.1254838660,  -0.1000441911,   0.0627881634
   0.1254838660,   0.7895542671,   0.1257503020,  -0.0813299447
</pre>
<pre>  -0.1000441911,   0.1257503020,   0.9237138418,   0.0492510997
   0.0627881634,  -0.0813299447,   0.0492510997,   0.9681964094
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
</div>
</div>
<div class="page" title="Page 4">
<div class="section">
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>30
31
32
33
34
35
36
37
38
39
40
41
42
43
44
45
46
47
48
49
50
51
52
53
54
55
56
57
58
59
60
61
62
63
64
65
66
67
68
69
70
71
72
73
74
75
76
77
78
</pre>
</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
<pre>Predictive distribution ~ N(0.06869, 1.66008)
--------------------------------------------------
Add data point (-0.19330, 0.24507):
</pre>
<pre>Postirior mean:
   0.5760972313
   0.2450231522
  -0.0801842453
   0.0504992402
</pre>
<pre>Posterior variance:
   0.2867129751,   0.1311255325,  -0.0767580827,   0.0438488542
   0.1311255325,   0.7892001707,   0.1242887609,  -0.0801412282
</pre>
<pre>  -0.0767580827,   0.1242887609,   0.9176812972,   0.0541575540
   0.0438488542,  -0.0801412282,   0.0541575540,   0.9642058389
</pre>
<pre>Predictive distribution ~ N(0.62305, 1.34848)
--------------------------------------------------
</pre>
…

<pre>--------------------------------------------------
Add data point (-0.76990, -0.34768):
</pre>
<pre>Postirior mean:
   0.9107496675
   1.9265499885
   3.1119297129
   4.1312375189
</pre>
<pre>Posterior variance:
   0.0051883836,  -0.0004416700,  -0.0086000319,   0.0008247001
</pre>
<pre>  -0.0004416700,   0.0401966605,   0.0012708906,  -0.0554822477
  -0.0086000319,   0.0012708906,   0.0265353911,  -0.0031205875
   0.0008247001,  -0.0554822477,  -0.0031205875,   0.0937197255
</pre>
<pre>Predictive distribution ~ N(-0.61566, 1.00921)
--------------------------------------------------
Add data point (0.36500, 2.22705):
</pre>
<pre>Postirior mean:
   0.9107404583
   1.9265225090
   3.1119408740
   4.1312734131
</pre>
<pre>Posterior variance:
   0.0051731092,  -0.0004872471,  -0.0085815201,   0.0008842340
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
</div>
</div>
<div class="page" title="Page 5">
<div class="section">
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>79
80
81
82
83
84
</pre>
</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
<pre>  -0.0004872471,   0.0400606628,   0.0013261280,  -0.0553046044
  -0.0085815201,   0.0013261280,   0.0265129556,  -0.0031927398
   0.0008842340,  -0.0553046044,  -0.0031927398,   0.0934876838
</pre>
<pre>Predictive distribution ~ N(2.22942, 1.00682)
--------------------------------------------------
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
2. b=100,n=4,a=1,w=[1,2,3,4]

1 (Consoleoutputomitted)

</div>
</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="section">
<div class="layoutArea">
<div class="column">
3. b=1,n=3,a=3,w=[1,2,3]

1 (Consoleoutputomitted)

</div>
</div>
</div>
</div>
<div class="page" title="Page 7"></div>
