## Videos (10s each, MP4)
Early (near-random):
<video src="spaceinvaders_early_random.mp4" controls width="480"></video>

Later (emerging policy):
<video src="spaceinvaders_later_trained.mp4" controls width="480"></video>

## Notes
- **Training length:** ~50k timesteps (brief run)
- **Wrappers:** `AtariWrapper` + `VecFrameStack(4)` to match standard DQN preprocessing
- **Why Space Invaders?** It balances accuracy and dodging; rewards aren’t trivial and require reactive policy.

