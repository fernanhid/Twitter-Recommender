# Twitter User Recommender

This notebook details the approaches and the conclusions of building a twitter recommender.

<b>This notebook covers:</b>
1. Data Acquisition
2. Data Cleaning & Formatting
3. Training and Optimizing LDA
4. Detailing Next Steps

<b>Our Approach:</b>
1. Our approach was to get twitter data via the Twitter Search API and derive topics mentioned by a user.
2. Used Latent Dirichlet allocation derive the topics and optimized it using coherenc.
3. I found topics for the main user and 2nd degree users and found the ones with the highest overlaps.
4. The users were then ranked according to how many topics they have 2 words in common.

<b> Uses:</b>
1. This can be used to recommend followers to others based on the topics that folks talk about.
2. Via an app one can learn about others that have similar interests.

<b> Next Steps:</b>
1. Try RMF unsupervised learning
2. Optimize it to cut down the time
3. Get access to larger amounts of data
4. Build An App

### Aside from that, I hope you enjoy this notebook!