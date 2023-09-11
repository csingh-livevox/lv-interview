# lv-interview

# Task-1
Write a small project to verify testcase A and Testcase B on ASG. 
#### ``` Note: ASG stands for AWS Auto Scaling groups.```
## Pass/Assertion Criteria:

#### Testcase:- A
 * 1- ASG desire running count should be same as running instances. if mismatch fails
 * 2- If more than 1 instance running on ASG, then the ec2 instance should on available and distributed on multiple availibity zones. 
 * 3- SecuirtyGroup, ImageID and VPCID should be same on ASG running instances. Do not just print.
 * 4- Findout uptime of ASG running instances and get the longest running instance.

#### Testcase:- B
 * Find the Scheduled actions of the given ASG which is going to run next and calculate elapsed in hh:mm: ss from the current time.
 * Calculate the total number of instances launched and terminated on the current day for the given ASG.


## Expectations from your project:
 * Validation of the above pass criteria in your project
 * Handling of Edge case and Empty response
 

# Further important instruction:

##  Don't: :no_entry_sign:
* Please do not check-in your received Access key ID and Secret access key. You can look at an example share on sample.py[https://github.com/csingh-livevox/lv-interview/blob/main/sample.py] for how to do it without expose/hardcoding into your project.
* Do not fork and create pull requests from this repo.

## Do's: :tick:
* Please use python and/or any python test framework
* Please use modular coding to do the same.
* Once done, please host the code on your public repo on GitHub and share the link.
https://github.com/youruser_name/livevox-assignment-task-1                                                           

``` Good Luck, Happy Coding !```
