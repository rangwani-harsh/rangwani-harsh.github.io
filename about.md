---
layout: page
title: About Me
permalink: /about/
redirect_from:
  - /
---







<img style = "float: right;" src="../me.jpg" width="192" height="192" title="Image">
  

I am Harsh Rangwani, ~~third~~ fourth year PhD student at Department of Computational and Data Science (CDS) at Indian Institute of Science. I am very fortunate to be advised by [**Prof.** **Venkatesh Babu**](http://cds.iisc.ac.in/faculty/venky/). Currently I am working on intersection of Machine Learning and Computer Vision. I am supported by [**Prime Minister's Research Fellowship**](http://pmrf.in/) in Computer Science. I previously completed an honors degree in Computer Science being jointly advised by [**Dr**. **Rajeev** **Sangal**](https://faculty.iiit.ac.in/~sangal/web/) and [**Dr**. **A**.**K**. **Singh**](https://faculty.iiit.ac.in/~sangal/web/) at Department of Computer Science, IIT BHU Varanasi. In the past I have interned with Amazon in Outbound Marketing Automtation team and also have been the lead maintainer of the placement portal [site](www.placement.iitbhu.ac.in). In my free time I like to read books and play basketball. 

### News

{% for article in site.data.news limit:9 %}
{{ article.date }} :
<em>{{ article.headline }}</em>
{% endfor %}
<a href="{{ site.url }}{{ site.baseurl }}/news">see all news</a>


### Research Interests:
I am broadly intereseted in Deep Learning algorithms that train and generalize well on real-world datasets, having presence of class-imbalances and distribution shifts. I use deep learning frameworks like PyTorch, Tensorflow etc. to develop algorithms, and techniques from statistics, optimization theory and information theory to analyze them. I am currently exploring applications in the domain of Computer Vision.


<!-- My research interest lies in the field of Adversarial Machine Learning. Specifically, I am interested in problems that involve min-max optimizations. Adversarial Learning is the common theme behind the following techniques Generative Adversarial Networks, Adversarial Training for robust Neural Networks, Adversarial Domain Adaptation, etc. As a long-term goal, I want to develop ML algorithms that train and generalize well on real-world datasets. Currently, I am working on Generative Adversarial Networks where I want to tackle the case of learning from imbalanced datasets. Along with this, I am also focusing on analyzing the nature of practical min-max optimization methods used in Deep Learning. 

 ### Courses completed in IISc (GPA: 9.83) :
- Pattern Recognition and Neural Networks 
- Game Theory
- Deep Learning for Computer Vision
- Advanced Image Processing
- Stochastic Methods and Applications
- Video Analytics

-->



Here is my detailed [CV](cv_updated.pdf).




### Contact me

[harsh.rangwani](mailto:harshr@iisc.ac.in)
