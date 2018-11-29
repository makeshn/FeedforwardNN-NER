# Named Entity Recognition

[Named Entity Recognition](https://en.wikipedia.org/wiki/Named-entity_recognition) is one of the most common [NLP](https://en.wikipedia.org/wiki/Natural-language_processing) problems. The goal is classify named entities in text into pre-defined categories such as the names of persons, organizations, locations, expressions of times, quantities, monetary values, percentages, etc.
*What can you use it for?* Here are a few ideas - social media, chatbot, customer support tickets, survey responses, and data mining!

### Try it now

[![Run on FloydHub](https://static.floydhub.com/button/button.svg)](https://floydhub.com/run?template=https://github.com/floydhub/named-entity-recognition-template)

Click this button to open a Workspace on FloydHub that will train this model.

### Predicting named entities of GMB(Groningen Meaning Bank) corpus


Entity tags are encoded using a BIO annotation scheme, where each entity label is prefixed with either B or I letter. B- denotes the beginning and I- inside of an entity. The prefixes are used to detect multiword entities, e.g. sentence:"World War II", tags:(B-eve, I-eve, I-eve). All other words, which don’t refer to entities of interest, are labeled with the O tag.

Tag | Label meaning | Example Given
--- | ------------- | -------------
geo | Geographical Entity | London
org | Organization | ONU
per | Person | Bush
gpe | Geopolitical Entity | British
tim | Time indicator | Wednesday
art | Artifact | Chrysler
eve | Event | Christmas
nat | Natural Phenomenon | Hurricane
O | No-Label | the

We will:
- Preprocess text data for NLP

- Evaluate our model on the test set
- Run the model on your own sentences!
