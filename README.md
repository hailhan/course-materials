[canvas_url]: https://canvas.uchicago.edu/courses/63368
[jon_oh]: https://calendar.app.google/yto22DQqDT1KxLDT8

# Principles of Computing 3: Big Data and High Performance Computing for Social Scientists
### Spring 2025 - MACS 30113

| Instructor Information       | TA Information       | TA Information  | Course Information     |
| :-------------               | :-------------       | :------------   | :------------          |
| Jon Clindaniel               | Yunrui Bao           | Pritam Gajbhiye        | Location: 1155 E. 60th Street, Rm. 295   |
| 1155 E. 60th Street, Rm. 215 |                      |                        | Monday/Wednesday Lecture, Friday Lab      |
| jclindaniel@uchicago.edu     | bao0211@uchicago.edu | pgajbhiye@uchicago.edu | 3:00-4:20 PM (CT) |
| **Office Hours:** Drop-In (No appointment needed): Tuesday 2:00-4:00pm <br/><br/> [Schedule an Appointment][jon_oh] Thursday 2:00-4:00pm | **Office Hours:** Tuesday 4:00 - 6:00 PM, 1155 E. 60th St., Room 222 | **Office Hours:** Monday 12:00 - 2:00 PM, 1155 E. 60th St., Room 222 | [Canvas Course Site][canvas_url] |

## Course Description
Computational social scientists increasingly need to grapple with data that is too big and code that is too resource intensive to run on a local machine. Using Python, students in this course will learn how to effectively scale their computational methods beyond their local machines -- optimizing and parallelizing their code across clusters of CPUs and GPUs, both on-premises and in the cloud. The focus of the course will be on social scientific applications, such as: accelerating social simulations by several orders of magnitude, processing large amounts of social media data in real-time, and training machine learning models on economic datasets that are too large for an average laptop to handle.

*Prerequisites: MACS 30111 and MACS 30112, or equivalent.*

## Course Structure
Each week in this course is focused on building a fundamental competency in scalable computing, with an emphasis on Computational Social Science research applications.
All readings, assignments, and resources for each of the class sessions can be accessed on the [Canvas course site][canvas_url]. If you have any questions about the course content, you should post these questions in the Ed Discussion forum for the course, which can be accessed by clicking the "Ed Discussion" tab on the left side of the screen on the Canvas course site. For an overall schedule and syllabus for the course, as well as to access additional course-related files (which we will walk through in in-class activities), consult (and clone/fork) this GitHub Course Repository.

During regular class hours, we will meet for a mixture of lecture, group activities, and in-class coding exercises related to the topic for the day. Attendance and active participation in each of the class sessions is mandatory and is an important component of the final course grade. Students should prepare for each class by reading the assigned readings for the day ahead of class time. All readings are available online and are linked in the course schedule below (and in the corresponding weekly module on Canvas). Starting in Week 2, there will be an additional lab section on Fridays from 3:00-4:20 PM CT, focused on providing additional practice with scalable computing strategies.

In order to practice scalable computing skills and complete the course assignments, we will provide free access to on-premise cluster computing resources, [Amazon Web Services (AWS)](https://aws.amazon.com/) cloud computing resources, and [DataCamp](https://www.datacamp.com/). More information about accessing these resources will be provided to registered students in the first several weeks of the quarter.

## Grading

Each week, we will release an assignment that is designed to give you a chance to further hone the skills you have learned in class. While there will be a total of 8 assignments, we will drop your lowest 2 assignment scores when calculating your final grade. Overall, these assigments are worth 60% of the overall grade. As a capstone assignment for this course, you will have the opportunity to either complete a final exam or a final project, which will count for 30% of the overall grade (you will elect your choice as a part of Assignment 6). Finally, attendance and participation will be worth 10% of the overall grade.

| Course Component                      | Grade Percentage  |
| :-------------                        | :-------------    |
| Assignments (Total: Best 6 of 8)      | 60%               |
| Final Exam **or** Final Project       | 30%               |
| Attendance/Participation              | 10%               |

Grades are not curved in this class or, at least, not in the traditional sense. We use a standard set of grade boundaries:
* 95-100: A
* 90-95: A-
* 85-90: B+
* 80-85: B
* 75-80: B-
* 70-75: C+
* <70: Dealt on a case-by-case basis

We curve only to the extent we might lower the boundaries for one or more letter grades, depending on the distribution of the raw scores. We will not raise the boundaries in response to the distribution.

So, for example, if you have a total score of 82 in the course, you are guaranteed to get, at least, a B (but may potentially get a higher grade if the boundary for a B+ is lowered).

If you would like to be graded on a Pass/Fail (P/F) basis, send a private message to the course staff on the Ed Discussion forum **before the Final Exam / Final Project due date**. A total score of 75 and above in the class will qualify for a "P" in the class.

## Participation Expectations
We expect all students to participate in each class session in person (having read all of the readings listed for the day ahead of class time). Your participation grade (10% of your overall grade in the class) will be based on your engagement and completion of in-class activities.

If, for whatever reason, you cannot attend a class session, send a private message to the course staff **ahead of the class session** on the class Ed Discussion forum. We will evaluate these requests on a case-by-case basis and assign an alternative assignment to make up participation credit for the day.

## Late Assignments
Unexcused Late Assignment Submissions will be penalized 10 percentage points for every hour they are late. For example, if an assignment is due on Wednesday at 11:59pm, the following percentage points will be deducted based on the time stamp of the last commit in your private GitHub assignment repository.

| Example last commit |	Percentage points deducted         |
| ----                | ----                               |
| 12:00am to 12:59am  |	-10 percentage points              |
| 1:00am to 1:59am    | -20 percentage points              |
| 2:00am to 2:59am    | -30 percentage points              |
| 3:00am to 3:59am    | -40 percentage points              |
| ...                 |	...                                |
| 9:00am and beyond   |	-100 percentage points (no credit) |

If, for whatever reason, you need an extension on an assignment deadline, send a private message to the course staff **ahead of the assignment deadline** on the class Ed Discussion forum and we will evaluate these requests on a case-by-case basis.

## Plagiarism on Assignments
Academic honesty is an extremely important principle in academia and at the University of Chicago.
* Writing assignments must quote and cite any excerpts taken from another work.
* If the cited work is the particular paper referenced in the assignment, no works cited or references are necessary at the end of the composition.
* If the cited work is not the particular paper referenced in the assignment, you MUST include a works cited or references section at the end of the composition.
* Any copying of work other than your own will result in a zero grade and potential further academic discipline.
* If we discover that you have shared or posted questions/solutions from any class assignments or exams in a public, online space, this will also result in a zero grade and potential further academic discipline.
* You are permitted to consult with an AI Assistant, such as ChatGPT or GitHub Copilot, as you work on assignments (just note that these tools will not always produce the most scalable or up-to-date responses). If you do use an AI Assistant, you must submit a complete log of the prompts that you used and [properly cite the use of the AI tool](https://apastyle.apa.org/blog/how-to-cite-chatgpt). To get the most out of this class, we recommend that you only use an AI Assistant in the following way:
  - First, write code/text on your own without AI assistance
  - Turn to your AI Assistant if you are stuck and have run out of ideas on how to proceed. Some areas where AI Assistants can be helpful are in idea generation, syntax correction, and providing alternative (potentially more scalable) solutions
  - Critically evaluate AI responses and assess their strength (by consulting course materials and/or writing formal tests for code)
  - Rewrite code/text from scratch (in your own voice) to consolidate what you have learned

If you have any questions about citations, references, or what constitutes plagiarism, consult with your instructor.

## Statement of Diversity and Inclusion
The University of Chicago is committed to diversity and rigorous inquiry from multiple perspectives. The MAPSS, CIR, and Computation programs share this commitment and seek to foster productive learning environments based upon inclusion, open communication, and mutual respect for a diverse range of identities, experiences, and positions.

This course is open to all students who meet the academic requirements for participation. Any student who has a documented need for accommodation should contact Student Disability Services (773-702-6000 or disabilities@uchicago.edu) and the instructor as soon as possible.

## Course Schedule

*Note that there will also be weekly lab sections in Weeks 2-9 on Fridays from 3:00-4:20pm CT in our normal classroom.*

| Week | Day | Topic | Readings | Assignment |
| --- | --- | --- | --- |  --- |
| Week 1: Introduction to Code Optimization and Parallelism | 3/24/2025 | Introduction to the Course + Code Optimization with Numba | [A ~5 minute guide to Numba](https://numba.readthedocs.io/en/stable/user/5minguide.html) | |
|  | 3/26/2025 | Parallel Computational Thinking | [Robey and Zamora 2021 (Chapter 1, through section 1.2)](https://livebook.manning.com/book/parallel-and-high-performance-computing/chapter-1) |   |
| Week 2: Distributed CPU-computing | 3/31/2025 | An Introduction to CPU Hardware and types of CPU Parallelism | Read [Robey and Zamora 2021 (Chapter 1, sections 1.3-1.5)](https://livebook.manning.com/book/parallel-and-high-performance-computing/chapter-1); skim and bookmark the [RCC User Guide](https://rcc-uchicago.github.io/user-guide/) for later reference | |
| | 4/2/2025 | Cluster Computing via Message Passing Interface (MPI) for Python | Read the `mpi4py` ["Introduction"](https://mpi4py.readthedocs.io/en/stable/intro.html), as well as the ["Overview"](https://mpi4py.readthedocs.io/en/stable/overview.html) and ["Tutorial"](https://mpi4py.readthedocs.io/en/stable/tutorial.html) Sections | Due: Assignment 1 (11:59pm) |
|  Week 3: GPU-computing | 4/7/2025 | An Introduction to GPU Programming in Python | Read CuPy ["Overview"](https://docs.cupy.dev/en/stable/overview.html) and ["The basics of CuPy"](https://docs.cupy.dev/en/stable/user_guide/basic.html); (Optionally) skim ["CuPy Interoperability"](https://docs.cupy.dev/en/stable/user_guide/interoperability.html) | |
| | 4/9/2025 | Running Full Data Science Pipelines on GPU Clusters | ["About RAPIDS"](https://rapids.ai/about.html), ["10 Minutes to cuDF"](https://docs.rapids.ai/api/cudf/stable/user_guide/10min.html) | Due: Assignment 2 (11:59pm) |
| Week 4: An Introduction to Cloud Computing and Cloud HPC Architectures | 4/14/2025 | Bursting HPC into the Cloud | Skim for a conceptual introduction to the Cloud (the specific technical details are outdated): [Jorissen and Bouffler 2017](https://pages.awscloud.com/rs/112-TZM-766/images/AWS_Research_Cloud_Program_Letter.pdf) (Ch. 1, 4-7), [Armbrust et al. 2009](https://www2.eecs.berkeley.edu/Pubs/TechRpts/2009/EECS-2009-28.pdf); Read for a vision of contemporary uses of AWS EC2 in Cloud HPC: [HPC Architectural Best Practices](https://docs.aws.amazon.com/wellarchitected/latest/high-performance-computing-lens/general-design-principles.html) (read the "General Design Principles" and "Scenarios" sections) | |
| | 4/16/2025 | An Introduction to Boto3 and Serverless HPC | [Jonas et al. 2019](https://arxiv.org/pdf/1902.03383.pdf), ["What is AWS Lambda"](https://docs.aws.amazon.com/lambda/latest/dg/welcome.html), [Boto3 Documentation (skim "Quickstart" and optionally "Code examples" to familiarize yourself with the syntax)](https://boto3.amazonaws.com/v1/documentation/api/latest/index.html) | Due: Assignment 3 (11:59 PM) |
| Week 5: Architecting Scalable Data Solutions in the Cloud | 4/21/2025 | "Data Lake" Architectures | [*Introduction to AWS Boto in Python*](https://campus.datacamp.com/courses/introduction-to-aws-boto-in-python) (DataCamp Course, Ch. 1-2 and optionally 3-4; Practice working with S3 Data Lake in Python) | |
| | 4/23/2025 | Scalable Database Solutions | ["Which Database to Use When?" (YouTube),](https://youtu.be/KWOSGVtHWqA) Optional: [Data Warehousing on AWS Whitepaper](https://docs.aws.amazon.com/whitepapers/latest/data-warehousing-on-aws/data-warehousing-on-aws.pdf), [Big Data Analytics Options on AWS](https://docs.aws.amazon.com/whitepapers/latest/big-data-analytics-options/welcome.html) | Due: Assignment 4 (11:59 PM) |
| Week 6: Engineering Pipelines for Data Ingestion and Processing | 4/28/2025 | Event-Driven Ingestion and Processing | ["Scalable serverless event-driven architectures with SNS, SQS & Lambda" (YouTube)](https://www.youtube.com/watch?v=8zysQqxgj0I) <br/> Optional: ["Using Lambda with Amazon SQS"](https://docs.aws.amazon.com/lambda/latest/dg/with-sqs.html), ["Fanout to Amazon SQS Queues"](https://docs.aws.amazon.com/sns/latest/dg/sns-sqs-as-subscriber.html), ["Using AWS Lambda with Amazon S3"](https://docs.aws.amazon.com/lambda/latest/dg/with-s3.html) | |
| | 4/30/2025 | Orchestrating large-scale parallel workloads with AWS Step Functions |  ["What is AWS Step Functions?"](https://docs.aws.amazon.com/step-functions/latest/dg/welcome.html) | Due: Assignment 5 (11:59 PM) |
| Week 7: Introduction to Spark for Big Data Workloads| 5/5/2025 | Introduction to EMR and PySpark | ["What is Amazon EMR?"](https://docs.aws.amazon.com/emr/latest/ManagementGuide/emr-what-is-emr.html), ["What is Apache Spark?"](https://spark.apache.org/) (read the home page for a high-level overview of what Spark is)
|| 5/7/2025 | Performing Exploratory Data Analysis at Scale with PySpark |  [*Introduction to PySpark*](https://learn.datacamp.com/courses/introduction-to-pyspark) (DataCamp Course, ch. 1-2) | Due: Assignment 6 (11:59 PM) |
| Week 8: A Deeper Dive into the Spark Ecosystem | 5/12/2025 | Machine Learning with PySpark | [*Introduction to PySpark*](https://learn.datacamp.com/courses/introduction-to-pyspark) (DataCamp Course, ch. 3-4)  |  |
| | 5/14/2025 | Expanding the Spark Universe: SNA and NLP at Scale | Skim through the [GraphFrames Documentation for Python](https://docs.databricks.com/spark/latest/graph-analysis/graphframes/user-guide-python.html) and the [Spark NLP Documentation](https://nlp.johnsnowlabs.com/) | Due: Assignment 7 (11:59 PM) |
| Week 9: Presenting Data and Insights from Large-Scale Data Pipelines | 5/19/2025 | Building and Deploying (Scalable) Public APIs and Web Applications with Flask and AWS Elastic Beanstalk | Read ["What is AWS Elastic Beanstalk?"](https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/Welcome.html) and skim through the [Flask "Forward"](https://web.archive.org/web/20211106135422/https://flask-doc.readthedocs.io/en/latest/foreword.html) as well as the [current documentation](https://flask.palletsprojects.com/) | |
|| 5/21/2025 | Considerations for Visualizing Large Data | ["What is Apache Zeppelin?"](https://zeppelin.apache.org/docs/0.7.3/index.html), ["Introduction to DataShader"](https://datashader.org/index.html) | Due: Assignment 8 (11:59 PM) |
| Week 10: Finals Week  | Date TBD | Capstone Option 1: Final Exam (Time TBD) | | |
|| 5/30/2025 | Capstone Option 2: Final Project | | Due: Final Project (11:59 PM) |


## Works Cited

"10 Minutes to cuDF." https://docs.rapids.ai/api/cudf/stable/user_guide/10min.html. Accessed 2/2023.

"A ~5 minute guide to Numba." https://numba.readthedocs.io/en/stable/user/5minguide.html. Accessed 3/2021.

"About RAPIDS." https://rapids.ai/about.html. Accessed 2/2023.

Armbrust, Michael, Fox, Armando, Griffith, Rean, Joseph, Anthony D., Katz, Randy H., Konwinski, Andrew, Lee, Gunho, Patterson, David A., Rabkin, Ariel, Stoica, Ion, and Matei Zaharia. 2009. "Above the Clouds: A Berkeley View of Cloud Computing." Technical report, EECS Department, University of California, Berkeley.

["Big Data Analytics Options on AWS." July 2021](https://docs.aws.amazon.com/whitepapers/latest/big-data-analytics-options/welcome.html). AWS Whitepaper.

"AWS Elastic Beanstalk Developer Guide." https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/Welcome.html. Accessed 3/2021.

Dalcín, Lisandro. "MPI for Python." https://mpi4py.readthedocs.io/en/stable/index.html. Accessed 2/2023.

["Data Warehousing on AWS." January 2021.](https://docs.aws.amazon.com/whitepapers/latest/data-warehousing-on-aws/data-warehousing-on-aws.pdf) AWS Whitepaper.

"DataShader Documentation." https://datashader.org/index.html. Accessed 3/2021.

"Fanout to Amazon SQS queues." https://docs.aws.amazon.com/sns/latest/dg/sns-sqs-as-subscriber.html. Accessed 3/2022.

"Flask Documentation." https://flask.palletsprojects.com/. Accessed 2/2023.

"Flask Forward." https://web.archive.org/web/20211106135422/https://flask-doc.readthedocs.io/en/latest/foreword.html. Accessed 2/2023.

"GraphFrames user guide - Python." https://docs.databricks.com/spark/latest/graph-analysis/graphframes/user-guide-python.html. Accessed 3/2020.

"HPC Architectural Best Practices." https://docs.aws.amazon.com/wellarchitected/latest/high-performance-computing-lens/general-design-principles.html. Accessed 2/2023.

*Introduction to AWS Boto in Python*. https://campus.datacamp.com/courses/introduction-to-aws-boto-in-python. Accessed 3/2020.

*Introduction to PySpark*. https://learn.datacamp.com/courses/introduction-to-pyspark. Accessed 3/2020.

Jonas, Eric, Schleier-Smith, Johann, Sreekanti, Vikram, and Chia-Che Tsai. 2019. "Cloud Programming Simplified: A Berkeley View on Serverless Computing." Technical report, EECS Department, University of California, Berkeley.

Jorissen, Kevin, and Brendan Bouffler. 2017. *AWS Research Cloud Program: Researcher's Handbook*. Amazon Web Services.

Petrossian, Tony, and Ian Meyers. November 30, 2017. "Which Database to Use When?" https://youtu.be/KWOSGVtHWqA. AWS re:Invent 2017.

Pirtle, Justin. December 8, 2020. "Scalable serverless event-driven architectures with SNS, SQS, and Lambda." https://www.youtube.com/watch?v=8zysQqxgj0I. AWS re:Invent 2020.

Robey, Robert and Yuliana Zamora. 2021. *Parallel and High Performance Computing*. Shelter Island, NY: Manning.

"Spark NLP Documentation." https://nlp.johnsnowlabs.com/. Accessed 3/2021.

"The basics of CuPy." https://docs.cupy.dev/en/stable/user_guide/basic.html. Accessed 2/2023.

"Use an Amazon EMR Studio." https://docs.aws.amazon.com/emr/latest/ManagementGuide/use-an-emr-studio.html. Accessed 2/2023.

"Using AWS Lambda with S3." https://docs.aws.amazon.com/lambda/latest/dg/with-s3.html. Accessed 3/2022.

"Using Lambda with Amazon SQS." https://docs.aws.amazon.com/lambda/latest/dg/with-sqs.html. Accessed 3/2022.

"What is Amazon EMR." https://docs.aws.amazon.com/emr/latest/ManagementGuide/emr-what-is-emr.html. Accessed 3/2020.

"What is Apache Spark?." https://spark.apache.org/. Accessed 2/2023.

"What is Apache Zeppelin?" https://zeppelin.apache.org/docs/0.7.3/index.html. Accessed 2/2023.

"What is AWS Lambda?" https://docs.aws.amazon.com/lambda/latest/dg/welcome.html. Accessed 3/2022.
