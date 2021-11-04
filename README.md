teb_local_planner_dynamic_planning ROS Package
=============================
Based on the official teb_local_planner.

However, adapted to work with dynamic environments:
The planner actually subscribes to a topic and reads the published path from there.

The topic is called `global_planner_plan` and should be the full path of a topic which a global planner publishes.