---
title: "One-shot pruning of recurrent neural networks by jacobian spectrum evaluation"

weight: 10

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Bradley Stadie

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2019-11-01T00:00:00Z"
doi: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: International Conference on Learning Representations
publication_short: ICLR

abstract: 'Recent advances in the sparse neural network literature have made it possible to prune many large feed forward and convolutional networks with only a small quan- tity of data. Yet, these same techniques often falter when applied to the problem of recovering sparse recurrent networks. These failures are quantitative: when pruned with recent techniques, RNNs typically obtain worse performance than they do under a simple random pruning scheme. The failures are also qualitative: the distribution of active weights in a pruned LSTM or GRU network tend to be concentrated in specific neurons and gates, and not well dispersed across the entire architecture. We seek to rectify both the quantitative and qualitative issues with recurrent network pruning by introducing a new recurrent pruning objective derived from the spectrum of the recurrent Jacobian. Our objective is data efficient (requir- ing only 64 data points to prune the network), easy to implement, and produces 95 % sparse GRUs that significantly improve on existing baselines. We evaluate on sequential MNIST, Billion Words, and Wikitext.'

# Summary. An optional shortened abstract.
summary: We propose a method for generating sparse RNN parameterizations with minimum performance degradation. This relies on preservation of the temporal Jacobian spectrum, which measures information loss across long time horizons. This allows for more efficient parameter utilization in sequential learning environments.

tags: []

# Display this page in the Featured widget?
featured: true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  focal_point: "Center"
  preview_only: true

---
