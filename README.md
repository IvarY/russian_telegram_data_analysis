# Russian propaganda Telegram channel EDA with sentiment analysis

## How to setup:
1. Create Python 3.9 virtual environment
2. Clone this repository ```git clone https://github.com/IvarY/russian_telegram_data_analysis.git```
3. Install requirements.txt ```pip install -r requirements.txt```
4. In project folder create "channels" folder and put here .csv channel files you want to analyze

## How to use:
Run preprocessing_v2.ipynb

a) For basic data overview: run analysis_v2.ipynb

b) For forward network analysis: run forward_analysis_v1.ipynb

c) For sentiment and reaction analysis:

**If you don't need the sentiment analysis part, you can skip steps 1-5 and in step 6 run cells selectively**

1. Open nlp_v1.ipynb on Google Colaboratory
2. Copy your raw data on your Google Drive (into folder <drive>/HW4-6_python_basics/nlp_v1/input_data or change path in code accordingly)
3. In Colab configuration choose GPU
4. Run notebook
5. Download processed data and put to <project_folder>/data/nlp_v1/output_data
6. Run analysis_v3.ipynb
