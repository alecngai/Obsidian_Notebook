# Terminology 

## SDLC 
	Systems development life cycle

### [Waterfall Model](https://www.javatpoint.com/software-engineering-waterfall-model)
The waterfall is a universally accepted SDLC model. In this method, the whole process of software development is divided into various phases.

The waterfall model is a continuous software development model in which development is seen as flowing steadily downwards (like a waterfall) through the steps of requirements analysis, design, implementation, testing (validation), integration, and maintenance.

Linear ordering of activities has some significant consequences. First, to identify the end of a phase and the beginning of the next, some certification techniques have to be employed at the end of each step. Some verification and validation usually do this mean that will ensure that the output of the stage is consistent with its input (which is the output of the previous step), and that the output of the stage is consistent with the overall requirements of the system.

### [RAD Model](https://www.javatpoint.com/software-engineering-rapid-application-development-model)
RAD or Rapid Application Development process is an adoption of the waterfall model; it targets developing software in a short period. The RAD model is based on the concept that a better system can be developed in lesser time by using focus groups to gather system requirements.

	-   Business Modeling
	-   Data Modeling
	-   Process Modeling
	-   Application Generation
	-   Testing and Turnover

### [Spiral Model](https://www.javatpoint.com/software-engineering-spiral-model)

The spiral model is a **risk-driven process model**. This SDLC model helps the group to adopt elements of one or more process models like a waterfall, incremental, waterfall, etc. The spiral technique is a combination of rapid prototyping and concurrency in design and development activities.

Each cycle in the spiral begins with the identification of objectives for that cycle, the different alternatives that are possible for achieving the goals, and the constraints that exist. This is the first quadrant of the cycle (upper-left quadrant).

The next step in the cycle is to evaluate these different alternatives based on the objectives and constraints. The focus of evaluation in this step is based on the risk perception for the project.

The next step is to develop strategies that solve uncertainties and risks. This step may involve activities such as benchmarking, simulation, and prototyping.

### [V-Model](https://www.javatpoint.com/software-engineering-v-model)
In this type of SDLC model testing and the development, the step is planned in parallel. So, there are verification phases on the side and the validation phase on the other side. V-Model joins by Coding phase.

### [Incremental Model](https://www.javatpoint.com/software-engineering-incremental-model)

The incremental model is not a separate model. It is necessarily a series of waterfall cycles. The requirements are divided into groups at the start of the project. For each group, the SDLC model is followed to develop software. The SDLC process is repeated, with each release adding more functionality until all requirements are met. In this method, each cycle act as the maintenance phase for the previous software release. Modification to the incremental model allows development cycles to overlap. After that subsequent cycle may begin before the previous cycle is complete.

### [Agile Model](https://www.javatpoint.com/software-engineering-agile-model)

Agile methodology is a practice which promotes continues interaction of development and testing during the SDLC process of any project. In the Agile method, the entire project is divided into small incremental builds. All of these builds are provided in iterations, and each iteration lasts from one to three weeks.

Any agile software phase is characterized in a manner that addresses several key assumptions about the bulk of software projects:

1.  It is difficult to think in advance which software requirements will persist and which will change. It is equally difficult to predict how user priorities will change as the project proceeds.
2.  For many types of software, design and development are interleaved. That is, both activities should be performed in tandem so that design models are proven as they are created. It is difficult to think about how much design is necessary before construction is used to test the configuration.
3.  Analysis, design, development, and testing are not as predictable (from a planning point of view) as we might like.

### [Iterative Model](https://www.javatpoint.com/software-engineering-iterative-model)

It is a particular implementation of a software development life cycle that focuses on an initial, simplified implementation, which then progressively gains more complexity and a broader feature set until the final system is complete. In short, iterative development is a way of breaking down the software development of a large application into smaller pieces.

### [Big bang model](https://www.javatpoint.com/software-engineering-big-bang-model)

Big bang model is focusing on all types of resources in software development and coding, with no or very little planning. The requirements are understood and implemented when they come.

This model works best for small projects with smaller size development team which are working together. It is also useful for academic software development projects. It is an ideal model where requirements are either unknown or final release date is not given.

### [Prototype Model](https://www.javatpoint.com/software-engineering-prototype-model)

The prototyping model starts with the requirements gathering. The developer and the user meet and define the purpose of the software, identify the needs, etc.

A '**quick design**' is then created. This design focuses on those aspects of the software that will be visible to the user. It then leads to the development of a prototype. The customer then checks the prototype, and any modifications or changes that are needed are made to the prototype.

Looping takes place in this step, and better versions of the prototype are created. These are continuously shown to the user so that any new changes can be updated in the prototype. This process continue until the customer is satisfied with the system. Once a user is satisfied, the prototype is converted to the actual system with all considerations for quality and security.

#### UAT
	User Acceptance Testing 

#### area charts;
#### bar charts;
#### clustered column charts;
#### combo charts;
#### doughnut charts;
#### funnel charts;
#### gauge charts;
#### line charts;
#### pie charts;
#### scatter plots;
####  waterfall charts.

#### Benchmarkeing 
#### Risk Analysis vs Issue 
	A issue is a risk that has alread happened

#### Selection Bias 
Selection bias is the bias introduced by the selection of individuals, groups or data during the sampling process when randomization is not achieved. This means that the sample we created does not represent the general population properly. It is called ‘selection’ because it refers to the ‘sample selection’.

Selection bias is a very broad term that encompasses many different biases. Here are some examples:

##### Sampling bias

Also known as ‘sample selection bias’ occurs when not everyone in the general population has an equal chance to be in the sample. Let’s say that we want to make a survey about students in one university. We can go to the university, enter random classrooms and ask all of them to participate in our survey. Great, right? Well, not exactly. There are two main issues:

-   We assumed that everyone who is a student at the university will be present at the chosen time and date. And that’s never the case, since students don’t have lectures every day, work part-time, get sick or even go on holiday.
-   We also expected that everyone who is present will want to answer the survey, which is a very optimistic assumption. Students can be forced to, but in that case, one shouldn’t expect a great quality of answers

##### Length time bias

It occurs when different observations in our sample have different development cycles. The most common case is when we are dealing with diseases like cancer. Some types of cancer develop faster than others, so examining 6 months of disease development for 2 different individuals may result in one having no change, while the other passing away. The reason is that they may be in different stages of cancer or different organisms react differently to the disease so time is extremely problematic in general for our sample.

##### Exposure bias

This one is very common and problematic. Imagine you’ve got funding to explore everything about a group of your customers, for instance, female customers. You complete your study and everything is great. However, you are then asked to conduct another study – about the shopping habits of your customers overall. Problem is – you don’t have data on the male customers. Using only the female data would lead you to some results, but they would definitely be problematic. If you are not provided with male data and are forced to complete the study, you will experience exposure bias. This is not uncommon when resources are limited – sampling has been done once and nobody wants to pay for another sampling process.

##### Data bias

There are several popular examples, but one such case is removing outliers with correct data. Usually, we remove the outliers to get better results, but sometimes some important patterns may be contained there.

##### Studies bias

It occurs when we use only the studies, where we have reached a good result. Often, we have formed a hypothesis and we look for studies that support it. In this effort, one could be misled to reference only papers that support their claim and thus introduce a bias. Note that in general academia is extremely biased in that regard. There is research that suggests that papers that reach results are 4 times more likely to be published than papers that have non-satisfactory results. This is very problematic as we know that determining there is ‘no effect’ is still a valid result.

##### Attrition bias

it is related to survivorship bias. The most common example that everyone uses is businesses (e.g. startups). All companies that could be studied are successful (profitable ones). Those that are non-successful seize to exist and cannot be studied.

##### Observer bias

This is the tendency to see what we expect to see – meaning we have already “decided” what outcome we want and we strive for them to be right. As you can sense this one is related to the ‘studies bias’ from above.

Okay. So, there are a lot of problems around selection bias, right?

The best way to get rid of selection bias… is to not introduce our sample to it. No joke, right? What we mean by that is that selection bias is formed in the sampling process. If we are not careful when we collect our data, our analysis will definitely be flawed.