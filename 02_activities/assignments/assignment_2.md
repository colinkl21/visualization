# Data Visualization

## Assignment 2: Good and Bad Data Visualization

### Requirements:

- Data visualizations are important tools for communication and convincing; we need to be able to evaluate the ways that data are presented in visual form to be critical consumers of information 
- To test your evaluation skills, locate two public data visualizations online, one good and one bad  
    - You can find data visualizations at https://public.tableau.com/app/discover or https://datavizproject.com/, or anywhere else you like! 
- For each visualization (good and bad):  
    - Explain (with reference to material covered up to date, along with readings and other scholarly sources, as needed) why you classified that visualization the way you did.
      ```
      This is a bad visualization: https://x.com/JonBoeckenstedt/status/1291602888376999936
      The biggest problem with this graph is that y axis on the left and y axis on the right side represent different values. The graph is meant to compare mask vs. no mask mandate counties covid cases. But if you look closely you would realize that it doesn't make sense to compare these two conditions because they have different starting points. You can only compare temporal wise (e.g., first day vs. the last day) within each condition, but it doesn't make sense to compare between conditions (e.g., not mask vs. no mask).  

      Good visualization: https://timogrossenbacher.ch/bivariate-maps-with-ggplot2-and-sf/
      I really like this map. It's visually pleasing and professional. The goal is to visualize income and inequality on the same map. The 9 color legend is really helpful and effective in distingushing the areas by income and inequality. I also like how there are captions on the map so we don't have to go back to the legend to check which color represents what info. 

      I also love this 3d visualization.  https://x.com/researchremora/status/1611115019529322498
      The story is simple, just population density. But the package rayshader does it in a way that's very visually pleasing and futuristic. Areas with a greater population are represented with peaks. It's easy to spot the major cities from a glance at this map.  


    







      ```
    - How could this data visualization have been improved?  
      ```
      If I were to improve the bad visualization, I would first make sure there's only one y axis. Then I would explicitly lable the y axis as confirmed covid cases per 100k population. I would keep the color scheme, but I would create a legend to indicate orange means counties that have mask mandate,and blue means counties without mask mandate. I would also show the full range of the y axis. 

      For the good visualization, the only thing I would improve would probably be explaning the white space. It's not clear to me whether those are geographical features like mountains or borders between areas, or no human lives there, or no data available. 






      
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
* Submission Due Date: `23:59 -  2026-06-09`
* The branch name for your repo should be: `assignment-2`
* What to submit for this assignment:
    * This markdown file (assignment_2.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [x ] Create a branch called `assignment-2`.
- [x ] Ensure that the repository is public.
- [x ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [x ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
