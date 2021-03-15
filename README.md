# Org-WorkProfiles-demo
Repository holding and hosting the prototype built for a paper submitted to BPM 2021

*Yang, J., Ouyang, C., ter Hofstede, A., van der Aalst, W., & Leyer, M. (2021). Seeing the Forest for the Trees: Group-Oriented Workforce Analytics.*


#### Preprocessing of the original BPIC15 event dataset

Preprocessing steps include:
1. focusing on only the executions of the main subprocess, and
2. keeping only cases started and completed within the period of year 2011 to 2014, and
3. keeping only cases with valid duration time (cycle time > 0), and
4. keeping only cases processed within each municipality (i.e., a few cases operated across municipalities are discarded).

In terms of categorizing cases, activities, and time periods, we consider case types based on whether they are related to construction permit, activity types based on different phases in the process, and time types based on the seven days of a week.

As a result, the preprocessed dataset used for analyses contains a total of `167,691` events from `4,792` cases involving `61` resources in the `5` resource groups.
Events and cases are linked to `2` case types, `9` activity types, and `7` time types.
