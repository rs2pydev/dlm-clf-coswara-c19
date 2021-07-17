<h1>dlm-clf-coswara-c19</h1>

<h2>DEEP LEARNING MODEL OF COSWARA PROJECT'S COVID-19 DATASET</h2>
<p>
  This work conforms to an assignment whose objective is to build a deep learning model using the Coswara project's Covid-19 dataset. This is bascially a multiclass classification problem wherein the target variable called "covid_status" consists of 7-classes. Due to time crunch, I have reduced this 7-class classification task to an "effc=ective" 2-class (binary) classification task. Due to heavy class imbalance even in the "effective" binary problem, I have resorted to the use of the <code>SMOTENN</code> class from the <code>combine</code> module of the <code>imbalanced-learn</code> library. 
</p>

<h2>INTERACTIVE NOTEBOOKS</h2>

  1. [Effective Binary Classification (deep learning) Model - Binder Link](https://mybinder.org/v2/gh/Tirthankar-Dutta-2016/dlm-clf-coswara-c19/1b8b41d7f3071f6469b7131c93e388a10a670ea4)

### NOTE: Do not run the interactive notebooks on [Binder](https://mybinder.org) as training the deep learning models are very slow.

<h2>TO DO LIST</h2>

  1. Reduce the original 7-class classification task to a 4-class classification task and solve it using Keras deep learning library.
  2. Approch the full 7-class classification task.
  3. Use Pytorch to address the 2-, 4- and 7-class problems. 
