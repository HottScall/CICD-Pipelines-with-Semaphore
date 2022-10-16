<h1 align="centre">CICD-Pipelines-with-Semaphore</h1>
<h1 align="centre">Set up of a CI/CD pipeline with Semaphore</h1>

This project was built from a series of tutorials and additional challeneges. This initiail source for this tutorial is: https://docs.semaphoreci.com/guided-tour/getting-started/


<h2 align="centre">Learning covered</h2>

Using a single job starter workflow 
Adding a new block titled "Tests" to your work flow which contains 2 blocks of parallel jobs, Unit and Integration tests. Each of these jobs runs at the same time. 

Pipelines - Pipelines can contain multiple blocks. The display below contains two blocks. Block 1 runs first and the "Tetsts" black runs once Block 1 is completed. 

Blocks - Blocks can contains a single job or many parallel ones. E.GF - The test bloack contains 2 parallel jobs 

Jobs - Jobs are a basic execution. Semaphore runs each job as  sequence of commands in an clean and isolated environment that it creates on-demand and destroys as soon as the last command is finished. If the exit code of each command i 0, Semaphire records the jobs as successful 

Viewing Logs - Within each job, once completed or run the logs can be checked to view the output log of the job. 

Added a CD pipeline via promotions, which trigger other pipeslines. Combining promotions and pipelines can: Manage multiple release targets, implement any development strategy, perform rollbacks, manage infrastructure, automate any DevOps task with a full log of who did what and when 

Added an automatic promoition and a deplopyment pipeline - Added a promotion, enabled it, addec conditions for automatic promotion, added Environment Variables for a false API Key to be called. 


