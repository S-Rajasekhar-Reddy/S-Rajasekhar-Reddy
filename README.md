# Hi, I'm Sai 👋

Infrastructure & security engineer (~5.5 years, US + India) building secure, observable, production-grade AI platforms: LLM serving, gateways and agent automation.

### 🔨 Now building
**[llm-inference-platform](https://github.com/S-Rajasekhar-Reddy/llm-inference-platform)**: production-style LLM serving with vLLM on Kubernetes (k3s on a 16 GB laptop GPU, then AWS EKS), with queue-depth autoscaling, Prometheus/Grafana and published latency/cost benchmarks. Built in public; ships 27 Nov 2026.
- Cut Qwen3-8B-FP8 cold start from ~35 min to ~2.3 min (weight + compile caching)
- Reproduced vLLM issue #54383 on 16 GB (23% less KV cache on cold vs warm boots) and validated the proposed fix, PR #54479

**Next:** a secure AI gateway (auth, rate limits, PII redaction, prompt-injection detection, OpenTelemetry audit logs), then an agentic NetOps/SecOps assistant with evals.

### 💼 Background
- **Softblitz Resources (US):** sole engineer on a legacy → AWS migration, then rebuilt it as code (Terraform, Ansible); GitHub Actions CI/CD with OIDC; Grafana/Splunk monitoring; DNS migration to Route 53 (>60% lower hosting cost)
- **L2X Tech (client: TPG Telecom):** multi-vendor firewalls and F5 LTM/GTM; zero-downtime migration of 2,800+ rules from Check Point to Cisco Firepower
- **Wipro:** built Path Tracer, packet-flow analysis automation (99.98% faster; Stellar Performance Award)

### 🛠 Stack
Terraform · Ansible · Python · AWS (VPC, EC2, ELB, Route 53, CloudFront, S3) · Kubernetes (k3s) · vLLM · Docker · Prometheus/Grafana · Splunk · BGP/OSPF · Palo Alto · Fortinet · Check Point · Cisco · F5 BIG-IP

### 📜 Certifications
AWS Certified Developer – Associate · HashiCorp Certified: Terraform Associate (004) · Cisco CCNA (Routing & Switching)

### 🎓 Education
MS in Computer Science (Data Analytics specialisation), Indiana Wesleyan University, 2025

📍 Hyderabad, India · open to remote · [LinkedIn](https://www.linkedin.com/in/sai-tammineni)
