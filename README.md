# MLC Release Process and Procedures

The purpose of this wiki page is to provide a comprehensive guide to the MLC Applications Release Management Process and Procedure. The goal is to establish standardized process that ensures consistency, quality, and control throughout the release lifecycle.

# Release Management Process Flow

![image](https://github.com/dheenapm/testreadme/blob/main/Picture1.png)
![image](https://github.com/dheenapm/testreadme/blob/main/Picture2.png)

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-o5n3{background-color:#FFF;font-weight:bold;text-align:left;vertical-align:bottom}
.tg .tg-wa1i{font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-mf8g{background-color:#8EA9DB;font-weight:bold;text-align:left;vertical-align:middle}
.tg .tg-zk71{color:#444;text-align:left;vertical-align:bottom}
.tg .tg-q3nt{background-color:#8EA9DB;border-color:inherit;font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-y6he{background-color:#8EA9DB;font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-2g1l{background-color:#FFF;font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-f4yw{background-color:#FFF;text-align:center;vertical-align:middle}
.tg .tg-kcps{background-color:#FFF;text-align:left;vertical-align:bottom}
.tg .tg-ktyi{background-color:#FFF;text-align:left;vertical-align:top}
.tg .tg-7zrl{text-align:left;vertical-align:bottom}
.tg .tg-2lxe{background-color:#FFF;color:#F00;text-align:left;vertical-align:bottom}
.tg .tg-7yig{background-color:#FFF;text-align:center;vertical-align:top}
.tg .tg-j6zm{font-weight:bold;text-align:left;vertical-align:bottom}
.tg .tg-nrix{text-align:center;vertical-align:middle}
</style>
<table class="tg"><thead>
  <tr>
    <th class="tg-q3nt">Activities</th>
    <th class="tg-mf8g">Step#</th>
    <th class="tg-y6he"> Description</th>
    <th class="tg-mf8g">Owner</th>
    <th class="tg-mf8g">Details Task</th>
    <th class="tg-mf8g">Release Mangement activites</th>
    <th class="tg-mf8g">Standard Release</th>
    <th class="tg-mf8g">Monthly Release</th>
    <th class="tg-mf8g">Quaterly Release</th>
    <th class="tg-mf8g">Emergency(Hotfix)Releases</th>
    <th class="tg-mf8g">Lead time</th>
    <th class="tg-mf8g">Notes</th>
  </tr></thead>
<tbody>
  <tr>
    <td class="tg-2g1l" rowspan="4">Pre- release activites</td>
    <td class="tg-o5n3">1</td>
    <td class="tg-f4yw">Rally's Milestones</td>
    <td class="tg-kcps">Release Manager</td>
    <td class="tg-zk71">Create milestones in Rally (Monthly/Quarterly/Sprint level (Thursday))</td>
    <td class="tg-kcps">Set up for the year calendar ahead for teams to use as placeholder for future releases</td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps"> </td>
    <td class="tg-kcps"></td>
  </tr>
  <tr>
    <td class="tg-o5n3">2</td>
    <td class="tg-f4yw">Request for a Release with the release manager </td>
    <td class="tg-kcps">Tech Lead</td>
    <td class="tg-ktyi">Need below information from the scrum team along with approvals from App Owner, PO and RTE<br>&nbsp;&nbsp; - Release date  <br> - Start and end time  <br> - Type of release (standard, Montly, QTR exception,fallouts) <br> - Brief description (for example: UI enhancement, JBOSS server upgrade...) <br> - Tech Lead for the release<br> - Any Plutora tasks that’s not applicable for this release <br> - User stories/defects involve in the release (optional) </td>
    <td class="tg-kcps">RM will identify MLC or App level milestone are needed</td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps">No</td>
    <td class="tg-kcps">No</td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-ktyi">Beginning of QTR - Quaterly release<br> At least 4 week prior - Monthly Release<br> Beginning of the sprint - Standard Release</td>
    <td class="tg-kcps">Release on Demand types:<br> Emergency Release: urgent releases not related to any fallouts<br> Hotifx Release: to remediate fallouts</td>
  </tr>
  <tr>
    <td class="tg-o5n3">3</td>
    <td class="tg-f4yw">Tag all US/Defect/Feature with Milestone</td>
    <td class="tg-kcps">Scrum Master</td>
    <td class="tg-kcps">Tag or update US/Defect/Feature to the MLC and App Level Milestone</td>
    <td class="tg-kcps">NA</td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps"></td>
    <td class="tg-kcps"></td>
  </tr>
  <tr>
    <td class="tg-o5n3">4</td>
    <td class="tg-f4yw">Create below tickets and app level milestones for each apps tagged within the milestones <br> - mTE<br> -Rally<br> -Plutora</td>
    <td class="tg-kcps">Release Coordinator</td>
    <td class="tg-kcps"></td>
    <td class="tg-kcps">- Create MLC level milestone for the the release<br> - Create milestone for each App level</td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps"></td>
    <td class="tg-kcps"></td>
  </tr>
  <tr>
    <td class="tg-2g1l" rowspan="11">During Sprint </td>
    <td class="tg-o5n3">1</td>
    <td class="tg-f4yw">Game plan Document/Link</td>
    <td class="tg-kcps">Tech Lead</td>
    <td class="tg-kcps">Preferably  Sharepoint link, upload on Plutora <br> <br> Update pre-release, release and post release tasks's status throughout the release to be documented as part of the game plan<br> <br> Readiness checklist</td>
    <td class="tg-kcps">NA</td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-7zrl"></td>
    <td class="tg-kcps">Standard - Can be a simplified version<br> <br> Emergency/Hotfix Releases - Can be informal some bullet points of the task and time frame in the release call email</td>
  </tr>
  <tr>
    <td class="tg-o5n3">2</td>
    <td class="tg-f4yw">Operational Checklist using the template provided in Plutora</td>
    <td class="tg-kcps">Tech Lead</td>
    <td class="tg-kcps">Tech lead will update operational checklist and Engage RE Squad if there's any Dynatrace, Splunk, any performance testing/result review</td>
    <td class="tg-kcps"></td>
    <td class="tg-kcps">TBD</td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps">TBD</td>
    <td class="tg-7zrl"></td>
    <td class="tg-kcps">standard/emergency releases might not need performance testing</td>
  </tr>
  <tr>
    <td class="tg-o5n3">3</td>
    <td class="tg-f4yw">RITMs and/or CHG tickets for the deployment ( Infra and App team)</td>
    <td class="tg-kcps">Tech Lead</td>
    <td class="tg-kcps">At times, CHG tickets will be created after RITM is received by the infrastructure team. <br> If no RITMs needed for release a CHG ticket still need to be created by core team to indicate who will be approving code deployment<br> </td>
    <td class="tg-kcps"></td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps"></td>
    <td class="tg-kcps"></td>
  </tr>
  <tr>
    <td class="tg-o5n3">4</td>
    <td class="tg-f4yw">Adhere to the Softfreeze and Hardfreeze date</td>
    <td class="tg-kcps">Scrum team</td>
    <td class="tg-kcps"></td>
    <td class="tg-kcps">RM to communicate softfreeze and Hardfreeze to the team</td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-2lxe">No</td>
    <td class="tg-kcps"></td>
    <td class="tg-kcps">Soft freeze may not applicable for the Emergency/Hotfix</td>
  </tr>
  <tr>
    <td class="tg-o5n3">5</td>
    <td class="tg-f4yw">QA Unlocks</td>
    <td class="tg-kcps">Scrum team</td>
    <td class="tg-kcps">Release Manager should be engaged at the beginning on any potential of QA Unlocks<br> needs both QA &amp; RTE(s) approvals with email confirmation as evidences</td>
    <td class="tg-kcps"></td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-2lxe">No</td>
    <td class="tg-kcps"></td>
    <td class="tg-kcps"></td>
  </tr>
  <tr>
    <td class="tg-o5n3">6</td>
    <td class="tg-7yig"> QA Unlock:<br> -Lesson Learnt<br> -Root cause</td>
    <td class="tg-kcps">Release Coordinator &amp; tech lead</td>
    <td class="tg-kcps">Communication established to identify root cause and lesson learnt for QA Unlocks</td>
    <td class="tg-kcps">Properly document details in QA Unlock report</td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps">Before release date</td>
    <td class="tg-kcps">Evidence required<br> </td>
  </tr>
  <tr>
    <td class="tg-o5n3">7</td>
    <td class="tg-f4yw">Complete Plutora's pre-release items</td>
    <td class="tg-kcps">RTE/PO/QA</td>
    <td class="tg-kcps">Complete below task and upload evidence with the signoff in the plutora<br> <br> - QA Testing<br> - UAT<br> - Quality Governance Check<br> - Disaster Recovery &amp; Cyber Recovery Documentation Reviews</td>
    <td class="tg-kcps"></td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps"></td>
    <td class="tg-kcps"></td>
  </tr>
  <tr>
    <td class="tg-o5n3">8</td>
    <td class="tg-f4yw">Game plan walkthrough with the App team and Impacted applications. Include contact details as part of the plan</td>
    <td class="tg-kcps">Tech lead</td>
    <td class="tg-kcps">- link to gameplan SharePoint document (preferred in case of new updates) <br> - include RITMs and/or CHG tickets in gameplan  <br> - all related key person: TLs, PO, RTE, RM <br> - Tech lead to communicate and secure requirement team member to be available during the release day<br> <br> ***RTE should be added as optional to review </td>
    <td class="tg-kcps"></td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps">Final version to be available 5 business day prior to the release<br> <br> Emergency/Hotfix: as soon as release is determined</td>
    <td class="tg-kcps">RTE should be added as optional to review </td>
  </tr>
  <tr>
    <td class="tg-o5n3">9</td>
    <td class="tg-f4yw">QA Sign off (TEST complete)</td>
    <td class="tg-kcps">QA team</td>
    <td class="tg-kcps">All releases under invest projects need to have sign off from QA team. If no E2E testing needed, team still need to perform functional testing and share to QE team as part of the signoff</td>
    <td class="tg-kcps">Ensure QA testing is reviewed by QE team </td>
    <td class="tg-kcps">TBD</td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps">TBD</td>
    <td class="tg-kcps">3 business days prior</td>
    <td class="tg-kcps"></td>
  </tr>
  <tr>
    <td class="tg-o5n3">10</td>
    <td class="tg-f4yw">App Owner Approval by reviewing all Pre-Release Items, and check Plutora tasks as complete</td>
    <td class="tg-kcps">App Owner</td>
    <td class="tg-kcps"></td>
    <td class="tg-kcps"></td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps">2 business day prior<br> <br> Emergency/Hotfix releases: as soon as gameplan walkthrough completed</td>
    <td class="tg-kcps"></td>
  </tr>
  <tr>
    <td class="tg-o5n3">11</td>
    <td class="tg-f4yw">Formal email communication using RE SQUAD communication template/mailbox about the application outage</td>
    <td class="tg-kcps">Tech lead</td>
    <td class="tg-kcps">Ensure an email sent notifying business groups about application outage ahead of time<br> <br> </td>
    <td class="tg-kcps"></td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps"> Prior to the release</td>
    <td class="tg-kcps">Raja would be working with the tech lead from RE and Invest to have consistent outage communication using the template</td>
  </tr>
  <tr>
    <td class="tg-2g1l" rowspan="7">Production day</td>
    <td class="tg-o5n3">1</td>
    <td class="tg-f4yw">Coordinate release activities </td>
    <td class="tg-kcps">Release Coordinator</td>
    <td class="tg-kcps"></td>
    <td class="tg-f4yw">Ensure smooth release activities. For any issue will coorodinate with the required team to secure support on time</td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps"></td>
    <td class="tg-kcps"></td>
  </tr>
  <tr>
    <td class="tg-o5n3">2</td>
    <td class="tg-f4yw">Deploy and validate</td>
    <td class="tg-kcps">Tech Lead</td>
    <td class="tg-kcps"></td>
    <td class="tg-kcps"></td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps"></td>
    <td class="tg-kcps"></td>
  </tr>
  <tr>
    <td class="tg-o5n3">3</td>
    <td class="tg-f4yw">IT Checkout</td>
    <td class="tg-kcps">Tech lead</td>
    <td class="tg-kcps">(1) Email from tech lead validating deployed version number, and everything is working as expected (usually mention "IT Checkout")<br> (2) Include smoke test completion/successful result</td>
    <td class="tg-kcps"></td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps">As soon as release process is completed</td>
    <td class="tg-kcps">Evidence required</td>
  </tr>
  <tr>
    <td class="tg-o5n3">4</td>
    <td class="tg-f4yw">Business Checkout</td>
    <td class="tg-kcps">Product Owner(s)</td>
    <td class="tg-kcps">(1) PO completes the plutora signoff activity<br> (2) Email chain from PO(s) validating that they providing "Business Sign Off", or release is successful<br> (3) Include test results if applicable</td>
    <td class="tg-kcps"></td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps">As soon as release process is completed</td>
    <td class="tg-kcps">Evidence required</td>
  </tr>
  <tr>
    <td class="tg-o5n3">5</td>
    <td class="tg-f4yw">Update Plutora</td>
    <td class="tg-kcps">Tech lead/PO/RM</td>
    <td class="tg-kcps">Double check any remaining tasks on Plutora and mark status accordingly, ensure all evidences are presented if the tasks required</td>
    <td class="tg-kcps"></td>
    <td class="tg-kcps"></td>
    <td class="tg-kcps"></td>
    <td class="tg-kcps"></td>
    <td class="tg-kcps"></td>
    <td class="tg-kcps"></td>
    <td class="tg-kcps"></td>
  </tr>
  <tr>
    <td class="tg-o5n3">6</td>
    <td class="tg-f4yw">Formal email communication using RE SQUAD communication template/mailbox about the application outage</td>
    <td class="tg-kcps">Tech lead</td>
    <td class="tg-kcps">Notify business group that application outage is completed and is available for usage</td>
    <td class="tg-kcps"></td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps"></td>
    <td class="tg-kcps">Raja would be working with the tech lead from RE and Invest to have consistent outage communication using the template</td>
  </tr>
  <tr>
    <td class="tg-j6zm">7</td>
    <td class="tg-nrix">Track any fallouts</td>
    <td class="tg-7zrl">Release Coordinator/ Scrum Masters/Tech Lead</td>
    <td class="tg-7zrl">defect should be logged in Rally under these categories:<br> -Environment: Production<br> -Milestone: original release from which defect is found<br> -Tag: using this format "yyyy month dd release fallout"</td>
    <td class="tg-7zrl">Making sure team create Rally defect once an issue is identified. <br> Adding the defect info on fallout report and have team lead complete the required metrics accordingly</td>
    <td class="tg-7zrl">Yes</td>
    <td class="tg-7zrl">Yes</td>
    <td class="tg-7zrl">Yes</td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps">As soon as release process is completed</td>
    <td class="tg-kcps">Any defect occured during and/or after release is considered fallout (even it was fixed at the time of release)</td>
  </tr>
  <tr>
    <td class="tg-wa1i" rowspan="6">Post Release</td>
    <td class="tg-j6zm">1</td>
    <td class="tg-nrix">Collect IT and Business Checkout documents from Plutora tasks and upload on main project page and mTE release ticket</td>
    <td class="tg-7zrl">Release Coordinator/Tech Lead/PO</td>
    <td class="tg-7zrl">ensure all tasks require evidences do have evidences attached and properly documented</td>
    <td class="tg-7zrl">ensure all tasks in Plutora and Servicenow and Plutora are marked with correct status (not yet started/complete/N.A); <br> <br> Upload all documents, evidences on main Plutora page, mTE</td>
    <td class="tg-7zrl">Yes</td>
    <td class="tg-7zrl">Yes</td>
    <td class="tg-7zrl">Yes</td>
    <td class="tg-7zrl">Yes</td>
    <td class="tg-7zrl">As soon as release process is completed</td>
    <td class="tg-7zrl"></td>
  </tr>
  <tr>
    <td class="tg-j6zm">2</td>
    <td class="tg-nrix">Post Release review (optional, if needed, will be listed under gameplan)</td>
    <td class="tg-7zrl">All</td>
    <td class="tg-7zrl">Post production stability review<br> </td>
    <td class="tg-7zrl"></td>
    <td class="tg-7zrl">No</td>
    <td class="tg-7zrl">No</td>
    <td class="tg-7zrl">Optional</td>
    <td class="tg-7zrl">Optional</td>
    <td class="tg-7zrl">following business day after the release</td>
    <td class="tg-7zrl">needed based on complexity of the releases</td>
  </tr>
  <tr>
    <td class="tg-j6zm">3</td>
    <td class="tg-f4yw">Collect Fallouts </td>
    <td class="tg-kcps">Release Coordinator &amp; Scrum Masters</td>
    <td class="tg-kcps">a meeting is opened for teams to report to release manager of any fallouts are found after release<br> properly using tags and parent userstories field under defect </td>
    <td class="tg-7zrl">Document in Fallout tracking sheet and have tech tead filling in all required metrics</td>
    <td class="tg-7zrl">Yes</td>
    <td class="tg-7zrl">Yes</td>
    <td class="tg-7zrl">Yes</td>
    <td class="tg-7zrl">Yes</td>
    <td class="tg-7zrl">Bi-weekly meeting</td>
    <td class="tg-7zrl"></td>
  </tr>
  <tr>
    <td class="tg-o5n3">4</td>
    <td class="tg-f4yw">Fallout lesson Learnt &amp; Root cause</td>
    <td class="tg-kcps">Release Coordinator &amp; tech lead</td>
    <td class="tg-kcps">Communication established to identify root cause and lesson learnt for release fallouts</td>
    <td class="tg-kcps">Properly document details in Release fallout report</td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps">Bi-weekly meeting</td>
    <td class="tg-kcps"></td>
  </tr>
  <tr>
    <td class="tg-o5n3">5</td>
    <td class="tg-f4yw">Hotfix releases (if needed)</td>
    <td class="tg-kcps">All</td>
    <td class="tg-kcps">Meeting with Scrum teams, PO, RTE, QA, RM regarding the defects and urgency.</td>
    <td class="tg-kcps">Gather details for release:<br> -Aprrovals from RTE, PO and QA<br> -Date/time<br> -Rally defects/user stories</td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps">Yes</td>
    <td class="tg-kcps">As soon as team decides for a hotfix</td>
    <td class="tg-kcps"></td>
  </tr>
  <tr>
    <td class="tg-j6zm">6</td>
    <td class="tg-nrix">Reports</td>
    <td class="tg-7zrl">QA, RM</td>
    <td class="tg-7zrl"></td>
    <td class="tg-7zrl">weekly/monthly release detail reports extend to business </td>
    <td class="tg-7zrl">Yes</td>
    <td class="tg-7zrl">Yes</td>
    <td class="tg-7zrl">Yes</td>
    <td class="tg-7zrl">Yes</td>
    <td class="tg-7zrl"></td>
    <td class="tg-7zrl"></td>
  </tr>
</tbody></table>
