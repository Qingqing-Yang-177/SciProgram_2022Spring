OMNI DATA

The omni dataset has data from people trying to learn Lithuanian-English word pairs.

EXPERIMENT OVERVIEW

Each person studied 45 pairs of words and gave a rating of how well they thought they learned the pairs. This is called a "judgment of learning", or JOL.

After a delay (see below), each person engaged in a retrieval test where they were presented with a Lithuanian word and attempted to recall the associated English word. Retrieval trials were scored as correct if the person recalled the English word and incorrect otherwise.

Each person was assigned to one of four groups, and the group assignment determined the approximate study-to-test delay (i.e., how long they waited between studying the words and trying to recall).

In addition, some of the participants did the learning task while in an MRI scanner and some did not.


DATA DETAILS:

The datafiles for this project are as follows:

omni_data_group-F.csv
omni_data_group-A.csv
omni_data_group-C.csv
omni_data_group-H.csv

The group letter indicates the approximate study-to-test delay time and each csv has data from individual people assigned to that group.

Each of the csv's has the following columns:

participant_number: a number assigned to each participant in each group (NOTE: these are not unique across groups. For example there is a participant_number 2 in both the F and A groups)

group: the study-test delay group (categorical) (NOTE: a unique ID for a person would be the combination of their participant_number and their group assignment)

judgment_of_learning: an individual person's average rating of how well they learned the words (numeric, 0 to 100)

response_time: how long it took a person to give their judgment of learning (numeric, in seconds)

percent_correct: the proportion of test trials that a person answered correctly. In other words, their memory performance. (numeric, 0 to 1)

test_delay_minutes: the delay in minutes from when a person finished the study session to when they started the retrieval session (numeric, in minutes)

in_mri: a binary indicator of whether a person was in the MRI scanner (is_mri=1) or not in the scanner (is_mri=0) during the study session (categorical, values of 1 or 0)

