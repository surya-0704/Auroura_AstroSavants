
# AstroSavants:

Main file [try3.ipynb](https://github.com/surya-0704/Auroura_AstroSavants/blob/main/try3.ipynb).

To test pre-process and train a model to predict dst labels.

We first studied the solar_wind data by dropping the nan values using 5 number summary and box plot analysis.

Then we have spread the sunspot_smoothed data columns over the course of number of data in solar wind according to the train_a train_b and train_c data lines.

Furthur we replaced the nan values with mean of the not nan vlaues and saved it as nonan_new.csv (present in try2.ipynb).

We have now used this new file to compress the present data from per minute analysis to per hour analysis by taking average over 60 values then added the corresponding label column to the data set and applied linear regression for testing.

To directly access the training data download [training_file.csv](https://drive.google.com/file/d/1kpQE39LR5SGKxlnylFtFZmnYmHX04gW6/view?usp=drive_link)


To see further report analysis see respective .HTML files.





## Authors

- [@surya](https://github.com/surya-0704)
- [@utkarsh](https://github.com/Utkarshgupta56)
- [@ramank](https://github.com/profresher149)
- @nishant
- @ahamd
- @adarsh




