# 2018-03-16 User Feedback Team Meeting

## Links

* **Recording**: https://www.youtube.com/watch?v=wXqKXiWCtrg 
* **GitHub Issue:** https://github.com/nodejs/user-feedback/issues/28 
* **Previous Minutes:** https://docs.google.com/document/d/1EHbxCOy-tlFAvVqO7r4n8Tu_4c6TnztfO1_dsjMrCRg/edit#heading=h.iwg4uzfxnbok 
* [Delivery Channel](https://github.com/orgs/nodejs/teams/delivery-channels/members)
* [Public meeting](https://github.com/nodejs/user-feedback/issues/38)
## Agenda
* Extracted from neuf-agenda labelled issues and pull requests from the user-feedback repo prior to the meeting.
* Intro / Attendance
* Key Initiatives
* TBD
* Closing Thoughts
## Invited
* Dan Shaw (@dshaw - User Feedback Champion, CommComm observer)
* Mike Hostetler (@mikehostetler - User Feedback member)
* Mihai Ene-Pietrosanu (@mihaiep, User Feedback member)
* William Kapke (@williamkapke - CommComm, User Feedback member)
* Michael Dawson (@mhdawson, TSC Chair, CommComm, User Feedback member)
* Tierney Cyren (@bnb - CommComm Co-Chair)
## Present
* Dan Shaw (@dshaw - User Feedback Champion, CommComm observer)
* Mihai Ene-Pietrosanu (@mihaiep, User Feedback member)
* Michael Dawson (@mhdawson, TSC Chair, CommComm, User Feedback member)
* Tierney Cyren (@bnb - CommComm Co-Chair)
* Chris Hiller(@boneskull.com)


**TOPIC**
## Notes
* Excellent brainstorm meeting. Thanks all for attending!  
* Dan Shaw: Intro, regular user feedback meeting. We want to prepare for tooling session.
* Chris: the two people that I’ve worked so far are interested, not just a one-time deal, they want to work with user feedback group
* Michael: We want to be as inclusive as we can, so anybody who shows up and self-select as representative of that group is 
  welcome to come and participate.
* Tierney: Is there a specific issue I can point people?
* Michael: I tweeted earlier so we can do kind of publicize.
* Dan: Maybe Diagnostics may be interested to engage, who’s leading that effort?
* Michael: I’m looking for the person who’s going to help pull it into core. I’ll take an action to figure out who can 
  get on that side.
* Chris: I’ll follow up with them to make sure they are available.
* Dan: I’m interested in this session to bring a little bit more representation from TSC. The context is how does tooling,
  like we’ve seen with modules engage with the technical project in the long term. 
  This is a dialogue opener and we don’t know the path.If we don’t have technical folks at the table then we should we go from there?
* Michael: Maybe after we have the initial discussion and understand better we could go back and look who might be interested 
  and ping them say if we can do on regular basis.
* Dan: couple of individuals to sort of potentially reach out to invite, Myles as one of the leads of the modules WG and maybe someone
  like Jordan Harbor who’s one of the participants.
* Michael: Chris how closely aligned you think the people working on modules are to the kind of tooling issues and stuff
  you were thinking, the sort of kind of things you want to address by this bringing this group together?
* Chris: I’m not familiar with submodules group.
* Michael: they’re focused on ES6 support in Node (Tierney: specifically, around the modules implementation),
  how that ES6 support will be implemented. I guess the interaction could be, is that some of that may affect what 
  some tooling can do and what some modules built on top can do. How do you test ES6 modules that might affect Mocha?
* Chris: There’s some overlap, but I wouldn’t say necessarily any more overlap that any other.
* Michael: Unless you think that’s a good fit I think we might want to be a bit cautious on. I’d like Chris to bring the group 
  that he was thinking of together plus whoever else selects as being like in the tooling area and see what the concerns are,
  and then figure out who to bring as opposed to trying to pre-figure that out.
* Tierney: The thing I’d be most concerned about with pre-figuring that out is optimizing for the people who have already given feedback pretty extensively, like Myles and Jordan (involved in the project for quite a while), and I just be concerned that continuing to build like an echo chamber kind to ourselves and the feedback that we’ve already gotten, I’m elevating those voices over something with people who at least I’ve considered I had conversations with say feel like we’re kind of very much in echo chamber in a very exclusive environment, it’s hard to break into so I think we really to optimize for the ecosystem tooling people who haven’t really interacted with the node project.
* Michael: I’ll like to have people come in tell us, what they’re thinking help us understand a bit better concerns 
  and where they might want see things going and from that we can sort of figure out how do we bring additional people from the project
  to align that versus some other way.
* Tierney: I already reached out to a few people, I’ll point people in that direction.
* Dan: My concern is: we are creating space for this discussion and then where is it go? Is not clear if is Comm-Comm, 
  user feedback is not an incubation space for initiatives…  
* Michael: I don’t think it need to go anywhere, our focus is to keep regular contacts with these groups and then once the contacts
  takes place, if there’s concrete actions that need to happen out of those, like for example here’s a real pain point, 
  our actions to figure out how to pull in the other people who can discuss that specific pain point have 
  a specific meanings around that. You’re thinking is like do we need to go to a strategic initiative around this or a WG,
  I could see that is useful in some cases, but I think it’s equally perfectly reasonable if we just have every 3 months
  we get together the group, in the different user representatives, this and this one around people building tooling 
  and have a discussion. It doesn’t have to graduate into something else,I think working groups to have like a close relationship
  too core.
* Chris: We have these user feedback session an maybe an intuitive coming out, well there needs to be some sort of champion in core
  to get much of anything done, I think we should be going(this is not going to happen overnight ) is that we need more people
  who come from this world basically just involved in core and so if eventually that would form a group great,
  but I do fear if we get a bunch of feedback and it’s clear there’s some actionable items whose really suitable to be a champion there.
  I’m sure it’s somebody on working groups that works more with command-line tools and others maybe a good person to reach out, 
  I’m trying to get more involved in core myself. I’m sure there will be some things that come out of this.
* Michael: I agree 100% with theory that group needs to get more involved, because it’s not going
  to be like “here’s a bunch of requirements, somebody else goes off and does it”;
  but I can easily say it’s like: “here it’s a bunch of things we’d like to see happen and we’re willing to invest some time in core
  to make it happen but we’re not as plugged in so we need some help and that some other people say, yeah we’ll support you doing that”. the first step is just coming to an understanding what those might be and what they look like and how much work they take, and once, if this group comes up with : well here’s the document now everybody understands it better that’s the next step for figuring out how you might actually make it happen.
* Chris: Part of the reason that I thought I’m going to propose this idea was that myself and some others who come from this world
  have kind of felt like when they proposed an idea to core it’s received as something completely out of left field and 
  that sort of make sense if the people in core mainly aren’t working in that world, so it’s my hope that we can kind of bridge 
  the gap and come to a better understanding of each other needs.
* Michael: If we can use this to bridge the gap, better understands each other and figure out how to work together on the things
  that are important. If you just open the PR and there’s no context and no discussion it’s easy for that just not to go the right way;
  if you had a discussion beforehand, we’ve identified some people who are interested in the area, 
  there’s already been a discussion then you open a PR and immediately some people can sort of jump in saying “this is a good idea”.
  We get together we hahe this discussion, if you get to the point where there’s enough people in the tooling committee, 
  like actively working, then easily see it forming an internal WG or something like that.
* Dan: We identified Myles as being the echo chamber who else could be a good fit?
* Michael: I’m happy to say this is going to be, anybody else interested come along. I certainly don’t want to say to anybody don’t come.
  just in terms of actively going to find additional attendees, for me would be better to understand a bit more what 
  the interest is and what kind of discussion are gonna have happen, because that’ll help me figure out who the right people are.
* Tierney: I don’t think we should exclude people who have been participating in this kind of discussion in the best, 
  I just want to make sure we’re not only including them, like they’re not our central people that we’re having in this discussion
  and that we’re actually going and getting people that are users that haven’t participated in addition to those people
  who have already participate it to these discussions.       
* Dan: What about Comm-Comm? Outside of this group are their perspectives, internationalization?
* Michael: If will be the case like supporting multiple languages then, probably we will have somebody.
* Tierney: I know the electron folks that are involved, I can ping few of them and see if they’re interested in coming.
* Michael: We created a team called delivery channel,  group who take node and either bundle it into their product and deliver
  it that way or they repackage some of the installers, or they help you install, so that team whenever we do something 
  around that we notify them an electrons part of that, that will be another end-user group. At some point we want to reach out 
  to them as a group and say should we have user feedback session with them, to hear what’s going on and make sure 
  that isn’t same thing where there they’re in echo chamber that we’re not hearing, just sort of bring the groups closer together.
  Chris do you have example of other modules that you’re getting people to come in for?
* Chris: Webpack and npm, maybe typescript.      
* Tierney: I reached out someone from Babel.
* Michael: That’ll be quite interesting to hear what the overlap is in terms of concern and what concerns are? Feedback from that group
  in terms of the things we’re doing.
* Dan: There is an Node issue 19079 which is runtime deprecation of buffer constructor, I’m wondering if that particular issue,
  particular concept, it’s too deep in specific?
* Michael: I would leave it to the end; my suggestions: everybody introduce themselves and then give it a sort of open-floor
  to Chris and the rest of the people to kind of say well what are kind of things you’d like to talk about and then at the end
  we can say one thing we know from Node community side that we are interested in feedback on is that particular one;
  we’ve taken a decision it will affect module owners in general, but we can get feedback from this particular group.
  Chris does this sound reasonable?
* Chris: I was thinking going back to the few people reached out to and say do you want to bounce a few ideas around,
  these are main challenges, and this is kind of what we want to talk about. 
  Do you have any specific questions that you want to ask? On the buffer thing I don’t feel like is any important than anything else
  necessarily.
* Michael: We could come up with some generic questions: if the project makes your life more difficult; LTS release cycle help/hurt
  the releases that you need to support; any PII for people who have native modules. Are there any pain points that we should be aware,
  so we have enough knowledge to understand how we might affect that end user group and be aware?
* Chris: …Node Sass
* Tierney: I’d like to ask if after we’re done here we’re not crossing streams because we’re talking about similar groups of people
  to reach out to, so I just want to make sure I’m not creating extra turn on inviting people in.
* Michael: The other thing would be like are there things that you think the project or even the foundation because we can be a channel
  into the foundation as well should be doing to support modules and tooling in a way that isn’t being done today.
  We could write some of those down in the agenda if we want. If you come with a set that they want to discuss that will give us some 
  more concrete things to talk about in the meeting. How often to get together? Are there burning issues or not?
  (Capturing the high level ones as a way to figure it out what next steps might be on)
* Chris: Would be helpful to have maybe somebody who is involved with modules.
* Dan: Do you think would be constructive to have a broad sort of opener with tooling folks just to get a baseline,
  describe how your tolling leverages Node.Js, but not sure how will be its context in the broader group?
* Michael: It’s kind of hard to understand each other if we don’t understand what the modules doing. Some of them like probably
  NPM we understand well, but others may not be as obvious to people what the relationship is an innovation dependence, 
  all that kind of stuff.      
* Dan: there is npm a new tooling that npm is building like mpx.
* Michael: Every meeting maybe could benefit from a what’s new in terms of our other modules planning something new that they think 
  might affect Node and vice-versa; NPM is introducing something new, hearing about that upfront and it won’t just be the people
  in the meeting it’s whoever else wants to watch the meeting afterwards and there’s something particularly interesting that comes 
  out of that that we point the people to the recording to go listen; it’s another way to sort of bring the two way communication.
* Chris:another questions is why do you use Node.Js to write your tools? Traditionally Javascript has not been a scripting language,
  people are gonna reach for Python or else, why using javascript and node when you could have this with a shell script. 
* Tierney: It will be probably helpful, should we reached out to Chris, Borchers from Node.Js foundation.
* Dan: I’m taking notes on [issue#38](https://github.com/nodejs/user-feedback/issues/38) as relates to agenda topics.
 
   * **Enterprise Advisory group: one month from now.**     
   * **Chris is reaching out to people to attend the meeting next week.**
 
**Closing Thoughts**
- 

## Upcoming Meetings
* The next meeting is scheduled for Friday, 2018-03-30 at 17:00 UTC / noon ET / 11am CT / 9am PT.
* **Node.js Foundation Calendar**: https://nodejs.org/calendar
 - Click `+GoogleCalendar` at the bottom right to add to your own calendar.
