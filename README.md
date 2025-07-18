# StockAnalysis

This project is a collection of Jupyter Notebooks for collecting and managing Japanese stock time series data, analyzing with technical indicators (such as moving averages, MACD, RSI, stochastics, etc.), detecting golden/dead crosses, and visualizing the results.

## Main Features
- Automatic collection and management of Japanese stock time series data
- Calculation of technical indicators (moving averages, MACD, RSI, stochastics, Bollinger Bands, etc.)
- Automatic detection of golden cross and dead cross
- Visualization of various indicators (using Plotly)
- Batch analysis of all stocks

## Folder & File Structure
- `getStockDataFrame.ipynb`: For Google Colab. Collects and manages Japanese stock data, prepares datasets, and generates/manages CSV files.
- `CrossSignal.ipynb`: Retrieves stock price data from local or internet sources, detects golden/dead crosses of moving averages, and can process all stocks in batch.
- `createGraph_anaconda.ipynb`: For Anaconda environment. Loads stock price data from local CSV, calculates technical indicators, and visualizes with Plotly.
- `createGraph_googleColabo.ipynb`: For Google Colab. Notebook for graph creation and analysis.
- `stock_code.csv`: List of stock codes, names, and market segments.
- `Prime_data/`, `Standard_data/`, `Growth_data/`: Stock price CSV data for each market segment.
- `result/`: Output files of analysis results.

## Required Libraries
- pandas
- numpy
- talib
- plotly
- pandas_datareader
- Jupyter Notebook or Google Colab

## Usage
1. Open `getStockDataFrame.ipynb` in Google Colab to collect and prepare data.
2. Use `CrossSignal.ipynb` to detect golden/dead crosses.
3. Create and analyze graphs visually with `createGraph_anaconda.ipynb` or `createGraph_googleColabo.ipynb`.

## About the Data
- Stock price CSV data for each market segment is stored in folders such as `Prime_data/`, `Standard_data/`, and `Growth_data/`.
- Stock lists are managed with `stock_code.csv` and `all_stock_data.csv`.


--------------------------------------------------------
このプロジェクトは、日本株の時系列データを収集・管理し、テクニカル指標（移動平均線、MACD、RSI、ストキャスティクスなど）を用いた分析や、ゴールデンクロス・デッドクロスの検出、可視化を行うJupyter Notebook集です。

## 主な機能
- 日本株の時系列データの自動収集・管理
- テクニカル指標の計算（移動平均線、MACD、RSI、ストキャスティクス、ボリンジャーバンド等）
- ゴールデンクロス・デッドクロスの自動判定
- 各種指標のグラフ化（Plotlyによる可視化）
- 全銘柄一括分析

## フォルダ・ファイル構成
- `getStockDataFrame.ipynb`：Google Colab用。日本株のデータ収集・管理、データセットの整備、CSVファイルの生成・管理を行う。
- `CrossSignal.ipynb`：ローカルまたはインターネットから株価データを取得し、移動平均線のゴールデンクロス・デッドクロスを判定。全銘柄に対して一括判定も可能。
- `createGraph_anaconda.ipynb`：Anaconda環境用。ローカルCSVから株価データを読み込み、テクニカル指標を計算し、Plotlyでグラフ化。
- `createGraph_googleColabo.ipynb`：Google Colab用。グラフ作成や分析のNotebook。
- `stock_code.csv`：銘柄コード、銘柄名、市場区分の一覧データ。
- `Prime_data/`, `Standard_data/`, `Growth_data/`：各市場区分ごとの株価CSVデータ。
- `result/`：分析結果の出力ファイル。

## 必要なライブラリ
- pandas
- numpy
- talib
- plotly
- pandas_datareader
- Jupyter Notebook または Google Colab

## 使い方
1. Google Colabで`getStockDataFrame.ipynb`を開き、データ収集・整備を行う。
2. `CrossSignal.ipynb`でゴールデンクロス・デッドクロス判定を実施。
3. `createGraph_anaconda.ipynb`や`createGraph_googleColabo.ipynb`でグラフを作成し、視覚的に分析。

## データについて
- `Prime_data/`, `Standard_data/`, `Growth_data/`などのフォルダに、各市場区分ごとの株価CSVデータが格納されます。
- `stock_code.csv`や`all_stock_data.csv`で銘柄リストを管理しています。

