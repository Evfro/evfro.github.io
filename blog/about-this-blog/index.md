<!--
.. title: About this blog
.. slug: about-this-blog
.. date: 2019-08-17 18:45:38 UTC+03:00
.. tags: blog
.. category: Blog
.. link:
.. description:
.. type: text
.. author: Evgeny Frolov
-->

## "Oh, not again..."

"*Is this yet another blog on machine learning containing ramblings on trivial topics and reincarnation of some dusty guides?*"
If this was one of your first thoughts, while being redirected to this website, then you are probably in the right place.

### General vision
One of the main motivations for me to start this blog was the desire to share and elaborate on underexplored or overlooked ideas with potentially high practical impact. I will be focusing primarily on the topic of **recommender systems** and will present ideas through the lens of my experience of working on both research and industrial projects. To some extent, it will have an anti-hype or anti-mainstream flavor. This means that sometimes I will revisit some good old concepts and attempt to make the most out of them. Check out my [tutorial on using SVD](link://slug/to-svd-or-not-to-svd) to get a glimpse of how it may look like.

As any personal blog, it is going be opinionated to a certain degree. In a sense, it will reflect my "eigen" values and views, hence the name "EigenTheories" (although, some people insist that I just misspelled the word "Eugene", which is a western variant of my name... who knows). It may also sometimes happen that I unknowingly present some common knowledge as a revelation. Shame on me in that case, and I will appreciate if you take time to tell me about that in the comments section!
On the other hand, in a fully authoritarian way, I also preserve the right to occasionally blog about some other not so fancy stuff (like how to configure this blog or how to make pandas work more efficiently), which is useful for my work and research. No complaints are accepted here.

### Values
From the scientific perspective, recommender systems is a vibrant interdisciplinary field with a whirling mix of math, engineering, behavioral sciences, philosophy, ethics, and even [quantum computing](https://www.quantamagazine.org/teenager-finds-classical-alternative-to-quantum-recommendation-algorithm-20180731/). Ok, the last one is more about grabbing your attention. There is an opinion that it does not add too much to what is already known from the cross approximation theory and the maximum volume approach. Nevertheless, the field of recommender systems provides many opportunities for attacking practical problems with math. Its beauty has never stopped fascinating me, even though I was never trained as a pure mathematician. I am always amazed by the elegance of solutions, achieved by an appropriate choice of mathematical abstractions and with the knowledge of some fundamental results. I hope to make this blog some sort of a tribute to that from a practical viewpoint.

### Commitments
Two aspects that I will try to commit to in this blog are rigorous experimentation and **reproducibility**. Such commitment means that from time to time there will be somewhat longish posts with a certain level of technical details seasoned with the source code. I will also write about reproducing others' results. I will be using [Polara](https://github.com/evfro/polara) – the recommender systems framework that helps to make reproducible research easier (disclaimer: I am the author). As an example, I invite you to verify at least some of the results from our recent paper [right in your browser](https://github.com/evfro/recsys19_hybridsvd)! No setup required. No excuses not to try.

I find reproducibility and openness of research especially important in spite of recent appraisal of many state-of-the-art methods based on both [neural networks](https://arxiv.org/pdf/1803.09587.pdf) and [classical algorithms](https://arxiv.org/pdf/1905.01395.pdf). As funny as it may sound, many modern SOTA algorithms have finally achieved the level of properly tuned decade-old baselines. Do not get me wrong, I am not trying to defy any of the recent achievements. In fact, I would be more than happy to have these achievements advance us to some new technological edges. It just requires a bit more of a careful work, in my opinion. The least I can do to help this situation is to point out some weak points that could be improved, make my own research transparent, and enable others to place my work under scrutiny. Hopefully, blogging will help me with that.

### Embracing uncertainty
Developing good recommender systems [is difficult](https://news.ycombinator.com/item?id=18377157) due to many uncertainties and even controversies in the decision making process modelling. There is even no agreement on how to perform quality evaluation and [how to reliably compare algorithms with each other](https://arxiv.org/pdf/1707.07435.pdf). Moreover, practitioners frequently observe a discrepancy between online A/B tests conducted with real users and offline verification on historical data, which is commonly used at initial phases of research. Of course, it does not mean that the recommender systems field is broken and doomed. It just shows that there is still **a lot to be learned**. This is a long journey, which I will be reflecting on down the road.

Probably, I have said more than enough already for introducing the blog. As a final remark, it won't be a regular blog with a weekly posts schedule. Crafting something interesting takes time and requires a tremendous amount of efforts. We will see how it goes. May the algorithms guide you.
