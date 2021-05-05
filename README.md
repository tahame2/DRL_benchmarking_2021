# DRL_benchmarking_2021



Below is an explanation of the format of the instance definitions (Excel files). 

To further investigate how close the solutions obtained from DRL approach are from the optimal solutions, we create two sets of benchmarking problem instances (for problem setup and travel time information, please see subsection 4.1.1 of the paper): problem instances in the first set each have six requests and three crowdsourcees (data_6req_3CRS.zip); problem instances in the second set each have eight requests and four crowdsourcees (data_8req_4CRS.zip).

In each Excel file of a given problem instance (for example, consider the latter sets of instances: eight requests and four crowdsourcees), the first 8 rows of information are associated with the pickup nodes of the requests, and the next 8 rows are delivery nodes-specific information, which follow the same order as their associated pickup nodes. Finally, we have 4 rows of crowdsourcee nodes-specific information.

The first column (Weight_CRS) provides weight-specific information for request nodes; second column (TW_node) provides  time window of request nodes – for pickup node it is earliest pickup time and for delivery node it is the latest delivery time; third column (Service_time) has additional time requirement (1 minute) considered for picking or delivering request nodes right after reaching it; fourth and fifth column (XCoord and YCoord) have x and y co-ordinate of the request or crowdsourcee nodes; and sixth column (Availability) has latest available time of the crowdsourcee nodes.
