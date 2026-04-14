# MH1823
MH1823 Package for R
Rename the file as a ZIP, unzip it and follow the directions on the Statistical Engineering website (https://statistical-engineering.com/mh1823/ ) and you should be OK.  Please read all the instructions before doing anything and you won't find things too onerous.   Especially don't unzip the ZIP file until you have created a directory for it, and then don't unzip the file within - R will do that when it installs the mh1823 POD package.
Greetings:



Please tell me that you got this note because firewalls sometimes stop mail with attachments.  Also, I'd like to know a bit about you and your work.  What can you tell me?  Thanks.

 

Since the software is mine, I am making it available to anyone who requests it, so here is the mh1823 POD software and test cases, etc. attached as a "ngzip" file.  (I have no idea what "ngzip" means but apparently it will get past a firewall when ZIP won't.)   Just rename it ZIP, unzip it and follow the directions on the Statistical Engineering website (https://statistical-engineering.com/mh1823/ ) and you should be OK.  Please read all the instructions before doing anything and you won't find things too onerous.   Especially don't unzip the ZIP file until you have created a directory for it, and then don't unzip the file within - R will do that when it installs the mh1823 POD package. 

 

NOTE: The software has had many updates to improve functionality or to keep it compatible with R (that also is continually updated).  You can see the history here: https://statistical-engineering.com/mh1823-history/

 

The mh1823POD software uses R, of course, and it also uses several R packages, most of which come with the basic R installation.  You will need to install several required ancillary R packages.  This is easy – within the R console, enter this command: install.packages(c("tcltk2", "survival", "xlsx", "numDeriv

 

Or you can install them individually: from R, choose Packages, Install package(s), and choose the package from the menu.  If you don't have internet access, you can load the necessary R files locally.  I have included them in this package. 

 

 ***   Please let me know that you got this note.   ***

 

I have received reports of difficulties installing the software and the most common cause is not having JAVA (both 32-bit and 64-bit versions) installed or not having the latest version.  Java has been plagued recently with mischief and has issued frequent updates.  

 

Background:

In 2007 I completed a year-long contract with the USAF to update the two-decades-old MIL-HDBK-1823 and the Air Force got around to approving the book in April 2009.  I’ve included a copy with the mh1823 POD software.

 

The deliverables of my 2006-2007 contract to update MIL-HDBK-1823 included the draft of the updated Handbook and algorithms necessary to implement the methods described in the Handbook.  Software was not a deliverable item.  However, it soon became obvious that delivering descriptions of statistical algorithms, with no convenient implementation of them, would be of limited utility, so I wrote the mh1823 POD software suite to help promulgate the handbook's methods.  I receive no financial support for this software apart from donations, so if you find the software useful and would like to contribute, you can do that here: https://statistical-engineering.com/support/

Thanks.

 

Caution:

I also want to caution you.  While the methods in MIL-HDBK-1823A are effective for a very large majority of quantitative NDE situations, they are not universally applicable.  There are at least two classes of data for which these methods are not valid:

 

1) Data that do not support a POD curve that goes to zero on the left, or to one on the right, i.e. POD "floor" and "ceiling" data (https://statistical-engineering.com/pod-floor-ceiling/), and

 

2) Field-Finds. (https://statistical-engineering.com/field-finds/)  If you have these types of data, you will be able to torture the mh1823 POD software into giving you an answer.  But it will be wrong.

 

Please note that I can teach a 2-day POD short course and workshop at your venue on the statistical foundations for the MIL-STD-1823A methods, and using the advanced version of the mh1823POD software.   (https://statistical-engineering.com/mh1823-workshop/ )   If you wish, we can use your enterprise data to solve real enterprise problems.  And if the demands of a specific project are becoming onerous, you might consider me as a collaborator, especially if your task involves the interplay of  fatigue/fracture, component life analysis, risk assessment and NDE efficacy.

 

Best wishes!



Charles Annis, P.E.  (Registered Professional Engineer since 1977)

AnnisC@Gmail.com

Charles.Annis@Statistical-Engineering.com
phone: 561-352-9699
http://www.Statistical-Engineering.com
