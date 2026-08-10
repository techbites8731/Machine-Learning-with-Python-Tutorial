<b>AI-DataSets</b><br>
This folder contains code samples and changed codes from the book "Machine Learning with Python Tutorial by Bernd Klein". I ustilized the book to learn coding as well as to learn more about the datasets featured in the examples. That way if you follow the codes given here it will be very easy to understand the principles given in the book and the datasets itself.<br><br>

Scikit-learn makes available a host of datasets for testing learning algorithms. They come in three flavors:<br> • <b>Packaged Data</b>: <br>these small datasets are packaged with the scikit-learn installation, and can be
downloaded using the tools in:<br><b>sklearn.datasets.load_*</b><br><br>

• <b>Downloadable Data</b>:<br>
  these larger datasets are available for download, and scikit-learn includes tools 
  which streamline this process.
  These tools can be found in:
  <b>sklearn.datasets.fetch_*</b><br><br>

• <b>Generated Data</b>:<br>
  there are several datasets which are generated from models based on a random seed. 
  These are available in the
  <b>sklearn.datasets.make_*</b><br><br>
  
You can explore the available dataset loaders, fetchers, and generators using IPython's tab-completion functionality. After importing the datasets submodule from sklearn , type datasets.load_ or datasets.fetch_ or datasets.make_<br>

to see a list of available functions.<br><br>

STRUCTURE OF DATA AND LABELS Data in scikit-learn is in most cases saved as two-dimensional Numpy arrays with the shape (n, m) . Many algorithms also accept scipy.sparse matrices of the same shape.<br><br>

from sklearn.datasets import load_
from sklearn.datasets import fetch_
from sklearn.datasets import make_
from sklearn import datasets
