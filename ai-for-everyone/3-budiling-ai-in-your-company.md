# Week 3: Building AI in Your Company

It takes about 2-3 years for a company to become good at AI.

- Case studies of complex AI products
- Roles in an AI team
- AI Transformation Playbook
- Taking your first step


## Case study: Building a smart speaker

"Hey Device, tell me a joke"
Steps to process the command
1. Trigger word/wakeword detection
2. Speech recognition
3. Intent recognition
4. Execute joke

Sometimes called a AI pipeline


> An AI pipeline is basically an assembly line for training AI models. Imagine it like a recipe with steps:
>
> 1. **Gather ingredients (data):** You gotta start with raw data, like for a cake you might need flour and sugar.
> 2. **Prep the ingredients (data cleaning):** Clean the data and get it ready for use, just like washing your flour and measuring sugar.
> 3. **Cook it up (training):** Train the AI model on the data, like baking your cake.
> 4. **Enjoy (prediction):** Use the trained model to make predictions, like serving and eating your cake!


An AI pipeline automates these steps, making it faster and easier to build and use AI models.

Key Steps:
1. Trigger word/wakeword detection
2. Speech recognition
3. Intent recognition
4. Specialized program to execute command

## Case study: Self-driving car

Steps for deciding how to drive

image/radar/lidar > motion planning > streer/accelerate/brake

1. Car detection uses supervised learning
2. Pedestrian detection uses supervised learning
3. Motion planning (plotting the path and speed)

Also includes:
- Other inputs: GPS/Maps
- Trajectory prediction
- Lane detection
- Traffic light detection
- Obstacle detection

## Example roles of an AI team

- Software engineers e.g. job execution
- Machine learning engineer e.g. write the program to do the A --> B mapping
- Machine laerning researcher
- Applied ML Scientist: does both of a ML engineer and ML researcher
- Data scientists: examine data and provide insights
- Data engineer: organize data, make sure data is saved, accessible, secure and cost effective
- AI product manager: help decide what to build, what is feasible and valuable

## AI Transformation Playbook
1. Execute pilot projects to gain momentum
    - more important for the initial project to succeed rther than be the most valuable
    - show traction within 6-12 months
    - can be in-house or outsourced
2. build an in-house AI team
3. Provide broad AI training
    - curate instead of create own content
4. Develop an AI strategy
5. Develop external and internal communcations
    - Investor and Government relations
    - Talent / recuritment 

> Refernce the [AI Transformation Playbook](docs/DeepLearning_AI-Playbook_v6.pdf)

## Pitfalls to avoid
Dont:
- expect AI to solve everything
- hire 2/3 ML engineers and count solely on them to come up with cases
- expect the AI project to work the first time
- expect traditional planning process to apply without changes
- think you need superstar AI engineers before you can do anything

Do:
- Be realistic about what AI can and cannot do given limitations of tech, data, and engineering resources
- Pair engineering talent with business talent and work cross-functionally to find feasible and valuable projects
- Plan for AI development to be an iterative process swith multiple attempts needed to succeed
- Work with AI team to establish timeline estimates, milestones, KPIs, etc
- keep building the team, but get going with the team you have

## Taking your first step in AI
- get friends to learn about AI
    - this course 
    - reading group
- start brainstorming projects
    - no project is too small
- hire a few ML/DS people to help
- hire or appoint an IA leader 
- discuss with ceo/board possibilities of AI transformation

## Survey of major AI application areas
### Computer Vision
- Image classification/object recognition
    - face recognition
- Object detection
    - image segmentation (pixel segmentatino)
- Tracking (motion in a video)

### Natural Language Processing (NLP)
AI understanding natural language, meaning the language humans speak. 
- Text classification: classifiying spam, product description
    - Sentiment recognition 
- Information retrieval:  web search
- name entity recognition
- machine translation, language translation
- speech recognition: speech-to-text
    - trigger word/wakeword detection
    - Speaker ID: figure out the identity of the speaker
    - speech synthesis: text-to-speech, TTS

### Generative AI
A **collection** of AI systems that can produce high-quality media, specifically text, images, or audio

LLMs are great at:
- text generation
- image generation
    - Journey Ali
    - Adobe Firefly
    - Stable Diffusion
- Audio generation
    - SyboI's Stable Audio 
    - Meta's Audicraft

### Robotics

- Perception: figure out whats in the world around you
- Motion planning: finding a path for the robot to follow
- Control: sending commands to the motors to follow a path

### General machine learning

Unstructured data

Structured data

## Survey of major AI techniques

AI Techniques

### Supervised learning
A to B mapping, is the most economical valuable today.

### Unsupervised learning
We don't exactly tell the AI system what we want, instead we feed it data and ask AI to find something interesting about the data

- Clustering
- Transfer learning
    - learn from task A, and use knowledge to help on task B
- Reinforcement learning
    - Uses a reward signal, to tell the AI system when it is doing well (giving a positive number) or poorly (giving a negative number), it automatically learns to maximize its rewards.
- Generative Adversarioal Networks (GANs)
    - Synthesize new images from scratch
- Knowledge Graph
    - basically means a database that lists objects and key information about these objects.