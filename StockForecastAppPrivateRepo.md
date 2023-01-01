# StockForecast App
A stock prediction application in Python using Streamlit to create the interactive web app, with various tools such as Yahoo Finance to fetch stock data and Facebook Prophet to predict prospect stock. The App also allows users to view the stock by specifying years, and using Plotly to generate plot graphs, charts and tables. 
## ***[Copyright and Commercial Use Disclaimer](https://github.com/KrystalZhang612/KrystalZhang-StockForecast-App/blob/main/README.md#please-carefully-read-licensemd-about-the-open-source-restrictions-and-the-personal-use-policy-of-this-project-under-gpl-30-license-any-commericial-uses-on-this-project-by-other-than-the-owner-krystalzhang612-or-the-authorized-users-and-organizations-including-unauthorized-modifications-forks-pull-requests-and-other-commercial-related-uses-will-be-subjected-to-copyright-violation-with-sebsequent-legal-concerns)***

⏬

### ***Please carefully read [LICENSE.md](https://github.com/KrystalZhang612/KrystalZhang-StockForecast-App/blob/main/LICENSE) about the Open Source restrictions and the personal use policy of this project under [GPL-3.0 license](https://www.gnu.org/licenses/gpl-3.0.en.html), any commericial uses on this project by other than the owner [@KrystalZhang612](https://github.com/KrystalZhang612) or the authorized users and organizations, will be subjected to copyright violation with sebsequent potential legal concerns.***
## StockForecast App Overview:
<p align = "center">
  <img src = "https://github.com/KrystalZhang612/KrystalZhang-StockForecast-App/blob/main/testing-result-stock-forecast-app/stock%20forecast%20app%20overview-1.PNG">&nbsp;
  <img src = "https://github.com/KrystalZhang612/KrystalZhang-StockForecast-App/blob/main/testing-result-stock-forecast-app/stock%20forecast%20app%20overview-2.PNG">&nbsp;
  <img src = "https://github.com/KrystalZhang612/KrystalZhang-StockForecast-App/blob/main/testing-result-stock-forecast-app/stock%20forecast%20app%20overview-3.PNG">&nbsp;
  <img src = "https://github.com/KrystalZhang612/KrystalZhang-StockForecast-App/blob/main/testing-result-stock-forecast-app/stock%20forecast%20app%20overview-4.PNG">&nbsp;
  <img src = "https://github.com/KrystalZhang612/KrystalZhang-StockForecast-App/blob/main/testing-result-stock-forecast-app/stock%20forecast%20app%20overview-5.PNG">&nbsp;
  <img src = "https://github.com/KrystalZhang612/KrystalZhang-StockForecast-App/blob/main/testing-result-stock-forecast-app/stock%20forecast%20app%20overview-6.PNG">
</p>
              
            
              
# Build
[Method to Run & Test the Project Locally](https://github.com/KrystalZhang612/KrystalZhang-StockForecast-App/blob/main/README.md#method-to-run--test-the-project-locally)<br/> 
[Prerequisites & Setups](https://github.com/KrystalZhang612/KrystalZhang-StockForecast-App/blob/main/README.md#prerequisites--setups)<br/> 
[Debugging&Troubleshooting](https://github.com/KrystalZhang612/KrystalZhang-StockForecast-App/blob/main/README.md#debuggingtroubleshooting)<br/> 
[Synchronous Developing Notes](https://github.com/KrystalZhang612/KrystalZhang-StockForecast-App/blob/main/README.md#synchronous-developing-notes)<br/> 
[Testing Result](https://github.com/KrystalZhang612/KrystalZhang-StockForecast-App/blob/main/README.md#testing-result)<br/> 
[Tags and Topics](https://github.com/KrystalZhang612/KrystalZhang-StockForecast-App/blob/main/README.md#tags-and-topics)<br/> 
# Contribution
[Author](https://github.com/KrystalZhang612/KrystalZhang-StockForecast-App/blob/main/README.md#author) 
# Functionalities/Demo
- The user can select the stocks they would like to predict by different stock names.
- The user can also specify certain years to inspect the previous stocks infos.
- Raw data as charts, graphs and plottings for users to analyze the stock datas and trends.
- The plot charts are interactive for users to zoom in/out.
- A thorough forecast stock data for user to predict and analyze the daily/yearly trends of stocks.
# Compatibility

| Browsers        | Supported          |
| -------         | ------------------ |
| Apple Safari    | :x:                |
| Google Chrome   | :white_check_mark: |
| Microsoft Edge  | :white_check_mark: |
| FireFox         | :white_check_mark: |
| Opera           | :white_check_mark: |
| DuckDuckGo      | :white_check_mark: |

# Method to Run & Test the Project Locally
### Install the entire StockForecast App to the local directory 
### In local Console, install StreamLit using `pip install streamlit fbprophet yfinance plotly`
### Run to initiate the App on web server by using `streamlit run main.py`
### Test the App in  http://localhost:8501
### `NOTE`: The App is not fully compatible with Apple Safari
### Have fun viewing stock prediction data
# 🛠️ Developing Languages, Tools, and Techniques Needed
[Vscode 1.73](https://code.visualstudio.com/updates/v1_73)<br/> 
[StreamLit](https://streamlit.io)<br/> 
[Facebook Prophet](https://facebook.github.io/prophet/)<br/> 
[Yahoo Finance](https://finance.yahoo.com/quote/AAPL?p=AAPL&.tsrc=fin-srch)<br/> 
[Plotly](https://plotly.com/)<br/> 
[Python3](https://www.python.org/downloads/)<br/> 
[PyStan 2.19](https://pystan2.readthedocs.io/en/latest/)<br/> 
<div>
  <img src ="https://github.com/devicons/devicon/blob/master/icons/visualstudio/visualstudio-plain.svg" title="Vscode" alt="Vscode" width ="60" height="60"/>&nbsp; 
  <img src ="https://github.com/devicons/devicon/blob/master/icons/python/python-original.svg" title ="Python3" alt ="Python3" width ="60" height="60"/>&nbsp; 
</div>

# Prerequisites & Setups
Install the modules in local Console at local directory:<br/>
Navigate to the project’s directory.<br/> 
Install Facebook Prophet, StreamLit, YahooFinance, Plotly:<br/> 
`pip install streamlit fbprophet yfinance plotly`<br/> 
Create [main.py](https://github.com/KrystalZhang612/KrystalZhang-StockForecast-App/blob/main/main.py) with `touch` command.<br/>

# Debugging&Troubleshooting
 Module installation error: Failed to install Facebook Prophet in virtual environment (VENV).<br/>
 DEBUGGING: Install PyStan 2.19: `pip install pystan==2.19`.<br/>
 Then install Facebook Prophet: `pip install fbprophet`
# Synchronous Developing Notes
Import data in main.py:
```python 
import streamlit as st
from datetime import date
import yfinance as yf
from fbprophet import Prophet
from fbprophet.plot import plot_plotly 
from plotly import graph_objs as go
```
Run the app by web server using Streamlit:
```
streamlit run main.py
```
Now the app runs on http://localhost:8501:<br/>
[app runs on streamlit localhost.PNG](https://github.com/KrystalZhang612/KrystalZhang-StockForecast-App/blob/main/testing-result-stock-forecast-app/app%20runs%20on%20streamlit%20localhost.PNG)<br/>
## ***Load stock data from Yahoo Finance:***
```python
 def load_data(ticker):
    data = yf.download(ticker, START, TODAY)
    data.reset_index(inplace = True)
    return data
  data_load_state = st.text("Load data...") 
  data = load_data(selected_stock) 
  data_load_state.text("Loading data....done!")
```
[start loading out data.PNG](https://github.com/KrystalZhang612/KrystalZhang-StockForecast-App/blob/main/testing-result-stock-forecast-app/start%20loading%20out%20the%20data.PNG)<br/>
## ***Cache data:***
```python 
st.subheader('Raw data') 
st.write(data.tail())
```
Now we got the raw data:<br/>
[raw data table fetched.PNG](https://github.com/KrystalZhang612/KrystalZhang-StockForecast-App/blob/main/testing-result-stock-forecast-app/raw%20data%20table%20fetched.PNG)<br/>
## ***Plot data:***
```python 
def plot_raw_data():
    fig = go.Figure()
    fig.add_trace(go.Scatter(x=data['Date'], y = data['Open'], name
='stock_open'))
    fig.add_trace(go.Scatter(x=data['Date'], y = data['Close'], name
='stock_close'))
    fig.layout.update(title_text="Time Series Data",
xaxis_rangeslider_visible=True)
    st.plotly_chart(fig)
plot_raw_data()
```
[raw plot data fetched.PNG](https://github.com/KrystalZhang612/KrystalZhang-StockForecast-App/blob/main/testing-result-stock-forecast-app/raw%20plot%20data%20fetched.PNG)<br/>
## ***Forecasting:***
```python
#Forecasting
df_train = data[['Date', 'Close']]
df_train = df_train.rename(columns = {"Date": "ds", "Close": "y"}) m = Prophet()
m.fit(df_train)
future = m.make_future_dataframe(periods=period)
forecast = m.predict(future)
st.subheader('Forecast date')
st.write(forecast.tail())
```
Now we have forecasting datas:<br/>
[forecasting data.PNG](https://github.com/KrystalZhang612/KrystalZhang-StockForecast-App/blob/main/testing-result-stock-forecast-app/forecasting%20data.PNG)<br/>
Fetch forecast data and forecast components as well:
```python
st.write('forecast data')
fig1 = plot_plotly(m, forecast)
st.plotly_chart(fig1)
st.write('forecast components')
fig2 = m.plot_components(forecast)
st.write(fig2)
```
[forecast data.PNG](https://github.com/KrystalZhang612/KrystalZhang-StockForecast-App/blob/main/testing-result-stock-forecast-app/forecast%20data.PNG)<br/> 
[forecast components.PNG](https://github.com/KrystalZhang612/KrystalZhang-StockForecast-App/blob/main/testing-result-stock-forecast-app/forecast%20components.PNG)<br/> 

# Testing Result 
<p align = "center">
  <img src = "https://github.com/KrystalZhang612/KrystalZhang-StockForecast-App/blob/main/testing-result-stock-forecast-app/app%20runs%20on%20streamlit%20localhost.PNG">&nbsp;
  <img src = "https://github.com/KrystalZhang612/KrystalZhang-StockForecast-App/blob/main/testing-result-stock-forecast-app/start%20loading%20out%20the%20data.PNG">&nbsp;
  <img src = "https://github.com/KrystalZhang612/KrystalZhang-StockForecast-App/blob/main/testing-result-stock-forecast-app/raw%20data%20table%20fetched.PNG">&nbsp;
  <img src = "https://github.com/KrystalZhang612/KrystalZhang-StockForecast-App/blob/main/testing-result-stock-forecast-app/raw%20plot%20data%20fetched.PNG">&nbsp;
  <img src = "https://github.com/KrystalZhang612/KrystalZhang-StockForecast-App/blob/main/testing-result-stock-forecast-app/forecasting%20data.PNG">&nbsp;
  <img src = "https://github.com/KrystalZhang612/KrystalZhang-StockForecast-App/blob/main/testing-result-stock-forecast-app/forecast%20data.PNG">&nbsp;
  <img src = "https://github.com/KrystalZhang612/KrystalZhang-StockForecast-App/blob/main/testing-result-stock-forecast-app/forecast%20components.PNG">&nbsp;
</p>



# Tags and Topics 
python, python3, frontend, backend, fullstack-development, api, stock-prediction, vscode, streamlit, facebook-prophet, yahoo-finance, plotly, pystan. 
# Author 
Krystal Zhang
https://github.com/KrystalZhang612<hr>
*This file was generated by [StockForecastApp-readme](https://github.com/KrystalZhang612/KrystalZhang-StockForecast-App/blob/main/README.md), on October 31th, 2022*
