# Word2vec-music-recommendation

Idea of using word2vec in recommendation and advertizing is illustrated in an article by
[Chris McCormick](http://mccormickml.com/2018/06/15/applying-word2vec-to-recommenders-and-advertising/).

Goal of the project is to build an effective word2vec-based music recommendation system, by 
translating user playlist into a word2vec-embedding, which utilizes the context of a track (other tracks)
to map similar songs close to each other [1]. T

## Prerequisites

Donwload the playlists dataset of #nowplaying project [2] from http://dbis-nowplaying.uibk.ac.at/.

`pip install numpy pandas sklearn gensim matplotlib`

## Example recommendation

![Screenshot](examplerec.PNG)

## References

[1] https://arxiv.org/pdf/1804.04212.pdf Caselles-Dupré, Hugo, Florian Lesaint, and Jimena Royo-Letelier. "Word2Vec applied to Recommendation: Hyperparameters Matter." arXiv preprint arXiv:1804.04212 (2018).

[2] https://www.evazangerle.at/wp-content/uploads/2017/06/somera15.pdf Pichl, Martin, Eva Zangerle, and Günther Specht. "Towards a context-aware music recommendation approach: What is hidden in the playlist name?." Data Mining Workshop (ICDMW), 2015 IEEE International Conference on. IEEE, 2015.





