# Machine Learning primer: A mini course

An interactive, beginner friendly course for machine learning, written and developed by [**Arghya Chattopadhyay**](https://chattopadhyaya.github.io).

📘 **Read the Jupyter Book:**  

https://chattopadhyaya.github.io/ml_course

This course is designed to help physicists build an intuitive and practical understanding of machine learning. It introduces the basic ideas with examples, explains the mathematics behind the concepts that operate under the hood, develops common ML terminology, and provides hands-on experience with Python based tools and models.

The material is intended not only to introduce a few algorithms, but also to give learners enough confidence and background to continue exploring machine learning independently.

## Topics covered

The course includes:

- basic statistics and probability;
- an introduction to machine learning;
- decision trees;
- support vector machines;
- gradient descent;
- neural networks and backpropagation;
- convolutional neural networks;
- transformers;
- applications of machine learning in high-energy physics;
- exercises and suggestions for further study.

Many chapters include executable notebooks, interactive figures, questions with hidden answers, and links for opening the notebooks in Google Colab.


## How to use this book: a guide for fellow travellers

Like any journey through Middle earth, this course is best explored one step at a time.

- Each chapter contains an [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://youtu.be/NPBCbTZWnq0?si=gqvhQB1CMYyacW7z) button. Clicking it will open the corresponding Jupyter Notebook in **Google Colab**, where you can modify the code, run the cells, and experiment freely. Remember: even the longest journey begins by running the first cell.

- The notebooks contain questions whose answers are initially hidden but can be revealed with a single click. This mini course follows an **honour system**: please do not consult the hidden answers (the course’s own little *palantíri*) before you are asked to do so.

- All pages allow you to **run basic Python directly inside the webpage**. Look for the <img src="content/images/pyodide_power_button.png" alt="Turn on interactive Python" style="height:30px; vertical-align:middle; margin-left:1px;"> button near the top of the page. Click it to start the interactive Python environment. The first startup may take a few moments while the browser prepares the kernel and loads the required packages.

- Once the interactive environment is ready, runnable code cells will display controls such as <img src="content/images/pyodide_cell_controls.png" alt="Run and collapse code cell controls" style="height:30px; vertical-align:bottom; margin-left:1px;">. The **play button** runs the selected code cell directly in your browser, while the button beside it can be used to collapse or hide the code area.

- For interactive figures, sliders, and widgets, first activate the environment using the power button and then run the corresponding code cell. Some cells depend on results produced by earlier cells, so it is usually best to follow the path in order rather than wandering ahead alone.

- The in-browser **Pyodide** environment is a useful travelling companion, but it is not designed to carry the heavier burden of training the machine learning models used later in the course. For pages involving model training (using PyTorch), please use the corresponding notebook in **Google Colab** or run it on your **local machine**, the setup instruction is alreasy there in the course page.

- If a code cell does not run in Google Colab, read the warning or error message carefully. A required package may be missing. Install it in a new cell using `!pip install <missing-package-name>`, and then run the notebook again.

> Go carefully, experiment boldly, and remember that no fellowship learns machine learning by merely watching the code pass by.


## Who is this for?

The course is primarily written for physicists and beginning ML learners. No advanced background in machine learning is assumed, although basic familiarity with Python is helpful.

## Author

This course, its notes, examples and overall structure were written and developed by:

**Arghya Chattopadhyay**  
https://chattopadhyaya.github.io

The material also benefits from the guidance and suggestions of mentors from the HSF Training Programme, as well as technical contributions acknowledged in the Jupyter Book.


## Repository structure

- `content/` — source material used to build the Jupyter Book;
- `content_nb/` — notebook versions used for interactive work and Colab;
- `exercises/` — course exercises;
- `myst.yml` — MyST/Jupyter Book configuration;
- `patch_thebe_lite.py` — support for the in-browser interactive notebook experience.

## Exercises and solutions

The course includes a set of exercises designed to help participants practise the ideas introduced in the notebooks. The exercise instructions can be found here:

https://chattopadhyaya.github.io/ml_course/exercises/

Workshop participants (and other wanderers), who complete the exercises are welcome to contribute their solutions to this repository. Please follow the submission directions given on the exercise page, place the solutions in the requested structure, and open a pull request.

Once the pull request is reviewed and accepted, the contributor’s name will be added alongside their submitted solutions.

> Learning is better when the path travelled by one wanderer can help guide the next.


## Free and open material

This repository is made freely available under the **CC0 1.0 Universal** license.

> **From Rivendell to the ends of the Earth, this code is free to all who wander.**

You are welcome to read, run, modify, reuse, and share the material.

## Citation

If this tutorial, its code, or its explanations help your project, thesis, article, teaching, or research, please cite or acknowledge this repository:

```text
Arghya Chattopadhyay,
"Machine Learning primer: A mini course",
GitHub repository:
https://github.com/chattopadhyayA/ml_course

Online Jupyter Book:
https://chattopadhyaya.github.io/ml_course
```

A simple acknowledgement such as the following is also welcome:

> This work made use of the tutorial *A mini course in Machine Learning for HSF training* by Arghya Chattopadhyay.


## Feedback and contributions

Feedback, corrections, and suggestions are warmly welcome. Please open an issue or submit a pull request through this repository.

For contact information, visit:

https://chattopadhyaya.github.io
