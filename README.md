README
This project demonstrates sentiment analysis using a BERT-based model and provides explainability using LIME (Local Interpretable Model-agnostic Explanations) and attention visualization. The model is capable of classifying text as either "Positive" or "Negative."
To run the code, ensure that you have the required dependencies installed. The pip install for lime is provided (as it is not automatically in google colab). Other dependencies should be available in google colab (as of 3-4-2025), but can also be installed via pip if necessary.
To use the program, change the variable 'text' to the review (string) you would like to analyse. As a standard example, it is set to "Good movie". Note that the BERT model that is used is optimized for movie reviews, and may respond unexpectedly to other types of textual input.
Running the final cell will generate a Attention Heatmap Matrix and a LIME explanation of the provided text.
