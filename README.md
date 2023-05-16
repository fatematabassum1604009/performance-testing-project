# performance-testing-project
I’ve completed performance test on frequently used API for test App https://restful-booker.herokuapp.com.<br>
Test executed for the below mentioned scenario in server https://restful-booker.herokuapp.com. <br>
<ul>
<li>100 Concurrent Request with 10 Loop Count; Avg TPS for Total Samples is ~ 74 And Total Concurrent API requested: 5000.</li>
<li>200 Concurrent Request with 10 Loop Count; Avg TPS for Total Samples is ~ 133 And Total Concurrent API requested: 10000.</li>
<li>300 Concurrent Request with 10 Loop Count; Avg TPS for Total Samples is ~ 220 And Total Concurrent API requested: 15000.</li>
<li>500 Concurrent Request with 10 Loop Count; Avg TPS for Total Samples is ~ 310 And Total Concurrent API requested: 25000.</li>
</ul>
While executed 300 concurrent request, found  18 request got connection timeout and error rate is 0.36%. <br><br>

<b>Summary:</b> Server can handle almost concurrent 350 API call with almost zero to one (0-1) % error rate.<br><br>
<b>Report for Thread Count 300:</b><br>
