# s3testing

low impact
Delete idle resources
right-size ec2 instances and launch configurations
buy RIs
improve autoscaling
automatically shutdown unused resources
implement cost-aware architectures
use serverless


Provide motivation
- executive support and consistent communications
- single threaded authority for optimization
- training/tools
- time given to engineers to optimize
- provide dashboards to see the progress
- weekly or monthly canence that includes review of spend

Tools for right sizing
- computer optimizer
- cost explorer resource optimizier
- truster advisor (average is 10% or less over the last 14 days) (5MB or less on more than 4 or less days)
- trusted advisor may not be the best toll as it doesnt consider network io and doesnt look at committed RI instances


turn off resources outside of work hours
look at AWS Instance Scheduler, uses tagging to shutdown your resources

- set ASGs to min size of 0 


Unattached Elastic IPs
Unattache EBS
Idle or unattached load balancers
incomplete s3 transfers
clearing old snapshots


EC2 RI Utilization - all reserved instances by hour vs total Reserved Instances

EC2 RI Coverage -- how much overall instance usage is covered by RIs
