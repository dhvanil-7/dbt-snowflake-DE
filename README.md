Data Engineering project with dbt and snowflake.

Follow below steps to setup the project:
1. Configure dbt profile for snowflake account. Create profiles.yml using reference of profiles.example.yml.
2. Update packages.yml based on requirements of the project.
3. Update dbt_project.yml based on requirements of the project.
4. Move to dbt_snowflake_de directory level and run "dbt debug" in command-line to check connection to the snowflake account.