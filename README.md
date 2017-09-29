# An anonymized dataset of 60+ million users of the Swarm App

Measurement and Analysis of the Swarm Social Network with Tens of Millions of Nodes (full citation below)

Licensed under [Creative Commons Attribution Share Alike 4.0](http://choosealicense.com/licenses/cc-by-sa-4.0/).

## Description
This dataset covers more than 60 million users of the Swarm App, including the friend list and the total number of check-ins of each user.

## Files
Download link:  
* ``[check-in_nums.txt](https://drive.google.com/open?id=0B6Ct8a-6OQtfNk5XNHE1ZlpCUE0)``: all the Swarm users' check-in numbers</br>
Each line in ``check-in_nums.txt`` is in the form of a pair (anonymized_user_ID, check-in_number). e.g. ``32, 9334`` means the anonymized user ID is 32 and he/she has 9,334 check-ins in total.

* ``[edges.rar](https://drive.google.com/open?id=0B6Ct8a-6OQtfX2tnQklHR3Jkd0E)``: all the Swarm users' friendlists</br>
Each line in ``friends_add_edges.txt``, extracted from ``edges.rar`` starts with an anonymized user ID and the number of her friends, then followed by a list of IDs of her friends.</br>
For example:</br>
In a line ``23 5 123 3 9909 1233 123``</br>
23 is the anonymized user ID, 5 is the number of her friends, 123, 3, 9909, 1233 and 123 are the IDs of her friends.

