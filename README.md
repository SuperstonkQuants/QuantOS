# GETTING STARTED WITH QUANTOS

## What it is

A Debian based Operating System for use in a Virtual Machine for Quant analysis and stonks.

It aims to standardize tools and data sources among our group, making sure our results are reproducable and our methods transparent.

Hopefully it makes getting started and following along easier, please don't be afraid to offer suggestions or ask for help.

### List of included software of note:
	Python3 - language
	Firefox - web browserp
	VSCodium - fully open source binaries of vscode
	Xcas - Computer Algorithm Software
	R & RStudio - language and client
	Julia - language
	PostgresSQL - Opensource relational database
	MongoDB - opensource NOSQL database
	TeXdoctk - LaTeX reader
	Scilab - free and open source software for engineers & scientists,
	Sage - " SageMath is a free open-source mathematics software system licensed under the GPL. It builds on top of 		many existing open-source packages: NumPy, SciPy, matplotlib, Sympy, Maxima, GAP, FLINT, R and many 			more. Access their combined power through a common, Python-based language or directly via 			interfaces or wrappers. "
        Fortran - Language
        Anaconda - python environment manager
	Freqtrade - "Freqtrade is a crypto-currency algorithmic trading software developed in python (3.7+) and 			supported on Windows, macOS and Linux."
	Node.js - JavaScript runtime
	Postman - API Tool
	Jesse - Jesse is an advanced crypto trading framework which aims to simplify researching and defining trading 			strategies.
	Ticker - Live stock prices in your terminal, built with golang
	GO - language
        Over 25  preinstalled in a conda environment (quants environment) - of note are:
	
	mechanize - automate anything
	yfinance - yahoo finance
	xlrd - xls reader
	tensorflow - end-to-end open source platform for machine learning.
	tf-quant-finance - TensorFlow based Quant Finance Library
	TA-Lib - is widely used by trading software developers requiring to perform technical analysis of 			 financial market data.

        	 Includes 150+ indicators such as ADX, MACD, RSI, Stochastic, Bollinger Bands, etc.
        	 Candlestick pattern recognition
		 
	tensorflow-probability - is a Python library built on TensorFlow that makes it easy to combine probabilistic 				      models and deep learning on modern hardware 
	Sphinx - is a tool that makes it easy to create intelligent and beautiful documentation
	sec-edgar-downloader - is a Python package for downloading company filings from the SEC EDGAR database.
	seaborn - Seaborn is a Python data visualization library based on matplotlib
	scipy - is a Python-based ecosystem of open-source software for mathematics, science, and engineering
	scikit-learn - Simple and efficient tools for predictive data analysis
	robin-stocks - This library provides a pure python interface to interact with the Robinhood API, Gemini API, 			    and TD Ameritrade API. 
	requests - is an elegant and simple HTTP library for Python, built for human beings
	python-binance - This is an unofficial Python wrapper for the Binance exchange REST API v3
	python-coinmarketcap - This is a non official (but working) Python package to wrap the CoinMarketCap API. With 				      this you can monitoring and watch the crypto market.
	pymongo - is a Python distribution containing tools for working with MongoDB,
	SQLAlchemy - is a Python distribution containing tools for working with SQL
	poetry - package manager
	Keras - Keras is a deep learning API written in Python, running on top of the machine learning platform 		TensorFlow.
	jupyter - open-source web application that allows you to create and share documents that contain live code
	ipython - The goal of IPython is to create a comprehensive environment for interactive and exploratory 			  computing
	GitPython - git, but for python
	FundamentalAnalysis - This package collects fundamentals and detailed company stock data from a large group of 			             companies (20.000+) from FinancialModelingPrep and uses Yahoo Finance to obtain stock 				 data for any financial instrument. It allows the user to do most of the essential 				      fundamental analysis. It also gives the possibility to quickly compare multiple companies 			      or do a sector analysis.
	Flask - module that lets you develop web applications easily
	fredapi - is a Python API for the FRED data provided by the Federal Reserve Bank of St. Louis
	finviz - Unofficial Python API for FinViz
	FinMind -is open source of more than 50 datasets, including
		 Taiwan stock trade data daily, Taiwan stock trade data (5 seconds) (2019-05-29 ~ now, more than 30 		     million data in total), Financial Statements, Balance Sheet, Cash Flows Statement, Month Revenue, 			 Holding Shares Per, Institutional Investors Buy Sell. Taiwan Futures Trade Detail, Taiwan Option Trade 		 Detail.

		 US stock price daily, minute (2019-06-01 ~ now, more than 80 million data in total), oil price, gold 		       price, G7 exchange rate, interest rate.

		 US Government Bonds Yield.

                 The datasets are automatically updated daily. You can analyze financial data without having to collect                  the data by yourself.
	FinanceDatabase - it features 300.000+ symbols containing Equities, ETFs, Funds, Indices, Currencies, 				  Cryptocurrencies and Money Markets. It therefore allows you to obtain a broad overview of 			      sectors, industries, types of investments and much more.

			  The aim of this database is explicitly not to provide up-to-date fundamentals or stock data 				as those can be obtained with ease (with the help of this database) by using yfinance, 				  FundamentalAnalysis or ThePassiveInvestor. Instead, it gives insights into the products that 				 exist in each country, industry and sector and gives the most essential information about 			     each product. With this information, you can analyse specific areas of the financial world 		          and/or find a product that is hard to find
	bulbea - "Deep Learning based Python Library for Stock Market Prediction and Modelling."
	beautifulsoup4 - Beautiful Soup is a library that makes it easy to scrape information from web pages
	pandas - is a fast, powerful, flexible and easy to use open source data analysis and manipulation tool
	pandas-datareader - Functions from pandas_datareader.data and pandas_datareader.wb extract data from various 				 Internet sources into a pandas DataFrame. Currently the following sources are supported:				Tiingo
        			IEX
        			Alpha Vantage
        			Enigma
        			Quandl
        			St.Louis FED (FRED)
        			Kenneth French’s data library
        			World Bank
        			OECD
        			Eurostat
        			Thrift Savings Plan
        			Nasdaq Trader symbol definitions
       				Stooq
        			MOEX
        			Naver Finance


	pandas-ta - Pandas Technical Analysis (Pandas TA) is an easy to use library that leverages the Pandas library 			  with more than 130 Indicators and Utility functions and more than 60 TA Lib Candlestick Patterns
	numpy - NumPy brings the computational power of languages like C and Fortran to Python
	matplotlib - pretty graphs
	backtesting - Backtest trading strategies with Python.
	backtrader - Live Trading With Interactive Brokers, Oanda v1, VisualChart and also with external 3rd party 			brokers (alpaca, Oanda v2, ccxt, ...)
		     Over 122 indicators with the usual suspects on board
		     Several built-in performance analyzers (TimeReturns, TradeAnalyzer, SharpeRatio, VWR, SQN, ...)
		     Automated (customizable) plotting with a single command.
		     Any number of simultaneous data feeds (memory constrained, obviously) can be run simultaneously
		     The trading logic and the broker are always run on an event by event basis
		     Agents which will be plotted and can observe everything in the system (usually will be used to 				plot statistics)

	alpha-vantage - api
	alpaca-trade-api - api
	mlflow - MLflow is an open source platform for managing the end-to-end machine learning lifecycle. It tackles 			four primary functions:

    			Tracking experiments to record and compare parameters and results (MLflow Tracking).

    			Packaging ML code in a reusable, reproducible form in order to share with other data scientists 			or transfer to production (MLflow Projects).

    			Managing and deploying models from a variety of ML libraries to a variety of model serving and 			       inference platforms (MLflow Models).

    			Providing a central model store to collaboratively manage the full lifecycle of an MLflow 			  Model, including model versioning, stage transitions, and annotations (MLflow Model Registry).

	mplfinance - matplotlib utilities for the visualization, and visual analysis, of financial data
	sacred - Sacred is a tool to help you configure, organize, log and reproduce experiments. It is designed to do 			all the tedious overhead work that you need to do around your actual experiment in order to:

    			keep track of all the parameters of your experiment
    			easily run your experiment for different settings
    			save configurations for individual runs in a database
    			reproduce your results

	selenium - Selenium automates browsers. That's it!
	ta - It is a Technical Analysis library to financial time series datasets (open, close, high, low, volume). You 		can use it to do feature engineering from financial datasets. It is builded on Python Pandas library.
	prometheius-client - Prometheus's main features are:

    				a multi-dimensional data model with time series data identified by metric name and 				   key/value pairs
				PromQL, a flexible query language to leverage this dimensionality
    				no reliance on distributed storage; single server nodes are autonomous
    				time series collection happens via a pull model over HTTP
    				pushing time series is supported via an intermediary gateway
    				targets are discovered via service discovery or static configuration
    				multiple modes of graphing and dashboarding support

	timeseries-cv - This python package aims to implement Time-Series Cross Validation Techniques.
	tradingview-ta - An unofficial python API wrapper to retrieve technical analysis from TradingView.
	dask - Dask provides advanced parallelism for analytics, enabling performance at scale for the tools you love 
	openpyxl - excel
	pandas-gbq - google big query
	google-cloud-storage - cloud storage
	boto3 - aws sdk
	--

	Last but never least:
	The GameStonk Terminal (the gst conda environment)
	

## What you need

The ISO: https://storage.googleapis.com/quantos/QuantOSv0-1-0.iso

A Virtual Machine:

	* [Default choice - VirtualBox (Windows, MacOS, most Linux)](https://www.virtualbox.org/)
	* [If you have Win10 Enterprise, Pro or Education - Hyper-V](https://docs.microsoft.com/en-us/virtualization/hyper-v-on-windows/quick-start/enable-hyper-v)
	* [KVM](https://www.linux-kvm.org/page/Main_Page) / [QEMU](https://www.qemu.org/) (Linux)
	* [Parallels - (paid, MacOS)](https://www.parallels.com/)
	* [VMWare Workstation (paid, all platforms)](https://www.vmware.com/products/workstation-pro.html)

## Setup

1. Install your virtual machine manager of choice.

2. Create a new Virtual Machine.

3. Choose QuantOS.iso as the installation source

4. Choose Debian Linux as the Operating System.

	You can configure how much RAM, CPU, and storage the machine has. 
	You probably want to give it at least 4GB of RAM, and two cores.
	You will be asked to create a virtual hard drive for the virtual machine, the file will expand to the max size given as it is used. 
		The base installation only takes around 11GB. 
		Filling the database takes <???>

6. Login with `deb : quants`.

Right now it's just a fancy toolbox, let us know what tools aren't there.
You can turn on and off the VM just like any other program, or set it to run in the background as you access it from the host as if it were another computer on you network.

## FAQ



## Roadmap

- [ ] Scripts to automatically populate the database at boot from various pulbic sources.

- [ ] Installer to automagically get the iso & VM set up.

- [ ] VM template for standard / faster / easier setup.

- [ ] Docker images hosting local web services.

- [ ] Script for building the .iso, so we can collaborate easier & distribute/automate the build process.
