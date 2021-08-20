
<h1>Analyst Ratings API - Finnworlds</h1>

<p><a href="https://finnworlds.com/finance-data/analyst-ratings-api/">The Analyst Ratings API</a> is available through JSON REST API and our databases are also downloadable as an excel or csv file.  Analysts and industry experts share their financial opinion publicly through their reporting. We make this data more accessible by structuring it into our database. We maintain the data on public companies of all sectors and industries. The analyst ratings API is designed to be easy to use for developers to build systems for your applications and platforms.</p>



<p><a href="https://finnworlds.com/">Finnworlds</a> Was set up to make access to financial data more universal. In reality our clients are big enterprises as well as individual developers. We try to offer something for everyone</p>




<p><a href="https://finnworlds.com/pricing">Sign up for an API key</a> to get started with the data right away. We don't have free packages on the website but for students we can do something. Just email us and lets talk about it.</p>



<h2>API Features</h2>



<ul><li><strong>Historical ratings</strong></li><li><strong>Current ratings</strong></li><li><strong>Buy, Sell, Hold and consensus</strong></li><li><strong>Stock Price forecasts</strong></li><li><strong>Analyst success scores</strong></li><li><strong>More can be requested</strong></li></ul>


<h2>How to access the data</h2>



<ul><li><strong>JSON rest API</strong></li><li><strong>Excel CSV download</strong></li><li><strong>PDF reports</strong></li><li><strong>Email link</strong></li></ul>



<h2>Documentation</h2>



Our <a href="https://finnworlds.com/documentation">documentation</a> includes input parameters, output objects with explanation of their meaning, we also provide clear examples on the documentation page of various endpoints and their output. On top of this we have SDKs for Javascript, JQuery, VueJS, Angular, JAVA, PHP, NodeJS, Python, Go, Ruby, C#, R, Strest, Rust, Swift and Scala</p>


<h2>Examples</h2>

https://www.finnworlds.com/api/v1/analystratings?key=YOUR-KEY&stock_ticker_symbol=AAPL,GOOG





        "status": {
        "code": 200,
        "message": "Success."
    },
    "results": [
        {
        "basics": {
            "name": "Apple Inc",
            "stock_ticker_symbol": "AAPL"
            "isin_identifier": "US0378331005"
            "exchange": "nasdaq"
            },
        "output": {
            "averageRecommendation": {
                "current": "1.33",
                "one_month_ago": "1.29",
                "two_months_ago": "1.35",
                "three_months_ago": "1.35"
            },
            "strongBuy": {
                "current": "18",
                "one_month_ago": "19",
                "two_months_ago": "20",
                "three_months_ago": "20"
            },
            "hold": {
                "current": "2",
                "one_month_ago": "2",
                "two_months_ago": "3",
                "three_months_ago": "3"
            },
            "strongSell": {
                "current": "0",
                "one_month_ago": "0",
                "two_months_ago": "0",
                "three_months_ago": "0"
            }
        }
    ]




<p>https://www.finnworlds.com/api/v1/analystratings?key=YOUR-KEY&analyst_firm=JPMorgan</p>




    
        "status": {
        "message": "Success."
    },
    "results": [
        {
        "basics": {
            "analyst_firm": "JP Morgan",
            NO EXAMPLE PROVIDED, CONTACT US FOR EXAMPLES
            }
        }
    ]





<h2>Customer Support</h2>

<p>Need help, have questions? <a href="mailto:support@finnworlds.com">Get in touch with Support</a>.</p>

<h2>Legal</h2>

<p>Use of the Finnworlds website, services like API and database are subject to the&nbsp;<a href="https://finnworlds.com/legal/terms-and-conditions-on-finnworlds-data/">mediastack Terms &amp; Conditions</a></p>
