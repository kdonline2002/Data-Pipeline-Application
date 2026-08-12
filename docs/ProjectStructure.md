# Project Structure

## DataPipeline

```text
DataPipeline/
│
├── app.py
├── config.py
│
├── import/
│   ├── excel_loader.py
│   └── sql_importer.py
│
├── api/
│   ├── address_validation.py
│   └── Google_Map_Api.py
│
├── transform/
│   ├── data_processing.py
│   ├── json_flatten.py
│   └── PowerBI_Prep.py
│
├── dashboards/
│   ├── streamlit_address_validation.py
│   ├── streamlit_geocoding.py
│   └── PowerBI_Data_Pipeline.pbix
│
├── sql/
│   ├── 01_Create_Tables.sql
│   ├── 02_Create_Indexes.sql
│   └── 03_Create_StoredProcedures.sql
│
└── README.md

```

