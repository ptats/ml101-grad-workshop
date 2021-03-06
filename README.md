# ML101 Workshop

This workshop is a little taste into machine learning, specifically deep learning for image classification. The approach that we will take is a 'code first' approach where you will be building and training your own image classifier before understanding what is going on under the hood.

## Prerequisites - can be completed on the day

We wil be using Google Collaboratory for our coding exercise as we need access to a GPU. Google kindly provides this for free!! However, there are some parts of the coding exercise that are not compatible with Google Collab and you will be required to run this section locally.

* a laptop with google chrome or firefox
* google drive account - if you don't have a google drive account you can create one [here](https://accounts.google.com/signup/v2/webcreateaccount?continue=https%3A%2F%2Faccounts.google.com%2FManageAccount&dsh=S-1694359826%3A1582007900873563&gmb=exp&biz=false&flowName=GlifWebSignIn&flowEntry=SignUp)
* Nice to have: local install of jupyter notebook (see instructions [here](https://jupyter.readthedocs.io/en/latest/install.html#install). If you are unable to install, that is fine, there are just one or two parts of the coding exercise that you will be unable to do
* Nice to have: local install of fastai following instructions [here](https://github.com/fastai/fastai/blob/master/README.md#installation). As above, only a small section of the coding exercise will be ommitted if you can't get this installed locally

## How to run

### Step 1: Access Google Collab

Firstly you need a goolge account. You will need to do this step before proceeding otherwise the notebook will not work. You can create an account or sign in [here](https://accounts.google.com/signin/v2/identifier?flowName=GlifWebSignIn&flowEntry=ServiceLogin).

### Step 2: Download notebook from Github

Navigate to the [Google Collab](https://colab.research.google.com/notebooks/welcome.ipynb#recent=true) home page and select **Github**. Search by user **ptats** and select the **Image_Classifcation** notebook.

![google_collab](http://cran.rstudio.com/bin/linux/ubuntu 18.04://github.com/ptats/ml101-grad-workshop/blob/master/images/Notebook_img2.PNG)

### Step 3: Configure GPU

You now need to tell google collab that you want to use a GPU. With the notebook displaying, go to runtime -> change runtime  and select the GPU option.

![runtime](https://github.com/ptats/ml101-grad-workshop/blob/master/images/Notebook_img3.PNG)
![gpu](https://github.com/ptats/ml101-grad-workshop/blob/master/images/Notebook_img4.png)

### Step 4: Work through Google Collab Getting Started Notebooks

Before you start the coding exercise you should familiarise yourself with the Google Collab environment. You should work through the following two notebooks:

* [What is Collaboratory?](https://colab.research.google.com/notebooks/intro.ipynb#scrollTo=5fCEDCU_qrC0)
* [Overview of Collaboratory Features](https://colab.research.google.com/notebooks/basic_features_overview.ipynb#scrollTo=WUtu4316QSHL)

### Other Notes

* When you first run the notebook you will get a pop up warning, **Warning: This notebook was not authored by Google**. Select **RUN ANYWAY**.

* Make sure you save a copy to your drive. Navigate to file -> save a copy in drive...


