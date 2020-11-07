---
layout: post
title: Step by Step Guide line of Web Load Testing using Visual Studio Ultimate 2013
date: 2014-07-06 07:56
author: techforumugm
comments: true
categories: [Performance Tuning]
---
To create a load test we will define user load, specify the web performance tests to use, the type of network and browser simulation to use, and the performance counters and other metrics that we want to collect for the duration of the test.<br /><br />Select <strong>Project | Add Load Test</strong> from the main menu in Visual Studio.<br />                                     <img /><br />In the <strong>New Load Test Wizard</strong>, select the <strong>Next</strong> button to start defining the load test scenario.<br />                                  <img /><br />                                  Figure :Load Test Wizard setup options<br />Enter a name for the scenario like “<strong>CodeProject</strong>” but leave the default think time profile in place.<br />                                 <img /><br />The default uses the think times of the web performance tests as a median value, with a normal distribution used to generate some variation. The goal is a more realistic generation of load on the web site.Click the <strong>Next</strong> button to continue on to the Load Pattern definition screen:<br /><div class="separator" style="clear:both;text-align:center;"><a href="https://www.blogger.com/" style="clear:right;float:right;margin-bottom:1em;margin-left:1em;"><img /></a><a href="https://www.blogger.com/" style="clear:right;float:right;margin-bottom:1em;margin-left:1em;"><img /></a></div>                                    <img /><br /><br />Now we want to keep load of 25 concurrent user. We are going to change the User Count to 25 and Click <strong>Next. </strong>After that Test Mix Model setup screen will appear now select the second option “Based on the number of virtual users”. Read the description of each test mix model by clicking on it and viewing the description that appears on the right-hand side. Select the <strong>Next</strong> button to continue on to the Test Mix screen.<br />                                          <img /><br />Select the <strong>Add</strong> button to Add Test window. Select test from available tests and then select <strong>OK</strong>.<br />                                      <br /><br />We can test the application considering the deployment scenario .Say 75% Real time user will be connected application through LAN, 20% by 3G and 5% 300Kbps LAN. <strong>Network Mix</strong> screen allows you to choose one or more network types and specify the distribution of those types across the tests to be executed by the virtual users. Select the <strong>Network Type</strong> dropdown to see the available options. These are the default list of Network Types but you can customize the network types. Say there are few user who can able to connect very thin bandwidth. So now you have to customize Network types.<br />                                             <img /><br />Application is used by different browser or version then Browser Mix screen allows to specify one or more browser types and specify the distribution. Select the <strong>Next</strong> button to continue on to the Counter Sets screen.<br />                                                  <img /><br />The <strong>Counter Sets</strong> screen allows you to specify the computers and counter sets from which to gather performance counters during the load test.<br />                                                        <img /><br /><a href="https://www.blogger.com/" style="clear:left;float:left;margin-bottom:1em;margin-right:1em;"></a><strong>ASP.NET</strong> and <strong>SQL</strong> counter sets to monitor since we are load testing a website. Note that <strong>Controller Computer</strong> and <strong>Agent Computers</strong> collect some data by default, and that both of these represent the same machine in this case. Once the counter sets have been set, select the <strong>Next</strong> button to continue on to the Run Settings screen.<br />                                                   <br /><strong>Run Settings</strong> for a load test allow you to specify how long the test should run using either time duration or a specific number of test iterations. We will use a <strong>time duration</strong>, but change it from <strong>10</strong> minutes to <strong>5</strong> minute for demonstration purposes. The default sampling rate of 5 you can change as your requirement .Select the <strong>Finish</strong> button to save the load test configuration.<br />                                  <img /><br />Now you can see load test1 configuration according to the scenario1 .You can set multiple scenario according to application requirement.<br />                                                                          <img /><br /><a href="https://www.blogger.com/" style="clear:right;float:right;margin-bottom:1em;margin-left:1em;"></a><a href="https://www.blogger.com/" style="clear:right;float:right;margin-bottom:1em;margin-left:1em;"></a><a href="https://www.blogger.com/" style="clear:right;float:right;margin-bottom:1em;margin-left:1em;"></a><a href="https://www.blogger.com/" style="clear:right;float:right;margin-bottom:1em;margin-left:1em;"></a><a href="https://www.blogger.com/" style="clear:right;float:right;margin-bottom:1em;margin-left:1em;"></a><a href="https://www.blogger.com/" style="clear:right;float:right;margin-bottom:1em;margin-left:1em;"></a>Start the load test by selecting the <strong>Run Test</strong> button from the toolbar.Once the load test initializes and starts its 5-minute run, the load test results window will load with the <strong>Graphs</strong> view visible. By default, you should see four panels showing some key statistics, with some key performance counters listed below that. Data is sampled every 5 seconds by default, but that can be changed in the load test settings.<br /><a href="https://www.blogger.com/" style="clear:left;float:left;margin-bottom:1em;margin-right:1em;"></a><a href="https://www.blogger.com/" style="clear:left;float:left;margin-bottom:1em;margin-right:1em;"></a><a href="https://www.blogger.com/" style="clear:left;float:left;margin-bottom:1em;margin-right:1em;"></a>                                               <img height="39" src="image/png;base64,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" width="221" /><br /><div class="separator" style="clear:both;text-align:center;"><a href="https://techforumugm.files.wordpress.com/2014/07/8cdff-result.jpg" style="margin-left:1em;margin-right:1em;"><img border="0" src="https://techforumugm.files.wordpress.com/2014/07/8cdff-result.jpg" height="133" width="320" /></a></div>                       