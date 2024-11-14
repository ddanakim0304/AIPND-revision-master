# Pretrained Dog Image Classifier

This project was completed as part of the **AWS x Udacity AI & ML Scholarship program**.

## Project Overview
<img width="694" alt="Screenshot 2024-11-14 at 4 54 14 PM" src="https://github.com/user-attachments/assets/cbf6424d-f4f6-4b12-9441-0272ff69bfec">

The Pretrained Dog Image Classifier is a machine learning application that leverages pre-trained CNN models to analyze and classify pet images. This program's primary goals are:

1. **Identify if an image is of a dog** – The classifier should distinguish between images of dogs and non-dog images, even if the breed is incorrectly classified.
2. **Classify the breed of dog** – For images identified as dogs, the classifier should attempt to correctly determine the breed.
3. **Evaluate CNN architectures** – Test the performance of different CNN model architectures (ResNet, AlexNet, and VGG) to identify which best meets objectives 1 and 2.
4. **Analyze time/resource efficiency** – Determine if alternative solutions could achieve an adequate result within a shorter runtime, evaluating the efficiency of each model.

## Project Instructions

### Main Objectives
- Correctly identify dog images (even if the breed is misclassified) and differentiate them from non-dog images.
- Accurately classify the breed of dog for dog images.
- Assess which CNN model architecture (ResNet, AlexNet, or VGG) performs best.
- Consider time resources for each model and evaluate if a simpler solution could provide acceptable results.

### Program Outline
The core of the project is contained in `check_images.py`, which includes a `main()` function and several `TODO` tasks. Here is an outline of the tasks you will perform:

1. **Time the Program**: Use the Python `time` module to calculate the total runtime.
2. **Get User Inputs**: Collect program inputs using command-line arguments.
3. **Create Pet Image Labels**: Generate labels from pet image filenames and store them in a dictionary.
4. **Create Classifier Labels and Compare**: Use a classifier function to generate labels, then compare these with the pet labels.
5. **Classify Labels as "Dogs" or "Not Dogs"**: Use the `dognames.txt` file to categorize labels, and store this information in the main data structure.
6. **Calculate Results**: Analyze the results to assess the accuracy of the classifier.
7. **Print Results**: Output the results to review each model's performance.

### Models Used
The project evaluates three pre-trained CNN models:
- **ResNet**
- **AlexNet**
- **VGG**

Each model’s performance is assessed based on accuracy and runtime.
