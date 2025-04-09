# DMGDP

## Running ##


Running experiments based our code could be quite easy, so below we use `walker2d-medium-expert-v2` dataset as an example. 


For conducting 'offline model selection', run the code below. The best_score will be stored in the `best_score_offline.txt` file.
```.bash
python run.py --env_name walker2d-medium-expert-v2 --device 0 --kl_lambda 1.0 --f_div wgan --lr_decay

Hyperparameters for DMGDP have been reported in papers for easily reproducing our reported results. 
Definitely, there could exist better hyperparameter settings. Feel free to have your own modifications. 
