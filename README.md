<h1>PrAIoritize</h1>

<p>PrAIoritize: Automated Early Prediction and Prioritization of Vulnerabilities in Smart Contracts</p>

<p>Data and Source code for the paper: "PrAIoritize: Automated Early Prediction and Prioritization of Vulnerabilities in Smart Contracts"</p>

<h2>Requirements</h2>

<ul>
  <li>Python 3.7</li>
  <li>PyTorch 1.1</li>
  <li>The Natural Language Toolkit (NLTK)</li>
  <li>scikit-learn</li>
  <li>TensorFlow</li>
  <li>Transformers</li>
</ul>

<h2>How to Run?</h2>

<p>To run the models, execute <code>python model_name.py</code> to train PrAIoritize with default data.</p>

<p>If you want to change the dataset, modify the <code>pd.read</code> line in the <code>model_name.py</code> file that you want to run.</p>

<p>This will execute the code and display any output in the terminal or command prompt.</p>

<p>Alternatively, you can use an integrated development environment (IDE) like PyCharm or Spyder to write and run Python code.</p>

<p>To run the TF-IDF and the Bag of Words (BoW) to generate the lexicon:</p>

<ol>
  <li>Ensure you have downloaded NLTK by running <code>nltk.download()</code>.</li>
  <li>Run the <code>preprocessing_nltk_ALL.py</code> in the <code>Preprocessing</code> folder.</li>
  <li>To run the TF-IDF, execute <code>TF-IDF_DICT.py</code> in the <code>Term Weighting</code> folder. Read the data file <code>.csv</code> from Python, and the results are stored in a file called <code>Sorted_TF_IDF.csv</code>.</li>
  <li>Then, run the models and select the final data file.</li>
</ol>
