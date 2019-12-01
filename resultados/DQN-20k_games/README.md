1. Hyperparameters
   - ROM: Standard ROM
   - Epochs: 400 where 1 epoch = 50 games(total of 20k episodes)
   - Experience Replay Buffer size: 10K
   - Batch Size: 32
   - Gamma: 0.99
   - Lr: 10^-4
   - Epsilon decay over 100K steps from 1.0 to 0.02

2. Observations
   - Original reward function.
   - No reset if Mario is stuck.
   - Speed ~ 36 steps/s
   - Total elapsed time ~ 58 hs
