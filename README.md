# Space Microbial Biomanufacturing is a Go: Survivability, Usability, and Reliability for Next Generation Life Support

## System Requirements
This codebase uses Python with version 3.11.13. The required packages and their corresponding versions for this repo can be found in `requirements.txt`. 

## Installation
The user is assumed to have Anaconda and an IDE that can open `.ipynb` files installed.

To set up the environment, open Anaconda Prompt and run the following command (where `<env_name>` is the name of the environment):
```conda create -n <env_name> python=3.11.13```

To install the required packages, first activate the environment:

```conda activate <env_name>```

Then, run the following commands:

```conda install -c anaconda git```

```pip install -r requirements.txt```

Installation on a "normal" computer should require approximately 1 hour.

## Demo
There are a total of four `.ipynb` files, each corresponding to a unique combination of growth/titer and before/after transfer learning.

To run the data, go to the corresponding main file (i.e. `main_growth.ipynb`) and click "Run all".

The expected output is a plot that shows the predicted 95% confidence interval of the model and the corresponding flight data.

On a "normal" computer, this will take approximately 10 minutes to run.
