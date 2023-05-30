# Group project for STAT222 course

The structure of the repository is the folloing: 

```bash
.
├── EDA
│   ├── Final_EDA.html
│   ├── Final_EDA.ipynb
│   ├── ind
│   │   ├── 222_EDA.ipynb
│   │   ├── Dmitri_EDA.ipynb
│   │   ├── charbel_analysis.ipynb
│   │   ├── eda+arima222.ipynb
│   │   └── eda222_zack.ipynb
│   └── pics
│       ├── Number_of_trans_for_popular_items_by_hours.png
│       ├── Number_of_trans_for_popular_items_by_weekdays.png
│       ├── Number_of_transactions_by_hour.png
│       ├── Sales_by_weekdays.png
│       ├── Sales_of_different_goods.png
│       └── Transactions_by_year.png
├── README.md
├── analysis
│   ├── aux_functions.ipynb
│   ├── daily_item_forecast.ipynb
│   ├── daily_lstm_forecast.ipynb
│   ├── test_notebook.ipynb
│   └── weekly_total_forecast.ipynb
└── data
    ├── calendar.json
    ├── shop_1_weather.csv
    ├── stat_222_data
    │   ├── shop_1_items_info.csv
    │   ├── shop_1_transactions.csv
    │   ├── shop_2_items_info.csv
    │   └── shop_2_transactions.csv
    ├── transactions_ds.csv
    └── weather_data.csv
```

Main notebooks with predictions are located in `analysis` folder. In `data` forder you can find information about sales and some additional covariates for the models. Folder `EDA` devoted to prelimitary analysis of the data. 
