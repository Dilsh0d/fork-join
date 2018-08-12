# Fork/join framework use select&inset from big table
> Task Description ETL (Extract Transform Load). <br/>
`Task consist of 3 steps.`
1. extract - during this step data loaded from source table.
2. transform - during this step data is processed (removed duplicates, added/merged missing information from existing records, removed unused
records, parse/correct existing data). After transform source table should contain one cleaned record which contains all information of previous
records.
3. load - load processed information into destination table.
Application should store actual state of processing, in case of stop or death should be able to restart process from stopped location and state.
Additional resources/tables for processing can be created.
