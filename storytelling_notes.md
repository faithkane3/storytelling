# Data Storytelling Notes from Coursera Course

> "Data tell you what's happening; stories tell you why it matters."

> Florence Nightingale claimed to use data visualization “to affect thro’ the Eyes what we fail to convey to the public through their word-proof ears.”

> "The goal of advertising is not to convince people, or make them think something. It's to make them feel something.
And for engendering emotion, there's no more powerful tool than the story. In other words, we make choices based on feelings, and then later we justify those feelings with the rational, left side of our brain." [source](https://adage.com/article/digitalnext/put-emotion-storytelling/304463)

## The 3Cs of Storytelling
1. Context
1. Challenge
1. Conclusion

#### Stories should be Clear, Compelling, and Accurate.

You have to cut out story clutter just as you would chart clutter and clearly define the who, what, and why of your story. You also must keep your audience central to the planning of your story and presentation.

> "[S]tory is the number one business tool in the world." [source](https://adage.com/article/digitalnext/put-emotion-storytelling/304463)

> Edward Tufte says that excellent visualizations express “complex ideas communicated with clarity, precision and efficiency.” Tell your story through the graphical depiction of statistical information.

##### Basic Story Elements

**Overview -> Zoom and Filter -> Details on Demand**

- The Hook: Catch the audiences attention and get them to care about the action or characters in your story.
- Change: Showing change in characters in your story can inspire change in your audiences actions, as well.
- Connection: Use personal and/or shared experiences to connect your audience to your story characters or cause.
- Story Structure: Good story plots involve conflict and change, trying, failing, and succeeding.
- Authenticity: Keep it real, not real over the top when it comes to emotion.

##### Elon Musk Story Telling Elements
- **Name the Enemy:** Don't start your pitch talking about yourself, your team, or your product; start by talking about what's in the way of your audience's/stakeholders' happiness and goals. Who/What is to blame and why?
- **Answer the question, "Why Now?":** Proactively address your audience's/stakeholders' skepticism that you can answer/change something that no one else has been able to. People often thing that everything that can be done has been tried, so tell them what's different about this time, about your solution.
- **Show the Promised Land before explaining how you'll get there:** Show the solution or the path to the solution before you dig into the "How" of the solution. Bottom Line Up Front. Show your audience where you're headed.
- **Identify Obstacles and Solutions to Each:** Lay out the obstacles and your solution to each, one at a time.
- **Present Your Evidence:** 

##### Journalistic Storytelling
- **Find the compelling narrative:** Finding a narrative structure will help you decide if there is a story to be told based on the data or if a dashboard for EDA would be more appropriate. However, if a dashboard can do the job, think gamification. It still needs to be compelling and inviting. User personalization.
- **Think About Your Audience:** Your visualizatioins need to be framed around the level of information your audience already has as well as their level of sophistication with viewing data visualizations.
    - Novice: first exposure to the subject, but doesn’t want oversimplification
    - Generalist: aware of the topic, but looking for an overview understanding and major themes
    - Managerial: in-depth, actionable understanding of intricacies and interrelationships with access to detail
    - Expert: more exploration and discovery and less storytelling with great detail
    - Executive: only has time to glean the significance and conclusions of weighted probabilities
- **Be Objective and Offer Balance:** Be objective and aware of bias in your visualization. Tufte's Lie Factor measures how misleading a visualization can be to an audience.
    - Label elements of the viz clearly to avoid ambiguity or misunderstandings.
    - Match graphic dimensions with data dimensions.
    - Use standard units of measure.
    - Keep design elements from compromising the data.
- **Don't Censor:** Don't be selective about the data you include and exclude unless confident that you are giving your audience the best representation of what the data says.
    - Think about how you deal with missing data, outliers, temporal ranges, intervals, creating discrete variables from continuous, etc.
- **Edit, edit, edit:** Don't think that decorating your data, dressing it up to look good, is more important that finding the best way to explain the data or reveal the story of your data.

## Pre-Planning - Stakeholders Goals & User Needs

### Design a Checklist of Who, What, Why, and How

- What key elements will drive your data story?
    - What's the purpose of creating your story?
    - What is the current situation? (Context)
    - What is the conflict being faced? (Challenge)
    - What is the payoff for solving the conflict? (Conclusion)
- Who includes interested parties.
    - Who is your audience?
    - Who are stakeholders?
    - Who are SMEs?
    - What data is available?
- Why includes goals and objectives.
- How includes the format and point of view.
    - Will you be presenting static slides, paper report, or an interactive dashboard?
- You might start with story points to build and organize your story in Tableau.
- You will need to refine and optimize as you build.
    - This will mean adding and removing story elements, visuals, etc.

### Expressiveness and Effectiveness

- Do you have data to express your story accurately?
- Does presentation style effectively convey data's meaning?

### Starting with Your Stakeholders

- They can help you refine drivers for the viz.
- Provide key requirements and purpose.
- Provide details about data available.
- Identify and clarify audience characteristics.
- Inventory stakeholder requirements, source materials, and goals.
- Assess your level of domain knowledge and understanding of the business case.

#### Questions to Ask Stakeholders

- Which elements, details, and results must be included in the story?
- What the timeline for the project/presentation?
- Summary of story points and goal for data story.
- Benchmarks or metrics to measure success.

### Know Your Audience

- Level of Understanding
- Reasons for Viewing
- Intended takeaways
- Types of visualizations and level of statistical or technical sophistication
- Different segements of audience that will be attending/viewing presentation

#### Create Personas

- Creating personas that represent segments of your audience helps you prioritize design requirements
    - Quantitative: Surveys to capture common patterns of audience segments
    - Qualitative: Changing your perspective
    
#### Early Interview Guidance

- List of needs and goals
- Interview a target audience segment
- Ask open-ended questions, not showing a prototype and asking what they like about it. Ask about needs, goals, pain points, level of understanding.
- Don't ask narrow and highly specific questions at the beginning.
- Focus on essential needs but be open to a new solution and design specific solutions.
- Ask right questions about goals and audience background.
- The solutions are your job as the designer.
- In what contexts or platform with the view the data story?

#### Later Interview Guidance

- At this point, it's ok to show a few design ideas. Avoid a single choice.
- Take into account your audience context, how much detail should you show, how much interaction will there be with presenter and viz, how long should the story be, etc.

#### Design to How the Human Brain Works

- People are good at finding stories in patterns even when the story is not really there. (Beward of False narratives, both created by you and created by audience from viewing your visualizations)
- Humans tend to see and amplify what they expect to find. (Confirmation Bias)
- Be aware of other types of bias, as well.
- Make sure data provides a complete picture to avoid audience drawing their own conclusions based on misunderstandings.

## Finding the Story - Getting Into the Data

- Questions about data:
    - What types of data do I have to work with?
    - What's the data quality and completeness?
    - What are the most relelvant dimensions of the data?
    - How fresh and frequently updated is the data?
    - How will the data be framed?
    - What type of actions and decisions might my story prompt?
    
    
- Not all patterns in the data make true stories. More data, more risk of false narratives and the temptation to turn insufficient data into false narratives.
- Where is the most useful data to be found? (Survivor Bias) Help the audience recognize and reframe the full data story using context and key points.
- Weight and evaulate available data and work to fill in the gaps.
- Relevance of data may shift with context and/or new data. (Context)
- All the necessary data may not be available at the start of a project.
- Seemingly irrelevant data may turn out to be essential to the story.
- Test data against various factors and other data and from various perspectives.
- To clarify thinking, try seeing from different perspectives.

## Aligning, Prioritizing, Optimizing, and Designing the Data Story

- Does the data provide the level of detail to meet the stakeholders' needs?
- Is your aim to persuade of to draw conclusions?
- Is your purpose to start an open-ended conversation?
- Prepare to pivot if the data surprises you or contradicts your initial hypotheses.
- Will your presentation/report explore or explain?
- Balance meeting needs of stakeholders as well as connecting with your audience needs.
- What level of detail will be most effective for your data story? This really depends on the eyes of the beholders.
- "Everything should be made as simple as possible but not simpler." You have to provide what the audience needs, not more, not less.
- The story arc you choose should depend on your audience and context.

## Personalizing Dashboards

- **Start with the questions, not the metrics.**
- Change the headings on filters to questions or prompts for your users.
- Use aliases in your filter values to make them more usable.
- Ability for side-by-side comparisons on a dashboard, country 1 on the left, same prompts on the right for country 2.
- Add the filter to the headings or titles, so if user changes the filter, it changes the heading for what they are looking at.
- Test your stuff on other people; what might be obvious to you may not be to those not familiar with your data.
- Customize and USE Tool Tips. You can even add viz to your tool tip to really add another layer of information.
- Narrative Science - Natural Language Generation.
- Perform a Heuristic Evaluation - Assess the viz and note what works well and what could be improved.

## Recommended Readings for Understanding the Science Behind the Human Brain

- This recommended reading provides some scientific explanation for why and how humans make decisions for reasons other than pure logic and facts.  Emotion, behavioral factors, and psychological factors also play an important role in decision making, and this article touches on why we believe that to be true. Dawes, Robyn M., A Message From Psychologists to Economists: Mere Predictability Doesn’t Matter Like it Should (Without a Good Story Appended to it), Journal of Economic Behavior & Organization Vol. 39 (1999) 29-40
- This article examines the intersection of emotion and storytelling in the context of human decision making.  While this article focuses on the marketing context, much of the underlying information is true for storytelling across all disciplines. Luhn, Matthew, How to Put More Emotion in Storytelling: Digital Advertisers Have Forgotten How to Make People Feel Something, Advertising Age, 2016 (http://adage.com/article/digitalnext/put-emotion-storytelling/304463/)
- This article from the VP of Research and Design at Tableau Software, Jock Mackinlay, confirms the importance of storytelling in making a human connection with data. The article provides some useful considerations for crafting data stories and reinforces many of the techniques included in this lesson. Mackinlay, Jock, Kosara, Robert, Wallace, Michelle, Data Storytelling: Using Visualization to Share the Human Impact of Numbers, Tableau Software (Mackinlay, Jock, Kosara, Robert, Wallace, Michelle, Data Storytelling: Using Visualization to Share the Human Impact of Numbers, Tableau)
- This Harvard Business Review article emphasizes among other things, the importance of considering the audience when crafting data stories.  Think about how the author describes the various audience profiles, and how you might incorporate that into your design checklist. Strikeleather, Jim, How to Tell a Story With Data, Harvard Business Review, 2013 (https://hbr.org/2013/04/how-to-tell-a-story-with-data)