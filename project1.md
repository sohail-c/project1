# **Project 1**
## Description
The purpose of this project is to learn about Software Development Lifecycles (SLDC) and selcecting the appropriate model dependent on particular scenarios. This project will be performed with a group and presented on the GitHub platform.

 ## Types of SLDC
 These are the software development lifecycles that will be chosen to best fit each scenario.
 | SLDC | Description |
 | -----| ------------|
 | Waterfall Model (WM) | Takes specification, development, validation, and evolution into seperate process phases. |
 | Incremental Development (ID) | Interleaves specification, development, and validation. System is developed as a series of versions. |
 | Integration and Configuration (IC) | Relies on reusable code and focuses on configuring and integration to the system. |

## Scenerios
These are the scenarios that will be matched to the appropriate SLDC.
1. **New e- Commerce Site**

    PerfectApparel wants to launch a new e-Commerce site to sell clothes, shoes, and accessories. The company wants to provide an online shopping experience that will attract customers to come back to the site. For example, customers may select their own colors, create their customized design, and quickly find matching outfits. 
Today, PerfectApparel mainly uses in-house templates with its own custom scripting and extensions to create web sites. An interpreter written in Java reads the templates and scripting and generates the appropriate web page based on a customer’s request. Your management expects you to use same tools with minor modifications to generate HTML5 pages and extensions needed for the new features. 
 Your team consists of a combination of developers from your previous projects, new hires, and interns. You will need to define requirements for any template or scripting extensions that you want and schedule their development with a separate group that develops the Java interpreter and related software.
> Key Thoughts: 
>> - Existing tools
>> - Work with a seperate group
>> - Team has mixed skill levels


2. **Dental Office Suite**

    Your good friend, a dentist, asks you to develop a web site for their new clinic. The web site should include common information about the clinic like hours, location, dental staff, and downloadable forms.  At some point in the future, they would like to include an ability to make online appointments, send automated reminders via text messages, and issue discounts. Your friend is flexible with the time when you will deliver software.  They also wish to continually add capabilities to the website in order to draw more patients to their clinic.
> Key Thoughts:
>> - Wants additional featurs in the future
>> - Time flexibility
>> - Casual 

3. **Nuclear Power Plant**

    You have been assigned to oversee the development of software that will monitor the status of a new nuclear power plant.  You have a group of scientists who can provide you with domain knowledge to help you design the software.   
Because of news of previous power plant failures, e.g., Three Mile Island and the more recent Fukushima-1 event in Japan, you want to make sure that the software you are designing will be robust, is able to deal with hardware failure, and can fail safely.  The software is expected to last for a long time (at least 10 years). 
The utility company who owns the power plant allows you to subcontract parts of the software development, but you are ultimately responsible for the overall operation of the software.
> Key Thoughts:
>> - Can work with outside companies
>> - Safety concerns
>> - Robust and long-lasting software needed

4. **Department of Transportation**

   Your company won the contract to develop a distributed application which stores data on the Cloud.  This is in response to a thorough 100 page specifications from the Department of Transportation. The specifications is very detailed in what’s expected from the application. 
Your company has developed similar solutions in the transportation domain on numerous previous occasions, and you have the appropriate experienced staff for the project. You bid on the project to be completed within 18 months based on a team of 10 software engineers.
> Key Thoughts:
>> - Strict specification
>> - Cloud utilization
>> - Expirienced staff
>> - Hard deadline

5. **Reducing Traffic**

    An experienced technology company hires you to manage a new project that incorporates distributed computing and networking with car tracking equipment. The equipment will be used to monitor individual cars (via GPS tracking devices) and general traffic (via sensors and cameras) in both surface streets and freeways.  Transportation officials should also be able to provide real-time traffic updates on digital billboards along the roads.   
    Your team has mainly created proprietary hardware/software solutions in the past. The team has substantially skills in using object-oriented C++ to develop embedded systems.

> Key Thoughts:
>> - Embedded systems
>> - Skilled staff

6. **Educational Game**

    You lead a small experienced team of 7 developers from a gaming company. Your team is responsible for quickly developing educational games based on preliminary and evolving set of requirements.  You have internal and external customers who expect to use your games ASAP for their own testing efforts. You have a team member who participates on educational conferences as well as acts a marketing representative to your customers, the teachers and administrators at your local school district.

> Key Thoughts:
>> - Small team
>> - Small amount of time
>> - Team member is close with stakeholders

7. **Global Health**

    You and your friends won a multi-million dollar grant from a foundation to develop software to address current global challenges.  Your startup company is also eligible to receive further grants if it can demonstrate significant positive impact on the health of the people residing in developing countries.  
    Your whole company currently only has 5 people. You will need to hire team members as part of the development effort. Your starting team consists of 2-3 developers who you know very well from previous projects.

> Key Thoughts:
>> - Small company and team
>> - Hiring more people of unknown competency
>> - More casual setting

## Individual Opinions and Group Desicion
Each scenario will have an opinion and justification by each group member and a final group decision.

### Scenario #1
#### Individual Opinions
| Team Member | SDLC | Justification |
|-------------| ---  | --------------|
| Dom | IC | Since there are existing templates that need to be used, integration and configuration methods would be the best choice. The stakeholders want a familiar software and reusing past code would make the most sense. |
| Sohail | Integration and configuration | This is an ideal scenario for the IC process model as the development team already has their own templates and their team includes developers with previous experience with the companies projects. Using their templates and existing architecture also means that there is consistency between all their sites, making them easier to maintain.
| Joseph | Agile | This is an online based software that will need new features based on evolving requirements. Agile is best for delivering the core functionality of an ever changing online environment, with the ability to deliver quick updates. Incremental would be a 2nd choice, but that one is locked to chronological stages. |
| Justin | ID | It’s a small-scale project and a team that works closely together. Also, an incremental model works better for this type of project because the website can be continually updated and improved based on customer requests. Since most of the work can be done in-house, scheduling for the development of the Java interpreter should not interfere with the rest of the process. |
| Shagufta | Integration and Configuration | This project builds upon existing tools like custom templates, scripting, and a Java-based interpreter, this makes IC the most suitable model. It allows for efficient reuse of code and focuses on configuring the current system with little custom development. |

### Group Decision: Agile with elements of Integration and Configuration
We chose Agile to be the main SDLC for this proposed software, with elements of Integration and Configuration. Agile mainly comes from the evolving, online nature of the software. Being able to deliver on new and improved features based on customer request can happen within this model without scheduling issues. Elements of Integration and Configuration come in due to the preexistence of templates, and the stakeholders desire for familiar and reusable code.

### Alternate Choice: Strictly Integration and Configuration
One alternative we had was the Agile model. We decided against this because the evolving nature does not seem as urgent. The chronological nature of ID ensures a more polished final product, while allowing for future updates.

---

### Scenario #2
#### Individual Opinions
| Team Member | SDLC | Justification |
|-------------| ---  | --------------|
| Dom | ID | Since the stakeholder is a friend, relaxed on time, and wants to make changes in the future; it makes sense to make a usable software and add features later on in newer versions. There is room for improvement to the software in the future in terms of time and functionality. |
| Sohail | Incremental development | Incremental development makes a lot of sense as the model to go with for this scenario. The stakeholder is clear about what features they would like first and are features they would like in the feature. This suits the incremental model as you can create the site with the minimal features the stakeholder wants at launch and then iterate over time, adding more features.|
| Joseph | Agile | This is an online based software, that will gradually need new features based off evolving requirements, specifically the eventual need for online appointments. Agile is best for delivering the core functionality off an ever changing online environment, with the ability to deliver on quick updates. Incremental would be a 2nd choice, but that one is locked to chronological stages. |
| Justin | ID | Since this is a small, individual project for a friend, that also needs to be updated over time, I would choose an incremental, Agile model and work closely with them to get feedback throughout the development process, as well as for any future updates or maintenance. |
| Shagufta | Incremental Development | The web site will start simple but expand over time with features like online appointments and automated reminders. Incremental Development allows the system to grow through manageable versions, accommodating future changes easily. |

### Group Decision: Incremental Development
We decided on Incremental Development. The stakeholder is familiar with us, flexible with timelines, and open to making changes or adding features in the future, which aligns with the Incremental approach of building a core version with features being added overtime.

### Alternate Choice: Agile
One alternate choice we had was the Agile model. We decided against this because the evolving nature does not seem as urgent. The chronological nature of ID ensures a more polished final product, while allowing for future updates.

---

### Scenario #3
#### Individual Opinions
| Team Member | SDLC | Justification |
|-------------| ---  | --------------|
| Dom | WM | Since the software needs to be very reliable and needs to last for over a decade; the waterfall method would be the best choice. Extra effort and time is needed to make sure previous mistakes are not recreated. |
| Sohail | Waterfall | This piece of software is a good fit for being developed with the waterfall model. The fact that the software is for a nuclear power plant means that there are definitely a lot of requirements and features it **needs** to have because of regulations and the like. The more methodical step-by-step approach of the waterfall model also helps ensure that nothing slips through the cracks while developing it. Lastly, the software needs to last a long time, which is one of the strengths of the waterfall model.|
| Joseph | Waterfall | This is a critical infrastructure software that would last for a decade with well-defined requirements. The long but concrete nature of waterfall helps ensures that the software will be delivered with no problems. |
| Justin | WM | Since this is a large-scale project, involving many safety concerns, specialized knowledge, and coordination with different stakeholders (the utility company, scientists, power plant operators, subcontractors), it would be best to use the waterfall model. This model also works best because the software is expected to last for a long time and does not need regular updates. |
| Shagufta | Waterfall Model | This project requires high reliability, safety, and long-term maintainability. The Waterfall Model ensures thorough specification, validation, and documentation at each phase. This is necessary for mission-critical systems like nuclear monitoring software. |

### Group Decision: Waterfall
We decided on the Waterfall model. The software is being developed for a nuclear power plant, which means it must be extremely reliable, long-lasting, and compliant with detailed and strict regulations. The set and stone, chronological nature of Waterfall ensures that the requirements are defined from the beginning, reducing the risk of error. This structured approach is also ideal for this large-scale project with multiple stakeholders and little room for evolution.

### Alternate Choice: Spiral
An alternate choice we had for this software was the Spiral model, which was discussed due to it's emphasis on risk analysis. We chose Waterfall over this due to the desire to not repeat the process with iterations, and deliver one solid deliverable at the end.

---

### Scenario #4
#### Individual Opinions
| Team Member | SDLC | Justification |
|-------------| ---  | --------------|
| Dom | ID | Since this program is ran in the cloud and the project has to be done in 18 months, it would be best get a running system right away and add features later since it is easy to update in the cloud. There is also a small team working on this project so there isn't enough manpower to use the waterfall method efficiently. |
| Sohail | Waterfall | This one is a little less straightforward. I think all three models fit it well to a certain extent. However, I think even given the cloud connectivity of the software and the timeline it fits the the waterfall model best. The clearly defined specifications from the stakeholders and, given the stakeholder and nature of the software, likely want for it to be long-lasting and reliable are two reasons the waterfall model would be appropriate for this product. |
| Joseph | Waterfall | The specifications for this software are thoroughly detailed. The staff are appropriately experienced and there seems to be no possibility of evolving requirements. Waterfall would work best here due to its concrete nature. |
| Justin | ID/WF | Based on the team size and the estimated time of completion, this seems to be a small to medium-scale project, which would be best to complete with an incremental, Agile model. Although, it may be best to use waterfall, since the project has thorough specifications and involves working with a government agency. |
| Shagufta | Waterfall Model | The Department of Transportation provided a long and detailed specification document, which makes the Waterfall Model a strong fit. Since the project requirements are stable, clearly defined, and supported by a team experienced in similar systems, the sequential nature of Waterfall supports predictable planning, implementation, and efficient tracking of deliverables throughout the 18-month development timeline. |

### Group Decision: Waterfall
We decided on the Waterfall model for this software. The requirements are thoroughly detailed, coming from a government agency, which means there is little room for evolving features or change in scope. This aligns with Waterfall's strength of defining requirements clearly and early. The software is also expected to be reliable and last a long time, which is complimented by Waterfall's emphasis on extensive planning, documentation and testing.

### Alternate Choice: Incremental Development
Another choice for this software we decided to pass on was Incremental Development, mainly due to the cloud based nature and scale of the project. We bypassed this because of the detailed requirements that waterfall caters to.

---

### Scenario #5
#### Individual Opinions
| Team Member | SDLC | Justification |
|-------------| ---  | --------------|
| Dom | WM | Since this software is on embedded systems, it would make sense to take the time to perfect the software since it will be impossible to update and fix any bugs. The software also plays an important role in society with traffic updates, so the program has to run flawlessly which requires more time. |
| Sohail | Waterfall | Given the embedded systems nature of the software it makes sense to develop it using the waterfall model. The inability to easily update the software once it is deployed means it is important to get the software as perfected as possible before deploying it, which is a strength of the waterfall model. |
| Joseph | Agile or Incremental | This is a system that can be delivered upon in stages with online functionality. The need for updates justifies the use of agile or incremental. Agile specifically will allow for more cross collaboration between developers. |
| Justin | WF | Since this is a large-scale project involving embedded systems in sensors and cameras for government infrastructure, as well as communication with different stakeholders (transportation officials, the company who hired you), it would be best to use the waterfall model. |
| Shagufta | [Insert] | [Insert] |

### Group Decision: Waterfall
We decided on Waterfall for this piece of software. The software is being developed for embedded systems, which will likely involve sensors and cameras used in traffic infrastructure. This would make updating the systems difficult if it is needed. This caters to the Waterfall life cycle where thorough planning, documentation and testing are conducted before deploying. The system plays an imporant role in society, and therefore should be reliable and error free.

### Alternate Decision: Spiral
We were pretty confident about our choice of waterfall for this model due to the embedded nature. Spiral was mentioned due to it having elements of both Waterfall and Incremental.

---

### Scenario #6
#### Individual Opinions
| Team Member | SDLC | Justification |
|-------------| ---  | --------------|
| Dom | ID | This process is the best choice to get feedback from stakeholders that are connected to the team member that holds relatioships with them. Also, since there is pressure for qucik turnaround time, this would put a working product into the stakeholders' hands faster. |
| Sohail | Incremental development | Given the requirement of quickly launching a version of the product, the incremental model seems like it fits the best. The evolving requirements is another reason to go with the incremental model as it allows the developers to more easily implement new requirements and incorporate feedback from users. |
| Joseph | Agile (Scrum) | The fast-paced nature of this project, the need for simultaneous testing, the small team, and evolving requirements are perfect for the Scrum Agile model. Builds can be delivered to the client in quick fashion as requirements evolve. |
| Justin | ID | For this project, I would choose an incremental model because of the small-scale, the evolving set of requirements, and the need to produce a version of the games quickly. There also aren’t many stakeholders to coordinate with since your team member participates at educational conferences and works with the stakeholders. |
| Shagufta | [Insert] | [Insert] |

### Group Decision: Incremental Development with Elements of SCRUM
We ended up deciding on Incremental Development with integrated parts of SCRUM for this piece of software. The fast-paced timeline and pressure to deliver a working product quickly make it essential to release a basic version early and then build upon it through continuous updates. This approach allows the team to gather feedback from stakeholders early on, especially since one team member already has strong relationships with them. The evolving requirements, small team, and need for frequent iterations are the main strengths of Incremental Development.

### Alternate Decision: SCRUM
An alternate option we discussed was a strictly SCRUM model, which would emphasize the need for testing and evolving requirements. We decided on a mix with the Incremental model because this project would not utilize all aspects of SCRUM.

---

### Scenario #7
#### Individual Opinions
| Team Member | SDLC | Justification |
|-------------| ---  | --------------|
| Dom | ID | Since this is not a big company that needs this program and the team is really small, it would be best to approach this in a more agile way.The team would be working close together and would be developing new versions during the duration of the process. |
| Sohail | Incremental development | The small team size is a sign this project may be a good fit for the more agile incremental model. Additionally the incremental model allows deployment of the product fairly early which means its impact can be seen earlier which can lead to more money/grants earlier as well. |
| Joseph | ID | For this one specifically, the grant specifies that the team could get further funding based off the positive impact of the software, implying the funding should be used for improving the software in the future. I say incremental because the process for adding features seems more defined. |
| Justin | ID (scalable) | Based on the size of the grant, and the function of the software to address global challenges, I would consider this a large-scale project; however, it's a very small team. I think this scenario lends itself to an incremental development model because of the team size, but it needs to be scalable to meet the growth of the company and the evolution of the project. The software is also for large-scale problems, so careful planning is needed to make sure the software is designed properly and functions correctly. |
| Shagufta | [Insert] | [Insert] |

### Group Decision: Incremental Development
We decided on Incremental Development for this piece of software. The small team size and collaborative nature plays to the strengths of Incremental Development, as it allows for close coordination, frequent updatesm and future software evolution. The nature of this projects funding (relying on positive impact to secure further grants), implies the need to release a basic functional version, and update as needed, which Incremental Development allows for. Since the software aims to take on large-scale global challenges, upward scalability is a critical factor to consider. The Incremental Model supports this.

### Alternate Decision: Agile
Another option we discussed for this software was the Agile model. This is mainly due to it also supporting evolving requirements. We decided against it because we assumed there would be a reasonable amount of time in between versions to warrant the chronological stages of the Waterfall model within Incremental Development.

