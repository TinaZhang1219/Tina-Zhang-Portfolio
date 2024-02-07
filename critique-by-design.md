| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [visualizing debt](visualizing-government-debt.md) | [critique by design](critique-by-design.md) | [final project I](final-project-part-one.md) | [final project II](final-project-part-two.md) | [final project III](final-project-part-three.md) |


# Original Data Visualization
Please click on the link.
https://www.forbes.com/lists/athletes/?sh=734b983d5b7e

## My Reviews on the Original Visualization
The table ranking the name, sport played, the total earnings and the off-the-field and on-the-field earnings of the top 50 highest-paid athletes in 2023. The table contains too much information and it doesn't use colors. Too much information makes me lose track of data when I scroll down. Besides, this table is not effective for the audience of Forbes (investors or business owners) to decide which athletes to sponsor or invest in because some athletes' total earnings mostly come from on-the-field earnings like prizes, instead of off-the-field earnings, which represents the underlying business value of the athletes. Simply ranking the total earnings does not deliver any insightful idea relevant to the target audience. 

# Wireframe of the Data Visualization
<img width="1470" alt="Screen Shot 2024-02-06 at 18 26 46" src="https://github.com/TinaZhang1219/Tina-Zhang-Portfolio/assets/157413922/28b041c4-badc-42b4-94be-70d4b34928c5">

## Summary of Wireframe
Since from the crituqe, I think simply ranking the total earnings does not deliver any insightful idea relevant to the target audience of Forbes, I remake the visualization as a bar chart and group by the off-the-field earnings with type of Sports. The rows are types of sport, and the columns are the average off-the-field eranings of athelets in each sport. I also sort the rows in descending order using the field of the average off-the-field eranings.

## User Feedback
- Student, hate sport: the user does not know what 'off-the-field earnings' mean and cannot understand the graph
  
- Student, actively doing sport: the user can grasp the insight immediately by looking at the headline, the axis title and the bars, but the user think it will be better if having data lable on the end of each bar

# Revised Data Visualization

## Written Summary
I remake my graph based on the user feedback. First, I include on-the-field earnings into the graph and add a caption explaning what is off-the-field and on-the-field earnings to take those who does not follow sports into consideration. The reason why I include on-the-field earnings is to make a direct comparison between the off-the-field and on-the-field earnings to provide insights on which sports' business value is overestimate or underestimateth, because from the critque part, the audience of Forbes are mostly business owners, if they consider a sport generates more business value than it actually is, the stereotypes will affect their judgement on making investment decision. Therefore, including the compariiosn can better help the audience to break the stereotypes, this cannot be done by only showoing the off-the-field earnings. I also use green on off-the-field earnings as green usually been perceived as profit/gainings, and use grey on on-the-field earnings to less-emphasize on it and put more attention on the off-the-field part. I also include data label but make it only shown when users click on the bar, because some sections of bar are really small and if the data lable is all shown on the bars, some label overlaps.

<div class='tableauPlaceholder' id='viz1707178052856' style='position: relative'><noscript><a href='#'><img alt='Sports with the Highest Business ValueRank of Sports Using the Average Off-the-Field and On-the-Field Earnings from the Top 50 Highest-Paid Atheletes in 2023 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Sp&#47;SportswiththeHighestBusinessValue&#47;Sheet12&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='SportswiththeHighestBusinessValue&#47;Sheet12' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Sp&#47;SportswiththeHighestBusinessValue&#47;Sheet12&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1707178052856');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

