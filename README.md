# Re-Tweet Prediction in the presidential elections context

## Overview
This project, developed as part of the INF554 course at École Polytechnique, aims to predict the number of retweets a tweet will receive. The dataset used contains various types of information including unnormalized numerical data and textual content in hashtags and tweets. The project involves several data processing steps, including normalization, vectorization, PCA, and the use of RNN and NN networks for prediction.

## Features
- Analysis of tweet data to predict retweet counts.
- Data preprocessing including normalization and vectorization.
- Application of PCA on hashtags and text data.
- Integration of RNN for sentence meaning extraction and a simple NN for final prediction.

## Installation
To set up this project, clone the repository and install the required dependencies:

```bash
git clone https://github.com/hannachoum/Tweet_Prediction.git
cd Tweet_Prediction
pip install -r requirements.txt
```

## Data Preprocessing
The data preprocessing steps include:
1. Handling empty values and blank spaces.
2. Observing correlations between different features.
3. Extracting time-related features using the `datetime` library.
4. Normalizing the data for training and validation.

## Model Architecture
The project employs a dual-network architecture:
1. **RNN (Recurrent Neural Network)**: Processes vectorized sentences to extract meaning.
2. **NN (Neural Network)**: Receives the output from the RNN along with other data like normalized numerical data and PCA results to predict the number of retweets.


## Contributing
Contributions to the "Tweet Prediction Project" are welcome. You can contribute by improving the prediction algorithms, enhancing data preprocessing methods, or adding new features.

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgements
- Special thanks to Professor Michalis Vazirgiannis and my teammates Mathieu Gierski and Maximilien Bohm for their guidance and collaboration.
- Acknowledge any frameworks, libraries, or other resources that have been instrumental in the development of this project.
