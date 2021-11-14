# GetStockData
Excel to get stock data (Email for support: luis.roman@digitalXU.com

This tutorial covers excel macro which you can use to download historical data for multiple stock quotes. It is useful when you need to perform detailed technical analysis on stocks you wish to invest. Here source of the data is Yahoo Finance.


  #### EXCEL MACRO FILE
In this excel macro, you have flexibility to play around with the following arguments -

Period You can select the frequency of historical data for stocks - Daily, Weekly, Monthly. By "daily" it refers to every day's low, high and closing price along with volume. Weekly refers to prices at the start of each week (one entry for one week). Similary monthly corresponds to one record for a month
Starting Date Date on which you want historical data starts from
End Date Date on which you want historical data ends with.
Allows specifying multiple stocks. Data to be appended once data for first stock completes.
Stocks Downloader
Output of stocks downloader look like below.
Reason for data for 15th February is not included because stocks specified in the input are US stocks and Nasdaq stock market was closed on that day on eve of Presidents' Day in US. Data for 22nd February was excluded because End Date argument is not inclusive of the date. If you want data for 22nd February, specify 23rd February in the end date argument.

 
Stocks Downloader Output
Fetch Historical Data for Non US Stocks
For US Stocks Yahoo Finance does not require any suffix added in symbols or tickers. You can use it directly. However suffix needs to be entered for non US stocks. See some of the examples below.








Canadian Stocks	Indian Stocks
DOL.TO	RELIANCE.NS
ENGH.TO	TCS.NS
AC.TO	HCLTECH.NSTable below shows a complete list of stock exchanges across world and corresponding suffix used for fetching stock quotes from Yahoo Finance.
Country	Market	Suffix
Argentina	Buenos Aires Stock Exchange (BYMA)	.BA
Austria	Vienna Stock Exchange	.VI
Australia	Australian Stock Exchange (ASX)	.AX
Belgium	Euronext Brussels	.BR
Brazil	Sao Paolo Stock Exchange (BOVESPA)	.SA
Canada	Canadian Securities Exchange	.CN
Canada	NEO Exchange	.NE
Canada	Toronto Stock Exchange (TSX)	.TO
Canada	TSX Venture Exchange (TSXV)	.V
Chile	Santiago Stock Exchange	.SN
China	Shanghai Stock Exchange	.SS
China	Shenzhen Stock Exchange	.SZ
Czech Republic	Prague Stock Exchange Index	.PR
Denmark	Nasdaq OMX Copenhagen	.CO
Egypt	Egyptian Exchange Index (EGID)	.CA
Estonia	Nasdaq OMX Tallinn	.TL
Europe	Euronext	.NX
Finland	Nasdaq OMX Helsinki	.HE
France	Euronext Paris	.PA
Germany	Berlin Stock Exchange	.BE
Germany	Bremen Stock Exchange	.BM
Germany	Dusseldorf Stock Exchange	.DU
Germany	Frankfurt Stock Exchange	.F
Germany	Hamburg Stock Exchange	.HM
Germany	Hanover Stock Exchange	.HA
Germany	Munich Stock Exchange	.MU
Germany	Stuttgart Stock Exchange	.SG
Germany	Deutsche Boerse XETRA	.DE
Greece	Athens Stock Exchange (ATHEX)	.AT
Hong Kong	Hong Kong Stock Exchange (HKEX)***	.HK
Hungary	Budapest Stock Exchange	.BD
Iceland	Nasdaq OMX Iceland	.IC
India	Bombay Stock Exchange	.BO
India	National Stock Exchange of India	.NS
Indonesia	Indonesia Stock Exchange (IDX)	.JK
Ireland	Euronext Dublin	.IR
Israel	Tel Aviv Stock Exchange	.TA
Italy	EuroTLX	.TI
Italy	Italian Stock Exchange	.MI
Japan	Tokyo Stock Exchange	.T
Latvia	Nasdaq OMX Riga	.RG
Lithuania	Nasdaq OMX Vilnius	.VS
Malaysia	Malaysian Stock Exchange	.KL
Mexico	Mexico Stock Exchange (BMV)	.MX
Netherlands	Euronext Amsterdam	.AS
New Zealand	New Zealand Stock Exchange (NZX)	.NZ
Norway	Oslo Stock Exchange	.OL
Portugal	Euronext Lisbon	.LS
Qatar	Qatar Stock Exchange	.QA
Russia	Moscow Exchange (MOEX)	.ME
Singapore	Singapore Stock Exchange (SGX)	.SI
South Africa	Johannesburg Stock Exchange	.JO
South Korea	Korea Stock Exchange	.KS
South Korea	KOSDAQ	.KQ
Spain	Madrid SE C.A.T.S.	.MC
Saudi Arabia	Saudi Stock Exchange (Tadawul)	.SAU
Sweden	Nasdaq OMX Stockholm	.ST
Switzerland	Swiss Exchange (SIX)	.SW
Taiwan	Taiwan OTC Exchange	.TWO
Taiwan	Taiwan Stock Exchange (TWSE)	.TW
Thailand	Stock Exchange of Thailand (SET)	.BK
Turkey	Borsa İstanbul	.IS
United Kingdom	London Stock Exchange	.L
Venezuela	Caracas Stock Exchange	.CR

 
