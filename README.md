# Detection-of-Parkinson-s-disease-with-Spiral-Wave-Test

One of the symptoms of Parkinson’s is tremors and rigidity in the muscles, making it harder to draw smooth spirals and waves.
Parkinson’s disease is a nervous system disorder that affects movement. The disease is progressive and is marked by five different stages:


    1. Stage 1: Mild symptoms that do not typically interfere with daily life, including tremors and movement issues on only one side of the body.
    2. Stage 2: Symptoms continue to become worse with both tremors and rigidity now affecting both sides of the body. Daily tasks become challenging.
    3. Stage 3: Loss of balance and movements with falls becoming frequent and common. The patient is still capable of (typically) living independently.
    4. Stage 4: Symptoms become severe and constraining. The patient is unable to live alone and requires help to perform daily activities.
    5. Stage 5: Likely impossible to walk or stand. The patient is most likely wheelchair bound and may even experience hallucinations.


While Parkinson’s cannot be cured, early detection along with proper medication can significantly improve symptoms and quality of life, making it an important topic as computer vision and machine learning practitioners to explore.

I utilized the Histogram of Oriented Gradients image descriptor to quantify each of the input images.

After extracting features from the input images, I trained a Random Forest classifier with 100 total decision trees in the forest, obtaining:

    83.33% accuracy for spiral
    71.33% accuracy for the wave

It’s also interesting to note that the Random Forest trained on the spiral dataset obtained 76.00% sensitivity, meaning that the model was capable of predicting a true positive (i.e., “Yes, the patient has Parkinson’s”) nearly 76% of the time.


