# Ring and police department partnerships: 2022 analysis

This repository contains data, code and findings around the Brookhaven, Georgia police department's relationship with Amazon/Ring cameras. 

# Data

Owners of Ring's doorbell and security cameras can upload their footage to the Neighbors app and add captions, questions and other information. Ring then sends email alerts about these posts to the Brookhaven police department. This data was gathered through a Freedom of Information Request from Lam Thuy Vo, in which copies of the alert emails were requested. 

For each email, the dataset includes the following details:

- subject	: the subject of the email (always 'A Resident Posted a Crime Incident')
- date	: date email was sent
- sender	: email sender (always 'Ring Team <no-reply@neighborhoods.ring.com>')
- to	: police department staff member who received email
- cc	: any email addresses CC'd on the email
- body_title_top	: description of post
- body_link1_title	: link to the post
- body_post_classification	: classification (always 'A resident in your area just posted a crime incident to the Neighbors App.')
- body_title	: description of the post
- body_date : date posted
- body_description	: short description
- body_link2_title	: link to the post
- body_link3_title	: link to the post
- body_full	file_name : all body data

# Methodology

This analysis consists of two parts. 1) A tallie of the emails over time, showing how many were sent per month and 2) A tallie of how many posts contain the word 'car' and how many posts contain the word 'package

# Analysis

All analysis can be found in the notebook assignment_4.ipynb

The notebook produces one file: a CVS file containing a tallie of how many emails were sent per month.

# Licensing

All data files in the output/ directory are available under the Creative Commons Attribution 4.0 International (CC BY 4.0) license. All data files in the data/ directory are available, under their own terms, from the sources described above.

# Feedback/Questions

I can be reached at james.m.odonnell4@gmail.com.

