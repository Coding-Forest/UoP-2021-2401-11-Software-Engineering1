# Unit 2 Research Notes - Software Requirements and Architecture

<br>

## Key term & concepts

 
 <br>

### Some theory: 

    The term FURPS+ refers to the non-functional system properties:
    - Functionality lists additional functional requirements that might be considered, such as
    security, which refers to ensuring data integrity and authorized access to information
    - Usability refers to the ease of use, esthetics, consistency, and documentation—a system
    that is difficult and confusing to use will likely fail to accomplish its intended purpose
    - Reliability specifies the expected frequency of system failure under certain operating
    conditions, as well as recoverability, predictability, accuracy, and mean time to failure
    - Performance details the computing speed, efficiency, resource consumption, throughput,
    and response time 

<br>

**user acceptance tests (UATs)**
  - A **test case** is a particular choice of input values to be used in testing a program and expected output values.


The key task of requirements engineering is formulating a well-defined problem to solve. A welldefined problem includes  

- A set of criteria (“requirements”) according to which proposed solutions either definitely solve the problem or fail to solve it
- The description of the resources and components at disposal to solve the problem. 


#### Types of requirements

1. Essential: have to be realized to make the system acceptable to the customer.
2. Desirable: highly desirable, but not mandatory requirements
3. Optional: might be realized if time and resources permit
4. Future: will not be realized in the current version of the system-to-be, but should be recorded for consideration in future versions


<br>

Acceptance tests:  
  - Evaluate System in life-like scenarios
  - From perspective of an external user of the system
  - In production-like test environments  

Protocol Driviers:    
  - Translate language of problem domain to interactions with system under test
  - Only part of test infrastructure that understands "how" 
  - Can be effective to "plug-in" different, multiple PDs


**Velocity** 

If in software project estimation size is measured in story points, then the development team’s velocity is defined as the number of user-story points that the
team can complete per single iteration (the unit of time). That is, the velocity represent’s the team’s productivity.

## Reading Notes

<br>

## References
Ivan Marsic (2007) Software Engineering https://www.ece.rutgers.edu/~marsic/books/SE/book-SE_marsic.pdf
