# AITurbo
Contains some experimental data

# Meaning of the data in the dataset.xlsx

In the dataset.xlsx, there are a total of 8692 rows of data, and each row represents a submitted job.

The meaning of each column is:

- Job type: There are a total of 27 types of distributed jobs, in which the model name used is unknown.

- Running time(second): The time from the start to the end of the job in the cluster

- Ps: The number of parameter servers used by the job

- Worker: The number of workers used in the job

- Epoch: The number of epochs for job training

- Accuracy: The accuracy of the final output of the job

- Loss: The corresponding loss value under the highest accuracy

- GPU: The number of GPUs used in the job

- Memory(GB): The number of memory used in the job 

- CPU: The number of CPUs used in the job 

- Batch Size: The amount of data processed by a job in a batch, one of the hyperparameters of the job

- Learning rate: One of the hyperparameters of job

- Step: The number of steps for job training

- Throughput: The amount of data processed by the job per unit time

- Resubmit: Whether the job is submitted repeatedly, 0 means the job is submitted repeatedly, and 1 is the first submission

- Predictability: Whether the job is predictable, 0 is predictable job, 1 is unpredictable job


# Distribution characteristics of jobs in the dataset.xlsx
<!--
- Job type and job number
Type| 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 | 12 | 13 | 14 | 15 | 16 | 17 | 18 | 19 | 20 | 21 | 22 | 23 | 24 | 25 | 26 | 27 
---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---
Number|339|456|466|227|370|404|327|303|404|372|338|604|401|384|273|512|330|247|501|150|291|42|138|215|46|37|525
-->

- Running time distribution


 <img src="https://github.com/LFSCODE/AITurbo/blob/main/figure/runtime.png" width = "400" height = "300" alt="图片名称" align=center />


- Ratio of predictable and unpredictable jobs

 <img src="https://github.com/LFSCODE/AITurbo/blob/main/figure/pre_unpre.png" width = "350" height = "300" alt="图片名称" align=center />

