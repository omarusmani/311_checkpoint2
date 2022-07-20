# Diary Location

  For my checkpoint 2 for 311 I would like model an app that lets you sign in to a website where you can right your thoughts down. It will store your location.
 
 Eventually I hope i can integrate an API to call to access the camera. 
 
 For this app i need three tables for now.
 
 The first table (USER_NAMES) will be the one that contains a USER_NAME and PASSWORD with a PRIMARY KEY id.
 
 The second table (INFO) will contain the PRIMARY KEY id and some of the users data, FIRST_NAME, LAST_NAME, MEMBER_START, PRIMARY_KEY id, #_OF_ENTERIES, LAST_POST.
 
 The third and current last table (ENTERIES) will conatain the enteries each with a PRIMARY_KEY, LOCATION,TIME, DATE, ENTRY.
 
 Once a user is signed in they can only get access to their data through the PRIMARY_KEY.
 EACH USER_NAME can only have one field on the INFO table.
 
 THE INFO_TABLE can access the ENTERIES table through the PRIMARY-KEy determine #_OF_ENTERIES & the LAST_POST.
 
 EACH USER_NAME can access their own and enteries in the table ENTERIES through the PRIMARY_KEY.
 
