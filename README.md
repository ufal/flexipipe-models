# flexiPipe Models

This repository provides information about available models to use with the [flexiPipe](https://github.com/ufal/flexipipe) NLP pipeline. flexiPipe can run NLP pipelines using a number of different backends, including most of the well-established NLP frameworks 
such as [SpaCy](https://spacy.io/), [UDPIPE](https://lindat.mff.cuni.cz/services/udpipe/), [NameTag](https://lindat.mff.cuni.cz/services/nametag/), [HuggingFace transformers](https://huggingface.co/docs/transformers/index), and [Stanza](https://stanfordnlp.github.io/stanza/). 
This repository provides two things: a central list of all the models for those backends where they need one and do not provide one, as well as additional models made available by the community in publicly accessible repositories. And additional models
for those backends that were trained using flexipipe, or provided by the community and hosted here. The models listed can of course also be used directly in the tools they belong to without the use of flexiPipe.

Available models that are not listed in the repository can be mentioned in the issues, and after verification will be added. And people interested in training new models on training data they either build themselves are acquired can do so using one of the backends listed or
using flexiPipe as a single entry training point for various backends. And they can use [UDMorph](https://lindat.mff.cuni.cz/services/teitok-live/udmorph/) to create new training data in a guided fashion, where UDMorph now uses flexiPipe as the backend to train models on 
the training data created in UDMorph.