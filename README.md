# Deep Reinforcement Learning Course

[![Deploy to GitHub Pages](https://github.com/phatcvo/Lec-DRL/actions/workflows/quarto-publish.yml/badge.svg)](https://github.com/phatcvo/Lec-DRL/actions/workflows/quarto-publish.yml)

**🌐 Website:** [https://phatcvo.github.io/Lec-DRL/](https://phatcvo.github.io/Lec-DRL/)

This comprehensive course covers the fundamental concepts and cutting-edge techniques in Deep Reinforcement Learning (DRL). From basic tabular methods to advanced deep learning approaches, you'll explore the complete landscape of modern RL.

## Course Content

The goal of this document is to keep track the state-of-the-art in deep reinforcement learning. It starts with basics in reinforcement learning and deep learning to introduce the notations and covers different classes of deep RL methods, value-based or policy-based, model-free or model-based, etc.

Different classes of deep RL methods can be identified. This document will focus on the following ones:

- **Value-based algorithms** (DQN…) used mostly for discrete problems like video games.
- **Policy-gradient algorithms** (A3C, DDPG…) used for continuous control problems such as robotics.
- **Recurrent attention models** (RAM…) for partially observable problems.
- **Model-based RL** to reduce the sample complexity by incorporating a model of the environment.

## Development

This website is built using [Quarto](https://quarto.org/) and automatically deployed to GitHub Pages.

### Local Development

1. Install [Quarto](https://quarto.org/docs/get-started/)
2. Clone this repository
3. Run `quarto render` to build the website
4. Run `quarto preview` to preview locally

### Deployment

The website is automatically deployed to GitHub Pages when changes are pushed to the main branch using GitHub Actions.
Application of deep RL to robotics
One could extend the list and talk about hierarchical RL, inverse RL, imitation-based RL, etc…