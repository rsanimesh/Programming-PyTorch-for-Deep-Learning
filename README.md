# Programming PyTorch for Deep Learning : Creating and Deploying Deep Learning Applications
A book by Ian Pointer 

<img src="https://github.com/rsanimesh/Programming-PyTorch-for-Deep-Learning/blob/181528534d66d636fb4bc3701cacffa16fb60fa1/book-cover-page.jpg" height="394px" width="300px">  

This Repository contain codes from the book Programming PyTorch for Deep Learning : Creating and Deploying Deep Learning Applications

# Notebooks

## Chapter 1: Getting Started with PyTorch

#### Setp 1: Clone this Repository
To begin, you'll need to clone this repository on your local machine. You can do this by running the following command in your terminal:

`git clone https://github.com/rsanimesh/Programming-PyTorch-for-Deep-Learning.git`

#### Step 2: Install Python
Make sure you have Python installed on your machine. If not, you can download it from the official Python website: [Python Downloads](https://www.python.org/downloads/). During installation, be sure to check the "Add Python to PATH" option.

#### Step 3: Create a Virtual Environment
It's a good practise to work in a virtual environment to manage project dependencies.
Open your command prompt or terminal and navigate to the cloned repository. Then, proceed to create and activate a virtual environment by following these steps:

**For Windows: Using PIP**
```
pip install virtualenv
python -m venv venv
venv\Scripts\activate
```

**For macOS and Linux: Using PIP**
```
pip install virtualenv
python3 -m venv venv
source venv/bin/activate
```

#### Step 3: Install Required Libraries using requirement file
In the root directory of the repository, you'll find requirement files that contain a list of available libraries along with their compatible versions.
If you have CUDA installed on your system, then use the file `requirements_cuda_available.txt` or `requirements.txt`. Install the required libraries by running:

`pip install -r requirements_cuda_available.txt` or `pip install -r requirements.txt`

This will set up the necessary dependencies to run the code examples.

#### Step 5: Start Jupyter Notebook
To work with the code and Jupyter Notebook, simply run the following command:
`jupyter notebook`

### Chapter 2: Image Classification with PyTorch

- [Building an image classifier.ipynb](https://github.com/Andrew-Ng-s-number-one-fan/Programming-PyTorch-for-Deep-Learning/blob/master/Notebooks/C1-Building-an-Image-Classifier.ipynb)

### Chapter 3: Convolutional Neural Networks

- [Building a CNN model.ipynb](https://github.com/Andrew-Ng-s-number-one-fan/Programming-PyTorch-for-Deep-Learning/blob/master/Notebooks/C3-Building-a-CNN-Model.ipynb)

### Chapter 4: Transfer Learning and Other Tricks

- [Transfer learning with ResNet.ipynb](https://github.com/Andrew-Ng-s-number-one-fan/Programming-PyTorch-for-Deep-Learning/blob/master/Notebooks/C4-Transfer-Learning-with-ResNet.ipynb)
- [Finding that learning rate.ipynb]()

### Chapter 5: Text Classification

### Chapter 6: A Journey into Sound

### Chapter 7: Debugging PyTorch Models

### Chapter 8: PyTorch in Production

### Chapter 9 - PyTorch in the Wild
