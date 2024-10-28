
Steps:
 In the terminal run the following commands to setup input data, run etl and run tests.

```bash
# setup input data
python ./setup/create_input_data.py
# run pipeline
python de_project/run_pipeline.py
# run tests
python -m pytest de_project/tests/unit/test_dim_customer.py
```

