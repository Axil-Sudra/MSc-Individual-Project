Note: Please request COMPUSTAT credentials from me privately.

Part One: .ipynb files that need to be run in the following order:
- COMPUSTAT - Data Extraction
- Piotroski's F-SCORE Calculation
- Exploratory Data Analysis
- Back-Testing Piotroski's F-SCORE Investment Strategy
- Model Dataset Generation
- Any one of the .ipynb files beginning with 'Model Implementation...' (order does not matter)
- Model - Combined Multilayer Perceptron 

Part Two: .ipynb files that need to be run in the following order:
- SEC EDGAR - Filings' Data Extraction Part 1
- SEC EDGAR - Filings' Data Extraction Part 2
- SEC EDGAR - Filings' Data Extraction Part 3
- Labeling Sentiment of Annual Filings - Lexicon Method
- Labeling Sentiment of Annual Filings - Annual Holding Period Return Method
- Model Implementation - Sentiment Analysis RNN

Note csv files in 'Part One' that constitute as data include:
- NYSE_ticker_list.csv
- fundamentals.csv.csv
- fundamentals_fscore.csv
Note: When any code is to be run, make sure all the input files are in same directory

Note csv files in 'Part Two' that constitute as data include:
- fundamentals_fscore_copy.csv
- loughran_mcdonald_dictionary.csv
Note: When any code is to be run, make sure all the input files are in same directory