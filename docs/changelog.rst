Changelog
=========

3.2.3
-----

New:

* Timeout
* Indicators: BBUpper and BBLower
* Test script (test.py)

3.2.2
-----

New:

* Indicators: open and P.SAR

3.2.1
-----

New:

* Removed EMA5 and SMA5 from analysis

Bug fix:

* Switched buy/sell on momentum

3.2.0
-----

New:

* Instantiate ``TA_Handler`` using parameters

3.1.6
-----

New:

* Set interval to ``"1d"`` if invalid

3.1.5
-----

New:

* Move indicators to ``Analysis`` class

3.1.4
-----

Bug fix:

* Pull request `#19 <https://github.com/brian-the-dev/python-tradingview-ta/pull/19>`_

3.1.3
-----

New:

* Added user agent
* Added ``__version__`` attribute

3.1.1
-----

Bug fix:

* Pull request `#7 <https://github.com/brian-the-dev/python-tradingview-ta/pull/7>`_

3.1.0
-----

New:

* Set symbol/exchange/screener/interval using functions

3.0.0
-----

New:

* Use scanner (https://scanner.tradingview.com/america/scan) instead of selenium
* Indicators

2.5.0
-----

New:

* Support for Heroku

2.2.0
-----

New:

* Rename ``pair`` to ``symbol``
* Support for Python 3.4
* Added warnings

2.1.0
-----

Bug fix:

* Requirements

2.0.0
-----

New:

* Use class
* Use headless selenium webdriver