﻿# Dataset
## How to use this project?
1. Preparations
2. Run Docker Compose
3. Create Output folder
4. Run Jupyter Notebook


### 1. Preparations
- **Clone repo** :
  ```
  git clone https://github.com/Kurikulum-Sekolah-Pacmann/data_pipeline_paccafe.git
  ```

- **Create env file** in project root directory :
  ```
  # Source
  SRC_POSTGRES_DB=...
  SRC_POSTGRES_HOST=...
  SRC_POSTGRES_USER=...
  SRC_POSTGRES_PASSWORD=...
  SRC_POSTGRES_PORT=...
  ```

### 2. Run Docker Compose :
  ```
  docker compose up -d
  ```
