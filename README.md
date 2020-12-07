# snake-reinforcement-learning

Snake game AI using deep Q-networks.
**Forked from https://github.com/choyi0521/snake-reinforcement-learning**.

## Training

Example:
```
python train.py --level_filepath levels/9x9_empty.yml
```
Refer to `python train.py -h` to see what arguments can be changed.

## Playing

Example:
```
python play.py --level_filepath levels/9x9_empty.yml --checkpoint best
```
Refer to `python play.py -h` to see what arguments can be changed.

## Results

Here are some good results.

9x9 empty:

![](./examples/empty.gif)

9x9 obstacles:

![](./examples/obstacles.gif)

9x13 double feed:

![](./examples/double_feed.gif)
