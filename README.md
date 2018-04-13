# JavaAPI

Java trading SDK, a wrapper SDK of FIX API, provides clients with a fully functioning programmable API into the FXCM FX trading platform. The API’s main features are streaming executable FX trading prices, the ability to open/close positions and entry orders as well as set/update/delete stops ands limits. The API Object model is based on the FIX specification for FX (http://fixprotocol.org/) and is very simple and easy to use.

## How to start:
1) A FXCM account. You can apply for a demo account <a href="https://www.fxcm.com/uk/forex-trading-demo/">here</a>. 
2) Download the [package at here](https://apiwiki.fxcorporate.com/api/java/trading_sdk.zip)
3) Documents are in the package at trading_sdk\fxcm-api\javadoc.
4) Sample code at trading_sdk\fxcm-api\src\QATest.java
5) How to run QATest example:
  To run, the following needs to be passed as the program arguments:  <test_command> <loginid> <loginpwd> <connection_name> <hostUrl>
  	test_command is one of the following:
     		LISTEN:    Just listen for message, do not do anything
		 	CMO:       createMarketOrder (previously quoted)
		 	SSLMO:     set Stop/Limit on an open position
		 	USLMO:     update Stop/Limit price on a positon 
		 	DSLMO:     delete Stop/Limit from a position
		 	CEO:       create entry order 
		 	SSLEO:     set Stop/Limit on an entry order
		 	USLEO:     update Stop/Limit on an entry order
		 	DSLEO:     remove Stop/Limit on an entry order
		 	DEO:       remove Entry Order
		 	CLOSEMO:   close positon
		 	UREO:      Update rate on an entry order
		loginid: 
		   	Your Trading statio username
		loginpwd:
		   	Your Trading station password
		connection_name:
		   	"Demo" or "Real"  
		hostUrl: 
		  	http://www.fxcorporate.com/Hosts.jsp 

## Real Case Study:
1. How to build Rsi signal and back testing using FXCM Java API. <a href="https://apiwiki.fxcorporate.com/api/StrategyRealCaseStudy/JavaAPI/FXCM_Java_API_Tutorial_RsiSignal_Strategy.zip" target="_blank"> click here</a>
2. Learn how to build and backtest CCI Oscillator strategy using Java API at <a href="https://apiwiki.fxcorporate.com/api/StrategyRealCaseStudy/JavaAPI/CCIOscillatorStrategy-2.zip">here</a>.
3. Lean how to build and back test Breakout strategy using Java API at <a href="https://apiwiki.fxcorporate.com/api/StrategyRealCaseStudy/JavaAPI/BreakOutStrategy_JavaAPI.zip">here</a>. 
4. Lean how to build and back test Range Stochastic Strategy using Java API at <a href="https://apiwiki.fxcorporate.com/api/StrategyRealCaseStudy/JavaAPI/RangeStochasticStrategy.zip">here</a>. 
5. Lean how to build and back test Mean Reversion Strategy using Java API at <a href="https://apiwiki.fxcorporate.com/api/StrategyRealCaseStudy/JavaAPI/MeanReversionStrategy.zip">here</a>. 

## Note:
o	This is for personal use and abides by our [EULA](https://www.fxcm.com/uk/forms/eula/)

o	For more information, you may contact us: api@fxcm.com
