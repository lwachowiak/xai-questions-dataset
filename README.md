# What Questions Should Robots be Able to Answer? A Dataset of User Questions for Explainable Robotics
The dataset and analysis code for the paper "What Questions Should Robots be Able to Answer? A Dataset of User Questions for Explainable Robotics" 

# Citation
```
forthcoming
```

# Reproduce Analysis

We ran the analysis with Python 3.12.9. Optionally create a virtual environment for example with
```
conda create -n xai-questions python=3.12.9
conda activate xai-questions
```

To then install the necessary packages, run:
```
pip install -r requirements.txt
```
Afterwards, you can run our analysis via the Jupyter Notebook analysis.ipynb

# Abstract
With the increased use of large language models and conversational interfaces in human–robot interaction, robots' ability to answer user questions is more important than ever.
We therefore introduce a dataset of 1,893 user questions for household robots, collected from 100 participants and organized into 12 categories and 70 subcategories. Most work in explainable robotics focuses on 
why-questions, such as "Why did you clean the bathroom but not the kitchen?". In contrast, our dataset provides a wide variety of questions, from questions about simple execution details to questions about how the robot would act in hypothetical scenarios —  thus giving roboticists valuable insights into what questions their robot needs to be able to answer. To collect the dataset, we created 15 video stimuli and 7 text stimuli, depicting robots performing varied household tasks. We then asked participants on Prolific what questions they would want to ask the robot in each portrayed situation. In the final dataset, the most frequent categories are questions about task execution details (22.5%), the robot's capabilities (12.7%), and performance assessments (11.3%). 
Although these questions are less frequent, users highly value robots being able to explain how they would handle potentially difficult scenarios and how they can ensure correct behavior when problems arise. Moreover, we find that users who identify as novices in robotics ask different questions than more experienced users. Novices are more likely to inquire about simple facts, such as what the robot did or the current state of the environment. 
As robots enter environments shared with humans and language becomes central to giving instructions and interaction, this dataset provides a valuable foundation for (i) identifying the information robots need to log and expose to conversational interfaces, (ii) benchmarking question-answering modules, and (iii) designing explanation strategies that align with user expectations.
