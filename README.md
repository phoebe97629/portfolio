# portfolio
Here is Phoebe's Portfolio

# About Me

Hi eveyone! My name is Phoebe, I'm the second year master student at CMU major in Healthcare Analytics and Information Technology. I love baking, reading and coding! 

# What I hope to Learn

I want to learn more about the data visulization. I want to be a story teller not just programmer. I also want to learn a little bit about design for PPT and Web Page. 

# Portfolio

Here's where all my cool work will go. You should probably hire me. 
1. Cell's classification. 
2. Face classification and Face verification. 
3. Data Visualization. 
4. ... to be continued...


[Assignment 2 Visulizing Government Debt](/assignment2.md)
[Assignment 3&4 Critique Redesign](/assignment2.md)


# Visualizing Government Debt
### How does Asian government deal with debt in 2020.
<iframe src="https://data.oecd.org/chart/6Bmi" width="860" height="645" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/6Bmi" target="_blank">OECD Chart: General government debt, Total, % of GDP, 2020</a></iframe>
Using Flourish Visualizing Tool
#### Grid Style:
<div class="flourish-embed flourish-chart" data-src="visualisation/8567284"><script src="https://public.flourish.studio/resources/embed.js"></script></div>
Animation style:
<div class="flourish-embed flourish-scatter" data-src="visualisation/8567575"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

#### For the grid style chart: 
Since it's for government debt, I used red as the base color. I used a grid line chart to show how the debt varies from 1995 to 2019 from different countries. I also added a title to the chart, which states what is y-axis represents (debt in % of GDP). I also added year labels on the graph. Instead of adding a y-axis value, I decided to show the year on each grid chart. Because I believe people will focus more on which year has highest the debt, rather than what's the highest value of debt. 

#### For the animation style: 
This chart is for the audience who want to see how the debt varied these years. The circle size represents the %of the debt, and each circle represents one country. Animation is a good way to show the trend by year. 

# In class exercise 2/2/2022

<div class='tableauPlaceholder' id='viz1643830900910' style='position: relative'><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Book1_16438308784440&#47;TrustInnewsorganizations_Circle_view' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1643830900910');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>



# HW 3&4 Re-Designed the MLS 2013 Salary Reports. 

### Step 1: The original design of the Salary Reprots: 
<div class='tableauPlaceholder' id='viz1644103262625' style='position: relative'><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='MLSSalaries&#47;MLSPUDashboard' /><param name='tabs' value='yes' /><param name='toolbar' value='yes' /><param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1644103262625');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='1260px';vizElement.style.height='910px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

This graph is using MLS 2013 Salary reports. The reasons why I choose this example are 1. This graph has many typical errors occurring in the data visualization task. 2. The data source is easy to access. Even though the salary report is PDF format, it can be easily covert to EXCEl.

Data source can be found here: https://mlsplayers.org/resources/salary-guide
<font color="red"> Insight: </font> Its really hard to find the graph with reliable data source. Most of the graph didn't mention where they get the data source or the data they provided is not valid. 

### Step two: critique and Re-Design Process: 

After analyzing the graph by using Few's method, I think this graph has several problems. The graph isn't intuitive and communicates well to the audience. 

Below is my first attemp for the re-desin:
1. Change salary as y-aixs and club as x-aixs. 
2. Sepearte graoh into base salary and compensation. 
3. Change the title name as MLS clubs' base salary vs compensation 2013. 
4. Reduce the color using. 
5. Provide Data source on the graph. 

<font color="red"> Insight: </font> It is really important to identify the target audience when designing the graph. Becuase you should concider what kind of information they want to know and what information they already know and unnecessary to them.  

### Step three: wireframe a solution
Here is my wireframe. The vary simple why to reduce confusion and reduce and the information and add more graphs. So I seperated the grpah into two comparable bar chart with salary and clubs name. 

![IMG_0143](https://user-images.githubusercontent.com/74167244/152657024-c6997f49-f8db-45a8-8a48-fec854a9dae2.jpg)
<font color="red"> Insight: </font> I guess using the team logo will be more intuitive to the audiance, especially the target audiance is for game fans. 

### Step four: Test the solution: My boyfriend and my friend Allen 

- Can you tell me what you think this is?. 
   bf: "Its Average Salary for each clubs? "
   Allen: "Salary for each clubs. "

- Can you describe to me what this is telling you? 
  bf: "NY salary is really high lol. "
  Allen:"Its hard to identify which club has highest salary since its not sorted. "

- Is there anything you find surprising or confusing?
  bf: "Is is average salary or the over salary?"
  Allen:"It looks fine. I'm not a MLS fans so I am not really know the MLS clubs' name. "

- Who do you think is the intended audience for this? 
  bf: "The MLS fans. "
  Allen:"People watch MLS games. "

- Is there anything you would change or do differently? 
 bf: "Overvall its a good graph i think. At least its readable. I guess you can keep the postion variable. Its kind of intereting to investigate which postion has higher salary.  "
 Allen: "I guess just tell the audience what's the meaning of the salary."
 
<font color="red"> Insight: </font> According the user feed back, the new design meet the usefulness, perceptibility, and intuitiveness requirements. However, by eliminating the position cause a little bit confuse. The audiance didn't mention the aesthetics and engagement parts, but I believe I should do better on that. 

### Step five: The final visulizaiton:

<font color="red"> The final: </font> I divided each bar by the position and explain the meaning of the salary. However, I didn't find the way to add team logo to the x-axis.(Maybe photoshop works) I also felt a bit confused about the meaning of the position. But I believe the target audience (MLS game fans) will know more than me. I also choose to use the color-blind friendly color theme. Below is my final result. 

<div class='tableauPlaceholder' id='viz1644105227490' style='position: relative'><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='2013MSLClubsBaseSalaryVS_Compensation&#47;2013MSLClubsBaseSalaryVS_TotalCompensation' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1644105227490');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>
