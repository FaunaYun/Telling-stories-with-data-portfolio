| [home page](https://faunayun.github.io/Telling-stories-with-data-portfolio/) |[visualizing-government-debt](https://faunayun.github.io/Telling-stories-with-data-portfolio/visualizing-government-debt) | [critique-by-design](https://faunayun.github.io/Telling-stories-with-data-portfolio/critique-by-design)|[final project I](https://faunayun.github.io/Telling-stories-with-data-portfolio/final-project-part-one) | [final project II](https://faunayun.github.io/Telling-stories-with-data-portfolio/final-project-part-two) | [final project III](final-project-part-three) |

# Wireframes / storyboards
> Using your sketches developed last week, further develop your story outline and relevant components visually through the use of wireframing / storyboards. Using your outline as a guide, include high-fidelity, individual draft data visualizations of the critical elements of your story you want to share with your reader. Note: you can build these elements out directly in Shorthand this week if you wish.  Reminder: this template is intended to help, but it doesn't substitute for reading through the full homework assignment!  The assignment page on Canvas includes many important details for completing Part II of the final project. 

<div class='tableauPlaceholder' id='viz1732753144303' style='position: relative'><noscript><a href='#'><img alt='Social mobility factors and housing&#47;neighborhood conditions ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;st&#47;story_part2-houseoverview&#47;Story1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='story_part2-houseoverview&#47;Story1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;st&#47;story_part2-houseoverview&#47;Story1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>
  var divElement = document.getElementById('viz1732753144303');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='1016px';vizElement.style.height='991px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

Drawing from the American Housing Survey (AHS), the nation's most comprehensive housing dataset since 1973, this analysis examines how housing conditions intersect with social mobility in California's major urban centers: Los Angeles-Long Beach-Anaheim and San Francisco-Oakland-Hayward, which can represent the overview of the state. Through correlation analyses of housing quality, neighborhood characteristics, and demographic factors, we can uncover patterns that illuminate the complex relationship between housing conditions and social advancement opportunities across different population groups. Our visualization of these relationships through correlation matrices reveals both challenges and opportunities in creating more equitable housing access in California's metropolitan areas.

1. The first two dashboards are the overview of the housing conditions and neighborhood qualities to give audience a general understanding of the two regions' housing conditions. 

2. The third dashboard is the correlation matrix between housing condtion metrics and demographic factors of house occupants.

3. 4th - 6th dashboards are specific visualization of the correlation between demographic factors ( education, citizenship, household income) and house value, which is the strongest and most direct indicator of house conditions.

4. 7th dashboard is the correlation matrix between neighborhood quality metrics and demographic factors of house occupants. 

5. 8th - 9th dashboard are the specific visualization of the relationship between two representative demographic metrics (citizenship and education) and overall opinion of the neighborhoods.


Key findings:
1. Education and income appear to be the strongest predictors of housing quality and size.
   Education shows moderate positive correlations with several housing characteristics: Household Income (0.319); Unit Size (0.319); Rooms (0.291). This suggests that higher education levels are associated with better housing conditions overall.
   Household Income demonstrates moderate positive correlations with: Value (0.322); Rooms (0.288); Unit Size (0.265). This indicates that higher income households tend to live in larger, more valuable properties.
#### From this finding, we can tell that Education's role is somewhat as a "triple multiplier": improves income prospects, housing access, and neighborhood quality; In terms of intergenerational effects, better housing conditions positively impact children's educational outcomes as those houses and communities probably have better schools. ####
3. Citizenship status has surprisingly little influence on housing conditions, from which we can assume that other factors (education, income) may be more crucial for housing access. The surprisingly weak correlations between citizenship status and housing conditions may mask a complex web of informal adaptations and community-based solutions, such as informal housing arrangements, from shared living spaces to unofficial rental agreements, alongside extended family living patterns that distribute costs. 
4. Good Schools and Overall Opinion (0.233): Areas with good schools are somewhat positively correlated with better overall neighborhood opinions.
5. Neighborhoods coded as having serious crime (1) tend to be rated lower in overall opinion. Crime and Overall Opinion (-0.261) is one of the strongest negative correlations in the matrix. This suggests that the presence of serious crime has a meaningful negative impact on how residents view their neighborhood. Overall, crime has the strongest negative impact on neighborhood perception.
6. However, most correlations(including the demographic factors of house occupants and the neighborhood condition matrics) are relatively weak (below 0.4), indicating that neighborhood characteristics are fairly independent of each other and complex in their relationships.

# User research 

## Target audience

Policy Makers
Need: Understanding housing inequality patterns Goal: Develop effective housing policies Challenge: Balancing multiple stakeholder interests

Urban Researchers
Need: Data-driven insights about housing and mobility Goal: Identify patterns and trends Challenge: Accessing comprehensive data analysis

Housing stands as a crucial indicator and driver of social mobility in America's urban policy landscapes, serving as both a mirror of existing social inequalities. For policy makers, understanding the intricate relationships between housing conditions, demographic factors, and neighborhood quality is essential for developing effective policies that promote equitable access to quality housing. For researchers, these patterns offer valuable insights into how housing intersects with education, income, and citizenship status to shape mobility outcomes. By examining how housing conditions correlate with various social and economic factors, this analysis aims to inform both practical policy solutions and theoretical frameworks for understanding social mobility. The findings are particularly relevant as cities grapple with persistent challenges in housing affordability, quality, and access, making this research an integral part of the broader conversation about creating more equitable environments.


## Interview script
> List the goals from your research, and the questions you intend to ask. 

Text here!

| Goal | Questions to Ask |
|------|------------------|
| Audience interest |What do you care about the most in factors that potentially affect housing quality? |
| Feedback on the storyline    |What do you think of the current structure of the story? |
| Feedback on visualization     |Any suggestions on the current visualizaitions? |


Text here!

## Interview findings
> Detail the findings from your interviews.  Do not include PII.  Capture specific insights where possible.

Text here!

| Questions               | Interview 1  | Interview 2 | Interview 3 |
|-------------------------|--------------------------------|-------------|-------------|
| What do you care about the most in factors that potentially affect housing quality? | Income level, as it is a very direct indicator of social class and is well quantified. | Citizenship, because California is a state with a lot of immigrants, so whether or not they get legal status may be related to their general social status.| Educational level, a homeowner's level of education may influence its preference when choosing a neighborhood, for example, someone with a high level of education may choose a neighborhood with good public schools. |
|What do you think of the current structure of the story? | Probably not as relevant to social mobility as housing is just one of the small factors that affect this. | The story line may not be as full as it could be, as it mainly only explores the possible correlation of demographic factors with housing quality.| The correlation is not that significant, so it's hard to draw very direct conclusions. |
|Any suggestions on the current visualizaitions? |  Could make the fonts and colors a bit more aesthetically pleasing and uniform| The type of visualization is rather basic and could be a bit more fancy.| A visualisation of the relationship between household income and neighbourhood opinion could be added to the analysis of neighbourhood quality to stay consistent with first part (housing conditions analysis)|


# Identified changes for Part III
> Document the changes you plan on implementing next week to address any issues identified.  

Text here!

| Research synthesis                       | Anticipated changes for Part III                                                |
|------------------------------------------|---------------------------------------------------------------------------------|
| Findings or observations from interviews | Continuing to develop and elaborate on my storyline. Doing more research on the topic. |
|                                          | Adding concluding visualization.  |
|                                          | Adding more explanatory text.|
                                                     

> ...include any final thoughts you have here. 

Text here!


