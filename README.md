# selenium_docker_runner_jenkins_job
Project that creates dockerized Selenium Grid and pulls the latest image that selenium_docker_builder_jenkins_job created, 
runs that image as a container, which results in the execution of tests on the dockerized Selenium Grid. 
Further, it brings the Selenium Grid down and provides generated TestNG reports in Jenkins, as well as all necessary environment variables. 
