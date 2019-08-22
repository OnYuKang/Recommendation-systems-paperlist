# Recommendation_systems_paperlist ![GitHub stars](https://img.shields.io/github/stars/OnYuKang/Recommendation-systems-paperlist.svg?style=plastic) ![GitHub forks](https://img.shields.io/github/forks/OnYuKang/Recommendation-systems-paperlist.svg?color=black&style=plastic) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

## Survey paper
* Recommender systems survey [Knowledge-based systems 2013]
* Deep Learning based Recommender System: A Survey and New Perspectives [2017]
* A Survey on Session-based Recommender System [2019] [[__pdf__](https://arxiv.org/pdf/1902.04864.pdf)]

## Recommendation Systems with Social Information 
* SoRec: Social Recommendation Using Probabilistic Matrix Factorization [CIKM 2008]
* A Matrix Factorization Technique with Trust Propagation for Recommendation in Social Networks [RecSys 2010]
* Recommender systems with social regularization [WSDM 2011]
* On Deep Learning for Trust-Aware Recommendations in Social Networks [IEEE 2017]
* Learning to Rank with Trust and Distrust in Recommender Systems [RecSys 2017]
* Social Attentional Memory Network: Modeling Aspect- and Friend-level Differences in Recommendation [WSDM 2019]
    - code : https://github.com/chenchongthu/SAMN
* Session-based Social Recommendation via Dynamic Graph Attention Networks [WSDM 2019]
  - code : https://github.com/DeepGraphLearning/RecommenderSystems/tree/master/socialRec
* Dual Graph Attention Networks for Deep Latent Representation of Multifaceted Social Effects in Recommender Systems [WWW 2019]
* Heterogeneous Graph Attention Network [WWW 2019]
* Graph Neural Networks for Social Recommendation [WWW 2019]
* GhostLink: Latent Network Inference for Influence-aware Recommendation [WWW 2019]
* SamWalker: Social Recommendation with Informative Sampling Strategy [WWW 2019]

## Recommendation Systems with Text Information
  ### Topic-based approach
  * Collaborative topic modeling for recommending scientific articles [KDD 2011]
    - code : https://github.com/blei-lab/ctr
  * Hidden factors and hidden topics: understanding rating dimensions with review text [RecSys 2013]
    - code : https://github.com/lipiji/HFT
  * Jointly modeling aspects, ratings and sentiments for movie recommendation [KDD 2014]
    - code : https://github.com/nihalb/JMARS
  * Ratings meet reviews, a combined approach to recommend [RecSys 2014]
  * Exploring User-Specific Information in Music Retrieval [SIGIR 2018]
  * Aspect-Aware Latent Factor Model: Rating Prediction with Ratings and Reviews [WWW 2018]
    - code : https://github.com/hustlingchen/ALFM
  * Exploiting Ratings, Reviews and Relationships for Item Recommendations in Topic Based Social Networks [WWW 2019]
  
  ### Deep learning-based approach
  * Collaborative deep learning for recommender systems [KDD 2015]
    - code : https://github.com/js05212/CDL
  * Convolutional Matrix Factorization for Document Context-Aware Recommendation [RecSys 2016]
    - code : https://github.com/cartopy/ConvMF
  * Joint Deep Modeling of Users and Items Using Reviews for Recommendation [WSDM 2017]
    - code : https://github.com/chenchongthu/DeepCoNN
  * Transnets: Learning to transform for recommendation [RecSys 2017]
    - code : https://github.com/rosecatherinek/TransNets
  * Latent Cross: Making Use of Context in Recurrent Recommender Systems [WSDM 2018]
  * Coevolutionary Recommendation Model: Mutual Learning between Ratings and Reviews [WWW 2018]
  * Neural Attentional Rating Regression with Review-level Explanations [WWW 2018]
    - code : https://github.com/chenchongthu/NARRE
  * Learning Personalized Topical Compositions with Item Response Theory [WSDM 2019]
  * Uncovering Hidden Structure in Sequence Data via Threading Recurrent Models [WSDM 2019]
  * Gated Attentive-Autoencoder for Content-Aware Recommendation [WSDM 2019]
    - code : https://github.com/allenjack/GATE
    
    
## Explainable Recommendation Systems
* Social Collaborative Viewpoint Regression with Explainable Recommendations [WSDM 2017]
* Explainable Recommendation via Multi-Task Learning in Opinionated Text Data [SIGIR 2018]
* TEM: Tree-enhanced Embedding Model for Explainable Recommendation [WWW 2018]

## Session-Based Recommendation Systems
### Markov-chain based approach
* Factorizing Personalized Markov Chains for Next-Basket Recommendation [WWW 2010]
* Where You Like to Go Next: Successive Point-of-Interest Recommendation [IJCAI 2013]
* Learning Hierarchical Representation Model for NextBasket Recommendation [SIGIR 2015]
* Fusing Similarity Models with Markov Chains for Sparse Sequential Recommendation [ICDM 2016]

### RNN based approach
* Session-based Recommendations with Recurrent Neural Networks [ICLR 2016]
  - code : https://github.com/hidasib/GRU4Rec
* Neural Attentive Session-based Recommendation [CIKM 2017]
  - code : https://github.com/lijingsdu/sessionRec_NARM
* Personalizing Session-based Recommendations with Hierarchical Recurrent Neural Networks [RecSys 2017]
* When Recurrent Neural Networks meet the Neighborhood for Session-Based Recommendation [RecSys 2017]
* Modeling User Session and Intent with an Attention-based Encoder-Decoder Architecture [RecSys 2017]
* Learning from History and Present: Next-item Recommendation via Discriminatively Exploting Users Behaviors [KDD 2018]
* Recurrent Neural Networks with Top-k Gains for Session-based Recommendations [CIKM 2018]
* Hierarchical Context enabled Recurrent Neural Network for Recommendation. [AAAI 2019] 
* RepeatNet: A Repeat Aware Neural Recommendation Machine for Session-based Recommendation [AAAI 2019]
  - code : https://github.com/PengjieRen/RepeatNet
* Time is of the Essence: a Joint Hierarchical RNN and Point Process Model for Time and Item Predictions [WSDM 2019]
  - code : https://github.com/BjornarVass/Recsys
* Predicting Dynamic Embedding Trajectory in Temporal Interaction Networks [KDD 2019]
* AIR: Attentional Intention-Aware Recommender Systems [ICDE 2019]

### CNN based approach 
* 3D Convolutional Networks for Session-based Recommendation with Content Features [RecSys 2017]
* Personalized Top-N Sequential Recommendation via Convolutional Sequence Embedding [WSDM 2018]
  - code : https://github.com/graytowne/caser_pytorch [Pytorch]
  - code : https://github.com/graytowne/caser [Matlab]
* Hierarchical Temporal Convolutional Networks for Dynamic Recommender Systems [WWW 2019]
* A Simple Convolutional Generative Network for Next Item Recommendation [WSDM 2019]
  - code : https://github.com/graytowne/caser_pytorch
  
### Graph based approach
* Billion-scale Commodity Embedding for E-commerce Recommendation in Alibaba [KDD 2018]
* Graph Convolutional Neural Networks for Web-Scale Recommender Systems [KDD 2018]
* Session-based Recommendation with Graph Neural Networks [AAAI 2019]
  - code : https://github.com/CRIPAC-DIG/SR-GNN
* Session-based Social Recommendation via Dynamic Graph Attention Networks [WSDM 2019]
  - code : https://github.com/DeepGraphLearning/RecommenderSystems/tree/master/socialRec  

### Other approach
* Diversifying Personalized Recommendation with User-session Context [IJCAI 2017]
* Attention-Based Transactional Context Embedding for Next-Item Recommendation [AAAI 2018]
* STAMP: Short-Term Attention/Memory Priority Model for Session-based Recommendation [KDD 2018]
  - code : https://github.com/uestcnlp/STAMP
* Self-Attentive Sequential Recommendation [ICDM 2018]
  - code : https://github.com/kang205/SASRec
* Taxonomy-aware Multi-hop Reasoning Networks for Sequential Recommendation [WSDM 2019]
  - code : https://github.com/RUCDM/TMRN
* Hierarchical Neural Variational Model for Personalized Sequential Recommendation [WWW 2019]

### News Recommendation
* Google news personalization: scalable online collaborative filtering [WWW 2007]
* Personalized News Recommendation Based on Click Behavior [IUI 2009]
* Personalized News Recommendation Using Twitter [IEEE 2013]
* Recommending Personalized News in Short User Sessions [RecSys 2017]
* Embedding-based News Recommendation for Millions of Users [KDD 2017]
* DKN: Deep Knowledge-Aware Network for News Recommendation [WWW 2018] 

### Video Recommendation
* Video suggestion and discovery for youtube: taking random walks through the view graph [WWW 2008]
* The YouTube Video Recommendation System [RecSys 2010]
* Deep Neural Networks for YouTube Recommendations [RecSys 2016]
* Wide & Deep Learning for Recommender Systems [DLRS 2016]
* Content-based Related Video Recommendations [NIPS 2016]

### Music Recommendation
* Playlist prediction via metric embedding [KDD 2012]
* Deep content-based music recommendation [NIPS 2013]
* Improving Content-based and Hybrid Music Recommendation using Deep Learning [MM 2014]
* Content-aware collaborative music recommendation using pre-trained neural networks [ISMIR 2015] 

### Image Recommendation
* Pagerank for product image search [WWW 2008]
* Related Pins at Pinterest: The Evolution of a Real-World Recommender System [WWW 2017]
* Pixie: A System for Recommending 3+ Billion Items to 200+ Million Users in Real-Time [WWW 2018]

## Time-aware Recommendation (Temporal Dynamics)
* Time Weight Collaborative Filtering [CIKM 2005]
* Collaborative Filtering with Temporal Dynamics [KDD 2009]
* Opportunity Models for E-commerce Recommendation: Right Product, Right Time [SIGIR 2013] 
* Multi-rate deep learning for temporal recommendation [SIGIR 2016]
* Recurrent Recommender Networks [WSDM 2017]
* Recurrent Recommendation with Local Coherence [WSDM 2019]

## Multi-Armed Bandit
* A Contextual-Bandit Approach to Personalized News Article Recommendation [WWW 2010]
* A survey of online experiment design with the stochastic multi-armed bandit [2015] [[__pdf__](https://arxiv.org/pdf/1510.00757.pdf)]
* Collaborative filtering as a multi-armed bandit [NIPS 2015]
* Online Context-Aware Recommendation with Time Varying Multi-Arm Bandit [KDD 2016]
* Collaborative Filtering Bandits [SIGIR 2016]

## Out of Category
* Learning Multiple Similarities of Users and Items in Recommender Systems [ICDM 2017]
* Neural Collaborative Filtering [WWW 2017]
* MRNet-Product2Vec: A Multi-task Recurrent Neural Network for Product Embeddings [ECML-PKDD 2017]
* A Gradient-based Adaptive Learning Framework for Efficient Personal Recommendation [RecSys 2017]
* IRGAN: A Minimax Game for Unifying Generative and Discriminative Information Retrieval Models [SIGIR 2017]
  - code : https://github.com/geek-ai/irgan
* Collaborative Memory Network for Recommendation Systems [SIGIR 2018]
  - code : https://github.com/tebesu/CollaborativeMemoryNetwork
* Variational Autoencoders for Collaborative Filtering [WWW 2018]
* Latent Relational Metric Learning via Memory-based Attention for Collaborative Ranking [WWW 2018]
* Causal Embeddings for Recommendation [RecSys 2018] 
  - https://github.com/criteo-research/CausE
* Linked Variational AutoEncoders for Inferring Substitutable and Supplementary Items [WSDM 2019]
  - https://github.com/VRM1/WSDM19
* RecWalk: Nearly Uncoupled Random Walks for Top-N Recommendation [WSDM 2019]
  - https://github.com/nikolakopoulos/RecWalk

