# 230project




1. ETF dataset:

	file name: etf.csv

	source: http://www.kibot.com/historical_data/All_ETFs_Historical_Intraday_Data.aspx
	link on Github: https://github.com/ytlisjsu/230project/blob/62ed76757a6984cc33f823508a16b1f4938a921b/etf.csv


2. ETF word cloud:
	
	2.1 file name: etfwordcloud.ipynb
	
	code link on Github: https://github.com/ytlisjsu/230project/blob/af5fd28edf4f116fc0af91469047b83be5069546/etfwordcloud.ipynb

	2.2 mask file name: comment.png
	
	mask image link on Github: https://github.com/ytlisjsu/230project/blob/af5fd28edf4f116fc0af91469047b83be5069546/comment.png

3. SPY dataset:

	3.1 file name: spy_location_sector_year.xlsx

	source_1: https://en.wikipedia.org/wiki/List_of_S%26P_500_companies
	link on Github: https://github.com/ytlisjsu/230project/blob/e304c7b221afc3833444107d192c6176e5b03b1c/spy_location_sector_year.xlsx

	3.2 file name: spy_weight.xlsx

	source_2: https://www.slickcharts.com/sp500
	link on Github: https://github.com/ytlisjsu/230project/blob/e304c7b221afc3833444107d192c6176e5b03b1c/spy_weight.xlsx


	3.3 file name: spy_location_sector_year_weight.tfl

	joined source_1 and source_2 by Tableau Prep Builder 
	tfl file link on Github: https://github.com/ytlisjsu/230project/blob/9fe989776af011664e2f9413b2a78c650b169a55/spy_location_sector_year_weight.tfl

	3.4 output file name: stock.csv

	link on Github: https://github.com/ytlisjsu/230project/blob/fccd3a7eaae6e3ff29e05679db592240206a78e3/stock.csv

4. SPY weight dashboard by Javascript API to Tableau
	
	4.1 file name: filter.html

	link on Github: https://github.com/ytlisjsu/230project/blob/a4ddcd70d7f19f2880f28c49c6e8be3c5c9d1b7c/filter.html

	4.2 js file name: myJavascript.js

	link on Github: https://github.com/ytlisjsu/230project/blob/a4ddcd70d7f19f2880f28c49c6e8be3c5c9d1b7c/myJavascript.js

	4.3 Tableau Public page link: 

	https://public.tableau.com/views/SP500_weight/stock_weight?:language=en&:display_count=y&:toolbar=n&:origin=viz_share_link


5. SPY and sector ETFs price from 2000 to 04/2021

	5.1 code file name: get_merge_data.ipynb

	collected in Python by pandas_datareader.data library
	link on Github: https://github.com/ytlisjsu/230project/blob/8ac8dc5172a9b62c4ed7f6ba55d3ea2ba3270282/get_merge_data.ipynb

	5.2 output dataset file name: spydata.csv
	
	link on Github: https://github.com/ytlisjsu/230project/blob/0af6eb0f45cedc3fa3f98edfdab20ec026ccdd78/spydata.csv

	5.3 adjust dataset file name: spydata_ir_adjust.csv
	
	link on Github: https://github.com/ytlisjsu/230project/blob/0af6eb0f45cedc3fa3f98edfdab20ec026ccdd78/spydata_ir_adjust.csv

6. Workbook

	file name: 230project.twb

	link on Github: https://github.com/ytlisjsu/230project/blob/2694c0bf3831aa8aa81bf2d17e613f5d99402254/230project.twb

	This workbook must work together with datasets "etf.csv", "spydata_ir_adjust.csv" and "stock.csv"


