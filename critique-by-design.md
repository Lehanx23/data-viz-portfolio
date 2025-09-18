| [home page](https://lehanx23.github.io/data-viz-portfolio/) | [data viz examples](https://lehanx23.github.io/data-viz-portfolio/dataviz-examples) | [critique by design](https://lehanx23.github.io/data-viz-portfolio/critique-by-design) | [final project I](https://lehanx23.github.io/data-viz-portfolio/final-project-part-one) | [final project II](https://lehanx23.github.io/data-viz-portfolio/final-project-part-two) | [final project III](https://lehanx23.github.io/data-viz-portfolio/final-project-part-three) |

# Critique and Redesign

_For each step below, you should document your progress as you move forward.  In terms of tone, think of the writeup as though you're keeping journal of your step-by-step process.   You should include a any insights you gained from the critique method, and what it led you to think about when considering the redesign.  You should talk about how you moved next to the sketches, and any insights you gleaned from your user feedback.  Document what you changed based on the user feedback in your redesign.  Finally, talk about what your redesigned data visualization shows, why you selected the data visualization you did, and what you attempted to show or do differently._

_You can include screenshots, sketches or other artifacts with your narrative to help tell the story of how you moved through the process.  Again, make sure to avoid including any personally identifying information about your interviewees (don't list full names, etc.).  While this template serves as a guide, make sure to reference the assignment writeup on Canvas for the official guidance.  This template does not include all guidance mentioned on the assignment page._

## Step one: the visualization

The visualization I chose was "Total yearly cost to study in select European countries," from an article called "The cheapest countries to study in Europe." 

Here is the website:

https://www.finder.com/uk/current-accounts/student-bank-accounts/cheapest-countries-to-study-europe.

Here is the visualization (code provided by the website):

<iframe title="Total yearly cost to study in select European countries (£)" 
  aria-label="Map" 
  id="datawrapper-chart-UamQC" 
  src="https://datawrapper.dwcdn.net/UamQC/3/" 
  scrolling="no" 
  frameborder="0" 
  style="width: 0; 
  min-width: 100% !important; 
  border: none;" 
  height="736" 
  data-external="1">
  
  </iframe><script 
             type="text/javascript">!function()
             {"use strict";window.addEventListener("message",
                                                   (function(a){if(void 0!==a.data["datawrapper-height"])
                                                   {var e=document.querySelectorAll("iframe");
                                                    for(var t in a.data["datawrapper-height"])
                                                      for(var r=0;r<e.length;r++)if(e[r].contentWindow===a.source)
                                                      {var i=a.data["datawrapper-height"][t]+"px";e[r].style.height=i}}}))}();
  </script>

I selected this data visualization because I felt that studying in European countries is a topic that would be of particular interest to people in the UK. All the data collected reflects average yearly costs for UK students, and the unit of measurement is pounds. These destinations are relatively close to their home while still offering the opportunity to study abroad and experience different cultures, which makes them very appealing.

I wanted to see how a data visualization on this topic could help audiences learn more about the cheapest countries to study in Europe, and to consider whether, if I were to design the visualization myself, I could tell a clearer story.

## Step two: the critique

#Observations on the Original Data Visualization

The data visualization is a filled map of Europe showing the average yearly tuition costs, with a color gradient to represent cost differences. I think the map is useful because it provides geographical context, and the color gradient shows the different total yearly costs each country has. The visualization is also truthful, engaging due to its interactive hover feature, and aesthetically pleasing with its clear blue color scheme.

However, there are some areas for improvement. The intuitiveness could be better, as audiences had to refer to the legend to understand whether the shallow blue or the dark blue is presenting the countries with low yearly total costs. The chart also lacks completeness, as it only shows the total cost without breaking it down into tuition versus living expenses. The authors had to add a separate table and additional textual explanation to introduce the average yearly tuition fees and living costs of each country to the audience. Finally, there is a perceptibility issue: it's hard to distinguish between countries with similar shades of blue, and the lack of country names makes it difficult to quickly locate specific nations without hovering, and makes it easy for the audience to overlook a country they are not familiar but may be interested in.

## Step three: Sketch a solution

This is my solution by Monday, September 15:

<div class='tableauPlaceholder' id='viz1758170148681' style='position: relative'><noscript><a href='#'><img alt='The Cheapest Countries to Study in Europe ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Th&#47;TheCheapestCountriestoStudyinEurope&#47;Sheet22&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='TheCheapestCountriestoStudyinEurope&#47;Sheet22' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Th&#47;TheCheapestCountriestoStudyinEurope&#47;Sheet22&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1758170148681');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

## Step four: Test the solution

Questions to ask: 

- Can you tell me what you think this is?

- Is there anything you find surprising or confusing?

- Who do you think is the intended audience for this?

- Is there anything you would change or do differently?

Results: 

| Question | Class critique participant 1 |  Class critique participant 2 |  Class critique participant 3 |
|----------|-------------|-------------|-------------|
| Can you tell me what you think this is? | "This is a bar chart showing the cheapest European countries to study in." | "This is telling me which European country has the lowest cost if I want to study there. I can also see the tuition fee and living cost for each country." | "This is giving me the total costs of study, tuition fee, and living cost of each European country." |
| Is there anything you find surprising or confusing? | "Not really, I think it's really clear." | "You may want to clarify in the title it's for who." | "I think it's easy to understand." |
| Who do you think is the intended audience for this? | "People who are interested in studying in Europe" | "Is it for everyone who's considering studying in Europe?" | "People who are interested in going to Europe to further their studies."  |
| Is there anything you would change or do differently? | "No, I like the colors, I like the stack bars." | "Have you thought about adding a feature that shows which region the countries are in?" |  "I would play around with the tick interval, maybe make it bigger. Since you already have the labels, you don't need this many grid lines." |

Synthesis: 

Overall, the feedback was mostly positive, which gave me confidence that I was telling the story clearly and to the targeted audience. However, people's answers to the third question and the question raised by the second particpant made me realized that I forgot to specify the targeted audience. I also think the suggestion to show the region of each country is valuable. This was something I had been hoping to include, since the original map provided geographical context, and I wanted my bar chart to do the same.

For my final redesign, I would like to rephrase the title and find a way to add a regional feature. For the title, I already know that this chart is made for people in the UK who are interested in studying in Europe. For the regional feature, my hope is to create a filter that allows people to choose which region (Northern, Southern, Western, or Eastern Europe) they want to explore, while still being able to view the overall ranking so they can see where the countries in a specific region fall within the complete list.

## Step five: build the solution

_Include and describe your final solution here. It's also a good idea to summarize your thoughts on the process overall. When you're done with the assignment, this page should all the items mentioned in the assignment page on Canvas(a link or screenshot of the original data visualization, documentation explaining your process, a summary of your wireframes and user feedback, your final, redesigned data visualization, etc.)._

## References
_List any references you used here._

## AI acknowledgements

I used Gemini to help me create number labels for each bar.

