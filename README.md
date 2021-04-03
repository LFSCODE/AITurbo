# AITurbo
Contains some experimental data

# Meaning of the data in the table

In the table, there are a total of 8692 rows of data, and each row represents a submitted job.

The meaning of each column is:

- Job type: There are a total of 27 types of distributed jobs, in which the model name used is unknown.

- Running time: The time from the start to the end of the job in the cluster

- Ps: The number of parameter servers used by the job

- Worker: The number of workers used in the job

- Epoch: The number of epochs for job training

- Accuracy: The accuracy of the final output of the job

- Loss: The corresponding loss value under the highest accuracy

- GPU: The number of GPUs used in the job

- Memory: The number of memory used in the job 

- CPU: The number of CPUs used in the job 

- Batch Size: The amount of data processed by a job in a batch, one of the hyperparameters of the job

- Learning rate: One of the hyperparameters of job

- Step: The number of steps for job training

- Throughput: The amount of data processed by the job per unit time

- Resubmit: Whether the job is submitted repeatedly, 0 means the job is submitted repeatedly, and 1 is the first submission

- Predictability: Whether the job is predictable, 0 is predictable job, 1 is unpredictable job
