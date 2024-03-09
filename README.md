# SensorLog
## Retrieve sensor log from Raspberry Pi and graph it
Data is acquired by a 2013 Raspberry Pi Model B 8GB with an attached BMP180 sensor for temperature and barometric pressure.
Measurements are taken with a small Python script that runs every 15 minutes triggered by a cron job. A separate file is created for each calendar month.
This analysis Jupyter notebook runs on a desktop Mac. It retrieves the measurement files and runs some analysis, mainly using pandas library.
Some graphs are saved locally and uploaded to my website www.alvazi.de.