# Tutor U

## Site Overview
The Tutor U site in part provides advertisement and information for a free, voluntary tutor based, online, on-demand tutoring scheme operated by a non-profit organisation. The tutoring is offered in core STEM subjects to secondary school and sixth form college students, and voluntary tutors register to tutor as often as they like each week, and provide arranged one hour video call sessions with a student seeking help in a core STEM subject. 

Additionally the site provides the means by which potential voluntary tutors apply to become a tutor and they can provide the days and times during a week they wish to tutor, and in what subjects. The site also provides the ability for students to book a session with an avaialble tutor and specify the topic and or problem they would like to discuss in advance.
![am i responsive screenshot](docs/screenshots/am_i_responsive_screenshot.png)

## Design Process

### Strategy

#### Target Audience:
The primary audiences are firstly secondary school and sixth form college students in the UK seeking tutoring in STEM subjects; and secondly individuals looking to become voluntary tutors in STEM subjects. It is anticipated that the bulk of said tutors will be undergraduates studying a STEM degree who are seeking voluntary tutor roles, for the sake of their CV development through gaining skills and experience. Students with a possible interest in teaching will also have a strong desire to seek experience. The other group of volunteers are anticipated to be retired teachers, or any other individuals who have sufficient expertise in a STEM subject, with an interest in helping students who would normally not have access to tutors, gain assistance in their learning.

#### User stories

##### Students:
- As a student, tutors are far too expensive for me, and there are very few schemes offering affordable tutoring. I wish there were more on demand affordable schemes I could use. 
- As a student tutoring is not accessible to me, there are no tutors nearby and I would have to travel which is not practical. I would like access to online tutoring
on a site that made booking a tutor very easy and stress free.
- As a student, if online tutoring were available through some site, I would want it to enable me to have the ability to specify my particular problem in advance in order to make a session worthwhile. I would also want the ability to have a range of times to pick from that fits my individual schedule.
- If a site existed that provided free online tutoring using voluntary tutors, I would want the site to have some way of ensuring voluntary tutors are sufficiently qualified.
- As a parent of a secondary school student I would like a site for organising online tutoring via a video call, to have a means of allowing tutors to provide enough 
information for safeguarding checks to be performed.

In summary potential student users desire affordable on-demand tutoring, that is easily accessible and thus online, tailored to them as individuals, and of good quality. A site should provide the ability for students to book a session on a topic of their choice with a qualified tutor with minimal effort.

##### Tutors:
- As an undergraduate I would like more opportunities to tutor in a STEM subject, in order to develop my CV.
- As an undergraduate considering a career in teaching, I would happily take part in a tutoring scheme for students in a STEM subject. It will allow me to gain a better insight in to what it entails. However I would want to tutor online in order to make it practical as I am often busy with my own studies attending lectures etc.
- As a postgraduate I would consider providing voluntary tutoring in maths and physics, but I would want the ability to choose how often and at what times I tutor, with the ability to stop when I want.
- As a professional working engineer, I would love the oppotunity to help the next generation with their studies and hopefully inspire them to become future engineers.
If a site existed that organised tutoring sessions, I would want it to be straightforward to apply to be a tutor. I would also want to only tutor in engineering, and so I would want to be able to specify this when applying through a site.
- As a retired teacher looking to keep busy, and still have the pleasure of teaching, I would want a site facilitating the organisation of online tutoring to be easy to use, and provide all the information I may need.

#### Site owners story:
Tutoring is generally expensive, in-practical and hard to access when tutoring is done in person, due the lack of nearby tutors, and the need to travel for either the tutor or tutee; it also limits scalability. We are a non-profit organisation that after taking inspiration from existing tutoring schemes that seek to provide free tutoring in STEM subjects, want to create our own scheme, but make it more accessible. We aim to do this by hosting the tutoring online. A secondary desire for our organisation is to provide opportunities for volunteers to tutor. We require a website to facilitate and advertsie our scheme.

### Scope
#### Scheme scope:
The scope of the scheme will be to provide tutoring in any of the core STEM subjects to secondary school and college students within the UK, and to use voluntary tutors. 
The tutoring is to be hosted via a video call application that provides the ability to screen share. Volunteer tutors will apply to become a tutor and indicate on a weekly basis on what days and at what times they want to tutor. They will also need to indicate the STEM subjects they are qualified to tutor in. Tutoring sessions will be a maximum of one hour, and will be allocated on a first come first serve basis, up to one week in advance. Students wishing to be tutored will book a session at least 48hrs in advance. Additionally they will need to indicate with a short description the topic they would like their potential tutor to cover in their session.

#### Site key functions and content
 In order to achieve the needs of the site owner and the users, as well as satisfy the websites purpose, it will minimally require the following functions and content:

- Provide advertisement of and information about the tutoring scheme
- A way for tutors to register their details, including their STEM subject expertise, as well as what dates and times during a week they will be available to tutor
- A way for students to book a tutoring session on a given date at a certain time, as well as enable them to provide a short description of the topic they would like to cover.
- A way to assist students with choosing which dates and times to request a session, and to have an idea of tutor availability.
- Content that answers any common questions tutors and students may have.

#### Proposed features
To address the  minimal required site content and functionality, the following features were proposed to be implemented:
- Home/landing page to act as a clear concise summary introduction of the tutoring scheme and provide its key information. Also it will act as a first point of contact for tutees and tutors, to direct them to the necessary pages to allow them  to apply to be a tutor and or arrange tutoring sessions. It will finally provide links to other pages explaining the full details of the scheme in more depth, and answering common questions.
- A form page for potential tutors to apply, where they can provide their personal details, including their STEM subject expertise, as well what dates and times during a week they want to tutor.
- A form page for tutees to book a tutoring session on a given date at a certain time, as well as enable them to provide a short description of the topic they would like to cover.
- To assist students in choosing which dates and times to book a session and enable them to have an idea of tutor availability, a  timetable page will be used that indicates at what times, on which dates, in which subjects how many tutors are available. This will be done for a rolling week.
- A further information page detailing the scheme in more depth, providing any important information not covered on the landing page.
- Finally a FAQ's page will be implemented to answer common questions of tutors and students.

#### Proposed future features
- Allow automation of session booking, and real-time updates to tutor availability, to be done using JavaScript. At the moment changes to the site need to be done manually, which is inefficient and error-prone; Session booking requires the use of emails to be sent manually. Automation will increase functionality of the site, and also make it more scalable.
- Allow tutees to provide feedback/reviews directly to the site.
- Allow allocation priority to be assigned that gives preference to those that have received fewer sessions, by tracking how many sessions in a given time period a student has had.