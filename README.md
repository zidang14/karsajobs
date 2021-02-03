Karsajobs
=============================
Karsajobs is simple jobs application written in Go.

## Configuration
Karsajobs read configuration from environtment variable

| ENV        |      Description                 |
|------------|:---------------------------------|
| APP_PORT   | run karsajobs in spesific port   |
| MONGO_HOST | mongodb hostname                 |
| MONGO_USER | mongodb user                     |
| MONGO_PASS | mongodb password                 |


  
## Endpoint
- /jobs
  - `GET` get list job
- /job
  - `POST` create a job  
- /job/id
  - `GET` get job
  - `DELETE` delete job