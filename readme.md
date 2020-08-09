HIFZA SABAB ALI

2K18/CSM/41

SOFTWARE ENGINEERING ASSIGNMENT ( BY SIR GULSHER LAGHARI )

PAPER 1

        LOGCHUNKS AND DATASET FOR BUILD LOG ANALYSIS

PAPER LINK {https://pure.tudelft.nl/portal/files/71450840/paper.pdf}

Q1) Tell about the title, author of the paper, and the conference name where it was published?

TITLE: Logchunks and data set for build log analysis

Authors: Brandt, carolin E; Panichella, Annibale: Zaidman, Beller, Moritz

Publication date: 2020

VENUE: 17th international conference on mining software repositories(MSR'20)


Q2) Introduction and motivation of the paper (what the paper is all about and why it is important)?

This paper is all about building log, continuous integration and build failure. 

BUILD LOGS: build logs are the utmost origin of information for developers when debugging into and understanding a build failure.

CONTINUOUS INTEGRATION: continuous integration has become a standard practice in programming building numerous product
 
utilize persistent coordination to identify bugs. We accept that having a regular informational index to analyze distinctive form log examination will propel 
 
the exploration region, it will at last increment our comprehension of CI fabricate disappointment. In this paper, 
 
we present log pieces, an assortment of 797 explained Travis CI Build logs from 80 GitHub stores in 29 programming dialects, for each form log lumps,

contains physically named log part(chunk) depicting why the manufacture fizzled. we remotely approved the informational collection with creating who caused the manufacture disappointment.

constant coordination produces logs that report the consequences of different sub-ventures inside the construct. these construct logs contain heaps of important data for engineers and specialists. be that as it may,

 structures can be verbose and enormous.

 Q3) (research methodology) how paper gathers and evaluate the results?

Github, Travis ci, popular repositories, logs for failed ci builds, manual labelling (search keywords, structural category)

Travis CI is a facilitated ceaseless combination administration used to fabricate and test programming ventures facilitated at GitHub and Bitbucket.

Travis CI provides various paid plans for private projects and a free plan for open source.

The author physically marked which text lump depicts why the fabricate fizzled. 

Following that, she allowed search watchwords and auxiliary classifications to each log lump.

A chunk that portrays why the build failed. For each repository, the labeller skimmed through the build logs and copied out the first

occurrence of a description of why the build failed. She preserved whitespaces, special characters and search Keywords. 
 
To extract the search keywords, we considered the Chunk and ten lines above and below. The labeller’s task was to note down three strings they would search for (“grep”) to find this failure description. The strings ought to 
 
show up in or around the Chunk and are case-touchy Structural Categories. To mark the basic classifications we introduced the Chunk and the encompassing setting to the labeller for all logs from a repository.

Q4) Results, the main finding and message of this paper?

In this paper, we present LogChunks, a cross-approved informational collection containing 797 build logs from 80 ventures utilizing Travis CI.

For each log, we explained the log piece depicting why the construct fizzled and gave watchwords a designer would use to scan for the log lump,

 just as a classification of the log lumps, as per their configuration inside the log. LogChunks propels the exploration field of assembling log examination by acquainting a benchmark with
 
thoroughly inspect research commitments and opening different exploration prospects that recently required repetitive manual order.



PAPER 2

UNDERSTANDING WHAT SOFTWARE ENGINEERS ARE WORKING ON:

PAPER LINK {https://research.fb.com/wp-content/uploads/2020/05/Understanding-What-Software-Engineers-Are-Working-on.pdf}


Q1) Tell about the title, author of the paper and the conference name where it was published?

TITLE: Understanding What Software Engineers Are Working on.

AUTHORS: Ralf Lämmel, Alvin Kerber and Liane Praza.

CONFERENCE: 28th International Conference on Program Comprehension, ICPC 2020.

Q2) Introduction and motivation of the paper(what the paper is all about and why it is important?

It is about understanding what a software engineer (a designer, an occurrence responder, a creation engineer) is taking a shot at is a difficult issue

particularly while considering the more mind-boggling programming building work processes in programming serious associations: 

i) engineers depend on a huge number (maybe many) inexactly incorporated devices;

ii) engineers take part in simultaneous and moderately long-running work processes; 

iii) foundation, (for example, logging) isn't completely mindful of work things;

iv) building forms (e.g., for episode reaction) are not unequivocally demonstrated. 

In this paper, we clarify the comparing work-thing forecast challenge on the grounds of delegate situations,

report on related endeavours at Facebook, talk about certain exercises learned, and audit-related work to an invitation to battle to use, advance, and join strategies from program appreciation,

mining programming stores, process mining, and AI.

Q3) Research methodology on how paper gathers and evaluate the results?

In this paper, we are worried about a fundamentally the same as the issue with regards to the environments 

and procedures that specialists use to create, to send, and to keep up programming

frameworks: the test of anticipating what work thing a software engineer is working at;
DELEGATE SCENARIOS: 
                                     At Facebook, we have experienced the requirement for and occupied
                            
with endeavours towards tending to the WIP challenge on a few events. 

We presently portray two unique situations in which work-thing expectation is required.

We infuse a few information points or illustrations to underline the characterizing attributes of the WIP challenge.

For non-revelation reasons, we can't report more points of interest of any genuine WIP situations at Facebook,

yet we consider the chose situations as illustrative of what is required in programming escalated associations. 

LEARNED: 
                In light of my work on work-thing prediction on Facebook, we share a few exercises learned. 
                
For nondisclosure reasons, we can't report the exact outcomes on the work-thing forecast. Rather, we centre here around more general discoveries.


Q4) Results (what is the main finding and message of the paper)?

In this paper, we have built up the work-thing expectation challenge, as it applies to program designing work processes in programming serious associations. 

The characterizing attributes of the test are these: 

i) engineers depend on a large number approximately incorporated devices; 

ii) engineers take part in simultaneous and generally long-running work processes; 

iii) foundation isn't completely mindful of work things; 

iv) building forms are not displayed. 

We have given all surrounding related work conversation which associates the work-thing predict challenge

to research in the areas of program appreciation, mining programming storehouses, process mining, and AI.

This conversation reports the requirement for and the capability of utilizing, progressing, and joining 

existing methods to handle the work-thing predict challenge more effectively.


PAPER 3

ON THE RELATIONSHIP BETWEEN USER CHURN AND SOFTWARE ISSUES:

Paper link { https://danielcalencar.github.io/papers/ElZarif_etal_MSR2020.pdf}

Q1) Tell about the title, authors of the paper and conference name where it was published?

TITLE: On the Relationship between User Churn and Software Issues.

AUTHORS: Omar El Zarif, Daniel Alencar Da Costa, Safwat Hassan, Ying Zou.

CONFERENCE: In 17th International Conference on Mining Software Repositories (MSR ’20), October5/6, 2020, Seoul, Republic of Korea. ACM, New York, NY, USA.

Q2) Introduction and motivation of the paper(what the paper is all about and why it is important)?

The fulfilment of clients is just a piece of the achievement of a product item since a solid rivalry can without much of a stretch degrade

clients from a product item. User Churn is the jargon used to indicate when a client changes from administration to the one offered by the opposition.

Here we experimentally researched the connection between the issues that are available in a product item and client stir. 

For this reason, we examine another dataset gave by the alternativeto.net stage. Alternativeto.net has a one of a 

kind element that permits clients to suggest choices for a particular programming item, which flags the goal to change 

starting with one programming item then onto the next. Through our experimental investigation, we saw that;

(I) the aim to change programming is firmly connected with the issues that are available in this product;

(ii) we can anticipate the pace of potential stir utilizing AI models; 

(iii) the more extended the issue takes to be fixed, the higher the odds of client beat; 

(iv) issues inside more broad programming modules are bound to be related with user churn.

Our investigation can give more bits of knowledge into the prioritization of issues that should be fixed to proactively limit the odds of client stir.

Q3) Research methodology how paper gathers and evaluate the results?

The objective of the alternativeto.net site is to assist clients with finding programming options that can all the more likely location

the client's necessities. The principal challenge happens because the client doesn't know about all the accessible programming options.

Likewise, picking an option for programming isn't generally basic, since clients might be as of now acquainted with a lot of highlights (from the product being used), which they might not want to settle.

Considering the .pdf peruser model, while the client wishes a sans freezing elective, the client may feel good to change if the option gives a similar degree of remarking 

capacities (when contrasted with the peruser being used). 

Alternativeto.net permits clients to give audits to programming options alongside evaluations (also to Google Play, which permits surveys to be accommodated portable applications). 

In any case, what sets alternativeto.net separated from different stages is that it permits clients to voice their assessments by putting a product item in context to its rivals.


Q4) Results (what is the main finding and message of the paper)?

In this paper, we study the information accessible on alternativeto.net to more readily comprehend the connection between programming issues and the potential client stir of clients.

Having seen that client concerns are firmly identified with programming issues, we examine the connection between issue reports and the potential client stir of clients.

Our investigation uncovers key issues that must be tended to for the achievement of a product item.

 For instance, we see that the potential client beat of clients might be firmly identified with the absence of vigorous documentation and backing for testing instruments (in the "IDE" and "Web Server" spaces).
 
  At last, our AI models uncover that

(i) the more drawn out the issue takes to be fixed, the higher the odds of client beat;

(ii) issues inside more broad programming segments are bound to be related to client agitate. Then we propose that the current prioritization performed by engineers should be expanded to cover the seemingly perpetual and exceptionally built-in issues.

Our investigation recommends that the prioritization procedure of issues can be improved by considering the potential client stir of clients related to such issues.







