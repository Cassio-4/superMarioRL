1. Parâmetros
   - ROM: Standard ROM
   - Epochs: 400 where 1 epoch = 50 games(total of 20k episodes)
   - Experience Replay Buffer size: 10K
   - Batch Size: 32
   - Gamma: 0.99
   - Lr: 10^-4
   - Epsilon decay over 100K steps até 0.02

2. Observações
   - Função de recompensa original.
   - Sem reset quando Mario fica preso.
   - Speed ~ 36 steps/s
   - tempo total ~ 58 hs
   - CONVERGIU!
