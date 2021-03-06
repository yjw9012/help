### Adding a Cloud Integration

Adding a cloud integration requires establishing a trust relationship between Amazon and Wavefront by sharing account IDs and an external ID. The external ID can be generated by Wavefront or by your company. If you use an ID generated by Wavefront you run **Set up Amazon Account** to configure all integrations&mdash;CloudWatch, Cloudtrail, and AWS Metrics+&mdash;at once. If you want to use an ID generated by your company, you set up each integration individually. 

You start by granting Wavefront read-only access to your Amazon account or by giving the permissions listed in [AWS Metrics Integration](https://docs.wavefront.com/integrations_aws_metrics.html). 