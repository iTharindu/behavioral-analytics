# Behavioral analytics project

This repositiory contains the source code for Behavioral analytics and outlier detection project. The outlier detection is done by identifying behavioral patterns from data.

## Directory Structure

The important files and directories of the repository is shown below

    ├── models : UI related files  
        ├── markov.py : Source code for Markov model
        ├── temporal.py : Source code for Time Series based modelS (Prophet and mean, std models)
    ├── templates : UI related files 
    ├── app.py : Backend of the web app created using Flask
    ├── test.py : test script to add synthetic data to the firebase


## Starting the web app

```commandline
git clone https://github.com/iTharindu/behavioral-analytics.git

cd behavioral-analytics

virtualenv -p python3 envname

source env/bin/activate

pip install -r requirements.txt

python app.py
```

