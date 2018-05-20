# Website-Load-Performance-Testing-Using-jMeter
Apache JMeter is an Apache project that can be used as a load testing tool for analyzing and measuring the performance of a variety of services, with a focus on web applications. Here we used the JMeter tool to test two different ecommerce websites load/performance testing.
Apache JMeter is an Apache project that can be used as a load testing tool for analyzing and measuring the
performance of a variety of services, with a focus on web applications. Here we used the JMeter tool to test
two different ecommerce websites load/performance testing. And also do weather REST API testing by using
this tool.
Here we used four different ecommerce websites Amazon.com, Aliexpress.com, Flipkart.com &
Daraz.com.bd for their load testing performance. For both of the websites we set 100 users thread group with
5 seconds ramp-up time period. Basically, the ramp-up period tells JMeter how long to take to "ramp-up" to
the full number of threads chosen. Here 10 threads are used, and the ramp-up period is 5 seconds, then JMeter
will take 5 seconds to get all 100 threads up and running. Each thread will start 25 (100/5) seconds after the
previous thread was begun. If there are 30 threads and a ramp-up period of 120 seconds, then each successive
thread will be delayed by 4 seconds.
Ramp-up needs to be long enough to avoid too large a work-load at the start of a test, and short enough that
the last threads start running before the first ones finish (unless one wants that to happen).

𝑺𝒕𝒂𝒓𝒕 𝒘𝒊𝒕𝒉 𝑹𝒂𝒎𝒑 − 𝒖𝒑 = 𝒏𝒖𝒎𝒃𝒆𝒓 𝒐𝒇 𝒕𝒉𝒓𝒆𝒂𝒅𝒔 𝒂𝒏𝒅 𝒂𝒅𝒋𝒖𝒔𝒕 𝒖𝒑 𝒐𝒓 𝒅𝒐𝒘𝒏 𝒂𝒔 𝒏𝒆𝒆𝒅𝒆𝒅

By default, the thread group is configured to loop once through its elements. For Amazon.com ecommerce
website we test three different pages. Sign In, Sign Up and TodaysDeal. Firstly we compare between own
pages load testing result for Amazon.com only then analysis four different sites load testing.
Here we use an assertion named response assertion script. We used it because, while testing performance of
websites/ web applications we would want to verify the pages are functioning as expected. But sometimes the
page is too huge for the JMeter test client to download, or sometimes we are not concerned about the contents
of the response page, rather we just want to make sure the page is delivered. So here we used response code
is 200 which means OK.
