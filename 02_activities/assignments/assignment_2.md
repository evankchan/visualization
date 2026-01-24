# Data Visualization

## Assignment 2: Good and Bad Data Visualization

### Requirements:

- Data visualizations are important tools for communication and convincing; we need to be able to evaluate the ways that data are presented in visual form to be critical consumers of information 
- To test your evaluation skills, locate two public data visualizations online, one good and one bad  
    - You can find data visualizations at https://public.tableau.com/app/discover or https://datavizproject.com/, or anywhere else you like! 
- For each visualization (good and bad):  
    - Explain (with reference to material covered up to date, along with readings and other scholarly sources, as needed) why you classified that visualization the way you did.
      ```
      Bad Visualization (https://public.tableau.com/app/profile/enes.golic/viz/badvisualization/map): This visualization by Enes Golic consists of a route map of all domestic flights that primarily traverse within the USA. This visualization, although is spatially attractive and stimulating to the viewer (has an overal Gestalt shape to it consisting of nodes and lines) [Reference to Gestalt Slide], unforunately, does not convey detailed information. Firstly, since the route maps are cluttered and there is not adequate spacing between many of the routes, it is difficult for the viewer to identify any specific routes within the borders of the USA. Instead, the conglomeration of the yellow lines make the routes look like a massive "blob" that does not provide useful information to the viewer-- it is NOT perceptual [Reference to slide 25 of the first deck of slides]. The viewer may ask specific questions like, "I wonder which node or city has many routes going to and from it?" Unforunately, with this visualization we cannot discerning this information for most of the cities (as represented by nodes). Furthermore, there is no directional information or specifiers (names of cities or routes) within this map. For example, are some routes only one way, or are they both ways? Furthermore, while I understand that the nodes represent presumably a city, what are those cities? [as shown in customizing plots, we should include labels to allow for perceptual accuracy from our viewers] Finally, like skewing graphs, this graph can be considered skewed, as all of the routes are assumed to be linear. Of course, we know that this is not true in actuality. Possibly modelling the curviture of the routes may present an alterantive. 

      Good Visualization (https://public.tableau.com/app/profile/natalie7346/viz/Evolutionoffilmduration-anexampleofgooddatavisualisation/Sheet7): This graph by "Natalie" is a line-graph visualization comparing movie and TV show durations side by side and their changes across time. The charge very clearly from the get go "tells a story" to the user [Ref. telling a story slide in first slide deck]. Immediately, it is clear to the viewer that both movie and TV show durations have increased over time, but movie durations have particularily increased drastically. Second, this visualization does not skew the graph [Ref. the skewed exponential graph example]. If the author had compressed the y axis ticks and kept the x-axis labels as is, the movie line data would particularily look  flat, possibly misleading the user's initial impression that movie durations have not changed drastically over time. Third, this graph makes very clear labels [Ref. discussed in our customization/matplotlib slides] that make this graph very visually appealing and immediately perceptual to the viewer. We know that the distinct count of duration on the y-axis is "how long" and there is a small legend immediately telling us which line belongs to movie and which line belongs to TV show.   







      ```
    - How could this data visualization have been improved?  
      ```
      Bad Visualization (https://public.tableau.com/app/profile/enes.golic/viz/badvisualization/map): This map could firstly be improved by using a series of labels and legend to enable perceptual accuracy by our viewers [Ref. to slides on customization]. These labels could include labels to major cities. Furthermore, the author must indicate what the colour gradation from yellow to red means. I think I know what they are alluding to, perhaps, darker red = more busy flight route. However, this is not explained or easily notable. Second, this map could improve by using 1 figure, but multiple axes; instead of 1 figure and 1 axes. Perhaps the author could generate multiple maps that show different routes of different topics (e.g., major routes, minor routes, expensive routes, less expensive routes). This would help "tell a story" [Ref. 1st slide deck with Minard or Nightingale]. One simple story could be told is "here are the more frequent routes and here are the less frequent routes." Even more cooler, would be if they made it interactive. Layer all of the routes on top of each other and allow the users to pick which routes they want to see. 


      Good Visualization (https://public.tableau.com/app/profile/natalie7346/viz/Evolutionoffilmduration-anexampleofgooddatavisualisation/Sheet7): As good as this visualization is, there are two major drawbacks. First of all, users who may be color blind or visually challenged may not be able to perceptually distinguish between the lines, one of which is darker purple and the other is a lighter shade of purple/magenta. Using completely contrasting colours will definitely make this graph more perceptual to users, especially those who may have perceptual limitations. As good as a story this visualization tells, it is not entirely accurate. [Ref. slide. while we can never be neutral, we do want to be accurate with our data]. We do not know if the author here is referring to "The average of all movie durations across time" or an "individual movie". Similarily, we do not know if the author here is referring to "The average of all TV shows durations across time" or an "individual TV show." Clarification in a legend or y-axis would improve this drastically!
      
      ```
- Word count should not exceed (as a maximum) 500 words for each visualization (i.e. 
300 words for your good example and 500 for your bad example)

### Why am I doing this assignment?:

- This assignment ensures active participation in the course, and assesses the learning outcomes
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story

### Rubric:

| Component               | Scoring   | Requirement                                                 |
|-------------------------|-----------|-------------------------------------------------------------|
| Data viz classification and justification | Complete/Incomplete | - Data viz are clearly classified as good or bad<br />- At least three reasons for each classification are provided<br />- Reasoning is supported by course content or scholarly sources |
| Suggested improvements  | Complete/Incomplete | - At least two suggestions for improvement<br />- Suggestions are supported by course content or scholarly sources |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 10/26/2025`
* The branch name for your repo should be: `assignment-2`
* What to submit for this assignment:
    * This markdown file (assignment_2.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-2`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
