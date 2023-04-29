# Numerai Example Notebooks

Welcome to the [Numerai](https://numer.ai/) data science tournament! 

If you are just getting started, then these notebooks are for you. These notebooks are designed to be your guide as you take you first steps as a tournament participant. We assume basic knowledge of Python and ML, but will otherwise explain everything from first principles and show you real working code examples where possible.     

The best way to use these notebooks is to open them in Google Colab (free!) using the links below. If you are in a hurry, you may choose to just read through the notebooks and the saved outputs. But for the best experience, we highly encourage you to step through and run each code cell, or even make edits to see what happens! Don't worry - any changes you make will only be saved to your personal copy. 

Need help or have any questions? Talk to us on [Discord](https://discord.gg/numerai)!

## Hello Numerai 
<a target="_blank" href="https://colab.research.google.com/github/numerai/hello-numerai/blob/master/hello_numerai.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

In this notebook we will go through the basics of the tournament. Our goal is to get your first model set up to start competing in the tournament as quickly as possible. 

1. Dataset: download and explore the Numerai dataset 
2. Modeling: train your first machine learning model
3. Submissions: upload your prediction pipeline to start making live submissions

## Model Diagnostics 
<a target="_blank" href="https://colab.research.google.com/github/numerai/hello-numerai/blob/master/model_diagnostics.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

In this notebook we will learn how to evaluate and diagnose model performance. We will run our first experiment and see if we can improve the performance of our model trained in the previous notebook.   

1. Performance: measure model performance with `Correlation`  
2. Risk: measure model risk with `Sharpe`, `Max Drawdown`, `Feature Exposure` 
3. Experiment: use `Feature Neutralization` to reduce risk and improve performance

## Advanced Concepts
<a target="_blank" href="https://colab.research.google.com/github/numerai/hello-numerai/blob/master/advanced_concepts.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

In this notebook we will go deep on advanced modeling concepts. We will go over common pitfalls and best practices when apply machine learning to Numerai's dataset. 

1. Risky Features: measuring feature risk and identifying risky features    
2. Auxilary Targets: what are auxiliary targets and how to use them 
3. Overlapping Eras: the problem with leakage and how to fix it with embargos

## Tournament Structure
<a target="_blank" href="https://colab.research.google.com/github/numerai/hello-numerai/blob/master/submissions_scoring.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

In this notebook we will learn about the core tournament structure of Numerai.   

1. Rounds: the lifecycle of a round   
2. Scores: `True Contribution`  
3. Compute:   

## Staking & Payouts
<a target="_blank" href="https://colab.research.google.com/github/numerai/hello-numerai/blob/master/stkaing_payouts.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

In this notebook we will learn about the core staking & payout systems of Numerai.

1. NMR: what is NMR 
2. Staking: `payout factor`, `multipliers`
3. Payouts: compounding 