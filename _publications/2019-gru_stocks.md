---
title: "Gated Recurrent Unit Hierarchical Architecture for Fundamental Stock Analysis and Forecast"
collection: publications
category: conferences
permalink: /publication/2019-gru_stocks
excerpt: 'This work proposed a novel technique for fundamental analysis using GRU hierarchical models.'
date: 2019-01-01
venue: 'WAIAF (Workshop of Artificial Intelligence Applied to Finance) 2019'
paperurl: 'https://gam.dev/files/gru_stocks19.pdf'
slidesurl: 'https://gam.dev/files/gru_stocks19_slides.pdf'
citation: 'Gabriel Adriano Melo, Paulo Marcelo Tasinaffo. "Gated Recurrent Unit Hierarchical Architecture for Fundamental Stock Analysis and Forecast." Presented at the Workshop of Artificial Intelligence Applied to Finance 2019 (WAIAF 2019).'
---

Work Presented at the WAIF 2019 workshop (not officially published): [https://www.comp.ita.br/labsca/waiaf/](https://www.comp.ita.br/labsca/waiaf/).

This work proposed a novel technique for fundamental analysis using a shared, hierarchical neural network
model, based on the state-of-the-art Gated Recurrent Unit (GRU).
The model uses the quarterly reports to predict the mean stock
price at the next report, a three month ahead forecast based
on past performance. There are 3 hierarchical models in the
proposed architecture: the first is a general recurrent feature
extractor, that can be interpreted as an encoder, the second is a
specialized feedforward layer that captures the information from
companies in the same sector, the third is a highly specialized
logistic regression performed on the activations from the second
model, trained separately for each company. This structure
provides a solid background for transfer learning in which
multiple neural networks, one for each stock, has most of it
weights shared between its instances.
