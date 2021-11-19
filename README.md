# data_sciences_exercises
En este repositorio realizare diferentes practicas para realizar el EDA en un modelo.
Utilizare el dataet de kaggle de HR Analytics: Job Change of Data Scientists
- https://www.kaggle.com/arashnic/hr-analytics-job-change-of-data-scientists/tasks?taskId=3015

## Features
- enrollee_id : Unique ID for candidate
- city: City code
- city_ development _index : Developement index of the city (scaled)
- gender: Gender of candidate
- relevent_experience: Relevant experience of candidate
- enrolled_university: Type of University course enrolled if any
- education_level: Education level of candidate
- major_discipline :Education major discipline of candidate
- experience: Candidate total experience in years
- company_size: No of employees in current employer's company
- company_type : Type of current employer
- lastnewjob: Difference in years between previous job and current job
- training_hours: training hours completed
- target: 0 – Not looking for job change, 1 – Looking for a job change

## EDA FILE NOTEBOOK
El archivo contiene informacion de como eliminar o completar valores nulos
Adicionalmente contiene las visualizaciones graficas clasicas para analizar cada variable, numerica, categorica y el target respectivo

## FEATURE ENGINEER FILE NOTEBOOK
En el documento encontraran las posibles transformaciones que tendran los features

Me estoy basando del siguiente repositorio de github:
https://github.com/solegalli/feature-engineering-for-machine-learning