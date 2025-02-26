# E-commerce Analytics dbt Project

This is an example dbt project: 
I transform raw e-commerce data into analytics-ready models.
The project showcases key dbt features including:

- **Modular model design**: Using staging, intermediate, and mart layers
- **Data testing and validation**: Testing primary keys, foreign keys, and business logic
- **Documentation**: Comprehensive documentation for all models
- **Custom macros**: Reusable code snippets
- **Snapshots**: Type 2 slowly changing dimension tracking
- **Seeds**: Static reference data
- **Analysis**: Ad-hoc analytical queries

## Data Model

![Data Model Diagram](assets/data_model.png)

## Project Structure

The project follows the recommended dbt project structure:

- **Staging models**: Clean and standardize source data
- **Intermediate models**: Perform complex transformations
- **Mart models**: Create business-ready dimensional models
- **Core mart models**: General purpose dimensional tables
- **Marketing mart models**: Marketing-specific analytical tables

## Features Demonstrated

1. **Source freshness testing**: Monitoring data pipeline health
2. **Custom schema generation**: Environment-specific schema handling
3. **Package dependencies**: Leveraging community packages
4. **Custom tests**: Business-specific validation logic
5. **Materializations**: Views, tables, and ephemeral models
6. **Documentation**: YAML-based model documentation
7. **Snapshots**: Type 2 SCD pattern