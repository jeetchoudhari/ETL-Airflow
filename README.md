# ETL-Airflow

### Overview


### What is Astro(Astronomer IO)?
- Platform which manages Airflow

### What is Airflow
- Opensource platform used to build ETL pipelines(Schedule, run pipeline)
- Orchestrates workflows as Directed Acyclic Graphs (DAGs)
- Schedules tasks (hourly, daily)
- Manages task dependencies ensuring they run in the correct order
- Monitors execution with a real-time web UI

### Steps
1. Install Astro
2. Create folder -> Initialize empty project(astro dev init)
3. Create new py file in dags
4. Write ETL code (functions, tasks)
5. Create Docker compose file
6. Run "astro dev start"
7. Airflow interface will open
8. Make connections in Admin (postgres, weather_api_meteo connection)
9. Run the workflow(or schedule it)
10. Check database if data in loaded

### Files
Python File: This file will define the tasks for extracting weather data, transforming it, and loading it into PostgreSQL.
Docker Compose File: This will define the Docker containers for Airflow, PostgreSQL, and any other dependencies.
Dockerfile: A Dockerfile for the Airflow setup to ensure it has the necessary dependencies.

![image](https://github.com/user-attachments/assets/51787ebe-0ddf-4485-bd7d-05dcd31e688c)
