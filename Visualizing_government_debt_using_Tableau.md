# Visualzing General Government Debt

General government debt is the gross debt of the general government as a percentage of GDP. In this excercise, we are visualizing general government debt across years and countries.  
Data used throughout this assignment is taken from the [OECD](https://www.oecd.org/en/data/indicators/general-government-debt.html?oecdcontrol-3122613a85-var3=2020).

## Illustration 1: General Government Debt for 2022
The below image has been directly picked from the OECD website. In 2022, we see that Japan had the highest general debt at 246%. The United States is above the average country debt (bar colored in blue).

<img src="Visualizing government debt.png" width="500"/> 

**Things I like about the chart:**
1. It is ordered, and hence it is easy to compare countries.
2. Since it also tells us information about an average debt value, we have a reference point to compare countries with besides the 100% mark

**Things I dislike about the chart:**
1. There are two blue bars, and I understand the meaning of only one when reading the pop-up text that appears upon hovering over bars.
2. The x-label does not display the names of all countries depicted in the chart.

## Illustration 2: General Government Debt of Countries across Years
The below image was created as part of class exercise. It is a highlight table and hence we are able to see the trends in general debt across years for various countries. What is interesting is that Tableau generated a line chart by default for this level of detail. The line chart was a bunch of messy lines and it was difficult to focus on specific countries. The highlight table immediately makes it apparent which countries have a higher and increasing debt.

<div class='tableauPlaceholder' id='viz1725999955876' style='position: relative'><noscript><a href='#'><img alt='General Debt % of Countries across YearsData Source: OECD ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;As&#47;Asg2_OECD_GeneralDebt&#47;GeneralDebtofCountriesacrossYears&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Asg2_OECD_GeneralDebt&#47;GeneralDebtofCountriesacrossYears' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;As&#47;Asg2_OECD_GeneralDebt&#47;GeneralDebtofCountriesacrossYears&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>

<script type='text/javascript'>
  var divElement = document.getElementById('viz1725999955876');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>
  
**Things I like about the chart:**
1. Very easy to read and focus on countries with high/increasing debt

**Things I dislike about the chart:**
1. The countries wiith missing information pop out a little more than I would like them to due to the white space showing lack of information.

## Illustration 3: Change in Government Debt around the Great Recession Period
The previous chart makes it intuitive to see which countries have higher and increasing debt. I now wanted to see rate of increase/decrease in debt across years and compare countries based on it. When visualizing this, I noticed that the change in debt as a percentage significantly peaked around the years of 2007 - 2009. I realised this period corresponds to the Great Recession and that became the focus of the chart. I also wanted to limit the number of countries to ones that were most greatly affected. Hence I chose the top 5 countries with highest jumps in debt in the year 2008 when the affect of recession first popped up. I also included the US since the Great Recession happened primarily due to the US housing bubble burst. It was interesting to see that even though the global financial crisis originated in the US, there were other countries more severely affected by it. Since I only had 6 countries to represent now, I chose a line chart for my visualization.

<div class='tableauPlaceholder' id='viz1726025248959' style='position: relative'><noscript><a href='#'><img alt='% Change in general debts spiked during the Great RecessionThe YoY change in general debt stabilized to under 10% around 2013, 6 years after the Great Recession ended. The US housing bubble burst triggered the Great Recession and caused a global financi ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;As&#47;Asg2_OECD_GeneralDebt&#47;Sheet2&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Asg2_OECD_GeneralDebt&#47;Sheet2' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;As&#47;Asg2_OECD_GeneralDebt&#47;Sheet2&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-GB' /><param name='filter' value='publish=yes' /></object></div>

<script type='text/javascript'>
  var divElement = document.getElementById('viz1726025248959');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>
  
**Things I like about the chart:**
1. The title gives is indicative of takeaway

**Things I dislike about the chart:**
1. Even by limiting the line colours to only 2, it is a squiggly mess and makes it hard to label the individual countries.
