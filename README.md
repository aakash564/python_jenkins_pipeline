# python_jenkins_pipeline
- Jenkins pipeline script using python file project. - 
Pipeline for Python applications. We will be building a pipeline as code .

The pipeline is the new feature of Jenkins, where we can write the Jenkins job as a sequence of steps. It is written in groovy. Since, it is a script we can keep it along with our code and can be easily replicated to other projects. We can also invoke Jenkins plugins in pipeline scripts.


Agent: specifies in which environment the job will be run.
Stages: a collection of stage or a working bundle.
Stage: a set of steps to perform a certain operation.
Steps: one or more steps that will be executed under each stage. Typically, it is a command.
Post: it will run on job completion. we can trigger different options based on build status, if successful, unstable, or failure.
