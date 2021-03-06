<h4>Reflective Report</h4>
<hr>
- <h5>Article Selection</h5> 
  - The articles, i have selected for this assigment reflective report is
    - Requirements Abstraction Model[1]
    - QUPER Model[2]
      
- <h5>References</h5>
  - [1]	T. Gorschek and C. Wohlin, “Requirements Abstraction Model,” Requir. Eng., vol. 11, no. 1, pp. 79–101, 2006.
  - [2]	R. B. S. B, “Requirements Engineering: Foundation for Software Quality,” vol. 9013, pp. 230–246, 2015. 

- <h5>Article 1: Requirements Abstraction Model</h5>
  - <h5> Method description</h5> 
    - The main aim of the RAM is to provide a requirement engineering model that helps professionals with product planning and development. It supports the continuous requirements engineering effort, aimed at taking the requirements at multiple levels as input and offers a structure for breaking down these requirements into detailed ones and vice versa by means of work-up. RAM model is implemented in three steps in requirements engineering
      - Specify: It involves specifying the initial requirement and eliciting enough information about it to specify a number of requirements. Four attributes are manually specified they are 
        - Description: It provides the central essence of the requirement.
        - Reason/Benefit/Rationale: It deals with why the requirement is specified and benefit of the requirement.
        - Risk/Restrictions: This attribute describes the restrictions and risks with the requirements.
        - Title: It reflects the contents of the requirement.
      - Place: It is centered around what abstraction level the now specified requirements reside on. It consists of four abstraction levels they are 
        - Product level: It is the most abstract level. In this requirements are considered abstract enough to be comparable directly to the product strategies.
        - Feature level: It is next level in the model. The requirements on this level are features that the product supports. 
        - Functional level: This requirement should be a descriptive of what a user should be able to perform. It mainly concentrates on the functional activities.
        - Component level: It is the last level in the model. These requirements are of a detailed nature depicting information in detail. These act as a possibility to breakdown functional level requirements into more detail and set the limits to functional level requirement.
      - Abstraction: It involves breakdown of requirement, depending on initial placement of original requirement. The work- process involves the creation of new requirements to the adjacent levels or linking the existing requirements. Two rules are used to do this work-process they are 
        - Rule 1 : NO requirement may exist without having a connection to the product level
        - Rule 2: All requirements have to be broken down to functional level.
      - If the requirements are not specified in the other levels then the additional requirements are specified in the abstraction levels until workup rule R1 and R2 satisfied. A how-to guide is also provided to help how to specify the requirements in the abstract level. 
 - <h5> Article selection and why </h5>
   - The main reason for selecting this article, is because a clear explanation of RAM model is presented, when it is used, why is it used and need for the RAM model. A guide how to implement and connect the requirements to abstract levels is also provided in this article and the description provided about RAM is easy to understand. RAM model contains several steps, each and every step is clearly explained and illustrated with the help of an example. Along with this, the process involved in RAM model is very interesting. After looking into this article, I thought this model would be simple and ease to implement by following the information and guide provided in the article.
 - <h5> Implementation plan:</h5>
   - For implementing this model, I have selected the system online book store. Only three requirements are considered related to online book store system. Finally, RAM model is implemented on three requirements by following how-to guide provided in this article. Each and every step provided for RAM model in this article are implemented on these three requirements.
 - <h5>Execution and proof of concept:</h5>
   - The RAM model is executed on the selected three requirements. The RAM model contains three steps
   
   - Step 1: Specify 
   - This step provides the information about the requirements. It mainly contains four attributes as mentioned. 
    - Requirement 1: 
       - Title: personal profile
       - Description: users in the system shall have a personal profile.
       - Why/Benefit: user wants to store the personal information/ allows the user to provide the personal information.
       - Risk/restriction: only accessible after login 
    - Requirement 2:
      - Title: Search option
      - Description: The users should be able to find information through a search option
      - Why/Benefit: user wants to find the books relevant to the given information
    - Requirement 3:
      - Title: Unsuccessful login
      - Description: If the user enters an incorrect user id and /or password the login page shall be reloaded with information
      - Why/Benefit: feedback will be given to the user/user will get to know he enter wrong details.
      - Risk/Restriction: user may not understand the information
      
  - Step 2: Place
  - This step mainly concentrates on placing the incoming requirement into one abstract level. It contains four abstract levels. They are product, feature, functional and component level.
    - Requirement 1: (personal profile)
      - Abstract level: Feature level
    - Requirement 2: (Search option)
      - Abstract level: Functional level
    - Requirement 3: (Unsuccessful login)
      - Abstract level: Component level 
    
  - Step 3: Abstraction (work-up) 
  - This step helps to create the requirements and to link them to other abstract levels. 
    - Requirement 1: (personal profile: original requirement)
      - Abstract level: Feature level
    - Requirement 4: (Secure product: New requirement)
      - Title: Secure product
      - Description: The product shall prevent the unauthorized users
      - Why/Benefit: unauthorized users are not able to access the system(no of views reduced) 
      - Abstract level: Product level
    - Requirement 5: (Modify/view personal profile: New requirement)
      - Title: Modify/view personal profile
      - Description: The users shall be able to view, modify their information by clicking update button.
      - Why/Benefit: need to change any personal information
      - Abstract level: Function level
    - Requirement 6: (Notification: New requirement)
      - Title: Notification
      - Description: After successful modification of the personal profile, users should be notified.
      - Why/Benefit: users shall know whether the information is changed or not.
      - Risk/Restriction: Notification should be displayed on the screen for 10 sec.
      - Abstract level: Component level
  - The requirement 1 is an original requirement and it is in the feature level. As there are no requirements for this in the other abstract levels. So I have created three more new requirements 4, 5, 6 and placed them in their respective abstract levels.
  
    - Requirement 2: (Search option: original requirement)
      - Abstract level: Functional level
    - Requirement 7: (Accessibility and traceability: New requirement)
      - Title: Accessible and traceability
      - Description: The system shall enable to access any sort of information easily
      - Why/Benefit: increase the traceability and performance of the system
      - Abstract level: Product level
    - Requirement 8: (Relevant information: New requirement)
      - Title: Relevant information
      - Description: The system should provide users to find relevant information
      - Why/Benefit: It enables users to find similar information that is required
      - Risk/Restriction: It should accept only alphabets and with a length of 100. 
      - Abstract level: Feature level
    - Requirement 9: (successful search: New requirement)
      - Title: Successful search
      - Description: After a successful search the information should be display in the same page 
      - Why/Benefit:  It enables the user to see the information.
      - Risk/Restriction: displayed 10 books per page
      - Abstract level: Component level
  - The requirement 2 is an original requirement and it is in the functional level.  As there are no requirements for this in the other abstract levels. So I have created three more new requirements 7, 8, 9 and placed them in their respective abstract levels.
    - Requirement 3: (Unsuccessful login: original requirement)
      - Abstract level: Component level
    - Requirement 4: (Secure product: New requirement)
      - Abstract level: Product level
    - Requirement 1: (personal profile: original requirement)
      - Abstract level: Feature level
    - Requirement 9: (login: New requirement)
      - Title: Login
      - Description: The user must login before the product usage.
      - Why/Benefit: Unauthorized users should not have access to product functionality
      - Risk/Restriction: User may forget login id
      - Abstract level: Function level
  - The requirement 3 is an original requirement and it is in the component level. It has two requirements in the abstract levels. So I have created one new requirement 9 and placed them in the function level. The requirements 1 and 4 are already existing requirements, I have lined them to this requirement without creating a new requirement.
  - <h5>Lessons learned</h5> 
    - It is easy to implement and work out the process. The requirements can be handled easily and can also break the complex requirements from higher level to lower level by using this model. It will be very useful in the context of LSRE and MDRE process.   The problems that, I have faced during the implementation was with placing the requirement into suitable level. 
  - <h5> Reflections</h5> 
    - The reflectionns are compared with one article releated to the RAM model. The observations are almost similar and article also address some other issues. THis model is suitable for LSRE engineering. 

    
  
- <h5>Article 2: QUPER</h5>
  - <h5> QUPER Description</h5>
    - Detailed guidelines for application of QUPER model is presented in 7 steps by considering an example of quality requirements. They are 
      -  Identify candidate quality requirements: It is important to consider the relevant features, market, competitor, and hardware platform capability when defining quality requirements.
      -  Define scale and unit: The quality level is identified with the help of scale and unit.
      -  Identify reference levels: Identify reference levels based on actual products and competing products. Estimations are considered based on the uncertainty level.
      -  Elicit quality breakpoints: For each quality requirement, market expectations should be defined as the values of quality breakpoints.
        -  Utility breakpoint which is the lowest acceptable value in the market 
        -  Saturation breakpoint, representing quality levels that are clearly considered excessive by the market. 
        -  Differentiation breakpoint, values above this breakpoint give a market advantage.
      -  Estimate cost barriers: For each quality requirement, the cost factor is estimated in terms of values of cost barriers. The recommended number of cost barriers are two.
      -  Set candidate requirements: Candidate requirements should be identified and decided for coming releases. Estimates can be given in three forms. They are
        -  Both a good target and a stretch target.
        -  Stretch target, highest accepted value is specified.
        -  Good target, lowest accepted value is specified.
      -  Identify cost dependencies: The other quality requirements that need to be changed if the quality requirement is improved from one breakpoint to another. It is important to identify the cost dependencies. Two factors should be considered during the selection process.
        -  Identifying the list of quality requirements that are cheaper and easier to improve when the one quality requirement is improved.
        -  Identifying the list of quality requirements that are more difficult and expensive to improve when the one quality requirement is improved.
      -  An extra step is Identifying cost dependencies were included in this paper. Dependencies have an impact on the estimated cost of another quality requirement. The cost to improve the quality level for one QR may imply an improved level of quality for other QR. This may lead to a change of other QR cost barriers and which QR to select for the coming release.
  - <h5>Article selection and why</h5>
    - The main reason for selecting this article, is because it is easy to understand. The process carried out in QUPER model is explained clearly. In this article, the steps involved in QUPER model is given clearly with an example. After looking into this article, I thought this model would be interesting and ease to implement by following the steps provided.
 - <h5>Implementation plan:</h5>
For implementing this model, I have selected the system online book store. Only two requirements are considered related to online book store system. Finally, QUPER model is implemented on two requirements. Each and every step provided for QUPER model in this article are implemented on these two
 requirements.

  - <h5>Execution and proof of concept</h5>
    - QUPER model is executed in 7 steps as follows:
      - Identify candidate quality requirements:
        - Quality Requirement 1: The competitor have recently released a product with a response time of 3 sec.
        - Quality Requirement 2: The competitor have recently released a product with a MTTR (mean time to repair) of 60 min.
      - Define scale and unit: 
        - Quality Requirement 1: 
          - Scale: Time
          - Unit: sec
      - Quality Requirement 2: 
          - Scale: Time
          - Unit: min
      - Identify reference levels:
        - Quality Requirement 1: 
          - Product: own product x                Level : 7 sec
          - Product: competitor product y      Level : 6 sec
          - Product: competitor product z	      Level : 2 sec
        - Quality Requirement 2: 
          - Product: competitor product  x           Level :85 min
          - Product: own product y		 Level :80 min
          - Product: competitor product z             Level : 60min
      - Elicit quality breakpoints
        - Quality Requirement 1: 
          - Utility breakpoint : 9 sec
          - Saturation breakpoint: 1sec
          - Differentiation breakpoint: 5sec
        - Quality Requirement 2: 
          - Utility breakpoint : 90 min
          - Saturation breakpoint: 30 min
          - Differentiation breakpoint: 70 min
      - Estimate cost barriers:
        - Quality Requirement 1: 
          - Q (ref) = 7 sec 
          - Q1= 4 sec          new software architecture needed
          - C1= 1 week
          - Q2= 2 sec       new hardware architecture needed
          - C2= 4 weeks
       - Quality Requirement 2: 
          - Q (ref) = 80min
          - Q1= 65 min     new software architecture needed
          - C1= 4 weeks
          - Q2= 40 min     new hardware architecture needed
          - C2= 9 weeks
      - Set candidate requirements:
        - Quality Requirement 1: 
          - Good:4sec    Rationale: Beats most of its competitors
          - Stretch:3 sec  Rationale: beats if software architecture is feasible
        - Quality Requirement 2: 
          - Good:50 min   Rationale: Beats most of its competitors
          - Stretch:45 min   Rationale: beats if software architecture is feasible
      - Identify cost dependencies:
      - The last step in this QUPER model is to identify the dependencies. If the change in system for one quality requirement impacts how many quality requirements are identified in this steps. For this step, I assume that there a total of 9 Quality requirements including the above two quality requirements. 
        - Quality requirement 1: In this case all the 9 requirements are dependent on each other. 
          - Among a total of 3 requirements are easier and cheaper to implement  
          - Among a total of 5 requirements are easier and cheaper to implement  
        - Quality requirement 2: In this case only 7 requirements are dependent on each other. 
          - Among a total of 4 requirements are easier and cheaper to implement  
          - Among a total of 2 requirements are easier and cheaper to implement  
      - After this an expert will identify to implement which dependencies either the easier or harder based on the estimated values and effort.
  - <h5>Lessons learned</h5>
   - The quality attributes play an importnat role in the competiton. Along with the functional attributes, quality attributes should also considerd. This model would be very helpful for the organizations as it easy to implement. It provides a roadmap with a set of releases. It enanbles the product the reach from current position to different level by overcoming the compitetors.
  - <h5> reflections</h5> 
    - In order to compare my observations with the observations of other articles, I have selected an article and compared my observations with it. The article I have selected is
Berntsson Svensson & Olsson “Introducing support for release planning of quality requirements –an industrial evaluation of the QUPER model”
The authors of this article presented an industrial evaluation model in a company and drawn the following conclusions from it.
With the QUPER model we will have an understanding of what is good enough quality in the market and how good our competitors are. They have faced challenge regarding the selection of performance requirements. And they have got a clear idea about how quality requirements are handled practically by overcoming various challenges.
These observations are closely related to my observations and as I have applied the model only for 2 quality requirements, my observations would be more abstract.







