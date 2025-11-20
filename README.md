# CE4145 NLP Coursework - Mateusz Borowicz (2202830) 

Dataset Used: https://huggingface.co/datasets/vimal-quilt/tweet-eval-emotion

# Overview

The vimal-quit tweet-eval-emotion dataset is a relatively medium sized collection of 3257 records of tweets containing emotional messages. The dataset is essentially structured as a collection of text and label pairs. Even though it's not a multi-class dataset, I hope it will fit my coursework guidelines just fine with my consideration towards pre-processing and vectorization techniques. If I had more time, I would definitely focus on research towards a more complex dataset.

The task performed in this coursework is a simple binary text classification. The goal of this task is to predict the appropriate label as output, given the textual contents of social media posts as input. Each tweet is labeled with intensity of emotions ranged from 0 to 3, therefore making 4 unique categories for tweets:

0 - Low emotional involvment, 1 - Moderate emotional involvment, 2 - High emotional involvment, 3 - Extreme emotional involvment,

Each category from 0 to 3 follows from lowest to highest level of hierarchy, though the classiffiers could also be split into their own columns with "0" and "1" markings to represent boolean values.
