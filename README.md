# POS-Tagging-Using-Hidden-Markov-Model-HMM-and-the-Viterbi-Algorithm

This project demonstrates the implementation of Part-of-Speech (POS) tagging utilizing a Hidden Markov Model (HMM) and the Viterbi algorithm. The dataset employed for this project is the Penn Treebank, which consists of 3,914 sentences along with their corresponding POS tags. A bigram model is constructed to create the HMM, and the Viterbi algorithm is used to decode the most likely sequence of tags for a given sentence.
## Dataset

The Penn Treebank dataset, included in the NLTK library, serves as the training and testing data for the HMM. This dataset provides a collection of sentences with words and their associated POS tags, enabling the training of a robust model for POS tagging.
## Script Details
## Training

The training script uses the Penn Treebank dataset to train a bigram HMM. The following HMM parameters are computed from the training data:

### Initial Probabilities: The probability of each POS tag being the start tag.
### Transition Probabilities: The probabilities of transitioning from one POS tag to another.
### Emission Probabilities: The probabilities of observing a word given a POS tag.
## Tagging

The tagging script implements the Viterbi algorithm to predict the POS tags for sentences in the test data. The Viterbi algorithm efficiently finds the most likely sequence of hidden states (POS tags) given the sequence of observed events (words).
## Evaluation

The evaluation script compares the predicted tags with the actual tags in the test data to assess the model's accuracy. Key metrics, such as overall accuracy and per-tag accuracy, are calculated to provide insights into the model's performance.

## Contributors

This project was developed by Malapati Sruthi Laya Reddy,Praveen Uppari, Rampalli Vamsi,Miyapuram Akshitha and Thatikonda Srivarsha, as part of B V RAJU INSTIUTE OF TECHNOLOGY NARSAPUR "## POS-Tagging-Using-Hidden-Markov-Model-HMM-and-the-Viterbi-Algorithm".

## Acknowledgments

We would like to express our gratitude to Ms.Srilakshmi Mam, our mentor and guide, for their valuable insights and support throughout this project.

## Contact Information

If you have any questions or suggestions regarding this project, please feel free to reach out to 21211a6628@bvrit.ac.in,21211a6630@bvrit.ac.in,21211a6643@bvrit.ac.in,21211a6655@bvrit.ac.in,21211a6658@bvrit.ac.in.


Feel free to personalize the placeholders, such as Malapati Sruthi Laya Reddy, Praveen Uppari, Rampalli Vamsi, Thatikonda Srivarsha and Miyapuram Akshitha, B V Raju Institute Of Technology Narsapur,POS-Tagging-Using-Hidden-Markov-Model-HMM-and-the-Viterbi-Algorithm.
