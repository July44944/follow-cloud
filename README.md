**English** | 中文

# Follow Cloud Builders, Not Hype

An AI-powered digest that tracks the top builders in Cloud Computing — architects,
SREs, DevOps engineers, and cloud product leaders who are actually building and
operating cloud systems — and delivers curated summaries of what they're saying.

**Philosophy:** Follow people who operate real infrastructure and have battle-tested
opinions, not influencers who regurgitate vendor press releases.

## What You Get

A daily or weekly digest delivered to your preferred channel with:

- Key posts and insights from 20 curated cloud builders on X/Twitter
- Full articles from official cloud provider blogs (AWS, Azure, GCP, CNCF)
- Summaries of new podcast episodes from top cloud podcasts
- Links to all original content
- Available in English, Chinese, or bilingual
- Optional focus weighting: AWS / Azure / GCP / Kubernetes / FinOps / Multi-cloud

## Quick Start

### Claude Code
```bash
git clone https://github.com/YOUR_USERNAME/follow-cloud.git ~/.claude/skills/follow-cloud
cd ~/.claude/skills/follow-cloud/scripts && npm install
```

Then in Claude Code, type `/cloud` to start setup.

### OpenClaw
```bash
git clone https://github.com/YOUR_USERNAME/follow-cloud.git ~/skills/follow-cloud
cd ~/skills/follow-cloud/scripts && npm install
```

## Default Sources

### Cloud Builders on X (20)
[Jeff Barr](https://x.com/jeffbarr) (AWS VP),
[Corey Quinn](https://x.com/QuinnyPig) (Cloud Economist),
[Kelsey Hightower](https://x.com/kelseyhightower) (ex-Google),
[Werner Vogels](https://x.com/Werner) (Amazon CTO),
[Brendan Burns](https://x.com/brendandburns) (Kubernetes co-creator),
[Adrian Cockcroft](https://x.com/adrianco) (ex-AWS/Netflix VP),
[Forrest Brazeal](https://x.com/forrestbrazeal) (Cloud Bard),
[Liz Rice](https://x.com/lizrice) (Isovalent/Cilium),
[Charity Majors](https://x.com/mipsytipsy) (Honeycomb CTO),
[Simon Wardley](https://x.com/swardley) (Wardley Maps),
[Brian Gracely](https://x.com/bgracely) (The Cloudcast),
[Bilgin Ibryam](https://x.com/bibryam) (Cloud Native patterns),
[Corey Sanders](https://x.com/CoreySandersWA) (ex-Azure CVP),
[Massimo Re Ferre](https://x.com/intothecloudnet) (AWS),
[Eric Hammond](https://x.com/esh) (AWS community),
[AWS](https://x.com/awscloud),
[Google Cloud](https://x.com/googlecloud),
[Microsoft Azure](https://x.com/Azure),
[Kubernetes](https://x.com/kubernetesio),
[CNCF](https://x.com/CloudNativeFdn)

### Podcasts (6)
- [The Cloudcast](https://www.youtube.com/@TheCloudcastNET) — weekly cloud + AI enterprise news
- [Screaming in the Cloud](https://www.youtube.com/@ScreamingCloud) — cloud economics & strategy with Corey Quinn
- [The Cloud Pod](https://www.youtube.com/@TheCloudPod) — weekly AWS/Azure/GCP news roundup
- [Kubernetes Podcast from Google](https://www.youtube.com/@KubernetesPodcast) — K8s community news
- [AWS Podcast](https://www.youtube.com/@awspodcast) — official AWS deep dives
- [On Cloud (Deloitte)](https://www.youtube.com/@DeloitteUS) — enterprise cloud strategy

### Official Blogs (4)
- [AWS News Blog](https://aws.amazon.com/blogs/aws/) — service launches and updates
- [Azure Blog](https://azure.microsoft.com/en-us/blog/) — Azure product announcements
- [Google Cloud Blog](https://cloud.google.com/blog) — GCP features and case studies
- [CNCF Blog](https://www.cncf.io/blog/) — cloud-native project updates

## Changing Settings

Tell your agent:
- "Focus more on AWS" / "Show me more Kubernetes content"
- "Switch to weekly digests"
- "Change language to Chinese"
- "Make the summaries shorter"

## Privacy

- No API keys needed for content — all fetched centrally
- Delivery keys (Telegram/Resend) stored locally in `~/.follow-cloud/.env`
- Only reads public content
- Your config and preferences stay on your machine

## License

MIT
