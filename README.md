# pipeline-demo
The files used for the pipeline demo are as follows:
  1. src/test/server.test.js - Test script. It tests the application by making an API call to it.
  2. src/server.js - Defines the application
  3. Dockerfile - Lists actions Docker takes to build the image
  4. Jenkinsfile - Defines the pipeline and each stage within it
  5. package.json - Defines metadata and dependencies for Node.js application
  6. script.sh - Lists commands that enable Jenkins to update the task definition and service running in the Amazon ECS cluster
  7. task-definition.json - Used by script.sh. Contains formatting necessary to make the new task definition machine readable
