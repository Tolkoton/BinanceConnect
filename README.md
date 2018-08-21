# BinanceConnect
This is simple tool that allows you to get data from Binance.
Includes test.

You can get trade data as list or as Pandas dataframe.
You can get last n candles or all candles starting from, for example, "1 Feb, 2018"

Details:

__init__(self, currency_pair_dict = {'LTC': 1, 'USDT': 0}, time_interval = Client.KLINE_INTERVAL_2HOUR):

'''Takes in a currency_pair_dict with currency names and balance for each currency and time interval for candles'''

connect(self): 
'''conects to Binance and returns Binance client. You will need to enter you API data here'''

get_candles_list
get_candles_list_all_time
get_n_candles_as_dataframe

get_available_currency_pairs_list(self)
''' returns all currency pairs traded on Binance'''


get_current_buy_price(self, amount = 1):
get_current_sell_price(self, amount = 1):
'''gets price from top offer in current moment'''


