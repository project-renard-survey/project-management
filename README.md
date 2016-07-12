This is our centralized repository for high level, project wide issues.

## Project Management:
We use **ZenHub** to organise our workflows. 
In order to see our full Kanban board and how the EPICs and tasks are connected, [you have to install the plugin here](https://www.zenhub.com/).

But even without Zenhub installed you can check out the tasks here:
  - [High-level tasks/EPICs](https://github.com/WorldBrain/project-management/issues) (i.e Features)
  - [Front-end related tasks](https://github.com/WorldBrain/webmarks/issues) (Webmarks)
  - [Back-end related ](https://github.com/WorldBrain/cortex/issues) (Cortex)


### Terminology of Repos

1. project-management
	- Centralized planning for the Worldbrain project. Encapsules all high level project wide tasks. (i.e. features)
2. webmarks
	- front-end for worldbrain project
3. cortex
	- back-end for webmarks


### How-to-use:
 - [Access ZenHub Board](https://github.com/WorldBrain/project-management#boards?repos=61628290,62507021,63184111)
 - Adding new tasks or file a bug
    - (High-level tasks/EPICs) affecting [BOTH front- and back-end](https://github.com/WorldBrain/project-management/issues)
    - [ONLY front-end](https://github.com/WorldBrain/webmarks/issues) (Webmarks)
    - [ONLY back-end](https://github.com/WorldBrain/cortex/issues) (Cortex)
  
## README-DRIVEN-DEVELOPMENT:

**This is our process:**

1. Write your README first!
    - When a developer accepting a new task, **the first thing is to write a README** stating all important information and make a pull request with it. Why the README is so important you can read [in the blog post of Tom Preston-Werner](http://tom.preston-werner.com/2010/08/23/readme-driven-development.html)
    - **IMPORTANT:** This is only a first version of the readme, with the purpose to put some brain juice into how to do it, before actually executing. It is a work-in-progress document that is finished, when the code is finished. 
    - Include the following: (**Bold** = Must have, Slim = When appropriate)

        - **High Level Goal of Cod**e (Ideally already available, through planning of task)
        - ** Technical Implementation** (High Level Description)
        - Technologies, Rough approach on solving the issue
        - Data and Format of expected Input
        - Data and Format of expected Output
        - How to Install
        - Important Information (like expected errors, workarounds, things to install before)
        - Current State of Development
        
3. Pull Request with README file
 	- Make a pull request in the READMES folder in the respective repo

2. Review of README by team
   - The team reviews the understandability of the README and gives feedback to the general approach of solving the issue. The team might point out that one of the "when appropriate" information can be added before starting development (f.e. Input/Output)

3. After the team accepts pull request with README, the developer can start hacking on the code. 

4. When finished, the code pull request is filed and must be reviewed by either Tim(@dev-tim), Martin(@grady-lad) or Luke(@lwm)




Coming soon. We will use readthedocs.org for that. 
[Wanna help to set it up?](https://github.com/WorldBrain/project-management/issues/19)
