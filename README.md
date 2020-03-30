<h1>Threshold for the colour of heatmap in MATLAB</h1>

How to use this function? <br>
The function name is generatecolormapthreshold, first argument is the threshold and second argument is the colour<br>
<pre><code>color= generatecolormapthreshold([1 10 25 30],[0 0.5 1; 0 1 0;1 0 0]);
h = heatmap(fluS,'DayName','noofweek','ColorVariable','Max_Data','Colormap',color,'ColorLimits',[1 30]);
h.FontSize=10;
h.Title='Heatmap';</code></pre>
 
means that range 1-25 is the colour for [0 1 1], 25-30 is the colour [1 0 0].<br>

![GitHub Logo](/images/logo.png)



