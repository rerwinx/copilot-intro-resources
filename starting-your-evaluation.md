# Starting your GitHub Copilot Evaluation
 
## Select participants:
 
Select the developers who will participate in the evaluation.  Candidates should:

- Represent a mix of experience levels to assess the broader impact on the team
- Use a supported development environment 
- Develop primarily in a commonly used language (e.g. JavaScript, Python, Go, etc.) 
- Select an organisation to enable for the evaluation
- The codebase does not have to be within the organisation – it will be used for user management and to control access
- Determine how you want to measure and collect feedback from your participants (see below)
 
## Onboarding participants
 
Share the following resources and documentation with your evaluation participants
 
> [Video: What is Copilot?](https://www.youtube.com/watch?v=IqXNhakuwVc)
> 
> [Getting started with Copilot](https://docs.github.com/en/enterprise-cloud@latest/copilot/getting-started-with-github-copilot)
>  
> [Configuring GitHub Copilot in your environment](https://docs.github.com/en/enterprise-cloud@latest/copilot/configuring-github-copilot/configuring-github-copilot-in-your-environment)
>  
> [Quickstart for GitHub Copilot](https://docs.github.com/en/enterprise-cloud@latest/copilot/quickstart)
>  
> [GitHub Copilot Discussion Forum](https://github.com/orgs/community/discussions/categories/copilot?discussions_q=category%3ACopilot)
>  
> [Troubleshooting common issues with GitHub Copilot](https://docs.github.com/en/enterprise-cloud@latest/copilot/troubleshooting-github-copilot/troubleshooting-common-issues-with-github-copilot)

Optionally arrange a training or overview session for all participants (Regular [EMEA-timezone demo session](https://gh.io/copilot-intro))

## Assessing Copilot via surveys
 
In assessments Copilot has been shown to have a significant impact on developer satisfaction and productivity – developers are able to stay in the flow, focus on more satisfying work, and spend less time searching. To measure these benefits it’s important to survey your developers. In fact, developer surveys are the fastest and most cost-effective way to assess Copilot for your business. 
 
At a minimum, we recommend surveying your developers at the end of your evaluation.  However, we’ve seen most evaluations leverage a weekly survey for the duration of the process to capture a fuller set of developer feedback.
 
The questions that were used in GitHub’s own assessment of Copilot are listed [here](example-survey-questions.md).  We have based these questions on the SPACE framework, a state-of-the-art framework that operationalises developer productivity holistically, and avoids over indexing on activity metrics (e.g. Lines of Code) that ignore key aspects of productivity and provide unhelpful or misleading results. The SPACE framework recognises five dimensions to developer productivity:
 
- S - Satisfaction & Wellbeing
- P - Performance
- A - Activity
- C - Communication & Collaboration
- E - Efficiency & Flow
 
Feel free condense the survey to the questions that are most relevant or add your own but be sure to keep the survey consistent across weeks for accurate trends.

Additional Reading:
                
> [Research: quantifying GitHub Copilot’s impact on developer productivity and happiness](https://github.blog/2022-09-07-research-quantifying-github-copilots-impact-on-developer-productivity-and-happiness/)
> 
> [Research: How GitHub Copilot helps improve developer productivity](https://github.blog/2022-07-14-research-how-github-copilot-helps-improve-developer-productivity/) 
> 
> [Productivity Assessment of Neural Code Completion](https://dl.acm.org/doi/pdf/10.1145/3520312.3534864)
 
 
## Assessing Copilot through metrics
 
Copilot can affect metrics that relate to engineering health, for example DORA metrics. If you are already using engineering health metrics, e.g. Change Failure Rate, Deployment Frequency, Lead Time for Changes, Time to Restore Service or similar, look for changes in these metrics after you adopt Copilot for Business. Keep in mind that these metrics depend on general system health so the effect of using Copilot for Business may show up later and/or depend on other factors as well (e.g. use of legacy code).
 
## Assessing Copilot through experiments
 
While it can be difficult to create perfect experimental conditions, here are some ways you can assess Copilot.
 
### Before/After comparisons
 
Before starting the Copilot evaluation, ask a developer to screen record themselves writing a unit test without using Copilot. After two weeks of using Copilot ask them to screen record a similar task, this time using Copilot. See if they perform slower/faster/better using Copilot. Ideally, repeat the same process after four weeks of using Copilot. 
 
### With/Without comparisons
 
At the start of the evaluation select one or more teams that will use Copilot in their software development, while other teams will not. To the degree possible, aim to have teams be equivalent, i.e. be similar in size, work in a similar codebase, have a similar mix of developer experience levels etc. At the end of the evaluation see if the teams that used Copilot performed slower/faster/better.

[HOME](README.md)

[SURVEY QUESTIONS](example-survey-questions.md)