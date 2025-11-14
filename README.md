# Leo Gordon
[![My Skills](https://skillicons.dev/icons?i=js,html,css,py,pytorch,postgres,sublime,scala,cpp)](https://skillicons.dev)

[lsgordon@seas.upenn.edu](mailto:lsgordon@seas.upenn.edu) | [github.com/lsgordon](https://github.com/lsgordon)

[![wakatime](https://wakatime.com/badge/user/8b342d6c-b796-4efc-8319-ecf5ff600457.svg)](https://wakatime.com/@8b342d6c-b796-4efc-8319-ecf5ff600457)

Hello!

My name is Leo, I'm a current 1st year grad student at UPenn, and a current senior at Haverford College. I'm interesting in Machine Learning, and Distributed Systems. These projects are the best examples of my work. Feel free to reach out with any questions you have.

---

## Highlighted Projects
**My Thesis: Automated Theorem Proving: Language Model Based Approaches to Tackle Undergraduate \& High School Competitions in Mathematics (Full Draft)** | [GitHub](https://github.com/lsgordon/Thesis)
*Fall 2025*
* Conducted a comprehensive literature review of Large Language Model (LLM) applications in Automated Theorem Proving (ATP).
* Proposed a taxonomy of current approaches, analyzing systems from fine-tuned provers (e.g., Goedel-Prover) to complex neuro-symbolic architectures (e.g., Hilbert, AlphaProof).
* Critically evaluated claims of superhuman performance on olympiad benchmarks (AIME, IMO, PutnamBench), focusing on the impact of data contamination.
* Assessed systemic issues in the field, including the validity of benchmarks like MiniF2F and widespread reproducibility challenges.
* Identified and proposed future research directions for developing more robust evaluation methods and advancing genuine mathematical reasoning.


**BirdCLEF+ 2025: Species Classification w/ YamNET** | [GitHub](https://github.com/lsgordon/ANN-Final-Project)
*May 2025*
* Developed a robust system for classifying 206 endangered and under-studied animal species (including birds, amphibians, mammals, and insects) from the Middle Magdalena Valley of Colombia using audio recordings for the BirdCLEF 2025 competition.
* Engineered a comprehensive data preprocessing pipeline: converted audio files to mono, standardized sample rates by downsampling to 22kHz (compatible with YAMNet) using `scipy.signal.resample`, and implemented custom functionsfor data cleaning and handling irregularities.
* Created fixed-length audio representations (1000 samples per segment) by padding shorter sequences and chunking/padding longer ones, preparing data for consistent model input.
* Utilized the pre-trained YAMNet model from TensorFlow Hub for feature extraction, transforming raw audio segments into 1024-dimensional embeddings.
* Addressed significant class imbalance in the BirdCLEF 2025 dataset by strategically downsampling processed audio segments, limiting each of the 206 classes to a maximum of 1000 samples for training the final model.
* Designed, built, and trained a deep neural network using the Keras functional API. The architecture included an input layer for 1024-dimensional embeddings, multiple Dense layers (512, 256, 128 units) with ReLU activations, Layer Normalization for improved stability, Dropout (0.2, 0.3) for regularization, and a residual connection, leading to a Softmax output layer for multi-class classification.
* Optimized model training by employing EarlyStopping (monitoring `val_loss` with a patience of 5 epochs), which helped in preventing overfitting and restoring the best performing model weights.
* Achieved a test accuracy of approximately 71% and a test loss of 1.14 on the classification of 206 species.
* Leveraged parallel processing with `concurrent.futures` to expedite the audio data reading and initial preprocessing stages.
* *Technologies: Python, Keras, TensorFlow, TensorFlow Hub, Scikit-learn, Pandas, NumPy, SoundFile, SciPy, Matplotlib, tqdm, concurrent.futures.*

**Big Data Final Project** | [GitHub](https://github.com/lsgordon/big-data-final-project)
* April 2025
* Developed a model to differentiate between real and fake news articles using linguistic features.
* Engineered features by calculating various text statistics (e.g., Coleman-Liau index, SMOG index, average sentence length, subjectivity, sentiment, word count, syllable count, Flesch reading ease, and Flesch-Kincaid grade level).
* Implemented Logistic Regression, XGBoost, LSTM, and TF-IDF classification models, evaluating their performance with accuracy, F1-score, and confusion matrices. Accuracy on the best models was 99%.
* *Technologies: Python, Pandas, Statsmodels, Textstat, TextBlob, Scikit-learn, XGBoost, Matplotlib, Seaborn, SHAP*

**Hidden Markov Model For Stock Prediction** | [GitHub](https://github.com/lsgordon/HMM-For-Stock-Prediction)
*Jan 2025*
* Designed Hidden Markov class from scratch and applied it to predict \$AAPL stock price.
* *Technologies: Pandas, Refinitiv, Python*

**J.P. Morgan Data for Good MKE Fellows Project** | [Pres Link](https://www.canva.com/design/DAGSr93W7hU/zZx3u7nRwaTn4fZh08GQDQ/edit?ui=eyJEIjp7IlAiOnsiQiI6ZmFsc2V9fX0)
*October 2024* 
* Received first place for our proposal to MKE Fellows non-profit for their next city to expand to.
* * Built k-means and agglomerative clustering models, engineered census data, and designed presentation in 24 hours. 
* *Technologies: Pandas, Python, Plotly* 

**D3 Track Times** | [GitHub](https://github.com/lsgordon/D3TrackTimes)
*May 2024*
* Built dual MongoDB/PSQL database of over 300K track records, which are queried to find percentile rank in D3. 
* Used by several D3 teams in PA area to aid with recruiting and modeling expected times. 
* *Technologies: HTML, CSS, JS, PSQL, Mongo* 
