# What Questions Should Robots be Able to Answer? A Dataset of User Questions for Explainable Robotics
The dataset and analysis code for the paper "What Questions Should Robots be Able to Answer? A Dataset of User Questions for Explainable Robotics" 

# Citation
```
@article{wachowiak2025questions,
  title={What Questions Should Robots be Able to Answer? A Dataset of User Questions for Explainable Robotics},
  author={Wachowiak, Lennart and Coles, Andrew and Canal, Gerard and Celiktutan, Oya},
  journal={arXiv preprint},
  year={2025}
}
```

# Reproduce Analysis

We ran the analysis with Python 3.12.9. Optionally create a virtual environment, for example, with
```
conda create -n xai-questions python=3.12.9
conda activate xai-questions
```

To install the necessary packages, run:
```
pip install -r requirements.txt
```
Afterwards, you can run our analysis via the Jupyter Notebook [analysis.ipynb](https://github.com/lwachowiak/xai-questions-dataset/blob/main/analysis.ipynb).

To explore the dataset yourself, check out the file [dataset.csv](https://github.com/lwachowiak/xai-questions-dataset/blob/main/data/dataset.csv).

# Abstract
With the growing use of large language models and conversational interfaces in human–robot interaction, robots' ability to answer user questions is more important than ever.
We therefore introduce a dataset of **1,893 user questions for household robots**, collected **from 100 participants and organized into 12 categories and 70 subcategories**. Most work in explainable robotics focuses on 
why-questions, such as "Why did you clean the bathroom but not the kitchen?". In contrast, our dataset provides a wide variety of questions, from questions about simple execution details to questions about how the robot would act in hypothetical scenarios —  thus giving roboticists valuable insights into what questions their robot needs to be able to answer. To collect the dataset, we created 15 video stimuli and 7 text stimuli, depicting robots performing varied household tasks. We then asked participants on Prolific what questions they would want to ask the robot in each portrayed situation. 

**Analysis.** In the final dataset, the most frequent categories are questions about task execution details (22.5%), the robot's capabilities (12.7%), and performance assessments (11.3%). 
Although questions about how robots would handle potentially difficult scenarios and ensure correct behavior are less frequent, users rank them as the most important for robots to be able to answer. Moreover, we find that users who identify as novices in robotics ask different questions than more experienced users. Novices are more likely to inquire about simple facts, such as what the robot did or the current state of the environment. 

**Impact.** As robots enter environments shared with humans and language becomes central to giving instructions and interaction, this dataset provides a valuable foundation for 
- (i) identifying the information robots need to log and expose to conversational interfaces,
- (ii) benchmarking question-answering modules,
- (iii) designing explanation strategies that align with user expectations.

# Related Repositories/Research
- [Overview of related explainable robotics research](https://lwachowiak.github.io/project/explainablerobots/)
- [A Taxonomy of Explanation Types and Need Indicators in Human–Agent Collaborations](https://github.com/lwachowiak/Explanation-Types-and-Need-Indicators-in-HAI)
- [When do People Want an Explanation from a Robot?](https://github.com/lwachowiak/HRI-Video-Survey-on-Preferred-Robot-Responses)
