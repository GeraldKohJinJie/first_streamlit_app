import streamlit as st
import pandas as pd
import numpy as np
import pydeck as pdk
import joblib
from joblib import load
import pickle
from sklearn import preprocessing
import requests
import snowflake.connector
from urllib.error import URLError

st.set_page_config(page_title='INVEMP Tasty Bytes Group 5', page_icon='🍖🍕🍜')

st.sidebar.title("INVEMP: Inventory/Warehouse Management & Prediction on Sales per Menu Item")
st.sidebar.markdown("This web app allows you to explore the internal inventory of Tasty Bytes. You can explore these functions in the web app (Description of Page)")

tab1, tab2 = st.tabs(['Prediction A', 'Prediction B'])
