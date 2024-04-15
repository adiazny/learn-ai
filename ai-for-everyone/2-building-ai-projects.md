# Week 2: Building AI Projects

## Workflow of a machine learning project
1. Collect data
2. Train model (iterate many times until output is good enough)
3. Deploy model (get data back, maintain/update model)

## Workflow of a data science project
> NOTE: Output is actionable insight!

1. Collect data
2. Analyze data (iterate multiple times to get good insight)
3. Suggest hypothesis/actions

## Every job function needs to learn how to use data

## How to choose an AI project

AI Knowledge and domain knowledge. Aim to select projects that are feasable, one that AI can do but also valuable to your business.

Consult with AI experts and domain experts (or cross-functional teams)

Brainstorming framework:
1. Think about automating tasks rather than automating jobs. e.g. Call centet routing, radiolgists.
2. What are the main drivers of business value?
3. What are the main pain points of your business?

> NOTE: You can make progress even without Big Data
> - having more data almost never hurt
> - but with small datasets, you can  still make  prgress.
> - The amount of data you need is very problem-dependent and speaking with a AI engineer or an AI expert would help you get a better sense.


The process to double-check if a project is worth that many months of effort:
- Due dillegence (spend time to understand if it is feasable and valuable)

Perform the following:
- Technical dillegence
    1. can AI system meet desired perforance 
    2. how much data is required
    3. engineering power/timeline
- Business dillegence
    1. lower costs / increase effeciency
    2. increase revenue
    3. launch new product / business

> Note: Don't forget to conduct ethical dillegence

Build or Buy:
- ML projects can be in-house or outsourced
- DS projects are more commonly in-house
- Some things will be industry standard - avoid building those

> "Don't sprint in front of a train"

## Working with an AI team
- specify acceptance criteria 
    - provide the AI team a "test" dataset on which to measure their performance. May not 
- Data sets
    - the training set: is the input to the machine learning software that lets it figure out what is this A to B mapping.
    - the test set: a different set of input and output data mappings to test against the model

> Pitfall: Expecting 100% accuracy

## Technical tools for AI teams
Open-source frameworks:
- PyTorch
- TensorFlow
- Hugging Face
- PaddlePaddle
- Scikit-learn
- R

Research publications
- Arxiv

Open source repos:
- GitHub

CPU vs GPU
- CPU: Central Processing Unit performing the computations in a computer
- GPU: Graphics Processing Unit: great for nueral network computation

> Google is making their own chip, a [TPU](https://cloud.google.com/tpu)

Cloud vs On-premises

Edge deployments: local processor where the data is collected without needing to tranmit data over the internet