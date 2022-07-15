# Project_3-Montana_uni-
A/B Testing: Improving UX Experience for Montana University

### All code details in Project_code_Montana_library_scipy file

During the sample period from April 3, 2013 – April 10, 2013, which included 10,819 visits to the library homepage, there was a large disparity among the three main content categories. The click-through rate for Find was 35%, Request was 6%, and Interact was 2%. This observation prompted a question: “Why are Interact clicks so low?” At this time the content beneath Interact included links to Reference Services, Instruction Services, Subject Liaisons, Writing Center, About, Staff Directory, Library FAQ, Give to the Library, and Floor Maps. The library’s web committee surmised that introducing this category with the abstract term “Interact” added difficulty and confusion for users trying to navigate into the library website homepage. Four different category titles were then proposed as variations to be tested: Connect, Learn, Help, and Services.

In an A/B Test, one of the tasks that usually belongs to the UX team is to perform user research and develop a new version of the website element that needs to be tested. The team had conversations with a few students and asked the following questions:

Have you previously clicked on Interact?

What content do you expect to see after you select Interact?

Does Interact accurately describe the content that you find after selecting Interact?

Which word best describes this category? Interact? Connect? Learn? Help? Services?


### Summary of work done so far:

1.Data Reading

2.Click Through rate(Defined as clicks / visits: how many visitors to the landing page clicked on the section we are interested in?)

3.Contingency table (A contingency table shows the frequency distribution of the variables.)

4.Scipy approach(used Chi-square Test )



### The hypotheses to be tested in the experiment are the following:

1.Null Hypothesis: all variants have the same CTR.

2.Alternative Hypothesis: there is a difference in the CTR for the different variants.



### How do we decide who's the best?

1.Click-through rate (CTR) for the homepage.

2.Drop-off rate for the category pages.

3.Homepage-return rate for the category pages.



