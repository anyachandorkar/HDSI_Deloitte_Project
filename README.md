# Testing page

<iframe src='Visualizations_Ethan/top_5.html' width=525 height=350 frameBorder=1></iframe>

<br>

<iframe src='Visualizations_Ethan/bottom_5.html' width=525 height=350 frameBorder=1></iframe>

```
This is my description for my plot.

<iframe src = 'https://10az.online.tableau.com/t/anyachandorkarportfolio/views/Deloitte_Geo_Analysis/Regional?:showAppBanner=false&:display_count=n&:showVizHome=n&:origin=viz_share_link' width=525 height=350 frameBorder=1></iframe>
```
<script src="https://10az.online.tableau.com/t/anyachandorkarportfolio/javascripts/api/tableau-2.min.js"></script>
<div id="vizContainer"></div>
function initViz() {
    var containerDiv = document.getElementById("vizContainer"),
    url = "https://10az.online.tableau.com/t/anyachandorkarportfolio/views/Deloitte_Geo_Analysis/Regional?:showAppBanner=false&:display_count=n&:showVizHome=n&:origin=viz_share_link";
    var viz = new tableau.Viz(containerDiv, url);
}
initViz();
