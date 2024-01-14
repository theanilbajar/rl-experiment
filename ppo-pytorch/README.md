## PPO Implementation for various enviroments with Gymnasium

## How to use this folder code
 
 ```
cd ppo-pytorch

# create and activate virtual env
virtualenv rl-env
source rl-env/bin/activate

# install libraries
pip install -r requirements.txt
 ```

## Trigger the learning process:

Assuming you're inside `ppo-pytorch`,

```
python main.py
```

It will create and save model weights to folders mentioned in the code i.e. `tmp/ppo`. It will also create plot of running average scores in `plots` folder. 

References:
- [Proximal Policy Optimization (PPO) is Easy With PyTorch | Full PPO Tutorial](https://www.youtube.com/watch?v=hlv79rcHws0)
- 