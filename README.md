This is our centralized repository for high level, project wide issues.

## Terminology of Repos

1. [project-management](https://github.com/WorldBrain/project-management/)
	- Centralized planning for the Worldbrain project. Encapsules all high level project wide tasks. (i.e. features)
2. [webmarks](https://github.com/WorldBrain/webmarks)
	- front-end for worldbrain project
3. [cortex](https://github.com/WorldBrain/cortex/)
	- back-end for webmarks

<br>
## Project Management Tools:

We use **ZenHub** to organise our workflows. 
In order to see our full Kanban board and how the EPICs and tasks are connected, [you have to install the plugin here](https://www.zenhub.com/).

But even without Zenhub installed you can check out the tasks here:
  - [High-level tasks/EPICs](https://github.com/WorldBrain/project-management/issues) (i.e Features)
  - [Front-end related tasks](https://github.com/WorldBrain/webmarks/issues) (Webmarks)
  - [Back-end related ](https://github.com/WorldBrain/cortex/issues) (Cortex)

### How-to-use ZenHub:
 - [Access ZenHub Board](https://github.com/WorldBrain/project-management#boards?repos=61628290,62507021,63184111)
 - Adding new tasks or file a bug
    - (High-level tasks/EPICs) affecting [BOTH front- and back-end](https://github.com/WorldBrain/project-management/issues)
    - [ONLY front-end](https://github.com/WorldBrain/webmarks/issues) (Webmarks)
    - [ONLY back-end](https://github.com/WorldBrain/cortex/issues) (Cortex)
  
<br>
## Documentation

### Code Documentation

Coming soon. We will use readthedocs.org for that. 
[Wanna help to set it up?](https://github.com/WorldBrain/project-management/issues/19)

### Readme-Driven-Development (RDD)

In order to provide not only modular software, but also a modular and thorough documentation, we follow the [RDD-approach](http://tom.preston-werner.com/2010/08/23/readme-driven-development.html)

#### How does it work?

1. Write your README first!
    - When starting to work on a new task, **the first thing is to write a README** with the following information (**Bold** = Must have, Slim = When appropriate):

        - **High Level Goal of Cod**e (Ideally already available, through planning of task)
        - **Technical Implementation/Approach on solving the issue** (High Level Description)
        - Data and Format of expected Input
        - Data and Format of expected Output
        - How to Install
        - Important Information (like expected errors, workarounds, things to install before)
        - Current State of Development
        
     - **IMPORTANT:** This is only a first version of the readme, with the purpose to put some brain juice into how to do it, before actually executing. It is a work-in-progress document that is finished, when the code is finished. 
        
3. Make Pull Request with README file **only**.
   - Make a pull request in the READMES folder in the respective repo

2. Review of README by team
   - The team reviews the understandability of the README and gives feedback to the general approach of solving the issue.

3. **After** the team accepts pull request with README, the developer can start hacking on the code. 

4. Make pull request with code and updated README


