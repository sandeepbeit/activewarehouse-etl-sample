# ActiveWarehouse-ETL sample

This is a sample of ETL built on a very small data set (the rails git commit log) for educational purposes.

# How to run

More explanations will be added here later on. In the mean time:

    bundle install
    mysql -u root -p -e "create database aw_etl_sample_etl_execution"
    mysql -u root -p -e "create database aw_etl_sample_datawarehouse"
    bundle exec etl etl/process_all.ebf