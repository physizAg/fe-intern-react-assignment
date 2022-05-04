# PhyFarm's Front End Intern Program's React Assignment

### Objective
Build a Single Page App on React to fetch sensor data from SQL, and plot it on a graph.

### Brief
A React App to display a graph, which pulls data from SQL to display a line graph for sensor data.
The SQL DB can have a table which stores a timestamp, sensor value, for example, the temperature.

A script to populate the SQL DB with random data should be running in a cron. 
A cron to update the graph with the new incoming data should exist.

### Tech
Use React, and as few external libraries as possible.
Either MySQL or PostgreSQL can be used.

### Evaluation Criteria
The exercise is graded against 7 criteria. We're looking for code that is clean, readable, performant and maintainable.
- [ ] Clean, modular code
- [ ] Comments explaining decisions and complex workflows
- [ ] Coding standards, naming conventions
- [ ] Feature coverage
- [ ] Handle as many edge cases as possible
- [ ] Dockerized code
- [ ] Test coverage

Not all features need to be implemeneted, we will be focusing on the approach used to write the codebase. 
Ensure minimal efforts are needed to run the codebase on our end, by using Docker (or even better, Docker Compose).

### Bonus 
- [ ] Docker Compose (The React App and the SQL Server)
- [ ] Real Time Graphs (Data should update on inserts in SQL)
- [ ] Multiple Sensor Data on the same graph 

### Submission
Create a PR to the same repo, with the branch name as your full name with - as a delimeter.
The SQL service should be maintained in the shared codebase. Scripts for table creation, data writes should be included.  
