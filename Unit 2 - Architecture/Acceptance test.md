a. “The user interface must be user-friendly and easy to use.”    

This is not testable because there is no objective and quantifiable metrics to measure this. 
The target here is the "user interface". The functionality we want to test for acceptance is "user-friendliness".
This could be measured if there are provided standards that are accepted used industry-wide. 
However, this will be almost impossible due to the flexibility of user-friendly definition. Additionally this will vary extremely from a project to project depending on the type of clients and their level of familiarity with user-interfaces.
 
 <br>
 
b. “The number of mouse clicks the user needs to perform when navigating to any window of the system’s user interface must be less than 10.”    

ATCb.01 Click each clickable tab/button/links to navigate to other windows within the system. (pass)
ATCb.02 Repeat ATCb.01 until there are no buttons to click on the window. 
 
 <br>
 
c. “The user interface of the new system must be simple enough so that any user can use it with a minimum training.”    

This is a similar problem as statement a. Unlike a, however, I think that this problem is simpler than a in the sense that the challenges are more easily quantifiable. 
The goal here is "developing a user interface". The functionality must be "simple". 
The user interface is usually designed to contain components that the user can click to control the features. If we can determine the number of components and features displayed on the interface, and calculate the amount of hours required to complete the training, this is not an impossible task, although the process to design the metrics itself can be costly.
 
 <br>
 
d. “The maximum latency from the moment the user clicks a hyperlink in a web page until the rendering of the new web page starts is 1 second over a broadband connection.”    

ATCd.01 Click the hyperlink and measure the rendering time on console. 
 
 <br>

e. “In case of failure, the system must be easy to recover and must suffer minimum loss of important data.”  
Given that the system is designed to require the user to designate a storage space to back up data...

SYSTEM FAILURE!!!

ATCe.01 Back up user data somewhere in a designated separate storage space. 
ATCe.02 Display recovery options.


<br>

References

Continuous Delivery (2020) How to Write Acceptance Tests https://www.youtube.com/watch?v=JDD5EEJgpHU&ab_channel=ContinuousDelivery
