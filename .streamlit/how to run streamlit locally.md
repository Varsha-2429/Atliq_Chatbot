**how to run streamlit locally:**



1. In cmd prompt we need to create the streamlit environment for that 



Create the virtual environment



Run one of these commands:



python -m venv venv--env 

venv is the name of your virtual environment folder





2.Activate the virtual environment



venv\\Scripts\\activate 



You should now see your environment name at the beginning of your prompt, like:



(venv) C:\\Users\\YourName\\Projects\\MyApp>



3\. after creating virtual environment we need to import all libraries in that virtual environment



import json 

import re

import requests 

import snowflake.connector

import pandas as pd

from snowflake.snowpark import Session from snowflake.core 

import Root from typing import Any, Dict, List, Optional, Tuple 

import plotly.express as px 

import time



imported all these with in one line for that we have:

**pip install streamlit requests snowflake-connector-python snowflake-snowpark-python pandas plotly**



**4.**After installing run **"streamlit run app.py"** in cmd prompt and your app will open







