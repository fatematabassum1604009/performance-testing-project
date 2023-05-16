# performance-testing-project
I’ve completed performance test on frequently used API for test App https://restful-booker.herokuapp.com.<br>
Test executed for the below mentioned scenario in server https://restful-booker.herokuapp.com. <br>

100 Concurrent Request with 10 Loop Count; Avg TPS for Total Samples is ~ 74 And Total Concurrent API requested: 5000.
200 Concurrent Request with 10 Loop Count; Avg TPS for Total Samples is ~ 133 And Total Concurrent API requested: 10000.
300 Concurrent Request with 10 Loop Count; Avg TPS for Total Samples is ~ 220 And Total Concurrent API requested: 15000.
500 Concurrent Request with 10 Loop Count; Avg TPS for Total Samples is ~ 310 And Total Concurrent API requested: 25000.

While executed 300 concurrent request, found  18 request got connection timeout and error rate is 0.36%. <br><br>

Summary: Server can handle almost concurrent 350 API call with almost zero to one (0-1) % error rate.
