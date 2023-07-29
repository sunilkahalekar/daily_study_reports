# daily_study_reports
This is summary of links of daily reading

# Malware reports links
1. https://blog.eclecticiq.com/dark-pink-apt-group-strikes-government-entities-in-south-asian-countries?utm_campaign=Website%20-%20blog&utm_content=241088372&utm_medium=social&utm_source=linkedin&hss_channel=lcp-10226527
2. https://blog.eclecticiq.com/enabling-file-integrity-monitoring-on-windows-with-osquery-and-eclecticiq-endpoint-response?utm_campaign=Website%20-%20blog&utm_content=241721778&utm_medium=social&utm_source=linkedin&hss_channel=lcp-10226527

Date: 23-03-2023
1. https://medium.com/hackernoon/malware-analysis-using-osquery-part-1-78f5f617cc19
2. https://symantec-enterprise-blogs.security.com/blogs/threat-intelligence/evolution-emotet-trojan-distributor
3. https://files.brucon.org/2015/Tomczak_and_Ballenthin_Shims_for_the_Win.pdf

Date: 25-04-2023
https://blog.eclecticiq.com/3cx-incident-attributed-to-north-korea-new-lockbit-macos-sample?utm_campaign=No%20campaign&utm_medium=email&_hsmi=255660707&_hsenc=p2ANqtz-9JH0K4F4YltAULrEVUeQe_QCu3HKODvO7RkzSLUpOeuLEKnxdUq6wbXpSt5GWgTje4bBVbo0baL_SIk107o-U7xwnMvrBdRnhFQ-BTWfo-JEpaZ7A&utm_content=255660707&utm_source=hs_email

Date: 02-05-2023

https://blog.eclecticiq.com/polish-healthcare-industry-targeted-by-vidar-infostealer-likely-linked-to-djvu-ransomware?utm_campaign=No%20campaign&utm_medium=email&_hsmi=256632541&_hsenc=p2ANqtz-9JXh1KtTIm0wsrac129fPgU0B7hJa6I53l_J4fG2mxf9CXy31YvTkZIaXV2-SNHxrMuKii-ysowSizcKGmHqT_LNKtjcCf9K4lL_fFQ96E8-o4s-s&utm_content=256632541&utm_source=hs_email

Meeting: 29-07-2023
Each and every api should have test case
crash in deletion. Deletion api kill server, we need to check that. 
Identify bugs: In User control and shut down application. it is big bug.

documentation and writting test part: 
Look at documentation cloud application, REST API documentation which will be helpful.
Link for Documentation : https://www.freecodecamp.org/news/build-consume-and-document-a-rest-api/?s=09#how-to-document-a-rest-api-with-swagger

Storing output of this test case.: github repository

Test cases, are much interative to user.
Run for non admin ,admin user, non supporting machines
Error Part: not much cases,
Screen shot of each folder

CACSL tool windows tool
https://learn.microsoft.com/en-us/windows-server/administration/windows-commands/cacls
just invoke this tool.

Marker file is indication of osquery pid file, orevent simultanous invocation
you have to reomve marker file. What is middle accidentaly doing twise. 
Corner cases. Improving whole programme. Fix for that.

Evented Log:
How does this eventing happen? Windows log, extension is doing. Many of linux table are evented. Process, file socket are evented.
How osquery manage evneted 
How tdo you
every os tells you
What is event. Any activity in system which cahage stste. So chaning registry event, file ete. Our objective is reorcd that chnage.
Certain Osallow you easer as piit of programmig ie information of those event. Linuz give those methond out of box. Same is MAC. also, has simmiliar method. Now concern about security event. Those mechcanism are trusted and reliable. 
On windows this event are typical from kernal which is complicated tast but not easy task.
Microsoft ensure that kernal is not easy task. It also required addisional skill test.

Osquery, destabalising sytem is detached from as kernal development is very risky.
window: etw is method capturing windows event.
Thery are writting technology and techniogy not cause a stabalizing issue.
ETW table are avaiable.

SISMON + osquery= ecleticiq

Sysmon has kernal mechnisum. Sysmon is not native compnent of osquery.
knowing sysmon parallen mechanisum fuse with osquery data.
sysmon is free but licenece version. 
Write an osquery + install sysomn out put server.















