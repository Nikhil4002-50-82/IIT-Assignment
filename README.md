# HDIC IIT Madras Assignment

## Repository Structure

* **images/** - Contains reference images used in the assignment
* **Aksharantar_sampled/** - Contains the test dataset provided
* **QuestionPaper.pdf** - Original assignment questions
* **IIT.ipynb** - Jupyter Notebook with solutions to all three questions

## Overview

This repository contains my solutions to the HDIC IIT Madras assignment. It includes required datasets, images, the question paper, and a iit.ipynb file with answers.

---

## Question 1 – Image Enhancement via Retinex Concept

This part focuses on improving image clarity by separating lighting from real surface details. Instead of simply boosting brightness, the approach estimates illumination and removes its effect, revealing the true texture beneath uneven lighting.

Think of it like cleaning dust from a glass window - once the unnecessary layer is removed, the original view becomes clear and natural.


## Question 2 – Camera Calibration Using Checkerboard

This section performs camera calibration using a checkerboard pattern. The algorithm detects board corners, estimates the camera’s internal settings (like focal length and lens distortion), and then corrects the image so straight lines appear straight.

It's similar to fitting the right pair of glasses — once calibrated, the camera sees the world more accurately and removes bending or distortion from images.


## Question 3 – Transliteration Model (Seq2Seq with GRU)

This part implements a sequence-to-sequence model to transliterate text from English characters to Hindi script. The model learns patterns by studying paired examples and then converts new words using what it learned.

Imagine a student practicing writing words in another language. After enough examples, they can write new words on their own — that’s what the model does here.

---

## Notebook

All the code for the above questions is in the file:

```
iit.ipynb
```

---

## Note

This assignment was completed for HDIC, IIT Madras. I have uploaded only the files required for evaluation.
