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

After analyzing the graph by using Few's methods, I think this graph has several problems. The graph isn't intuitive and communicates well to the audience. 

When the audience first took look at it, they will immediately be overwhelmed by the color (rainbow effect) and the information. The first thing that stood out is the graph includes too much information and even has a sub-graph with a similar design. The graph did well on the completeness, we can see for each bar (represents location), it contains multiple clubs and position information. However, the audience should take a great effort to figure out what each little block represents. Overall, this graph is a bad visualizing example, it’s not aesthetics, it didn’t choose a good color and caused rainbow effects; it’s not intuitive and engaging, it tried to contain too much information at once and the graph itself is complex; it’s not perceptible and useful, the title didn’t give clear information (salary varied by which factor); it’s not truthful, the accuracy of data is doubtful. When you look at the text on the graph, it said “it has been noted by MLS clubs that this data can be a bit inaccurate”. I will do it differently for sure. The major part I will do for this visualization is to reduce the unnecessary information and focus on what kind of information the audience wants to know.


Below is my first attemp for the re-desin:
1. Change salary as y-aixs and club as x-aixs. 
2. Sepearte graoh into base salary and compensation. 
3. Change the title name as MLS clubs' base salary vs compensation 2013. 
4. Reduce the color using. 
5. Provide Data source on the graph. 

<font color="red"> Insight: </font> It is really important to identify the target audience when designing the graph. Because designer should consider what kind of information the audience want to know and what information they already know and unnecessary to them.  

### Step three: wireframe a solution
Here is my wireframe. The most simple way to reduce confusion is reducing the information each group includes, and adding more graphs. So I separated the graph into two comparable bar charts with salary and total compensation as y-axis and clubs name as the x-axis. I used dark green for the graph to represent money. 

![IMG_0143](https://user-images.githubusercontent.com/74167244/152657024-c6997f49-f8db-45a8-8a48-fec854a9dae2.jpg)
<font color="red"> Insight: </font> I guess using the team logo will be more intuitive to the audiance, especially the target audiance is for game fans. 

### Step four: Test the solution: My boyfriend and my friend Allen. 

- Can you tell me what you think this is?. 
   bf: "Its Average Salary for each clubs? "
   Allen: "Salary for each clubs. "

- Can you describe to me what this is telling you? 
  bf: "NY salary is really high lol. "
  Allen:"Its hard to identify which club has highest salary since its not sorted. "

- Is there anything you find surprising or confusing?
  bf: "Is it average salary? I'm confused about what's the meaning of the salary."
  Allen:"It looks fine. I'm not a MLS fans so I am not really know the MLS clubs' name. "

- Who do you think is the intended audience for this? 
  bf: "The MLS fans. "
  Allen:"People watch MLS games. "

- Is there anything you would change or do differently? 
 bf: "Overvall its a good graph i think. At least its readable. I guess you can keep the postion variable. Its kind of intereting to investigate which postion has higher salary.  "
 Allen: "I guess just tell the audience what's the meaning of the salary."
 
<font color="red"> Insight: </font> According to the user feedback, the new design meets the usefulness, perceptibility, and intuitiveness requirements. However, eliminating the position cause a little bit of confusion. The audience didn't mention the aesthetics and engagement parts, but I believe I should do better on that. I also found that the person who is not interested in the MLS games didn't take the interview seriously. The suggestions they provided are very general or limited. But for the people who love watching games, they keep inquiring different questions.


### Step five: The final visulizaiton:

<font color="red"> The final: </font> I divided each bar by the position and explain the meaning of the salary. However, I didn't find a way to add the team logo to the x-axis. (Maybe photoshop works) I also felt a bit confused about the meaning of the position. But I believe the target audience (MLS game fans) will know more than me. I also choose to use the color-blind-friendly color theme. Below is my final result. 

<div class='tableauPlaceholder' id='viz1644277396457' style='position: relative'><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='2013MSLClubsBaseSalaryVS_Compensation&#47;2013MLSClubsBaseSalaryVS_TotalCompensation' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1644277396457');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

In summary, by doing each step, the graph improved from different perspectives. I re-interviewed my friends, and they think the new design makes a lot more sense. 
From doing this homework, I realized that today's data visualizations have so many things to improve. The first thing is to provide reliable data sources. Most of the data visualization just provided the graph without a data source or link of the source. Which makes the data visualization less reliable. Secondly, it is really hard to find a balance between each requirement that Few's said. For example, if the graph tried to include most of the information (completeness), is usually very complex and hard to read. The graph looks aesthetic always lacks information and usefulness. Besides, when I re-designed the graph and interviewed other people, I realized I cannot satisfy everyone. And that's the reason why the data visualization design needs to figure out who is the target audience. Focusing on the target audience will provide a clear direction to improve the graph.   

### Other Thoughts from doing this homework: 
1. Tableau sometimes is difficult to use. As a designer, it's a lack of flexibility. 
2. I tried to move the x-axis title to the bottom. I google the solution, and many people have such issues but have no solution. 
3. The color themes are very limited. 
4. The label position. Since each bar is divided by the position, the label cannot be set at the top of each bar. 
