# ashiish23.github.io
URL - https://ashiish23.github.io/

CS498 Narrative Visualization

Messaging
In this narrative visualization, the main theme is to examine the relationship between change in a country's population size and the difference in per capita income between the poor and wealthy segments of the population. The message I want to convey is that, we can see in the case of the study of change in the population of each country and change in income differentials, these changes are loosely related. 
Scatter chart is plotted to visualize relation between the population change and the change in the income difference between the wealthy and poor over the period of 10 years (from 1988 to 2008).It is expected the countries with the largest change in the population level would have the higher change in the difference in incomes of the population. But the graph shows that this dependence is absent, because the scatter of countries is not dependent on these 2 parameters. The graph highlights 3 countries that most clearly demonstrate this. More details are visualized in absolute and relative values with bar and line chart respectively.
Visualization provides an opportunity to examine the changes in both relative and absolute values of these indicators. Viewers can see and assess trends in these indicators. The main page (Overview) summarizes the current state of the country's population, the difference between GDP per capita between the richest and poorest people, and the change in income differences since 1988. Further, the user can examine in detail each country and the dynamics of these indicators in both absolute and relative values in scene 2 and scene 3.
Narrative Structure
My narrative visualization follows the drilldown story structure. On the main page (Overview), the user sees the overview of all the data and can then move on to either absolute value chart, which shows the absolute dynamics of the indicators, or relative value chart, which shows the dynamics of changes in relative indicators, of his choice. In this way, users can explore the dynamics of any country of their choice.
Scene 1: Overview:
This slide shows a summary of all countries on the scatter plot graph.
•	Axis X - relative change in population over 10 years (from 1988 to 2008)
•	Axis Y - relative change in income difference over 10 years (from 1988 to 2008)
•	Axis Z - population in 2008
Below the graph, there are 2 buttons that allow the user to switch to a detailed study of the dynamics of the indicators for each country of his choice (Only 3 countries are shown in detailed view). To go to the graph, the user must click the corresponding button and use previous and next button for navigation between countries.
The graph shows annotations and detailed data in the form of tooltips.

Scene 2: Absolute Value Chart:
This view shows the visualization of absolute population size and the difference between GDP per capita for the poorest and wealthiest segments of the population. 
The linear chart shows the number of populations depending on the year. 
The bar chart shows the levels of GDP per capita for the poorest and richest segments of the population for each year of measurement of these indicators. 
User can navigate between countries using the navigation buttons below the graph. The graph shows annotations and detailed data in the form of tooltips.
Scene 3: Relative Value Chart:
This slide shows the relative size of the population and the difference between GDP per capita for the poorest and wealthiest segments of the population. 
The red line shows the level of change in GDP per capita for the poor and wealthy segments of the population for each year of measurement and the blue line shows changes in population size. 
The graph illustrates the relationship between these indicators. User can navigate between countries using the navigation buttons below the graph. The graph shows annotations and detailed data in the form of tooltips.
Visual Structure
For all scenes, this narrative visualization uses the same background color, the background color of the chart, the location of the scene (i.e. a single chart with subsequent descriptions), the alignment of charts and text for to provide a consistent visualization sequence. Scene names, axes and legends are given in all scenes, to help the audience understand the data. Slide numbers as well as back and forth buttons also are used to facilitate navigation between scenes. Annotations are also provided to help the user to focus on important parts of the charts. There are data detail in the form of tooltips on each graph.
Scenes
My narrative visualization has three main scenes (and 3 subscene for scenes 2 and 3), including the opening scene and two drilldown scenes. They all use the same scene template. The second and third scene are independent, and the user chooses, to which one of them it is necessary to make the transition from the main stage (from Scene 1: Overview). In other words, viewers can put forward a hypothesis (e.g., a change in the GDP per capita difference between the poor and wealthy segments of the population depend on the size of the population of a given country) on the main stage, which can then be tested on stage 2 or 3 at the user's choice.
Annotations
D3 notation library created by Susie Lou is used to annotate on a template. I used this template because it is easy to implement, has a good abstract design and sufficient color contrast between the background and annotations. Important values necessary for studying the information are given in the diagrams in the form of annotations. Annotations doesn’t change in single scene.
Parameters
The slide number (e.g., Scene 2, Scene 3, Country for detail, etc.) is a parameter, who control the fortune. Narrative visualization states include scene 1, scene 2, scene 3. The status and scene are defined by the numbers after the word "scene". For example, the "Subscene 3" parameter indicates that the state is the third scene. The "Subscene" parameter is displayed on scene 1, 2 and 3, the "country" parameter is displayed on scene 2 and 3. The second parameter is country. User can navigate by each country for detail in Scenes 2 and 3 via navigation buttons.
All parameters showed in the title of the scene.
Triggers
The slide number, the Overview button, the Absolute Value Chart and the Relative Value Chart button, Previous and Next button are triggering that link user actions to changes in the narrative visualization state. Buttons are displayed at the bottom of the page in the form of colored rectangles with white text, informing viewers about the possibility of moving back and forth between the scenes. 
