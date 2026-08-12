# ETF Portfolio Analysis

A personal project for quantitative portfolio analysis applied to my own ETF investments, with automated reporting.

## Features
- Retrieval of historical market data (yfinance)
- Calculation of performance and risk metrics: return, annualized volatility, Sharpe ratio, maximum drawdown
- Comparative visualization (normalized performance, return/risk cloud)
- Professional risk tearsheet generation via QuantStats (Sharpe, Sortino, Calmar, rolling metrics, drawdown analysis) with benchmark comparison
- Automated generation and sending of a report via email (smtplib), scheduled via a schedule

## Technologies
Python, pandas, yfinance, matplotlib, quantstats, smtplib, schedule

## Background
Project developed to apply Python skills to portfolio risk analysis, as a complement to my AML screening project
([aml-screening-tool](https://github.com/ctngc/aml-screening-tool)).


