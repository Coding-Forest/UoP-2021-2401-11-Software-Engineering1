# <span id="top">Unit 1 Research Notes</span>

<br> 

[1.1 What is Software Engineering?](#chapter11)  
[1.2 Software Engineering Lifecycle](#chapter12)  
[1.3 Case Studies](#chapter13)  
[1.4 The Object Model](#chapter14)  


# Reading


<br>

### Key term & concepts

#### People!
  - Fritz Kahn
  - Maurits Cornelis Escher (1898-1972) is one of the world’s most famous graphic artists, known for his socalled impossible structures
  - Reuben Lucius Goldberg (Rube Goldberg) (1883-1970) was a Pulitzer Prize winning cartoonist, sculptor, and author.

1.1
  - software domain vs problem domain (application domain)
  - “coarse graining”: meaning that our abstractions for solution development are unavoidably just approximations (because we are not the experts of the problem domain).
  - The second law of thermodynamics (the universe tends towards increasing disorderOur 
    - Software engineers' (approximate) abstractions necessarily become invalid with passing time and we need to start afresh.

  - software engineering: a a discipline for **solving business problems** by designing and developing software-based systems.
  - "*Software development still largely depends on heroic effort of select few developers. Product line and development standardization are still largely missing, but there are efforts in this direction.*"
    - product development & project management 
 
1.2 
  - *static* domain model
  - unit testing and integration testing
  - Waterfall model (linear and monolithic project life cycle)
  - Prototype vs. working instance
    - "*Incremental and iterative process seeks to get to a working instance as soon as possible (Marsic, 2012).*"
  -  incremental and iterative (or, evolutionary) development methods
    -  Unified process
    -  Agile
<br>
  
  - Modular design
  - Symbol language 
  - Project and product metrics
  - Design heuristics

<br>

  - use case modeling: a popular modelling technique


<br>
 
## <span id="chapter11">1.1 What is Software Engineering?</span>
 
[[👆top]](#top) 
 
#### Software engineering starts from *problem definition* and applies the tools of the trade to find a *problem solution*. 
  - Requires methodology 
  - Manages software development process

#### A software engineer must:
  - understand the customer’s business needs and design software
  - quickly learn new disciplines and business processes

#### Software engineering vs. Programming
  - Software engineering (designing): understanding the business problem, coming up with an idea for solution, and designing the “blueprints” of the solution.
  - Programming (writer): painting the picture on the blueprint. Writing the story in code. Giving a shape to the idea.

#### (Security) risks
After all, dividing the problem into smaller sub-units and conquering them piecewise could run the risk of harboring unforeseen problems that may arise when put together. 
Security risk is also another potential problem that may arise from logical cracks of the fabric.

Risks typically include conditions such as, the program can do what is expected of it and then some more, unexpected capabilities ("*does not guarantee logical rigor and strict consistency between the pieces.*")

<br>

## <span id="chapter12">1.2 Software Engineering Lifecycle</span> 

#### Software development processes

  - Planning / Specification
  - Design
  - Implementation
  - Evaluation 

#### Software development (Marsic, 2012)

  1. Requirements Specification
    - Understanding the usage scenarios and deriving the static domain model
  2. Design
    - Assigning responsibilities to objects and specifying detailed dynamics of their interactions under different usage scenarios
  3. Implementation
    - Encoding the design in a programming language
  4. Testing
    - Individual classes/components (unit testing) and the entire system (integration testing)
  5. Operation and Maintenance
   - Running the system; Fixing bugs and adding new features 

####  incremental and iterative (or, evolutionary) development methods

  1. Break the big problem down into smaller pieces (increments) and *prioritize* them.
  2. In each iteration *progress through* the development in more depth.
  3. Seek the customer *feedback* and change course based on improved understanding.

<br>

"*the key of incremental and iterative methods is to progressively deepen the understanding or “visualization” of the target product, by
both advancing and retracting to earlier activities to rediscover more of its features.*"

<br>

  - All lifecycle processes have a goal of incremental refinement of the product design
  - Unified Process
  - Agile (short iterations and heavy customer involvement)

<br>

1.2.2 Requirements Analysis and System Specification

1) use case modeling: a popular modelling technique

<br>

#### 1.2.3 Object-Oriented Analysis and the Domain Model 
#### 1.2.4 Object-Oriented Design 

*What makes the latter design realistic and what is lacking in the former design? Some observations:
  - The Rube Goldberg design uses complex components (the rabbit, the hound, etc.) with many unpredictable or uncontrollable behaviors; 
  - conversely, a realistic design uses specialized components with precisely controllable functions.

<br>

Recurring issues of software design

  - Design quality evaluation: feasibility of the real-world application
  - Design for 
    - change
    - reuse
    - security
    - testability

<br>

#### 1.2.5 Project Effort Estimation and Product Quality Measurement
  - "*there is a point beyond which only minor improvement in estimation accuracy is brought at a huge cost (known as the law of diminishing returns).*"


<br>

## <span id="chapter13">1.3 Case Studies</span>

[[👆top]](#top) 



<br>

## <span id="chapter14">1.4 The Object Model </span>

[[👆top]](#top) 





<br>

## References
- Marsic, I. (2012). Software engineering. Rutgers Unversity. http://www.ece.rutgers.edu/~marsic/books/SE/book-SE_marsic.pdf. 
