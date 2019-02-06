# Climate-Analysis-App
An analysis of climate data using SQLAlchemy ORM queries, Pandas, Matplotlib, and Flask.

The SQLite database contains precipitation and temperature data collected by numerous stations throughout Hawaii. The database was queried and returned results were explored with Pandas dataframes. Visualizations included:
* Line graph | precipitation over time for a 365-day time span
* Histogram | frequency of temperature observations for a 365-day time span
* Bar chart with error bar | average / min / max temperature for a selected week of the data

A Flask API was designed with routes that return:
* A JSON representation of a dictionary containing each date and precipitation level for the 365-day range
* A JSON list of all stations measuring climate data
* A JSON list of temperature observations for the 365-day range
* A JSON list of the minimum temperature, the average temperature, and the max temperature for a user-given start or start-end range

Analysis presented via a Jupyter notebook and a Flask API.
