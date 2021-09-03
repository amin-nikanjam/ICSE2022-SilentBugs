# ICSE_2022_Silent_Bugs
This Replication Package is intended for replication of results presented in the paper "Silent Bugs in Deep Learning Frameworks: An Empirical Study of Keras and Tensorflow" submitted at the 44th International Conference on Software Engineering (ICSE 2022). It contains the data and artifacts used in the paper.
The replication package `Keras Bugs Sheets.xlsx` contains three sheets:
* **Issues Voting**: Contains the 1168 gathered issues. For each of them, we provide title, URL, GitHub labels as well as whether it was accepted by each of the three reviewers with eventually a comment. The total of issues for each of the number of votes assigned is given at the end of the sheet.
* **2 votes bugs**: Contains the list of the 38 two votes bugs that were discussed by reviewers for eventual acceptation. We liste the title, URL and labels of those issues, as well as the comments of each reviewer for the issue. We higlighted comment from the reviewer that refused it. The decision after discussion is presented in the "Accepted?" column.
* **Comparison Category**: Contains the list of the 83 issues accepted after the voting round. The same information as before are presented. We add the proposition by each reviewer for impact on the user's program (column "Scenario") as well as which part of the API was affected (column "Component"). Final decision after group discussion are presented in "Final Scenario" and "Final Component", as well as the column "Impact" which determine the threat level according to the scale presented in our paper for each of the issue. The last columns gives information about the URL of the gist for reproduction, the version(s) were the bug happened, the version that fixed the bug and eventually the commit fixing the issue.
