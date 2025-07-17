# Walmart-Recruiting---Store-Sales-Forecasting

## პროექტის აღწერა
ამოცანა არის Walmart-ის რამდენიმე მაღაზიისა და განყოფილების ყოველკვირეული გაყიდვების პროგნოზირება 2010-2012 წლების მონაცემების გამოყენებით. შეფასების მეტრიკაა Weighted Mean Absolute Error, სადაც სადღესასწაულო კვირების წონა 5-ჯერ უფრო მაღალია, ვიდრე არასადღესასწაულო კვირების. 

## ჩვენი მიდგომა
1) Data exploration - შევისწავლეთ გაყიდვების კანონზომიერებები, სეზონურობა და დღესასწაულების გავლენა.
2) Feature Engineering - შესაბამისი არქიტექტურებისთვის დავამატეთ ახალი feature-ები, როგორიცაა lag features, სეზონურობის ინდიკატორები და ა.შ.
3) მოდელის არქიტექტურები - გამოვიყენეთ კლასიკური time-based მოდელები (arima, sarima, sarimax, prophet), tree-based მოდელები (lightgbm, xgboost) და deep learning მოდელები ().
4) MLflow ინტეგრაცია - ექსპერიმენტების ტრეკინგისთვის გამოვიყენეთ MLflow.

## რეპოზიტორიის სტრუქტურა

Walmart-Recruiting---Store-Sales-Forecasting/
|
│── EDA.ipynb # მონაცემების ანალიზი
├── model_inference.ipynb  # submission ფაილის დაგენერირება
├── model_experiment_xgboost.ipynb  # XGBoost მოდელის ტრენინგი და MLflow-ზე დალოგვა
├── ... # სხვა მოდელები (XGBoost-ის მსგავსად)
└── README.md
