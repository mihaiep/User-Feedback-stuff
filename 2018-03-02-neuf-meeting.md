## 2018-03-02 User Feedback Team Meeting

## Time Friday, 2018-03-02 at 17:00 UTC / noon ET / 11am CT / 9am PT
### Links
 * Minutes Doc: https://docs.google.com/document/d/1EHbxCOy-tlFAvVqO7r4n8Tu_4c6TnztfO1_dsjMrCRg/edit# 
 * Previous Minutes Doc: https://docs.google.com/document/d/1RoPPTUxR9xtZ_3NS4Z5P8mXHZrKyGz3jwGPnD9hpjlA/edit#(public session)
 * Recording:https://www.youtube.com/watch?v=UwIk56lzytQ 
 * https://github.com/nodejs/user-feedback/tree/master/data/2018-02-benchmarking-wg-survey
## Agenda
### Extracted from neuf-agenda labelled issues and pull requests from the user-feedback repo prior to the meeting.
* Intro / Attendance
*	Key Initiatives
 * 	2017 Benchmarking WG Survey (ref: #22)
 * 	End User Feedback - Looking for Participants (ref: #20)
 * 	Enterprise Advisory Group (ref: #18)
 * 	Benchmarking WG Survey - landing data (ref: #22)
 * 	Diagnostics WG survey?
 * 	Node.js Tooling User Feedback
 * 	Closing Thoughts
### Invited
•	Dan Shaw (@dshaw - User Feedback Champion, CommComm observer)
•	Mike Hostetler (@mikehostetler - User Feedback member)
•	Mihai Ene-Pietrosanu (@mihaiep, User Feedback member)
•	William Kapke (@williamkapke - CommComm, User Feedback member)
•	Michael Dawson (@mhdawson, TSC Chair, CommComm, User Feedback member)
•	Tierney Cyren (@bnb - CommComm Co-Chair)
•	Greg Wallace (@gtewallace - Node.js Foundation)
Present
•	Dan Shaw (@dshaw - User Feedback Champion, CommComm observer)
•	Mihai Ene-Pietrosanu (@mihaiep, User Feedback member)
•	Christopher Hiller (@boneskull  IBM Developer Advocate) 
•	Michael Dawson (@mhdawson, TSC Chair, CommComm, User Feedback member)
•	Tierney Cyren (@bnb - CommComm Co-Chair)
•	Greg Wallace (@gtewallace - Node.js Foundation)
Topic
Thanks to Greg for sharing the survey data.
Thanks to Christopher to come with tooling initiative. 
<Dan Shaw> Intro- primary objective is to see if we can get to landing the data in github. 
We want to make the data that we collect for user feedback and for other workingroups inside the Node.Js project available for everyone to do some analysis to be able to evaluate trends and for decision making. 

<Greg Wallace>: We used Survey Monkey which is good, is somewhere between Google forms and some really sophisticated software .
    We worked as a group to ensure that the way we were asking the questions would make the analysis of the results as easy as possible.
    Initially there were a lot of open-ended questions which have required us to read a sentence or a paragraph, we close those up. There was a list of options that the respondents can pick from.
    We cranked out a PDF report out of the Survey Monkey that basically have just those answers represented as bar charts. 
    There were 4 or 5 questions left as open ended, Survey Monkey doesn’t know what to do with that data, but they have a built-in analyzers so for those ones it was created a PowerPoint 
It’s a simple way for viewing the data that summarize in  a hopeful manner.
EG:
  

And an open- ended question
 

From a summary perspective this combination between PDF and PowerPoint will provide a good level of visibility of the data.
For more analysys we have an Excel spreadsheet/data file and we’ve ensured there’s no PII (nothing that can be traced to any individual respondent), meaning we can put this on a public domain and there is no way for anybody to be identified right by the answers. 
The survey has 3 Outputs- the PDFs and the PowerPoint, the PDF has majority but for questions like where Survey Monkey does not visualize it we provide a summary swithing over PowerPoint
 
<Tierney> The PDF and Excel files will be available? 
<Greg> Yes, all of it. For top level results PDF and PowerPoint and for more analysing Excel data  files. There will be people who will take that and contribute in the insights that they produce back/that might be a task and the community might find interesting slicing and dicing the data.
<Dan> What I like to propose, as kind of a point of process and as attempted to model how we take responsibility, how we allow the foundation to take responsibility of managing this data and responsibilities of certifying in a way we’ve prepared the data that is ready for public consumption would you try to initiate the PR here and just have a little bit of a data trail and some attribution?
<Michael> We should agree where it should go in the repo; do we want a survey directory under user feedback, a directory which is the name for benchmarking survey 2017,2018 and then 3 documents under there? 
<Dan> Is a folder created now: https://github.com/nodejs/user-feedback/tree/master/data/2018-02-benchmarking-wg-survey  to drop the data.
<Mihai> How happy are we with the number of answers, under 300?
<Tierney> I was hoping we would hit 100 goal,I’m very happy to get that high (around 290 answers) and I think definitely hit higher in the future 
<Michael> Greg told us that number is in relatively statistically significant 
<Greg> There is a tool that I find on the web that will allow you to determine the confidence percentage that you can have based on the population size and sample size. 
<Dan> Chris has a major contribution to the open source ecosystem, he’s a maintainer for Mocha and will be wonderful a tooling builder to get together, collaborate with other tooling maintainers and developers and get some user feedback, so what I like to propose to allocate our next public meeting user feedback around tooling and invite some tooling folks, Chris, I know you reached some folks/another tooling providers, who else do you think potentially could join that session?
<Christopher> Everybody I asked said is a good idea 
<Michael> Is good to have a public call saying with not self selecting the people 
<Tierney> One of the goals is not just end users necessarily, but the mid user who is creating the tooling end users are using and also focusing on that mid user 
<Michael> At some point we want to end up here are the different types of end users we have, like we have people to deploy node in production, people generating tools will be another type of user and if we form a group that go to around each of those.
<Dan> Given what we need for call for participation, I propose to start by the end of March begin to invite folks to that sessions and allocate that as a public session.
<Michael> We talked about Benchmarking diagnostic survey as are we going to do the next survey, we have to go back to diagnostic team  and talk how to put  together a survey.
<Tierney> I’m wondering if the website group initiative would be interested in something as well, specifically how people use the Node.Js website? What are our users? How do we define them or whether  the gals were trying to serve? To define if they have a specific kind of set of questions to go and reach out with.
<Christopher> I was answering the survey and I did mention that I worked in online surveys  for eight years (I’m not a marketer) but I have some knowledge, basically the things not to do,  and I will be happy to look what we’re ready to send out and I might have some really good feedback there (eg: this question type is not what we want to use) , I would like to volunteer with that.
<Michael> We want to capture some external reviewers, once we get a set of questions from a particular group, we’ll review them in these meetings.
<Tierney> We need a section in Readme (in Comm-Comm we have 3 separate lists, one of the members, one of the individual members and one of the emeritus we can create the same structure, PR people and we will get more and more. I’ll do that and Christopher I’ll add your name
<Chris> Sure, add me as a reviewer 
<Michael>  We want to continue to ask for more participants, more tweets? Or more links? 
Standard explanation for user feedback:  is like anybody who’s interested who use Node or not using Node because they’re having problems we’re interested for anybody who will give us feedback on Node.Js 
The Enterprise Advisory group is  cast as a group of large enterprises who have large deployment of Node.js. If we have changes that will be the group that could go and say can you try these changes in advance and because they have large deployments they should be able to do that for us. We want to get a bunch of different constituents.
We should set up a meeting to sort these specifically. (send tweets, promote).
Dan: Set up a meeting for sorting  out Enterprise Advisory group to define, how to move forward 

Next meeting: 2018-03-16
 


