# Open-source implementation for KDD '24 paper: Achieving A Better Tradeoff in Multi-stage Recommender Systems Through Personalization

## Abstract

Recommender systems in social media websites provide value to their communities by recommending engaging content and meaningful connections. Scaling high-quality recommendations to billions of users in real-time requires sophisticated ranking models operating on a vast number of potential items to recommend, becoming prohibitively expensive computationally. A common technique "funnels" these items through progressively complex models ("multi-stage"), each ranking fewer items but at higher computational cost for greater accuracy. This architecture introduces a trade-off between the cost of ranking items and providing users with the best recommendations. A key observation we make in this paper is that, all else equal,  ranking more items indeed improves the overall objective but has diminishing returns. Following this observation, we provide a rigorous formulation through the framework of DR-submodularity, and argue that for a certain class of objectives (reward functions), it is possible to improve the trade-off between performance and computational cost in multi-stage ranking systems with strong theoretical guarantees. We show that this class of reward functions that provide this guarantee is large and robust to various noise models. Finally, we describe extensive experimentation of our method on three real-world recommender systems in Facebook, achieving 8.8% reduction in overall compute resources with no significant impact on recommendation quality, compared to a 0.8\% quality loss in a non-personalized budget allocation.

## Usage

Load the notebook on your favorite Jupyter notebook hosting service.

See the [CONTRIBUTING](CONTRIBUTING.md) file for how to help out.

## License

This project is [CC-BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/) licensed, as found in the LICENSE file.
