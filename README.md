import numpy as np
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt
from matplotlib.colors import ListedColormap

train = pd.read_csv('train.csv')

train.head()

train['credit'].unique()

train.info() # 자세히 살펴보기
