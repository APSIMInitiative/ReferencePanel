# 2019-05 Minutes

### Date

Tuesday 21/5/19; 9:30AM AEST

## Agenda Item 

### 1.1 Welcome/Apologies


### Welcome from @Keith-Pembleton

### Members

@HamishBrownPFR; @hol353; @jbrider; @kchenu; @Keith-Pembleton; @LouisAK; @MarkLieffering; @peter-devoil; @sarahcleary; @sno036; @yashvirchuauhan
  
### Apologies/Not in attendance

@sarchontoulis; @EnliWang

### 1.2 Review Minutes and Actions
  Attached - [2019-03 Minutes](https://confluence.csiro.au/display/APSIM/2019-03+Minutes)
<br>Taken as read and correct

## 2. Science/Software

### 2.1 Check for new APSIM Major Improvements
  
   **GitHub MAJOR science issues since last RP meeting** 
   
   @Keith-Pembleton noted  new links since the last meeting. <br>These included:
   **Simple Fruit Tree Model** https://github.com/APSIMInitiative/ApsimX/issues/3801 - @HamishBrownPFR noted it was not so simple due to the complexities of the water and N balance.<br>
   **ACTION** - @Keith-Pembleton to link Hamish with a local consultant who developed a banana model which may have relevance to the Simple Fruit Tree Model.  @HamishBrownPFR might be able to help include banana model into NextGen.
   
   **CLEM** - https://github.com/APSIMInitiative/ApsimX/issues/3575 - see notes below
   
   **AgPasture** - https://github.com/APSIMInitiative/ApsimX/issues/3689 - see notes below
      
### 2.2  Updates from RP on models and reviews 
  ALL issues tagging APSIM Initiative Reference Panel
  Models under development - https://github.com/APSIMInitiative/ApsimX/labels/major
  - [Sorghum model](https://github.com/APSIMInitiative/ApsimX/issues/572)
    <br>Drew Holzworth now working with @jbrider on the Sorghum model.  @jbrider provided an update on progress.
    
  - Models currently under review -https://github.com/APSIMInitiative/ApsimX/labels/underreview
    - [Fodder beet model](https://github.com/APSIMInitiative/ApsimX/issues/78) <br> No further movement.  With Rob Zyskowski to respond to comments
    - [White Clover model](https://github.com/APSIMInitiative/ApsimX/issues/2069) <br> RP confirmed that model is ready for release.  <br>**ACTION** @sarahcleary to ask Rogerio to work with Dean to put in release.  
    
    - [CLEM](https://github.com/APSIMInitiative/ApsimX/issues/3575)
    <br>@Keith-Pembleton discussed issues with running CLEM (as per the GitHub issue). Ask the CLEM team to contact Keith directly if they want to work through any of the issues he raised.
    <br>**ACTION** (1) @APSIM RP reps to try and run CLEM and provide comment on issue. <br> (2) @sarahcleary to contact CLEM team to resolve issues and tag them into the CLEM issue
    
    
  - New models requiring review 
      - [AgPasture](https://github.com/APSIMInitiative/ApsimX/issues/3689)
     <br>**ACTION:**  @sarahcleary to contact Matt Harrison to see if he is happy to review.  
       
    <br>**Models/Updates in release since last RP meeting**
    - none noted. 
    
    **Process comment**
    <br> Hamish questioned the issue that major issues were being identified too late in the process.  Does the process need modificaiton?  It was agreed that the engagement of the AI RP reps earlier on in the GitHub review, will alleviate or at least minimise this issue. AI RP to see an eye on this issue to see if it continues.  
    
### 2.3  Update from AI SC meeting in March

  - **Paper "Audit of APSIM papers containing models (and/or improvements) not in an APSIM release"**
  <br> Noted for this to be a 'live' document.  Useful to keep on top of any issues.  AI SC requested that RP raises and discuss issues as they arise.
  - **Development plan  (updates and days vs hours issue)**
  <br> **ACTION** @sarahcleary to send out current 18/19 development plan and request updates including all to check people have entered days not hours.  18/19 to be complete by end of financial year.  Look at new format for 19/20 development plan. 
  - **Funded Projects - Stock Model - to be reviewed out of session**
  <br> **ACTION** Agreed for @sarahcleary to forward Vals' draft to AI SC for approval 
  - Request for report on AI funded software position at each SC meeting
  <br> **ACTION** @Keith-Pembleton and @sarahcleary to work with Drew on paper (possible template to be used in future reports)
  - Request for update of GitHub process and RP Meeting structure/changes
  <br> **ACTION** @Keith-Pembleton and @sarahcleary to commence work on paper
  - Request for updates on conversations/workshops/activities – arising out of the RP Strategy session related to encouraging cross fertilisation  (and updates/actions arising from these) - including phosphorous developments
  <br> **ACTION** @sarahcleary to share email with actions from RP Strategy session.  @Keith-Pembleton to work with @sarahcleary to determine actions for agenda for next RP meeting. 
  - HB and GH working on "next gen documentation"
  <br> Hamish provided and update on conversation with Graeme.
  <br> **ACTION**   Hamish to organise to meet Graeme in person when visiting in August to work through documentation. 

### 2.4  Update on Actions from the RP Strategy Session - Feb 2019
  
 <br> **ACTION**  Outstanding actions to be included in agenda of June 2019 RP Meeting; Completed actions to be reported on.  @sarahcleary and @Keith-Pembleton to work on offline.
  
### 2.5  Update on Actions from AI-PFR Workshop - Nov 2018

 - Hamish led the discussion as the RP worked through actions from AI-PFR Workshop. Actions were as follows: 
 
AI to consider the following five areas of potential future focus/priority
1.	Developing horticultural/perennial tree crop functionality in APSIM.
2.	Climate change response functionality in APSIM.
3.	Developing multi-functional landscape capability in APSIM.
4.	Precision agriculture.
5.	Considering high performance computing needs and potential implications.  Recommendation - First step would be to collate what everyone is doing.  To ensure APSIM Infrastruture can deal with the high perforamnce computer.  Keith to start Github repository
<br> **ACTION**  RP agreed to review each of these areas as part of the review of the Development Plan.  Each home org would provide interest, syngery as part of the process of developing the plan for 19/20.  


### 2.6 Software

@peter-devoil led the discussion on the move from APSIM Classic into continuous release and a process to follow.  Note comment from Pete: *For the forseeable future, the Apsim Classic release will remain at 7.10, and links to upgrade to the latest bugfix are available to developers only via the bootleg system on bob. This means registered users don't have a) knowlege of available bugfixes, and b) access to them. I'm proposing some sort of notification system to registered users: some of these bugfixes have serious impact.* 
  
<br> **ACTION** @peter-devoil to work with @hol353 to propose a solution which is likely to involve version and build number.  Once agreed, @sarahcleary to provide a news article and web page for process and referencing. 


## 3.  Training	
  
Agreed for week commencing 23 March 2019. 
<br> **ACTION** @sarahcleary to start GitHub project; map out timeline; input from RP on speakers; structure provided out of session
  
  
## 4. Website/Communications	
  
  Updates requested from @sarahcleary <br>
  Outstanding articles from @HamishBrownPFR - barley model and Rogerio Cichota - white clover
  <br> **ACTION** @sarahcleary to follow up and send reminder to RP 
  
  **RG Trial** <br>
  New articles; better engagement - how to achieve this?
  <br> **ACTION** RP reps to either invite colleagues to RG or send @sarahcleary email addresses.  RP reps to insert updates in RG when new papers have been published.  
  
## 5. Other Business
  
  [acknowledgement guidelines](https://github.com/APSIMInitiative/ApsimX/issues/3813#issuecomment-488866569)
  <br> **ACTION** RP agreed to base the recommended acknoweldgement on the words provided by @sno036. @hol353 to update APSIMX and @peter-devoil to update APSIM Classic.  @sarahcleary to provide News Article and linked web page. 
  
## Next meeting

  Discussion of Date as @Keith-Pembleton is unavailable for next 3 meetings. 
  <br>**ACTION**: @sarahcleary to send out 3 doodle polls and send out new meeting requests.
  
