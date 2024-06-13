# AWS_EKS_EBS_Code
This is used to create storage driver that helps to connect with EBS service . 

We need to modify eks_autoscaler_for_slave.yaml file and update our cluster name at line 164. 

We need to update cluster name and region in both configmaps of cloud watch agent and fluentd agent cloudwatch_fluentd_agent/create_fluentd_cloudwatch_agent.yaml file
