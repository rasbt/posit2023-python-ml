Machine Learning and Deep Learning with Python
================

### Workshop materials for [posit::conf 2023](https://posit.co/conference/) in Chicago

by [Sebastian Raschka](https://sebastianraschka.com)

-----

:spiral_calendar: September 18, 2023  
:alarm_clock:     09:00 am - 5:00 pm CDT  
:hotel:           **Grand Hall J**  
:writing_hand:    [pos.it/conf](http://pos.it/conf)

Please also check the official [Tutorial Schedule](https://reg.conf.posit.co/flow/posit/positconf23/attendee-portal/page/sessioncatalog) for updates.

-----

&nbsp;

## Abstract

In this workshop, you will learn the machine and deep learning fundamentals using a modern open-source stack. We’ll start with a brief introduction to Python’s scientific computing libraries, including NumPy, Pandas, and Matplotlib, which provide the foundation for data analysis and visualization. From there, we will dive into the scikit-learn API, a user-friendly, open-source library for machine learning in Python.

In the second part of this workshop, we will also cover deep learning concepts and introduce PyTorch, the most widely used deep learning research library. You will also learn about training multi-layer neural networks efficiently using multi-GPU and mixed-precision techniques. Finally, we will explore how to use a pretrained large language transformer and fine-tune it on a custom downstream task using PyTorch. 

By the end of this workshop, you will have a good understanding of the fundamental principles of machine learning and be able to construct advanced classification pipelines for tabular data using scikit-learn. Additionally, you will gain experience in image classification and natural language processing techniques using PyTorch and be able to implement them in your own predictive modeling projects effectively. 

This workshop is for you if you:

- are a researcher, programmer, or engineer who wants to apply machine learning and deep learning
- are a scientific computing practitioner who is interested in predictive modeling
- are a problem solver who want to learn about Python-tools for tabular, image, and text data

&nbsp;

## Material & Preparation

The workshop material will be posted ahead of time but may be updated on the weekend before the event. To prepare for the workshop, there are only 4 small action items prior to the workshop are

1. (Optional) If you are new to Python, you may find the **Python Setup Guide** ([./00-1_python-setup-guide](./00-1_python-setup-guide)) helpful, which mainly describes how I set up Python on my computer(s).
2. Please go through **Python Library Installation** ([./00-2_python-libraries-for-workshop](./00-2_python-libraries-for-workshop)) guide to ensure you have all the required libraries installed prior to the workshop.
3. I recommend downloading this repository before the event so you can access the materials offline in case of a slow internet connection during the workshop.
4. If you are new to Python, it would be useful to read about the basics of array computing in NumPy (e.g., see my blog article [Scientific Computing in Python: Introduction to NumPy and Matplotlib](https://sebastianraschka.com/blog/2020/numpy-intro.html)); but no worries, will will only be needing a smaller subset of these features.
5. And, of course, please bring your laptop (and charger) to get the most out of this workshop!

Looking forward to seeing you there!

PS: If you have any questions, please feel free to reach out via the [Discussion page](https://github.com/rasbt/posit2023-python-ml/discussions) here on GitHub.

&nbsp;

# Schedule and Slides



| Time          | Activity                             |
| :------------ | :----------------------------------- |
| 9:00 am - 10:30 am | (1) Introduction to machine learning [[Slides](https://sebastianraschka.com/pdf/posit2023/01_intro-ml__slides.pdf)] [[Code](00-2_python-libraries-for-workshop)] |
|               | (2) The scikit-learn API [[Slides](https://sebastianraschka.com/pdf/posit2023/02-1_scikit-learn-api__slides.pdf)] [[Code](02_scikit-learn-api)]           |
| 10:30 am - 11:00 am | *Coffee break*                       |
| 11:00 am - 12:30 pm | (3) Data processing in Python [[Slides](https://sebastianraschka.com/pdf/posit2023/03-1_data-processing-api__slides.pdf)] [[Code](03_data-processing)]             |
|               | (4) Evaluating & tuning machine learning classifiers [[Slides](https://sebastianraschka.com/pdf/posit2023/04-1_ml-classifiers__slides.pdf)] [[Code](04_ml-classifiers)]|
| 12:30 pm - 1:30 pm | *Lunch break*                        |
| 1:30 pm - 3:00 pm | (5) Introduction to deep learning [[Slides](https://sebastianraschka.com/pdf/posit2023/05-intro-dl__slides.pdf)] [[Code](05_intro-dl)]   |
|               | (6) Understanding PyTorch [[Slides](https://sebastianraschka.com/pdf/posit2023/06-pytorch-api.pdf)] [[Code](06_pytorch-api)]           |
|               | (7) Training deep neural networks [[Slides](https://sebastianraschka.com/pdf/posit2023/07-multilayer-neural-nets.pdf)] [[Code](07_training-dnns)]   |
| 3:00 pm - 3:30 pm | *Coffee break*                       |
| 3:30 pm - 5:00 pm | (8) Accelerating PyTorch model training [[Slides](https://sebastianraschka.com/pdf/posit2023/08-accelerating-pytorch.pdf)] [[Code](08_accelerating-pytorch)] |
|               | (9) Finetuning Large Language Models  [[Slides](https://sebastianraschka.com/pdf/posit2023/09-1_finetuning-llms.pdf)] [[Code](09_finetuning-llms)] |
|               | (10) Conclusion [[Slides](https://sebastianraschka.com/pdf/posit2023/10-conclusion.pdf)] [[Code](10_conclusion)]   |
| Bonus materials |  (11) Organizing PyTorch code  [[Slides](https://sebastianraschka.com/pdf/posit2023/11-organizing-pytorch-code.pdf)] [[Code](11_bonus-organizing-pytorch-code)] |
| |  (12) Advanced features and techniques  [[Slides](https://sebastianraschka.com/pdf/posit2023/12-advanced-techniques.pdf)] [[Code](12_bonus-advanced-features)] |



&nbsp;

## About the Instructor

My name is [Sebastian Raschka](https://sebastianraschka.com), and I have been working on machine learning and AI for more than a decade.

Next to being a researcher, I also have a strong passion for education and am best known for my bestselling books on machine learning using open-source software.

After my PhD, I joined the University of Wisconsin-Madison as a professor in the Department of Statistics, where I focused deep learning and machine learning research until 2023.

Taking a yearlong break from academia, I joined Lightning AI in 2022, where I now focus on AI and LLM research, developing open-source software, and creating educational material. 