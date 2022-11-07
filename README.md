# TTCdelay_timeseries
Time series model predicting incidents

When doing data projects, I often focus on topics and datasets that are familiar to me. As a Torontonian, there is nothing more familiar than Toronto Transit Commission (TTC) delays. If you live in Toronto and have taken transit, you've felt the frustration of the TTC delays.

The TTC has releases data monthly about delays on buses, streetcars and subways on the Toronto Open Data Portal. I mostly use the subway, so I decided to focus on subway data. In this project, I'll organized the data to identify the number of incidents per day. The goal was to create a model to predict the number of incidents per day using historical data.   

Data files

There are three data files downloaded from the Toronto Open Data Portal -- "ttc-subway-delay-codes.xlsx" --"ttc-subway-delay-data-2018.xlsx" --"ttc-subway-delay-data-2019.xlsx"
There needs to be a folder called "combined" in the "Data" folder, because that is where the combined data set will be exported.
There is currently a combined dataset in the folder, but it will get overwritten when you run the jupyter notebook.

How to: When you run the notebook, the "Data" folder needs to be in the current working directory.
