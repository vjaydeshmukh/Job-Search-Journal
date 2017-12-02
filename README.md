The process of applying for jobs can be time-consuming and stressful: You’re filling out applications, attending interviews, and keeping track of what step you are in the application process with each company you apply to. Eventually names, dates, emails, and interviews all blend together. In this paper an application called “JobApp Tracker” is presented. JobApp Tracker is an application that helps individuals track the applying-to-jobs process for various jobs, keeping all potentially-useful information within the application for later retrieval.

The main screen shown when the application is first started lists each company that a user has entered (either alphabetically by name or sorted by step in the application process, based on a user’s choice in the settings). This information is stored in an SQLite database on the device. Each company’s logo, name, website, position the user applied for, and step in the application process is shown. Companies’ logos and websites are retrieved via the Glassdoor Web API.

When a user clicks on a company’s name in this list, the user is brought to a screen that contains information about the company. The Glassdoor Web API provides access to a company’s logo, industry, website, and ratings. At the top of this screen is a button that reads “Click to track progress with this company!” This button brings the user to the “Track Your Progress” screen, which offers the aforementioned functionality. Another API that is used is the Google Street-View API, which will provide the user with a street-view image of a company based on its address.

The initial contact fragment within the “Track Your Progress” activity accesses the device’s call logs to count how many times calls have been exchanged with a particular phone number. The scheduled interview fragment uses an intent to bring up the user’s email client with an email already addressed to the recipient (based on the “Contact Email Address” provided). All of these features exist to help users track their application process, in addition to granting users quick-and-easy access to recruiters’ and interviewers’ contact information.


--------------------------------------------------



Main page

![Main page](https://github.com/cjaiello/MobileBSMSProject/blob/master/screenshots/mainpage.png)



--------------------------------------------------

Tracking progress with a company

![Adding a new company](https://github.com/cjaiello/MobileBSMSProject/blob/master/screenshots/entry.png)
![Company view](https://github.com/cjaiello/MobileBSMSProject/blob/master/screenshots/companyview.jpg)
![Imported ratings](https://github.com/cjaiello/MobileBSMSProject/blob/master/screenshots/ratings.png)


--------------------------------------------------

Initial contact info

![Initial Contact Info](https://github.com/cjaiello/MobileBSMSProject/blob/master/screenshots/screenshot-2.png)


--------------------------------------------------

Interview scheduling

![Interview Scheduling](https://github.com/cjaiello/MobileBSMSProject/blob/master/screenshots/screenshot-3.png)


--------------------------------------------------

Interview results

![Interview Results](https://github.com/cjaiello/MobileBSMSProject/blob/master/screenshots/screenshot-4.png)

