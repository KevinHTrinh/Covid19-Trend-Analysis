# Covid19-Trend-Analysis

README for G17
--------------

File structure:

* G17_extra_graphs (folder) 			<--------- shows extra results more in detail
* G17_csv_data_links.txt 				<--------- links to download the csv files to use in the notebook
* G17_code_and_data.txt				<--------- link to public google colab
* G17_presentation.mp4				<--------- video presentation
* G17_Public_Copy_of_COMP_432_Project.ipynb 	<--------- notebook from google colab downloaded locally
* G17_readme.txt 					<--------- readme for instructions
* G17_report.pdf					<--------- latex report and findings

Our project relies mainly on sklearn, pmdarima, and Prophet.

Our code submission can be found on google collab at:
https://colab.research.google.com/drive/13dn-gJuSn7bq-9iR9t3PEhVhv7QiPOYe?usp=sharing

Notes for Google Colab:

* The google colab notebook can be ran sequentially as is
* GPU is not required.
* Training only takes a few minutes at most.
* The notebook will save the files locally on the google colab and output are shown directly in the notebook

Data was taken from:
* https://www.kaggle.com/mabusalah/brentoilprices
* https://github.com/ishaberry/Covid19Canada/tree/master/timeseries_canada

For preprocessing and training we relied heavily on the tutorial found at:
* https://medium.com/@josemarcialportilla/using-python-and-auto-arima-to-forecast-seasonal-time-series-90877adff03c
* https://www.kaggle.com/mabusalah/brentoilprices

Complete source can be found in the report
