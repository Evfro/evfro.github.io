<!--
.. title: About this blog
.. slug: about-this-blog
.. date: 2019-08-17 18:45:38 UTC+03:00
.. tags:
.. category: Blog
.. link:
.. description:
.. type: text
.. author: Evgeny Frolov
-->
# "Oh, not again..."
"Is this yet another blog on machine learning containing ramblings on trivial topics and the 100th reincarnation of some dusty ML guides?"
If this was one of your first thoughts when visiting this web-site for the first time, then you're probably in the right place.

One of the main motivations for me to start this blog was the desire to share and elaborate on ideas with potentially high practical impact, which yet somehow remained underexplored or overlooked. I'll be focusing primarily on the topic of **recommender systems** and will present ideas through the lens of my experience of working on both research and industrial projects. To some extent, it will have an anti-hype or anti-mainstream flavor. This means that I'll revisit some of the good 'ol concepts and attempt to make the most out of them. Check my [tutorial on using SVD](link://slug/to-svd-or-not-to-svd) as an example.

As any personal blog, it is going be opinionated to a certain degree in a sense that it will reflect my "eigen" values and views, hence the name "eigentheories" (some people insist that I simply misspelled "Eugene", which is a western variant of my name... who knows). It may sometimes happen that I unknowingly present some common knowledge as a revelation. Shame on me in that case and I welcome you to tell me about that in the comments section!
On the other hand, in a fully authoritarian way, I also preserve the right for myself to occasionally blog about some other not so fancy stuff (like how to configure this blog or how to make pandas work more efficiently), which is useful for my work and research. No complaints are accepted here.

Recommender systems is a vibrant interdisciplinary field with a whirling mix of math, engineering, behavioral sciences, philosophy, ethics, and even [quantum computing](https://www.quantamagazine.org/teenager-finds-classical-alternative-to-quantum-recommendation-algorithm-20180731/). Ok, the last one is more about bringing your attention. There's an opinion that it doesn't add too much to what is already known from the cross approximation theory and the maximum volume approach. Anyway, the field of recommender systems provides a lot of opportunities for attacking practical problems with the **pure math**. Even though I wasn't trained as a pure mathematician, it doesn't prevent me from getting fascinated by the beauty of math. The elegance of solutions, which can be achieved with an appropriate choice of mathematical abstractions and with the knowledge of some fundamental results, is astonishing. I hope to make this blog some sort of a tribute to that as well.

Another two aspects that will receive a lot of attention in this blog are rigorous experimentation and **reproducibility**. I'll do my best to provide substantial evidence to support my conclusions. This means somewhat longish posts from time to time with a certain level of technical details seasoned with the source code. I'll also write about reproducing others results. In most of the tutorials I'll be using [Polara](https://github.com/evfro/polara) -- the recommender systems framework designed to make reproducible research easier (I'm the author). As an example, I invite you to verify at least some of the results from our recent paper [right in your browser!](https://github.com/evfro/recsys19_hybridsvd). No setup required. No excuses not to try.

I find reproducibility and openness of research especially important in spite of recent appraisal of many state-of-the-art methods based on both [neural networks](https://arxiv.org/pdf/1803.09587.pdf) and [classical algorithms](https://arxiv.org/pdf/1905.01395.pdf). As funny as it may sound, many modern SOTA algorithms have finally achieved the level of properly tuned decade-old baselines. Don't get me wrong, I'm not trying to defy any of the recent achievements. In fact, I'd be more than happy to have these achievements advance us to the new edges of technology. It just requires a bit more careful work, in my opinion. The least I can do to help this situation is to point out some weak points that could be improved, provide all the details of the experimental setup in my own research and make it easier for others to place my work under scrutiny. My hope is that blogging will help me with that.

What makes recommender systems field especially difficult, is that it's full of uncertainties and even controversies stemming from the very nature of decision process modelling. There's even no agreement on how to perform quality evaluation and how to reliably compare algorithms with each other [link to DL paper]. It gets only worse due to a discrepancy between online A/B tests on real users and offline tests on historical data. This, of course, doesn't mean that the recommender systems field is broken and doomed. It just shows that there's still a lot to be learned there.

Probably, I've said more than enough already for introducing the blog. As a final remark, it won't be a regular blog with a weekly post schedule. Crafting something interesting takes time and requires a tremendous amount of efforts.  I still hope that it will be worth your reading.
