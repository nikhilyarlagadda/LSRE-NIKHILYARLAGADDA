<h4>Week 46</h4>
Release Planning is a process of selecting requirements for the next releases based on the priority,development effort estimates and expected revenues[3].As part of releasing planning assignment, 73 issues are provided in the GitHub. Each and every issue is clearly observed. Some of the issues were clearly stated while some I did not understand. The issues that are not so well understood were left and proceed with the next issue. Some questions were raised during this process.

<h4>Week 47</h4>
 In this week, some questions were posted by me in the github are as follows:
 
- <h5>Issue 38 (Participator privileges) </h5>
  - <h5>Issue Description:</h5>It shall be possible to set different privileges for each participator in a course.
  - <h5>Question:</h5>Who are the different participants of the course? On which hierarchy these privileges are assigned to the                                participators?  
- <h5>Issue 53 (Access to edit user database) </h5>
  - <h5>Issue Description:</h5>Course Administrators and System Administrators shall be able to add users to the system. Only System administrators shall be able to remove users from the system.
  - <h5>Question:</h5>In which way the system administrator needs to edit the user database either by internally (i.e. directly communicating with the back-end database) or externally (through an external application i.e. HTML pages which internally communicate with the database)?
- <h5>Issue 8  (Course Information) </h5>
  - <h5>Issue Description:</h5>The product shall provide information to interested authorized system users about courses.
Courses they are registered on (in any function), as well as the general course catalogue.
  - <h5>Question:</h5>How the information regarding the courses should be provided to interested authorized users either by using simple text or by links (so they can view the details of the course)?
If links are used, how the privileges for the user should differ between registered and non-registered courses?
- <h5>Issue 28 (List Courses for User) </h5>
  - <h5>Issue Description:</h5>The product shall be able to list which course(s) a user is participator in.
  - <h5>Question:</h5>Does it need to show the list of courses on the same page (parent page) or should it open in a separate page(Target page) after accessing?
The lists should be displayed in which format either in ordered lists or in unordered lists?
If ordered list which type attribute should be used (1,A,a,I,i) ?
- <h5>Issue 50 (CRUD Course links) </h5>
  - <h5>Issue Description:</h5>It shall be possible to create/read/update/delete links to the list of links attached to a course
Do we need to create a database for links separately or for the entire course (which contains links as a column)?
  - <h5>Question:</h5>Does it notify the users before deleting the links like pop ups ? So that it can avoid the unexpected deletion of links.
- <h5>Issue 16 (Personal Profile) </h5>
  - <h5>Issue Description:</h5>Users in the system shall have a Personal Profile. Allow other users to find contact information. Facilitate interaction between users.
  - <h5>Issue 32  (Access to view Course Info) </h5>
    - <h5>Issue Description:</h5>The Personal Profile shall contain first name, last name, social security number.
Most basic information in order to be able to find information about user in e.g. other systems.
  - <h5>Issue 33  (EditBasic Contents of Personal Profile) </h5>
    - <h5>Issue Description:</h5>It shall be possible to edit the basic contents of a user's personal profile.
  - <h5>Issue 35  (Extra Contents of Personal Profile) </h5>
    - <h5>Issue Description:</h5>The personal profile shall have the following text fields: address, zipcode, city, e-mail address, ICQ UIN, home, mobile, and office phone number, fax number, age, interests, "about me", link to personal homepage.
 - <h5> I assigned a duplicate label. I thought issue #32,#33,#35 were the duplicates of the issue #16.</h5> 

<h5> Week 48 </h5>
   - In this week, i got responses to some of the questions that i have posted.
   - For some of the issues i got clarification for some issues.
   - In previous week, i labeled some issues as a duplicate with issue #16. I got clarified that those issues are not the duplicates of #16 they provide better clarification regarding the issue #16.
   - In the course discussion forum, we have disscussed about the prioritization techniques. i supported the prioritization techniques which doesnot need any experties and previous data.
   
<h5> Week 49 </h5>
  - In this week, I have raised some questions regarding some issues, opened some issues and added requirements for the responses obtained in the week 47.
  -  <h5>Issue 80(Access to delete the message in course discussion forum)</h5>
     -  <h5>Issue Description</h5>Access should be provided to delete the message for the participator who wrote it. So, it enables the participator to remove the redundant messages.
     - I added an enhancement label for this issue because it is an extra feature to the issue 23, along with the responsibility for this issue by assigned it to myself.
  -  <h5>Issue #56 (Access to View Course News)</h5>
     - <h5>Issue Description</h5>Only participators of a course shall be able to view course news. The course news may contain sensitive information that is intended only for course participators.
     - <h5>Question</h5>Does the system need to provide all the sensitive course news to the non-participants of that course also?
     - My reason for raising this question is because there should be a differentiate between previliges among the members and non-members of the course for providing information. this question was raised for better understanding.
  - <h5>Issue 38 (Participator Privileges)</h5>
     - Assigning privileges based on the roles (position power) in a course #37
     - My solution to the question raised by me on Week 46 is providing access based on their power in the course. 
  - <h5>Issue 36(Add/Remove Participators to Course)</h5>
     - <h5>Issue Description</h5>It shall be possible to add/Remove users as participants in a course.
     - <h5>Question</h5>Which users have the power to remove the participants in a course either system administrator or course administrator? As mentioned in the issue #53, if  only system administrator has the power to remove the course participators, can we also extend the power to course administrators along with system administrators?
  - In this week, i have added labels to some issues as clarifications and enhancements. I find the dependicies for one issue, assigned myself as a responsible to some issues.

<h5>week 50</h5>

  - <h5>Issue 102 (Activity Log)</h5>
     - <h5>Description</h5>Through this option, all the participators of the system are able to view their activities they have done in the system.
     - It is a feature which enables the participators to track down their activities.
     - I have create this issue and labeled it as new feature and assigned myself.
  - <h5>Issue 101 (Trash Box)</h5>
     - <h5>Description</h5> There should be a trash box option in the system (like gmail). It contains all the deleted data (links/ course news....) for some period of time, where the administrators of the course and system can check what they have deleted. If they have deleted the data unexpectedly, they can retrieve the data if they feel it is important.
     - I have created this issue and labeled it as enhancement to the issue #50 and assigned this issue to myself.
  - <h5>Issue 85 (Access to delete the message in course discussion form)</h5>
     - <h5>Description</h5>Before deleting the messages/ links/files from the system, there should be a user-friendly message (like pop-up messages) notifying the users about the activities they are doing.
     - Colleague Question Who is the user here?
     - I answered to the question as The participators who are using the system.
 I created this issue and also added an enhancement label to this issue with issue #50. I also assigned this issue .
  - <h5>Issue 112 (Notifications for messages)</h5>
     - <h5>Description</h5>Notifications should be provided to the course participators whenever an activity takes place in the course discussion forum.
     - I have assigned myself as a  reponsible for the issues #52,#23. These mainly focuses about course discussion forum, i taught of adding features to this area so i have created this issue which will be an additional feature to the course discussion forum. I labeled this issue as a feature and assigned myself.
  - By the end of this week i mainly focused on assigning myself to issues releted to same area(Course Discussion Forum) and also created an issue which helps  improving this feature more.
<h5>Week 51</h5>
  - I started assigning myself to the area Course Discussion Forum. Iam intersted in this and took the responsibility for this area.
  - As a part of release planning, i suggested some of the prioritization techniques that are used for the requirements prioritization in the discusiion forum. In this i mainly discussed mainly about the methods like Grouping,Top 10,100-Dollar Test, AHP,Ranking. I also suggested that ranking technique should be used for release planning as it requires individual priority list of stakeholders which does not lead to raise of conflicts among stakeholders. I also mentioned that if class members feel it as a complex technique as no of requirements are more i have suggested an alternative technique is Grouping.
  - Along with the prioritization techniques, attributes of a project also play an important role during the prioritization of requirements.  I have also mentioned some of the  aspects/attributes that need be considered during the requirements prioritization are Cost,Time,Risk,Importance, Volatility.I also raised the question which attributes should be considered for the release planning?.
  - i got response as With the possible exception of "Importance", these all focus on the cost side. Any attributes that will help you define the *value* of a feature?
  - i am clarified that the aspects, i have mention in the course discussion forum comes under the category cost expect importance. I also understood that i have to focus on the attributes that define the value.
  - <h5>Issue 51(Discussion forum message overview)</h5>
   - I also got clarified that it would be better to assign the issues related to the same area. So i assigned myself to the issue #51 that is related to the area course discussion forum.
  - <h5>Issue 59(Access to Discussion Forum)</h5> 
   - There is one more issue #59 related to the area i have chosen. I assigned this issue myself.

<h5> Week 52 and week 1</h5>
- <h5>Issue 69(Course Chatroom)</h5>
  - I assigned myself as a responsible for the issue #69. I thought course chat room is similar to some extent as the course discussion forumn.
- <h5>Issue 85(User-friendly messages)</h5> 
  - I added issue #85 as an enhancement to the issue #80(Access to delete the message in course discussion form). It would be better if a notification is provided for the participator before the deletion of the message.
- <h5>Issue 67(Reply to Message) </h5>
  - I assigned myself to the issue #67 as it is related to the course discussion forum. 
- <h5>Issue 101(Trash Box)</h5> 
  - I already assigned the label enhancement to this issue #101. I have also assigned a new label feature to this issue #101 as it is a new feature in the system which enables the user to retrieve the messages that are deleted.
- <h5>Issue 113(Unread Notifications for messages)</h5> 
  - I changed the label of this issue #113 from feature to enhancement. Initially i thought this would be a new feature to the system after that i realized it could be an enhancement to issue #23(Discussion Forum). 
  - The main aim of this issue #113 is to notify the participators of the course about the messages that are added in the course discussion forum and unread messages. I also added this as an enhancement to the issue #23.
- <h5>Issue 101(Trash Box)</h5>
  - I added this issue as an enhancement to the Issue 80(Access to delete the message in course discussion form ) . THis will act as a source for the participants to retrieve the mesages thata rae deleted by mistake from the course discussion forumn or from the chat box.
  - As a part of this release planning assignment initially 73 issues were created and given. Some of these issues were ambigious,uncertain and not properly structured. while some other requirements are clear. As part of product release process in LSRE it is very important to identify which requirements are provided with clear information and Questions were raised for the requirements which are not clearly described. 
  - Till now i have  concentrated on clarifying the issues,identifying the dependencies and adding the requirements based on the dependencies.
  - Requirements Abstraction model[2] helps me a lot for this process, as it mainly contains four levels 
   - Product level
   - Feature level
   - Functional level
   - Component level
  - This model helped me alot in understanding the level of each requirement given in the course. If it is in the product level then this requirement should have childs in the remaining three levels which is termed as sub requirements and depenedent requirements.The requirements dependencies also play an important role in the releas planning.The no of dependencies between diffrent releases should be less for reducing the complexity[1].
 
  - A group meeting was conducted for discussing about the techniques that should be used for the prioritization of requirements and the factors that should be considered during prioritization. Along with the prioritization, road mapping of the product is also done in the presence of the team members.A road map[3] is a document that provides the layout of a product releases to come over a time frame. This road map contains a total of 6 milestones, in which these requirements are assigned to these milestones and along with that the development life cycle of the entire product is completed.
 
  - For prioritizing the requirements the technique that we opt is grouping[4]. In which we used MoSCoW technique.
  - MoSCoW technique mainly concentrates on delivering the greatest and most immediate business benefits early.In this technique the requirements are classified into four categories They are 
    - Must have: these requirements are critical to the current delivery in order for it to be a success. Even one requirement of this category is not included then the project leads to the failure.
    - Should have: These requirements are important but not necessary for delivery in the current release. These are as important as must but not that much critical as must.
    - Could have: These requirements are desirable but not necessary, and could improve user experience or customer satisfaction for little development cost. These requirements are considered when the time and resources permit.
    - Won't have:These requirements are least critical or not appropriate at the time. These requirements are not considered in the delivery and they are either dropped or reconsidered in the next release.
    
  - All these requirements are prioritized using MoSCoW technique using customer value as a factor among all the milestones.We assumed time and resources are available for doing all the requirements in the milestones.
  - The goal of milestone 1 is "Early version, get the bare minimums up and running so that teachers can at least keep students informed about a course." Among all the requirements the basic requirements which are mainly necessary for delivery the goal of this mile stone are considered in presence of all th team members. A total of 13 requirements come under this milestone. Again among these 13 requirements based on the customer value prioritized using MoSCoW. 
  - <pre> Must Should Could Wont
          8      2     3    0       </pre>
  - The goal of milestone 2 is "The most important features are available, but perhaps not with full functionality". A total of 32 requirements were selcted based on the goal of the milestone. Among these using MoSCoW and customer value the requirements are prioritized.
  - <pre> Must Should Could Wont
          10    14      7    1   </pre>
  - The goal of milestone 3 is "Full functionality for the most important features. All features at least partially implemented". Depending upon this goal atotal of 38  requirements come under this. 
  - <pre> Must Should Could Wont
          11   14    12    1 </pre>
  - The goal of milestone 4 is " All functionality implemented". Based on this goal a total of 13 requirements come under this category.
  - <pre> Must Should Could Wont
          7     5        1    0 </pre>
  - The goal of milestone 5 is " Bugs addressed, most important feedback from earlier releases taken into account.". Based on this goal a total of 3 requirements come under this category.
  - <pre> Must Should Could Wont
            3     0      0    0 </pre>
  - The redundant messages are not considered again during the selection of requirements in milestones. Among all the redundant requirements, one requirement is considered which refers all these redundant requirements. The requirements that i have assigned and taken responsibilty are assigned to the milestones.
  - <h5>All these are assigned to milestone 0.5</h5>
    - Issue 23 (Discussion Forum) 
    - Issue 52 (View/add messages)
    - Issue 59 (Access to Discussion Forum)
    - Issue 67 (Reply to Message)
    - Issue 69 (Course Chatroom)
    - Issue 101 (Trash Box)</pre>
  - <h5> All these are assigned to milestone 0.8 </h5>
    - Issue 51 (Discussion Forum message overview) 
    - Issue 80 (Access to delete the message in course discussion form)
    - Issue 85 (User-friendly messages) 
  - <h5> All these are assigned to milestone 0.9</h5>
    - Issue 102 (Activity Log) 
    - Issue 113 (Unread Notifications for messages) </pre>
  
  
- References:
  - [1]	S. Brinkkemper, “13 Market-Driven Requirements Engineering for Software Products”.
  - [2]	T. Gorschek and C. Wohlin, “Requirements Abstraction Model,” Requir. Eng., vol. 11, no. 1, pp. 79–101, 2006.
  - [3]	P. Carlshamre, K. Sandahl, M. Lindvall, B. Regnell, and J. N. O. Dag, “An industrial survey of requirements interdependencies in software product release planning,” Proc. Fifth IEEE Int. Symp. Requir. Eng., pp. 84–92, 2001.
  - [4]	P. Berander and A. Andrews, “Requirements Prioritization,” in Engineering and Managing Software Requirements SE  - 4, A. Aurum and C. Wohlin, Eds. Springer Berlin Heidelberg, 2005, pp. 69–94.









