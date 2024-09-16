Welcome to your new dbt project!

### Using the starter project

Try running the following commands:
- dbt run: To run data modelling scrips.
- dbt test: To test configured generic and singular tests.


### Resources:
- Learn more about dbt [in the docs](https://docs.getdbt.com/docs/introduction)
- Check out [Discourse](https://discourse.getdbt.com/) for commonly asked questions and answers
- Join the [chat](https://community.getdbt.com/) on Slack for live discussions and support
- Find [dbt events](https://events.getdbt.com) near you
- Check out [the blog](https://blog.getdbt.com/) for the latest news on dbt's development and best practices


### Identify components:
* <b>dbt_packages</b>: The location where packages defined in packages.yml get installed.
* <b>logs</b>: Logs are stored during the dbt execution.
* <b>macros</b>: Helps to implement DRY(Do not Repeat Yourself) code. You can define function and utilize in models.
* <b>[seeds](https://docs.getdbt.com/docs/build/seeds)</b>: Helps to maintain refernce data which does not change frequently with time. One can refer seeds as static data.
* <b>[snapshots](https://docs.getdbt.com/docs/build/snapshots)</b>: Dbt snapshots the models 
* <b>target</b>: It stores compiled sql queries which can be referenced by DEs to verify ETL logics.