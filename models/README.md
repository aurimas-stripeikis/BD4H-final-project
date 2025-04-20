Running the models
==================================

Once you have unpacked the data in eICU, you can run all the models in your terminal. Set the working directory to the TPC-LoS-prediction, and run the following:

    ```
    python3 -m models.run_tpc
    ```
    
    ```
    python3 -m models.run_transformer
    ```
    
    ```
    python3 -m models.run_lstm
    ```
    
    Each experiment you run will create a directory within models/experiments. The naming of the directory is based on 
    the date and time that you ran the experiment (to ensure that there are no name clashes). The experiments are saved 
    in the standard trixi format: https://trixi.readthedocs.io/en/latest/_api/trixi.experiment.html.
    

