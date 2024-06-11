# Airbnb Property Unlisting Prediction

## Project Description

The goal of this project is to use Natural Language Processing (NLP) models to predict whether a property listed on Airbnb will be unlisted in the next quarter. This project leverages real Airbnb property descriptions, host descriptions, and comments from previous guests.

Using the NLP techniques learned during the Text Mining course, the objective is to implement an NLP classification model that predicts if a property will be unlisted (1) or remain listed (0). The project is developed using Python and libraries such as NLTK, Scikit-Learn, Keras, or PyTorch. Multiple solutions are possible, and collaboration between groups on code is not allowed.

## Datasets

The corpora for the project is divided into the following sets:

- **Train (train.xlsx)**: Contains 6,248 lines of Airbnb and host descriptions (`description` and `host_about` columns), and the property listing status (`unlisted` column). A property is considered unlisted (1) if it was removed from the quarterly Airbnb list, and listed (0) if it remains on that list.

- **Train Reviews (train_reviews.xlsx)**: Contains 361,281 lines of guests’ comments for each Airbnb property. Note that there can be multiple comments per property, not all properties have comments, and comments can be in various languages.

- **Test (test.xlsx)**: Contains 695 lines with the same structure as the train set, but without the `unlisted` column. The actual statuses are withheld and will be used to compare against the predicted statuses (0 or 1).

- **Test Reviews (test_reviews.xlsx)**: Contains 41,866 lines of comments for the properties in the test set, with the same structure as the train reviews set.

## Project Purpose

- **What the project does**: Predicts the unlisting status of Airbnb properties using NLP techniques on descriptions and guest reviews.
- **Why the project is useful**: Helps identify properties that are likely to be unlisted, aiding hosts and the platform in better understanding property dynamics.
- **How users can get started with the project**: Follow the installation and usage instructions provided below to set up the project environment and run the models.
- **Where users can get help with your project**: For support, refer to the [Contributing Guidelines](#contributing) and [Code of Conduct](#code-of-conduct) sections, or open an issue on the repository.
- **Who maintains and contributes to the project**: This project is maintained by [Your Name/Team]. See the [Contributors](#contributors) section for more details.
