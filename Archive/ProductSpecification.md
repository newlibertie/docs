
# Overview
This document outlines *New Libertie", an online portal and set of widgets,  designed for enhancing and enabling political participation with modern web and mobile technologies.

The supported political functions are expected to use modern cryptographic and cryptocurrency primitives in order to protect the identities and contributions of low level political participants from criminal players and corrupt government officials who may wish to monitor and/or influence democratic political activity.

New Libertie consists of three main building blocks as described below:

## Discussion and Reporting Platform
The first building block is a discussion and reporting web site.  This web site shall interface with popular politically oriented social networks including Facebook and Twitter, and later perhaps others.   Not all of the integrations may be available at the outset depending on an adoption plan.  However, each of the integrations shall share the overall methodology of how the web site gains views and visitors from participants of the social network. In particular, people will see political messages from their party and group of connections on the social network feed once they register for the app.   They will have the capability to upvote and downvote statements or vote on secure formal polls shared through the app and the website.

The discussion and reporting web site features various levels of discussion.  These levels correspond to the levels of governance.  For example, municipal, state, and national government could serve as the levels at which particular discussion topics may be relevant.

As new issues become relevant or important, designated super-users will be able to create new topics for discussion.   Initially we will allow lay users to search for discussions and to request the creation of new discussions.  However, later we will allow users to earn a “topic creation privilege” that allows them to create new discussions.  This privilege can be earned by contributing to various beneficial activities on the site, as outlined in the subsequent sections.

The discussion platform will feature a view that displays the most current posts relating to the user’s topics of interest. These shall be categorized according to the basic levels of governance, namely a national level column,  a state level column, and a local level column.

Since the user will have the ability to link with the social network of their choice, we will attribute a given discussion opinion to the proper platform.

For example, there could be a local topic that aims to discuss whether an existing public park should be modified to support a new kind of activity, say, to add a tennis court or to add slides for children.  Currently the park is a grassy area lacking any additional recreational facilities. The topic would then the allow users of this platform, who are also local residents of that area, to weigh-in on the pros and cons of whether a tennis court or a children’s playground should be constructed.

Such topics would be featured within the third column of the screen, and within that topic (or “block”) various opinions and comments from users would be featured. We will attribute them to Facebook or to any other platform that has been linked to our platform in order to be able to able to show the “unified view” to the user.

Each topic has a moderator.  One can imagine that various users will be able to discuss topics amongst each other. Once sufficient discussion has taken place, the moderator of that topic will be able to create voting buttons to select from a few main positions extracted from the discussion. Voting will establish a user’s position on a particular topic and also be able to predict the expected support of topics using “support-generalization” as explained below.

For example, I may vote on the option that the park should have a children's slide and a swing set, and also a little plastic rock for climbing. That would be my vote. However, the counting method should be able to derive support count for sub-positions.  For example if my above vote does not have enough support in its full form, it should nevertheless be able to count towards a more general position that supports a children's slide only, unless explicitly prohibited by the user.   Note the few options would be selected by the moderator depending on the “word cloud” of the discussion that has already happened within that topic.

Discussions will not be limited to non-controversial topics; they may also involve more divisive matters. In order to protect the privacy of the voters and to provide a fear-free environment in which voters can honestly commit to their choices, we will use **cryptographic counting** with the following properties:

1. Given a count of votes, it will be impossible to attribute who voted for which choice.

2. The voting protocol will ensure that the final result is provably true. This is to be ensured by having:

3. The voting algorithm available as open source, and

4. The voting protocol published with a reputed research venue so that users can have broad confidence with regard to the two critical safety features: their privacy is protected, and the count is accurate.

Each topic will feature a Wikipedia-like autogenerated **analytics page** highlighting a diverse range of statistics:

1. How many users voted for each option?

2. What was the activity level and what kind of people were voting (demographics)?

3. How many discussions were logged?

4. How many comments were logged?

5. Which of the positions ranked as most popular (before and after the application of support generalization)?

6. And perhaps others.

Regarding the various options that might contribute towards improving the local park, its analytics page will highlight the statistics above.  The analytics page will also have links to comments with public linkage to their originators.  Whether a user has cast a vote will be public,  but the specific choice made with the vote will remain private.  In other words, it will not be possible to determine “who voted for what”.

The discussion platform has two aspects.  Firstly it is a venue for people to discuss on topics of interest. The topics of interest are managed by moderators and allow privacy preserving voting on various choices that are relevant to the discussion.  Secondly, statistics with respect to each discussion and topic are available and are saved permanently for anybody to review at a future date.  Note that it is possible that some of the statistics may be behind a paywall in order to sustain the cost of running the site.


## Assemble and Local Activities

Assembling people and supporting local activities is another building block of the platform.  The motivation comes from the following observation: A lot of platforms allow people to discuss and debate political topics.  However, anecdotal evidence suggests that these discussions typically do not lead to positive action.  New Libertie bridges this gap in the following manner:

Given any local topic, people from that locality will be able to enter a video conference room where they can talk at length with the other people on the same topic.

In order to handle any scarcity caused by having a large number of participants, people who have a higher reputation, will have a better chance of getting ahead in the queue and being able to broadcast and discuss their points.  The reputation of course would have been earned by casting votes and perhaps other useful activities done for the site.

The reputation would have been earned by casting votes, posting comments, which have not been marked as unproductive, negative or unnecessary by the moderators.  So people will have the opportunity of creating the virtual town hub where people with a higher reputation can queue up to give video messages. Of course they can also comment in line regarding the discussion.

Video clips will be saved on the web site for future use.  These video clips might be behind a paywall or be used for promotional or other purposes.

Another local feature helps get the people together in a single location and be able to discuss without facing the downside of text-only communications on social networks where people unnecessarily go into useless arguments.  New Libertie will make it easy for people to assemble and meet and discuss on a particular topic.

Every local topic shall have a tool that helps people assemble to discuss.  When you click on the tool, it will allow you to say “let’s discuss this at whatever location” so that it just creates an “assembly” whenever you click on that.     Once that point of discussion is created for the future, everybody who is in that discussion will be able to see its existence and the local discussion venue will be highlighted (i.e. this topic is being discussed at this place, at this time).  You can register for it using your social network account, and the event will show up in your calendar.  The event will also show how many people are expected to show up.

Whenever there is an assembly, the people who use a smartphone app will be able to register for the event automatically when they are in the vicinity.  Once they are registered, they will stay for some time and then leave.  This activity should be saved in an anonymous manner so that the assembly page will be able to show count statistics with time of day and member demographic and topic preference attributes.

For example, consider a local assembly discussing about the local park improvements.  The assembly page shall show the topic of this assembly and that 5000 people were present from 5 to 6pm.  It will be possible to “drill down” into the person count: that among the people who were there, 2000 were long-time supporters of “tennis courts in the park”, whereas 3000 were more recent, or they did not have any affiliation; they were just there.

Summarizing the locality oriented angle,  for some small countries, it might be national, local, and international levels that make sense, because the politics may be more influenced by the external neighborhood.

In summary, this aspect of the web site involves making it easy to tell people to assemble at a given location,  be able to count the number of people that assembled, and to link these back to topics of political interest as well as to produce long lasting summary pages that capture the location oriented statistics for reference.


## Political Parties and Issue Based Organizations

When people are assembling for a particular political purpose, political parties may want to sponsor or encourage attendance at the event.   This feature is supported in the following manner.  First, the political party would have to specially register with New Libertie and get a “privileged account”.  Having a priviledged account provides the ability to send one-time invitations (maybe one invitation every year) to anybody at once, for a service fee.  If the person accepts the invitation, then that party affiliation will show on their profile page.  The privileged account can create events and invite existing members to events.  The privileged account will also have the capability to send messages to people within any geographical area.  It will also have the capability of creating topics and inviting people to those topics.

The political party or organization may want to reimburse and/or pre-pay people for their expenditures.  New Libertie will allow direct payments to the people who attended a given event.  This helps because sometimes the participants may not be able to afford the transportation cost to reach a particular venue where the party is assembling people for an event.

Just as participants could be discouraged by the financial aspect of buying a tickets in advance, and in turn require advance payments, similarly some participants may not have smartphones, and instead be having traditional cell phones which and can only send and receive SMS.    Therefore when you register for the web site, the web site will ask you your mobile number, and on your profile you’ll be able to update or maintain your current mobile number which is expected to receive text messages.  The SMS or smartphone path choice is made as follows:
When the invitation for the event is being sent,  it will either go to your profile on the web or it will go to your phone as a text message (or both).  The text message would contain instructions set up by the political party and also include the date time and location of the event.

Upon reaching the event venue,  the smart phone users will automatically be counted by virtue of the smartphone reporting back the location of the user to New Libertie.  The SMS user would have a different workflow.  The initial invitation sent by text messaging will instruct the person to find a given location co-ordinator at the venue (this is a person who has been placed by the party and his role as co-ordinator is known to the app).  The coordinator will necessarily have a smartphone, and when a person comes, the coordinator will enter the “phone number” of the person who has come. The web site will then send a text message to the person who has arrived and give him a random code, and the person will then give that random code to the coordinator who will then enter it into the app.  At this point, the web site will claim or believe that the given person has arrived at the venue.





