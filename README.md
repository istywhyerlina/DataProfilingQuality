# ELT With Python
## How to use this project?
2. Preparations
3. Run ELT Pipeline


### 2. Preparations
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

- **Run Data Sources** :
  ```
  docker compose up -d
  ```