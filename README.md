Reinforcement Learning for Flappy Bird in JS
===================

<img src="https://raw.githubusercontent.com/nileshsah/reinforcement-learning-flappybird/master/images/high-score.png?token=AJ-IX5fex3nle8myzjXQyWzlA-1-rOZqks5ZoGimwA%3D%3D" width="256" height="256"/>

A project aimed to explain reinforcement learning in the most simplistic way ever possible by training a _32px by 32px_ game of flappy bird using Q-learning through a script written purely in JavaScript.

The script [`js/brain.js`](js/brain.js) is where the learning logic resides and has been documented heavily to explain the baseline Q-learning algorithm from scratch and how it can be applied in a real-time scenario.

With everything written solely in JS, the game can be trained and tested right inside our browser with no external dependencies at all. You can witness how the bird learns to play the game in real-time by visiting the link:  [`http://nileshsah.github.io/reinforcement-learning-flappybird/`](http://nileshsah.github.io/reinforcement-learning-flappybird/) ¯\\_(ツ)_/¯

In an ideal scenario, the bird learns to operate upon a static non-volatile environment in mere 25 trials of the game while for a randomized environment it might take up to 1000+ trials.

### Further Reading
---

`[1]` http://people.revoledu.com/kardi/tutorial/ReinforcementLearning/

`[2]` https://medium.com/emergent-future/simple-reinforcement-learning-with-tensorflow-part-0-q-learning-with-tables-and-neural-networks-d195264329d0

`[3]` https://www.cs.toronto.edu/~vmnih/docs/dqn.pdf






