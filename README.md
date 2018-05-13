# [tushare](https://www.tushare.org/) [MooQuant](http://bopo.github.io/mooquant/) Module

This is a very early version of the module. **Live trading is not yet implemented.** Right now, I have only implemented LiveFeed (extends ```barfeed.BaseBarFeed```). Live data is fetched from the trades and order book API endpoint of tushare. Hopefully in the near future, a live broker class will be implemented.

The LiveFeed class can be plugged just as any other bar feed in MooQuant. To subscribe for bid and ask prices, just call ```getOrderBookUpdateEvent().subscribe(<your_callback_function>)``` from the LiveFeed instance. Kindly see example at sample.py.

Liked my work? **Leave me a tip @ 32dzQMkn4RgChSFzemwdYyKJ85PcsVmP6e**

Sample dump:
```

```

This is based on Bitstamp and Xignite module of MooQuant.
# mooquant_tushare
