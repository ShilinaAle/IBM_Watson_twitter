# IBM_Watson_twitter

The app that provides information about personality characteristics, needs and values based on their Twitter account.

The test function in the app compares your choice of personality characteristics, needs and values with information about Joanne Rowling, Donald John Trump, Serena Jameka Williams, Lady Gaga, Sylvester Stallone and Charlize Theron.

---
used libraries:

import twint
import os
from os.path import join
from ibm_watson import PersonalityInsightsV3
from ibm_cloud_sdk_core.authenticators import IAMAuthenticator
import pandas as pd
from matplotlib import pyplot as plt
import seaborn as sns
