# Sample Cloud Digest Output

This is an example of what your Cloud Builders Digest looks like.

---

Cloud Builders Digest — April 17, 2026

X / TWITTER

AWS VP Jeff Barr
Announced three new EC2 instance types optimized for AI inference workloads,
featuring NVIDIA Blackwell GPUs with up to 40% better price-performance than
the previous generation. Available immediately in us-east-1, us-west-2, and
eu-west-1, with more regions coming next month.
https://x.com/jeffbarr/status/example1

Cloud Economist Corey Quinn (Last Week in AWS)
Dropped a thread breaking down the real cost of running Kubernetes on EKS vs.
self-managed: "After accounting for the control plane fee, NAT Gateway costs,
and the engineer-hours to keep it running, EKS is actually cheaper for teams
under 50 engineers. Above that, the math flips." Sparked a big debate about
hidden cloud costs.
https://x.com/QuinnyPig/status/example2

Ex-Google Distinguished Engineer Kelsey Hightower
Shared his take on the multi-cloud debate: "Multi-cloud isn't about avoiding
vendor lock-in. It's about using the right tool for each job. Run your ML on
GCP, your enterprise apps on Azure, your everything-else on AWS. Stop pretending
one cloud fits all." Also demoed a new open-source tool for cross-cloud
service mesh configuration.
https://x.com/kelseyhightower/status/example3


OFFICIAL BLOGS

AWS News Blog: Amazon S3 Tables Now Generally Available
S3 Tables brings native Apache Iceberg support to S3, enabling analytics engines
to query data lakes without ETL pipelines. Pricing starts at $0.0025 per 1000
queries. Supports Athena, Redshift, and EMR out of the box. Big deal for teams
currently maintaining Glue crawlers.
https://aws.amazon.com/blogs/aws/s3-tables-ga

Google Cloud Blog: Introducing Cloud Run GPU Support
Cloud Run now supports attaching NVIDIA L4 GPUs to serverless containers.
Pay only for GPU time during request processing — no idle GPU costs. Currently
in preview in us-central1. This directly competes with AWS Lambda's lack of
GPU support and could be a game-changer for inference workloads.
https://cloud.google.com/blog/cloud-run-gpu


PODCASTS

The Cloudcast — "FinOps at Scale: How Spotify Cut Their Cloud Bill by 30%"
Bottom line: Spotify's FinOps team saved $50M/year not by switching clouds,
but by fixing three things: right-sizing instances (automated weekly), killing
zombie resources (automated daily), and renegotiating committed use discounts
(quarterly review cycle).

Key insights:
- 60% of their savings came from right-sizing alone — most instances were
  2-4x oversized because engineers defaulted to "just pick a big one."
- They built an internal "Cloud Cost Score" that gamified optimization across
  teams. Teams with the best scores got priority access to new GPU capacity.
- "The biggest FinOps win isn't a tool. It's making cost visible to the
  engineer who's writing the Terraform."
https://youtube.com/watch?v=example789

Generated through the Follow Cloud skill
