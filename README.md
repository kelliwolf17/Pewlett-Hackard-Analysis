# Pewlett-Hackard-Analysis

# Overview
The purpose of this analysis was to update Pewlett Hackard's database department and determine certain relationships around their employees of or near retirement age, also referred to as the "silver tsunami". 

# Results
After providing some analysis, it was determined that:
* From the retirement_titles table, we know that many of the employees that are of retirement age have worked several roles throughout their time at PH. We were able to pull 133,776 titles. 
* Then from the unique_titles tables, we narrowed down the retirement_titles table to give us distinct names and their current role. We were able to pull 90,398 employees, so over 40K employees had more than one role at PH that are of retirement age.
* Then from the retiring_titles, we pulled the list of titles/positions that will need to be filled once the retirees actually retire. The list is shown below.

        ![retiring_titles](https://user-images.githubusercontent.com/71397190/99208319-b540f980-2785-11eb-9b14-70f12c3ba869.PNG)

* Lastly, from the mentorship_eligibility table we were able to pull a list of 1,549 employees who fit the requirements of those who are eligibile to participate in a mentorship program.

# Summary
## "Silver Tsunami" Effects
As dictated by the unique_titles table, we were able to identify 90,398 roles that will be need to filled as the "silver tsunami" starts impacting the business.

## Mentorship Program
The titles held by the 1,549 employees that are eligible for the mentorship program are Senior Staff, Staff, Technique Leader, Senior Engineer, Engineer, and Assistant Engineer. These are nearly all the roles encompassed by the retiring_titles table. The retirement-ready employees should be able to cover the mentorship program fairly easily personnel-wise. There would have to be a vetting process to make the right pairings, and unfortunately not too many managers available to help mentor the next manager generation at PH. Even so, the senior positions can mentor the lower level positions and so on to help ease the transition.
