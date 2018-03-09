# HER_Research
Trying various research ideas on OpenAI baselines HER algorithm.


## Experiments on existing enviroments and algorithms
We experimented with different hyperparameters on the robotics environment and the results can be found here. 
https://drive.google.com/open?id=1UIeB1r060VEJphE2i2FGyAgH2QC8FBHV 

We chose the hyperparameters based on these dicussions #311 https://github.com/openai/baselines/issues/311 and #314 https://github.com/openai/baselines/issues/314

The hyperparameters we varied are 
1. Number of cpu cores --num_cpu 
2. Minibatch_size --batch_size 
3. Number of rollouts per MPI worker --rollout_batch_size 
4. Number of epochs --n_epochs

