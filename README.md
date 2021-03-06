# ETF_Analyzer
This is a review of the potential stocks that are pulled specifically from a SQL database. We're trying to assess the performance of this ETF, and whether or not the assets from the information will allow us to have good performance over the life of investing in it. This analysis will take into account the information from the SQL database and show the aspect of improving and making it apparent. This can be launched through the Voila function on a web browser locally to facilitate with the analysis/review of the ETF

---

# Required Installs/Installation Guide 

Currently this requires use of Python 3.8, Jupyter Lab and packages:

Please double check before running the application, you need to be sure to install the above mentioned technologies. More information on installation of jupyter lab is located on the link: https://jupyterlab.readthedocs.io/en/stable/getting_started/installation.html

Additional Packages: sqlachemy, pandas, numpy, voila
```python
pip install pandas
pip install SQLAlchemy
pip install numpy
pip install voila
```

---
# Usage
Running Voila to launch the jupyterlab Notebook in a web window:

```python
voila etf_analyzer.ipynb
```
![Command Input](https://github.com/AndrewAu42/ETF_Analyzer/blob/main/Images/Voila%20Command%20Line.PNG)

Launching into it from the terminal input
![Voila Launching on Terminal](https://github.com/AndrewAu42/ETF_Analyzer/blob/main/Images/Voila%20Launching.PNG)

Web Application Launching Locally in Browser
![Voila Launching on Web Browser](https://github.com/AndrewAu42/ETF_Analyzer/blob/main/Images/Voila%20Web%20Launch%20Window.PNG)

Information on the ETF, will appear in the web application and allow you to take a look at the analysis of the provided info to use in making a decision on the analysis

---

# Contributors

Modified and updated by Andrew Au, with provided code from 2021 Rice FinTech Bootcamp. Hope this facilitates with the decision process for the end user.  

---

# License

MIT License