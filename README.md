# Amazon CloudWatch Dashboard for k6

This repository includes an Amazon CloudWatch dashboard to visualize k6 results.

⚠️ Please note: Starting from v0.47.0, new k6 releases no longer include the  [`CloudWatch(StatsD) output`](https://grafana.com/docs/k6/latest/results-output/real-time/amazon-cloudwatch/). However, you can still use this feature as its development continues in the [LeonAdato/xk6-output-statsd extension](https://github.com/LeonAdato/xk6-output-statsd).

![Amazon CloudWatch dashboard for k6](./images/cloudwatch-k6-dashboard.png)

You can use the [`dashboard.json`](./dashboard.json) file to create the above dashboard. Please replace **REGION** and **ADDRESS** with the information from your environment, the AWS region(s) and the private IP address of the EC2 instance respectively.
