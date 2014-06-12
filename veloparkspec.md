# Introduction
There is a post-Olympic cycling legacy, including a velodrome, a road circuit, a BMX track and off-road trails, opening to the public during 2014. The Velopark Supporters League (VPSL) is the users' group for these facilities.
The VPSL exists to help to promote events, primarily races, initially on the road circuit, and to help riders to enter the events. This will be done largely via a VPSL web presence.
VPSL is independent of the Velopark's owners and administrators; it is an informal group run by event organisers and participants.
# Overview of requirements for web pages
The job is to manage events at the Velopark.  VPSL will not be the only organisation promoting events there, but we do want to provide a comprehensive management tool for those events that we do manage.  We may need to interface to the Velopark systems.
* http://www.visitleevalley.org.uk/en/content/cms/london2012/velo-park/
We will have to work with the various cycling governing bodies, as organisers can choose which of these (if any) will be the one they use.
* British Cycling (BC, http://www.britishcycling.org.uk/ )
* League of Veteran Racing Cyclists (LVRC, http://www.lvrc.org.uk/ )
* The League International (TLI, http://www.tlicycling.org.uk/ )
* Cycling time trials (CTT, http://www.rttc.org.uk/ )
And the features we need include:
1. Organisers to be able to create events, to accept entries, to publish start lists and signing on sheets (hardcopy for signing on), to record and publish results and reports
 These events may be road races (BC, LVRC, TLI or independent governing body), time trials (CTT rules), or other style events as chosen by the organiser.
2. All races to be visible to the general viewer, both as entry sheets before they run and as result sheets afterwards.
3. Riders to be able to enter events, including paying entry fees, and to track their results.
3. Authorised people to be able to publish articles (perhaps in a blog style)
4. Discussion area to exist, rather like a Facebook group or an older-style bulletin board like PHPBB.
#Details
## Supporters League Number
In any bike race, the riders have a race number, issued by the race organiser.  What we hope to do is to assign to each rider a unique VPSL number that can be used in all races, and is a clear way of identifying the rider to the organiser without any more details being entered.
So, when a rider or organiser signs up, the system will issue a unique Supporters League Number (SLN).  To avoid 'special' or 'unlucky' numbers:
* the first number issued will be 14
* no number ending in 13 will be issued
* no number with 3 or 4 digits the same will be issued.
The system administrator will be able to alter any rider's number to any (unissued) number, including allocating numbers that are not issued automatically.  This is to allow in future the ability to offer memorable numbers to 'celebrity' riders.
Sign in will be either by email address or SLN.
If someone is both a rider and an organiser, they will have two separate VPSL IDs and so two SLNs. It's possible for the two IDs to have the same email address; if the user signs on with email, the system will ask which ID they want to use. They will still of course have to enter the appropriate password.
## Riders' features
Some features below are labelled optional to make it easy and quick for riders to sign-up, but various of them will be needed when they try to enter events.  The system will prompt for those values at the time, and save them on the rider's database entry.
1. Required details
 * email address (for sign up/sign in)
 * first name
 * surname
* sex (m or f)
 * date of birth
2. Optional details
 * cycling club (drop down list, but must be able to make new entry too, then added to list)
 * British Cycling member?  (y or n)
  * British Cycling racing licence holder (y or n)
   * BC level (E, 1, 2, 3, or 4)
   * British Cycling qualified coach? (y or n)
  * TLI member? (y or n)
    * licence number (text field)
  * LVRC member? (y or n)
   * licence number (text field)
  * home address
  * next of kin (text field)
  * phone number (valid phone number)
  * blood group  (text field, checked as valid)
  * disabilities (text field)
## Organisers features
1. Required details
 * email address
 * first name
 * surname
2. Optional details
  * cycling club  (drop down list, but must be able to make new entry too, then added to list, same as for riders)
..* bank account number and sort code for entry fees.
## Races features
* Governing body (BC, LVRC, TLI, CTT, other)
* Categories eligible to ride (decided by the organiser), will vary by governing body
* maximum field size
* visible by start date, with start sheet and already entered riders listed.  Riders to appear on the start sheet as soon as they enter and pay, of course.
* Riders are always required to sign-on for a race on paper, so that a sign-on sheet will need to be printed with the appropriate disclaimers on it.  This is to ensure that the organisers have the correct insurance cover.
#Final note
This is a high-level specification.  On researching how to implement it, you may come across on the one hand, problems, errors and omissions, on the other hand, extra features you may wish to implant. In each case the first point of contact is your Maker's Academy instructor, then back to the author of this spec.

