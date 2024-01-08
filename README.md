#  Machine Learning for Humanists:  Course Syllabus
### UCLA DH150, Seminar 2
Winter 2024

### Meeting Times
- Monday
- 2:00pm - 4:50pm
- Rolfe Hall 2118

* **Note:** We will not meet on January 15 and February 19, due to holidays.  Online content will be posted during these weeks for your to review on your own schedule.

## Instructor:

Ben Winjum (bwinjum@oarc.ucla.edu)

## Office Hours: 

* Thursdays 10AM - 12PM and by appointment
    * [Schedule here](https://calendly.com/bwinjum/dh150)

## Course Description
Machine learning is a subset of artificial intelligence and a powerful tool for analyzing and extracting meaningful insights from large datasets, including textual, visual, and cultural artifacts. It is also a technology whose (imagined and actual) applications have raised many questions that must be considered in a humanistic way. Machine learning has allowed for impressive technological strides that span everything from email, search engines, and character recognition to self-driving cars, vaccine creation, and automated surveillance. One can also use machine learning to write essays, identify people in photographs, assess loan or job applications, or perform risk assessment in criminal justice systems, applications that risk propagating bias and are fraught with social and ethical implications. This course will be an introduction to what machine learning is, what some of its implications are, how to apply machine learning as a creative and analytical tool in the humanities, and how to take stock of its advantages, disadvantages, limitations, and potential. The course will be very applied, and students are expected to have a basic understanding of Python or another programming language.

## Course materials & technology

The course materials will consist primarily of Jupyter Notebooks and online readings. The only technology requirement on your part is access to a web browser.

**Jupyter Notebooks:** All class notebooks will accessible on the web at [this GitHub repository](https://github.com/benjum/UCLA-24W-DH150). For the first half of the course, you will be able to run them on the JupyterHub accessible via BruinLearn.  When the computing gets more resource-intensive, we will cover local software installations.  If you anticipate needing accommodations for a computer, please discuss with me.

**Online Readings:** Each week there will be several readings of online content. These will provide context and stimulus for in-class discussions and for our coding activities.

**BruinLearn:** Assignment submissions will take place through our BruinLearn course site, accessible at [bruinlearn.ucla.edu](https://bruinlearn.ucla.edu).

## Evaluation

### Grading Breakdown

| Graded Activities | Percentage | Notes |
| --- | --- | --- |
| Discussion Posts | 10% | Weekly responses to reading |
| Assignments | 60% | Bi-weekly coding assignments |
| Final Project | 30% | Culminating project demonstrating concepts learned throughout course |

### Grading Scheme

| Grade | Range: |
| --- | --- |
| A+ | 100% to 97.0% |
| A | < 97.0% to 93.0% |
| A- | < 93.0% to 90.0% |
| B+ | < 90.0% to 87.0% |
| B | < 87.0% to 83.0% |
| B- | < 83.0% to 80.0%
| C+ | < 80.0 % to 77.0%
| C | < 77.0 % to 73.0%
| C- | < 73.0% to 70.0% |
| D+ | < 70.0% to 67.0% |
| D | < 67.0% to 63.0% |
| D- |< 63.0% to 60.0% |
| F | < 60.0% to 0% |

### Discussion Posts

Each class session will have an assigned reading(s) that you should complete prior to the following class.  I will post a prompt or question on BruinLearn, and you will be required to submit a short discussion post in response to it by 9:00am on the day of the next class.  The posts should be thoughtful and substantive but relatively brief, just a few sentences up to two paragraphs max in length. You’ll get full marks for completing a post that is on-topic. These posts are simply intended to get you thinking about the material. You are also strongly encouraged to read and respond to the posts of your peers, and we will discuss readings in the class after postings have been made.

### Assignments

Assignments will be the majority portion of your grade and consist of coding exercises, short answer questions that reflect on content, and preliminary work to get you moving smoothly towards your culminating final project.

They will be graded according to the following criteria:

* **Does it work?:** Unless you purposefully created code cells that produce errors to make a point, notebook assignments must run from top to bottom without any errors. Verify this by restarting the kernel and running all cells.
* **Does it work correctly?:** It’s possible to write code that runs ok but does not produce the intended results. The code should be bug-free.
* **Cleanliness:** Nobody wants to go through unreadable code! Make sure to document your work accordingly, providing markdown cells and comments throughout.
* **Thinking out of the box:** It is easy to copy an existing notebook and replace datasets and parameters to fulfill an assignment, but how well have you grasped the underlying concepts? This can be demonstrated by *applying* your skills in new ways rather than *copying* each step of a given assignment. For example, you may experiment with functions not demonstrated in class, or create your own workflow that borrows certain concepts learned in class to make them your own.

### Final Project

Your final project will be a combination of a hands-on machine learning coding project and a critical analysis term paper.  I will distribute a more-detailed explanation during the 2nd week, but the final project will involve the following:
1. Choose a dataset of interest to you from a pre-defined list of acceptable datasets (primarily drawn from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/index.php) and [Kaggle](https://www.kaggle.com/))
1. Analyze the dataset and use machine learning to make predictions about the dataset.
1. Summarize and critique articles associated with the dataset, including:
    1. Pros and cons of their analysis
    1. Pros and cons of their machine learning technique
    1. Humanistic and ethical concerns relevant to their analysis
1. Compare your results with the papers' results
    1. They do not have to match!! In fact, I will not expect an exact match.  Simply give a thoughtful explanation of how they make sense together (or don't).

The final product will be a Jupyter notebook/report (1500+ words, not including figure captions) and a short (5-10 minute) presentation of your analysis.

All necessary coding details will be covered over the course of our class.

## Late Work Policy

* If you can not submit something on time, please contact me before a due date and we can make alternative arrangements.
* If we do not make prior arrangements, I will give a one-day grace period on assignments, following which 5% will be deducted from your assignment grade for each subsequent day.
    * Ideally we should make alternative arrangements first before falling into this edge case.
* Final projects are due on Monday March 18, one week after our final in-person class.
  * This is not a flexible deadline unless you discuss with me.

## Weekly Schedule

**Note:** Weekly content is subject to change and will be modified as needed based on class discussions, needs, and progress.

| Week | Technical Topic | Reading |
| :---: | :--- | :--- |
| 1<br>Jan. 8 | <ul><li>Intro to machine learning</li><li>Applications in humanities</li><li>Ethical considerations</li></ul> | <ol><li>["Large-scale physical activity data reveal worldwide activity inequality"](https://doi.org/10.1038/nature23018)</li><li>["Predicting poverty and wealth from mobile phone metadata"](https://doi.org/10.1126/science.aac4420)</li></ul> |
| 2<br>Jan. 15<br>(online content) | <ul><li>Regression</li><li>Feature engineering and selection for humanities data</li></ul> | 1. ["Beyond prediction: Using big data for policy problems."](https://doi.org/10.1126/science.aal4321) |
| 3<br>Jan. 22 | <ul><li>Classification</li><li>Bias</li></ul> | 1. ["Discovering Shifts to Suicidal Ideation from Mental Health Content in Social Media"](https://doi.org/10.1145%2F2858036.2858207)<br>2. ["Mining Eighteenth Century Ontologies: Machine Learning and Knowledge Classification in the Encyclopédie"](http://www.digitalhumanities.org/dhq/vol/3/2/000044/000044.html) | 
| 4<br>Jan. 29 | <ul><li>Decision Trees and Random Forests</li><li>Ensemble Learning</li><li>Interpretability</li></ul> | 1. ["Literary Pattern Recognition: Modernism between Close Reading and Machine Learning"](https://lucian.uchicago.edu/blogs/literarynetworks/files/2015/12/LONG_SO_CI.pdf)<br>2. ["On the Dangers of Stochastic Parrots: Can Language Models Be Too Big?"](https://doi.org/10.1145/3442188.3445922) | 
| 5<br>Feb. 5 | <ul><li>Natural Language Processing</li><li>Large Language Models</li></ul> | ["Mommy Blogs" and the Vaccination Exemption Narrative: Results From A Machine-Learning Approach for Story Aggregation on Parenting Social Media Sites.](https://doi.org/10.2196/publichealth.6586)  | 
| 6<br>Feb. 12 | <ul><li>Unsupervised Learning</li><li>Topic Modeling</li><li>Dimensionality Reduction</li></ul> | 1. ["Missed Connections: What Search Engines Say About Women."](https://safiyaunoble.files.wordpress.com/2012/03/54_search_engines.pdf)<br>2. ["The Algorithm as a Human Artifact: Implications for Legal {Re}Search"](http://dx.doi.org/10.2139/ssrn.2859720) | 
| 7<br>Feb. 19<br>(online content) | <ul><li>Recommendations</li><li>Collaborative filtering</li><li>Search Engines</li></ul> | 1. ["ImageNet: A Large-Scale Hierarchical Image Database."](https://ieeexplore.ieee.org/document/5206848)<br> 2. ["Excavating AI: The Politics of Training Sets for Machine Learning"](https://www.excavating.ai/) | 
| 8<br>Feb. 26 | <ul><li>Deep Learning</li><li>Image analysis, classification, and detection</li></ul> | 1. ["Gender Shades: Intersectional Accuracy Disparities in Commercial Gender Classification"](http://proceedings.mlr.press/v81/buolamwini18a/buolamwini18a.pdf)<br>2. ["Racial Discrimination in Face Recognition Technology"](https://sitn.hms.harvard.edu/flash/2020/racial-discrimination-in-face-recognition-technology/) |
| 9<br>Mar. 4 | <ul><li>Deep Learning II</li><li>Applications to language, time, and artifact</li></ul> | 1. ["Privacy, ethics, and data access: A case study of the Fragile Families Challenge"](https://doi.org/10.1177%2F2378023118813023)<br>2. ["Measuring the predictability of life outcomes with a scientific mass collaboration"](https://doi.org/10.1073/pnas.1915006117)<br>3. ["Stop explaining black box machine learning models for high stakes decisions and use interpretable models instead."](https://doi.org/10.1038/s42256-019-0048-x) | 
| 10<br>Mar. 11 | <ul><li>Reinforcement learning</li><li>Playing games</li><li>Final projects</li></ul> |  | |

## How to ask a technical question

Given the nature of the course, you may have many, many questions along the way. However, please adhere to the following guidelines in order to make consultations as productive as possible. If you do not follow these guidelines, you may be asked to simply reconsider your question.

Before asking a question:

1. Close all open programs, restart your computer, then try your task again
1. Search google and stackoverflow for the topic/problem (for example, the name of the function you’re struggling with or the error message you are seeing)
1. Go back through the relevant lecture materials to look for any insights
1. Go back through the assigned reading materials to look for any insights

If the above steps haven’t solved your problem, send an email (or attend office hours) and include the following information:

1. A **brief** description of what you’re trying to do, why, and how
1. A complete [minimal reproducible example](https://stackoverflow.com/help/minimal-reproducible-example) of your code so far (never send screenshots of code)
    1. This should really be a **minimal** example.  Do not send all of your code; whittle the code down to be as short as possible while still being able to reproduce your error.
1. What you’ve already tried to do to solve your problem and what you have learned from it (specifically, explain the results of steps 1-4 above, including relevant links from stackoverflow etc)

## Readings and Resources

Readings will be posted in the assignment sections for each week. The following are a list of resources to help you with Python and Jupyter as needed:

* [Think Python 2nd Edition](https://greenteapress.com/wp/think-python-2e/) by Allen B. Downey
* [Beginner's Guide to Python](https://wiki.python.org/moin/BeginnersGuide), a list of resources from python.org
* Jupyter Notebooks [Documentation](https://jupyter.readthedocs.io/en/latest/index.html)

## Statement of Affirmation

I intend to make this classroom a space that affirms all identities and perspectives, including your race, color, national origin, ethnic origin, ancestry, marital status, religion, age, sex, gender, gender expression, gender identity, transgender status, pregnancy, physical or mental disability, medical condition, genetic information (including family medical history), sexual orientation, political ideology and affiliations, citizenship, or service in the uniformed services. Regardless of background, all students have a right to an equitable education. Because of the multi-faceted and complex nature of our identities, it is imperative that we are committed to affirming one another’s perspectives as a community for all enrolled in this course. I encourage all members to embrace and learn from the diversity in this classroom, school, and university. I want to highlight that discrimination, harassment, or forms of hateful transgressions will not be tolerated in our learning environment. If you have any recommendations about how to make our environment more inclusive please feel free to let me know.

## Academic Integrity

UCLA is a community of scholars. In this community, we are all responsible for maintaining standards of academic honesty. As a member of the University community, you are expected to demonstrate integrity in your academic endeavors. You are evaluated on your own merits. I encourage interaction whil learning the material, but cheating, plagiarism, collaborative work on written assignments such that you are sharing answers, or other kinds of academic dishonesty are unacceptable and may result in formal disciplinary proceedings, which may result in suspension or dismissal.

**Don’t take chances.** Ask me if you are unclear about UCLA policy. Ignorance is NO defense. In addition, avoid placing yourself in situations which might lead me to suspect you of cheating.

**Alternatives to dishonest behavior:**

* **Seek out help.** Talk with me to see if there is special tutoring or other arrangements to be made.
* **Drop the course.** Can you take it again in the future when you might feel more prepared or less pressured?
* **See a counselor.** UCLA has many resources for students who are feeling the stresses of academic and personal pressures.

You have worked very hard to get here, so don’t cheat! You don’t need to. If you would like more information, please see the Dean of Students’ Office in 1206 Murphy Hall, call (310) 825-3871, or visit their website at www.deanofstudents.ucla.edu.

## Student Resources for Support and Learning

**Providing feedback to me:** I encourage your feedback at any time throughout our winter quarter about things that are helping you learn, or things that aren’t helping. Please communicate with me if there are ways that we can improve the course.

**Personal problems:** Sometimes, factors out of our control make it difficult to focus on schoolwork. If you are having a personal problem that affects your participation, please talk to me so we can create a plan. If you are not comfortable speaking with me directly, please utilize the other student resources provided below in order to understand how to best approach success in this course given your personal needs. Please do not wait until the end of our winter quarter to share any challenges that have negatively impacted you. The sooner we meet, the more options we will have to support your overall academic success.

**Academic accomodations based on a disability:** If you are already registered with the Center for Accessible Education (CAE), please request your Letter of Accommodation on the Student Portal. If you are seeking registration with the CAE, please submit your request for accommodations via the CAE website. Please note that the CAE does not send accommodations letters to instructors–you must request that I view the letter in the online Faculty Portal. Once you have requested your accommodations via the Student Portal, please notify me immediately so I can view your letter. Students with disabilities requiring academic accommodations should submit their request for accommodations as soon as possible, as it may take up to two weeks to review the request. For more information, please visit the CAE website (www.cae.ucla.edu), visit the CAE at A255 Murphy Hall, or contact by phone at (310) 825-1501.

**Campus Resources and Support Services around UCLA Available to Students:**

* **Students in Crisis:** From the Office of the Dean of Students: Faculty and Staff 911 Guide for Students, commonly known as the “Red Folder.” This tool is intended to provide you with quick access to important resources for assisting students in need.
* **Bruin Resource Center:** Includes services for transfer students, undocumented students, veterans, and students with dependents. www.brc.ucla.edu
* **Counseling and Psychological Services Wooden Center West:** (310) 825-0768, www.caps.ucla.edu
* **Letters & Science Counseling Service:** A316 Murphy Hall: (310) 825-1965, www.college.ucla.edu
* **Academics in the Commons at Covel Commons:** (310) 825-9315, free workshops on a wide variety of issues relating to academic & personal success, www.orl.ucla.edu (click on “academics”)
* **Lesbian, Gay, Bisexual and Transgender Resource Center Student Activities Center, B36:** (310) 206-3628, www.lgbt.ucla.edu
* **Center for Accessible Education (Formerly Office for Students with Disabilities):** A255 Murphy Hall: (310) 825-1501, TDD (310) 206-6083; www.cae.ucla.edu
* **Dashew Center for International Students and Scholars:** 106 Bradley Hall: (310) 825-1681, www.internationalcenter.ucla.edu
* **Student Legal Services:** A239 Murphy Hall: (310) 825-9894, www.studentlegal.ucla.edu
* **Dean of Students Office:** 1206 Murphy Hall: (310) 825-3871, www.deanofstudents.ucla.edu
