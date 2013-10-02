# Mettings

## Sept 23rd

### Location - Toronto Reference Library
### Time - 6pm

### Agenda
1. Review wireframes
2. Landing page

###Notes
####Triggio design:

#####Main features:
1. summary board
2. feed
3. sound reply
4. icon/heading

#####Manipulation
	For Summary Board: manipulating the location of the summary board
	For Feed: Color coded vs. not colour coded
	For Sound reply: icon (2 types) vs no icons
	For icon/heading: main focus is triggio, main focus is the company, 


#####Final Pick:
summary board: on the bottom
for feed:  colour coding as an option
sound reply: hover
heading: company feed board, brought to you by Triggio


Saas getting started page for integration - Firebase

####Next step: setting up sound interface
#####tasks: 
- upload sound
- select sound for a specific identifier
- sound list
- search button

#####sound control
- admin only
- grant access - to everyone - final decision
- voting - no voting

- dashboard or no dashboard…..

#####dashboard:
- sound management - separate from rest of settings
- batching
- account management - password, email, personal info
- color coding
- integration for preset sites - add and revoke
- editing company information
- user management - managing list of users: grant and revoke access
- multiple admin
- grant admin access and revoke admin access

- grant individuality - have profile icon - no name

####Landing Page
#####goal: 
- explain what triggio is about - people don't know what triggio is
	 - demos - global newsfeed
	- text - keep it clean and at a minimal
	- images - maybe animated
	 - videos - NOOO
	- use cases
	- sounds -  MUST

- examples:
	- dropbox
	- facebook

- easy to sign up - prominent
- sign in 

	
## Sept 15th

### Location - starbucks passed Sobey's on Mount Pleasant

### Agenda
1. summary for Feed
2. integration
3. Feed planning

### Notes
#### Summarization for Feed
  - summarize by different sources
  - summarize by tags(another feature to talk about)
  - number of notifications from a different source within a time frame(anything within 2weeks. more focused on the very short-term:)
  - time units: past hour; 24hours; today:midnight to right now; 
  - one time line: 1hr; number of events from different sources within the timeline
  - possible idea: showing what happened the past minute
  - Final look: an category per line, total count per category within the time line, timeline=1hr (can be changed)

#### integration
  - What services do we want to integrate?
  - batching notifications: allows them do it through settings - 
  - Engineering
  - Sales
  - Support - customer service
  - Marketing


  - Google Analytics - 1 - Website services - many notifications types (referals, spikes) - **visitors**
  - github - 3 - **code**
  - *desk - 4 - analyze customer sentiment* - **suppport**
  - Recurly - 2 - **sales**
  - Stripe - 2 - **sales**
  - pingdom - 1 - **website's down**
  - chargely - 2 - **sales**
  - braintree - 2 - **sales**
  - ifthenthat -  3 (pick one)
  - Zapier - 3 (pick one)
  - uservoice - 4 
  - Salesforce - 5- **sales**

#### Feed Planning
general format: notification type, message, date, time

##### Visitors
  - from google analytics
  - subject: visitors
  - notify every x number of visitors
  - 
  
mockup details: 
- replay sound
- hover
- colour coding
- messaging layout
- objective: look cool

### Action Items
1. wireframes - incorporate real feeds

## Sept 11th

### Location

### Agenda
  - Use Case
  - Brainstorm Funcionalities/Features: User and System

### Notes
#### Random Thoughts
  - Triggio should be a social conversation starter. It should promote social interactions between people as a by-product instead of through the program. It is very powerful because it can create a source of interaction that is intergrated with people's lives.

#### Functionalities/Features: User

**Log-in**
  1. Easiest way to log-in: open it when the computer starts. EX: like Dropbox
  2. Go to Triggio.com - login page, allow users to save account info. EX: like Facebook
  3. Log-in through work email only. EX: desk.com

**Sign-up**
  1. One person in the company signup with work email ONLY
  2. May send invite link to people he thinks should join. EX: desk.com
  3. With invite link: sign up with email (work ideally) so say "work email" instead of "email"
  4. Without invite link: MUST use work email. send a confirmation email to validate the account.

**Capture Attention**
  1. Sounds - always on
  2. ~Person's name - maybe apply it to other people in the company. EX: Draco did x.....~
  3. pop-ups on computer - annoying if coming up every minute; *to think about: summarize updates every x period*
  4. images (more than words) - maybe for summaries/trends, OCCASIONALLY; EX: Graphs on daily sales, everyday at x time;
  5. Contrast - design

Notification
- Sound focused - sounds should be unique
- option to turn off sound on the native app

Feed
- on the native app or on website
- mixed of text and images - skip image (sept 15th)
- option to replay the sound
- when the notification is made
- Source of notification - changed to type
- No Scrolling

Features to Implement:
  1. summarize information on the feed
  2. integrations: Salesforce
  3. Admin account for changing sounds
  4. option to upload sounds through all accounts
  5. User driven data

Idea Bucket:
- Allow people to "favour/like" events. Popular events will reply if there is enough demand 
- click on events to get more summary/information 
- Colour code feeds (EX: colour code for good or colour code for bad)
