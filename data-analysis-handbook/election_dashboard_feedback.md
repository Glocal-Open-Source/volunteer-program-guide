# 2025 Federal Election Tableau Dashboard

You can view the dashboard

```{div} dashboard
<div class='tableauPlaceholder' id='viz1754410934791' style='position: relative'><noscript><a href='#'><img alt='Canada Election Turnout ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;20&#47;2025-Federal-Election&#47;ElectionTurnout&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='2025-Federal-Election&#47;ElectionTurnout' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;20&#47;2025-Federal-Election&#47;ElectionTurnout&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1754410934791');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} else { vizElement.style.width='100%';vizElement.style.height='1727px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>
```

[here](https://public.tableau.com/app/profile/trizia.tating/viz/2025-Federal-Election/ElectionTurnout).

Below is an example of feedback given to a public dashboard created by Patricia, a GLOCAL data volunteer. Use this as a checklist when reviewing your own visualizations or dashboards for clarity and accuracy.

## Feedback

-   **Pie Chart Misrepresentation:** The bottom-right pie chart showing the gender breakdown of voters is incorrect. The chart displays all genders as less than 30% each, and both men and women make up only about a third of the pie, rather than the expected majority. In reality, we would expect 90% or more of votes to come from men or women combined.

-   **Default Map View:** The map defaults to showing votes from all genders between 18–24 years old in the 2004 election, even though the dropdown menus are set to "All." Could this be updated so the default reflects all genders and all ages across all federal elections from 2004 onward?
-   **Missing Legend:** Provinces are coloured differently from territories, but there’s no legend indicating this distinction. Could a legend be added to the bottom or top left corner of the map box?

-   **Gradient Usage:** What is the purpose of the gradient used across the provinces and territories in the "Provincial Distribution" section? A gradient typically implies a progression or change, but province/territory is a nominal (not ordinal) variable. While the design looks fine, perhaps the gradient could instead be based on turnout rates rather than province or territory names. This would make the visualization more informative.

-   **Turnout Calculation:** Dividing “Votes” by “Eligible Electors” does not yield the same value as “Voter Turnout.” Also, what year(s) do the “Votes,” “Eligible Electors,” and “Voter Turnout” numbers represent?

-   **Unclear or Inaccurate Text:** The statement “In 2004 to 2021, the average voter turnout for the selected age group was All in All was 20.55% to 98.08%” needs clarification and correction. These percentages seem unlikely—it’s doubtful that any age group in Canada would have turnout rates as low as 20.55% or as high as 98.08%. Ideally, the sentence should read something like: “From 2004 to 2021, the average voter turnout for people aged [age group] was X%.”

