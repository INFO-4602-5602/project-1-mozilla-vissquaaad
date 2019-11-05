Mozilla Survey Group Project

Instructor: Danielle Albers Szafir 

INFO 4602-001: Information Visualization

Group Members: Elise Bergmann, Savannah Bornstein, Joshua Paup, Conner Sinjem

VISUALIZATION #1 CATEGORICAL

Information:

Overview: This specific visualization focuses on comparing the average ranking for user-review based on a specific country. In the Mozilla survey, one of the questions asks individuals to rank aspects (such Price, Features, Safety, User Reviews, and many more), based on the order of importance that is considered when making a purchase of a smart device, (i.e. TV or smartphone).

Interactions: By hovering over a certain bar in the bar graph, a user can specifically identify the country associated with a particular bar. This allows the user to not only be able to see the overall picture of different regional trends, based on the bar’s color, but also have the ability to view which bar is which country to get more specific data based on particular country.

Preprocesses: In terms of Preattention, gist is utilized by the colorful bar graph being the quick picture that is first observable in the visualization; the graph is very tight with numerous bars being presented to represent all included countries. Gestalts are utilized by the grouping of the data being portrayed through different colors that identify specific regions that each country is a part of.

Tasks: By visualizing countries based on the average ranking of user reviews in purchasing decisions, the viewer of the visualization can interpret different trends that exist in buying behaviors based on different countries. By quickly being able to identify which countries have a lower number out of 10, it can be interpreted that the lower the y-axis for a specific bar, the higher the priority of relying on user reviews when making a purchase. For example, an average ranking of 1 for a country would indicate that that specific country, on average, most highly prioritizes referencing user reviews before purchasing a smart device.

Design Process:

Designing: The actual design of this visualization encompassed determining the most effective way of showcasing the average ranking for user reviews based on the specific country; based on this task, we chose to use a bar graph. Bar graphs are a fantastic way of comparing a certain attribute among different groups; in this case, the attribute is the average ranking of user reviews and the groups are different countries.This visualization also allows individuals to see trends of specific regions based on the color of the bars.

Building: The building process of this visualization involved using techniques learned in class, utilizing templates created/given in class, as well as conducting online research to find new and unique ways of creating our visualization that may not have been covered in the classroom lectures. 

Refining: Refining was definitely the most time consuming/difficult part of creating this visualization. Many aspects of the creation process involved trial and error in terms of trying to incorporate as many creative aspects as possible while also having realistic expectations for what we could develop. 

Reasoning: This visual representation was chosen because it is interesting to compare trends among different countries in terms of prioritizing considerations that go into purchasing a smart device. By grouping by country, we can specifically see which countries more highly prioritize referencing user reviews when making purchasing decisions for smart devices. 


VISUALIZATION #2 QUANTITATIVE

Information:

Overview: This visualization first divides users by how they answered the question, “What is your biggest fear as we move towards a more connected future?”. It further averages the privacy and convenience responses, based on the responses to that initial question. Therefore, each answer option to that initial question is listed in the legend, and each point represents those answers in relation to the averages expressed through privacy and convenience. 

Interactions: With this visualization, a viewer can hover over a given point to enlarge it. Additionally when a viewer hovers, all of the necessary information regarding the average privacy and convenience responses clearly pops up as a text box. 

Preprocesses: When first viewing this visualization a viewer can quickly get the gist of how polarizing the responses are by seeing how spread out the points are on the graph.  Gestalts were additionally utilized through color, in order for the viewer to easily be able to differentiate between points. 

Tasks: This visualization allows a viewer to quickly view the average rank for privacy and convenience responses based off how respondents responded to, “What is your biggest fear as we move towards a more connected future?” This visualization additionally highlights the polarity of responses, thus showing how polarized responses regarding technology use are. 

Design Process:

Designing: Beginning with the excel file, we sifted through the data as a group, and highlighted areas of interest that we wished to cover in our visualizations. When thinking about visualizing the “biggest fear” question in relation to privacy and convenience, we thought a scatterplot would be visually appealing to viewers; especially since we were attempting to condense multiple elements to represent one given point.  By designing the visualization like this, a viewer is able to very clearly see the polarization occuring in the scatterplot. 

Building: To build this visualization, we expanded off of the skeleton code provided for a scatterplot, using our insights from class. We gained additional insights through researching online and tweaking elements of code we found. Additionally, we read through different forums to gain more insight regarding the different ways to achieve our desired visualization.

Refining: The refining process was very time consuming as we were experimenting with placement, as well as how to achieve those placements. We played around with our code and through the process, tweaked and refined our visualization to eventually achieve our desired outcome.
 
Reasoning: We chose this visualization in order to provide a more simple visual, while representing more condensed information. By doing this, a viewer would not be overwhelmed by the amount of information they are receiving from a given point. But rather, it very effortlessly displays the information in a format that is clear to any viewer. Additionally, the distance between each point allows for the viewer to carefully examine each point, without being overwhelmed, or losing sight of what information is vital. 


Team Roles

Elise Bergmann: 
This team member focused on the write up portion of the project, primarily for the second visualization details, while assisting in other aspects of the write up deliverable as well. This member also contributed towards researching areas of uncertainty in creating the second visualization and assisted Conner in anything that he needed help with in the d3 creation process.

Savannah Bornstein: 
This team member focused on the write up portion of the project, primarily for the second visualization details, while assisting in other aspects of the write-up deliverable as well. This member also contributed towards researching areas of uncertainty in creating the second visualization and assisted Joshua in anything that he needed help with in the d3 creation process.

Joshua Paup: 
This team member focused on the creation of the visualization that used categorical data. This work encompassed all design and building aspects for the actual visualization that involved the coding executed in d3. This group member ensured that all technical requirements were met by making a visualization that is interactive, has meaningful comparisons, and visualizes at least five data attributes total when compared with the other visualization created.

Conner Sinjem: 
This team member focused on the creation of the visualization that used quantitative data. This work encompassed all design and building aspects for the actual visualization that involved the coding executed in d3. This group member ensured that all technical requirements were met by making a visualization that is interactive, has meaningful comparisons, and visualizes at least five data attributes total when compared with the other visualization created.


How to Run Our Project
For visualization #1, open project1-2.html and the column “AE” was renamed to “User Reviews” which can be used with the original csv file.
For visualization #2, open project1-3.html and the file mozilla.csv will be shared with you in google drive from cosi4160@colorado, (The only content changes were column header names.)



------------------------------------------------------------------------------------------------
# 4602-Mozilla
*Due November 4, 2019 @ 11:59pm through GitHub Classroom*

Projects may be submitted up to 3 days late, with a 10% penalty per day

<h2>Overview: </h2>
Mozilla (the same company that created the Firefox web browser) recently conducted a survey on people's perceptions of privacy in our modern, highly connected world. The survey was aimed at understanding how comfortable people from all over the world are with various technology and how that comfort varies with things like device ownership or tech savvy. You can learn more about their data here: https://blog.mozilla.org/blog/2017/11/01/10-fascinating-things-we-learned-when-we-asked-the-world-how-connected-are-you/?utm_source=newsletter-mofo&utm_medium=email&utm_campaign=IOTsurveyresults&utm_content=callout&utm_term=4434975

The challenge is that, while they have a rich set of data, they don't have strong ways of exploring that data beyond basic spreadsheets and descriptive statistics. Your goal is to create a set of visualizations that allows them to engage with their data. The raw data is available at: https://drive.google.com/file/d/0B5UMbl9u1_wQc2l0ZTU0dTdoYnM/view

To do this, create visualizations that illustrate at least two insights into their data. The above blog post has some insights you can use to start thinking about this dataset, but I encourage you to think outside of these ideas as well. 

<h2>Minimum Requirements:</h2> 
Your project must:
<ul>
<li> Include a README.md file that outlines:
  <ul>
  <li>Information about your visualizations and what they show. Include information about interactions, preprocesses, and design as appropriate. Note what tasks the visualization allows you to accomplish to derive this insight and how your design is tailored to support these tasks. </li>
  <li>Your design process (e.g., how did you go about designing, building, and refining your system? Why did you choose these representations?)</li>
  <li>Your team roles for each individual</li>
  <li>How to run your project</li></ul></li>
<li>Include at least two unique visualizations:
  <ul>
  <li>One visualization must include some quantitative data</li>
  <li>One visualization must include categorical data</li>
  <li>Each visualization must be interactive</li>
  <li>Your visualizations should support at least one meaningful comparison between related data attributes</li>
  <li>Your visualizations should visualize at least five data attributes total</li></ul></li>
<li>Be able to work with any dataset of this format (e.g., the numbers are interchangable but the columns and document titles are fixed).</li>
</ul>

<h2>Above and Beyond:</h2> 
The above requirements are the minimum for a passing grade on this project. Some ideas to improve your project include:<ul>
<li>Unusual Representations: Draw on some of the examples from class to represent data in ways beyond a typical scatterplot or bar chart.</li>
<li>Style: Keep the style consistent across all your views, with an eye towards intelligently applying visual design.</li>
<li>Geography: Incorporate maps or other geospatial data components into your visualization.</li>
<li>Interesting Tasks: Derive insight into the data beyond that provided in Mozilla's current post. Highlight these insights in your readme and describe how the visualization enables them.</li>
<li>Perceptually-Informed Design: Integrate perceptual concepts into your visualization design and discuss how you've integrated those concepts in your readme.</li>
<li>Coordinated Views: Have two or more visualizations that interact with one another as you move through the data.</li></ul>

<h2>Platforms:</h2> 
You can use any development platform you'd like so long as your final project runs in the browser without having to install anything new. Your project readme should include step-by-step instructions on how to run your projects and it should run without me having to modify the code. You are welcome to use different platforms for each visualization.

Some platforms to look at include:
<ul>
<li>D3</li>
<li>R with ggplot</li>
<li>WebGL or Three.js</li>
<li>ProcessingJS</li>
<li>Google Maps API</li>
<li>Open Street Map API</li>
<li>Bokeh</li>
</ul>

If you would like to use a platform that will push you in creative ways but may not support all of the requirements of the project, please come talk to me. 

<h2>Submissions:</h2>
All submissions must be made through GitHub with a timestamp by 11:59pm on 11.4. Your submission files should include:
<ul>
<li>Your README</li>
<li>Your code and/or project</li>
</ul>
Note that each group only needs to submit one file. 

## Project Teams
Group 1:	Savannah Bornstein, Joshua Paup, Elise Bergmann, Conner Sinjem

Group 2:	Lanea Blackburn, Priya Panati, Edgar Mendoza, Jacob Boeckenstedt

Group 3:	Hannah Weber, Trevor Buck, Clark Mousaw	

Group 4:	Madeline Cupchak, Hunter Rief, Kathleen Anderson, Yizhen Wu

Group 5:	Jiaheng Zhao, Jiahao Wang, Juliet McFarlane, Michael Rogers

Group 6:	Mary Yoder, Julia Merten, Paige Stockebrand, Lu Liu

Group 7:	Jihoon Jang, Caden Bradbury, Talia Colalancia	

Group 8:	Joshua Barker, Angus MacDonald, Malik Tefridj, Keaton Whitehead

Group 9:	Anthony Camacci, Dilon Clark, Steven Yatko	
