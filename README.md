# Plot.ly-Challenge



<h1 id="plot-ly-homework-belly-button-biodiversity">Plot.ly Homework - Belly Button Biodiversity</h1>


<p>In this assignment, you will build an interactive dashboard to explore the <a href="http://robdunnlab.com/projects/belly-button-biodiversity/" class="highlight">Belly Button Biodiversity dataset</a>, which catalogs the microbes that colonize human navels.</p>

<p>The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.</p>

<h2 id="step-1-plotly">Step 1: Plotly</h2>

<ol>
<li><p>Use the D3 library to read in <code>samples.json</code><span class="copy-to-clipboard" title="Copy to clipboard"></span>.</p></li>

<li><p>Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.</p></li>
</ol>

<ul>
<li><p>Use <code>sample_values</code><span class="copy-to-clipboard" title="Copy to clipboard"></span> as the values for the bar chart.</p></li>

<li><p>Use <code>otu_ids</code><span class="copy-to-clipboard" title="Copy to clipboard"></span> as the labels for the bar chart.</p></li>

<li><p>Use <code>otu_labels</code><span class="copy-to-clipboard" title="Copy to clipboard"></span> as the hovertext for the chart.</p></li>
</ul>



<ol>
<li>Create a bubble chart that displays each sample.</li>
</ol>

<ul>
<li><p>Use <code>otu_ids</code><span class="copy-to-clipboard" title="Copy to clipboard"></span> for the x values.</p></li>

<li><p>Use <code>sample_values</code><span class="copy-to-clipboard" title="Copy to clipboard"></span> for the y values.</p></li>

<li><p>Use <code>sample_values</code><span class="copy-to-clipboard" title="Copy to clipboard"></span> for the marker size.</p></li>

<li><p>Use <code>otu_ids</code><span class="copy-to-clipboard" title="Copy to clipboard"></span> for the marker colors.</p></li>

<li><p>Use <code>otu_labels</code><span class="copy-to-clipboard" title="Copy to clipboard"></span> for the text values.</p></li>
</ul>

<ol>
<li><p>Display the sample metadata, i.e., an individual’s demographic information.</p></li>

<li><p>Display each key-value pair from the metadata JSON object somewhere on the page.</p></li>
</ol>



<ol>
<li>Update all of the plots any time that a new sample is selected.</li>
</ol>

<p>Additionally, you are welcome to create any layout that you would like for your dashboard. An example dashboard is shown below:</p>



<h2 id="advanced-challenge-assignment-optional">Advanced Challenge Assignment (Optional)</h2>

<p>The following task is advanced and therefore optional.</p>

<ul>
<li><p>Adapt the Gauge Chart from <a href="https://plot.ly/javascript/gauge-charts/" class="highlight">https://plot.ly/javascript/gauge-charts/</a> to plot the weekly washing frequency of the individual.</p></li>

<li><p>You will need to modify the example gauge code to account for values ranging from 0 through 9.</p></li>

<li><p>Update the chart whenever a new sample is selected.</p></li>
</ul>



<h2 id="deployment">Deployment</h2>

![Image1](https://raw.githubusercontent.com/Robert-W2019/Plot.ly-Challenge/main/Deployment%20images%20for%20Readme/Deployment%20image%201.JPG)


![Image2](https://raw.githubusercontent.com/Robert-W2019/Plot.ly-Challenge/main/Deployment%20images%20for%20Readme/Deployment%20image%202.JPG)




<h3 id="about-the-data">About the Data</h3>

<p>Hulcr, J. et al.(2012) <em>A Jungle in There: Bacteria in Belly Buttons are Highly Diverse, but Predictable</em>. Retrieved from: <a href="http://robdunnlab.com/projects/belly-button-biodiversity/results-and-data/" class="highlight">http://robdunnlab.com/projects/belly-button-biodiversity/results-and-data/</a></p>


<footer class="footline">
	
</footer>

        