# Paperfetcher

Paperfetcher is a set of tools to automate time-intensive parts of the systematic review process. At v1.0, Paperfetcher automates hand-search and snowball-search.
To begin with, read our preprint (coming soon!).

Paperfetcher is free and open source, and is licensed under the [MIT License](https://github.com/paperfetcher/paperfetcher/blob/master/LICENSE). If you wish to use paperfetcher for your research, all we ask is that you cite our preprint.

# Getting started with Paperfetcher

## I want a quick solution - no setup, no Python coding. | I'm okay with storing my data on Google Drive.

We have three Google Colab notebook apps for you! These are small apps/widgets that run inside your browser on Google Colab (a cloud computing platform by Google for running Python code), and require just a few mouse clicks to run. Read our preprint to learn more about each app! 

Click on the links below to open the apps in your browser.

1. [Hand-search version A](https://colab.research.google.com/github/paperfetcher/paperfetcher-colab-app/blob/main/paperfetcher_handsearch_DOI_app.ipynb): saves DOIs of search results only. Can directly import .txt output into Zotero.
2. [Hand-search version B](https://colab.research.google.com/github/paperfetcher/paperfetcher-colab-app/blob/main/paperfetcher_handsearch_citations_app.ipynb): saves multiple fields (from choices of DOI, URL, Title, Authors, and Publication Date) of search results.
3. [Snowball-search](https://colab.research.google.com/github/paperfetcher/paperfetcher-colab-app/blob/main/paperfetcher_snowballsearch_app.ipynb): saves DOIs of search results only. Can directly import .txt output into Zotero.

### Video tutorials

We have video tutorials demonstrating how to run and use these apps. Check these out!

1. Hand-search version A:

   [![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/o3S5hyQSyME/0.jpg)](https://www.youtube.com/watch?v=o3S5hyQSyME)
   
2. Hand-search version B
3. Snowball-search

## I'm okay with setup, but no Python coding. | I want to store my data offline.

The setup process involves a couple of steps:
1. [Install Python]()
2. [Install pip]()
3. [Install Jupyter notebook]()
4. Install Paperfetcher using pip by typing this command in a new Terminal (MacOS, Linux) or Command Prompt (Windows) window:

        pip install paperfetcher

5. Download the Paperfetcher apps from [here]()
6. In a new terminal window, launch any one of the Paperfetcher apps by first navigating to folder and then typing this command:

        jupyter notebook --execute <app name>.ipynb

## I know some Python. | I want to experiment with using the code.

Setup Paperfetcher:
1. [Install Python]()
2. [Install pip]()
3. [Install Jupyter notebook]()
4. Install Paperfetcher using pip:

        pip install paperfetcher

Check out the [example Jupyter notebooks]() for step-by-step usage guides.

Check out the [Paperfetcher documentation]().

## I'm comfortable with Python. | I want to add custom features to Paperfetcher.

Install Paperfetcher from source:
1. Obtain sources using git
2. Navigate to the source directory in a new Terminal or Command Prompt window, and install paperfetcher by typing in the following command:
        
        python setup.py install

or

        pip install .

Check out the [Paperfetcher documentation]().

If you wish to contribute to a Paperfetcher repository, fork the repository, make your changes, and create a pull request. The organization administrators will review your pull request within 1-2 weeks.

# The team
Paperfetcher was formulated by [Qiyang Zhang](qiyangzh.github.io) at the [Johns Hopkins University](jhu.edu) and developed by [Akash Pallath](apallath.github.io) at the [University of Pennsylvania](upenn.edu).
