# Luis Enrique Sánchez P.

Cloud and DevOps engineer who also ships the product. Platforms on AWS, GCP, and Azure: isolated environments, the pipeline that deploys them, and the path when a region or a cloud fails. Python, Node.js, and Java services. Flutter apps when the product needs a phone.

Caracas, Venezuela · remote · [LinkedIn](https://www.linkedin.com/in/lesanpi/) · [github.com/lesanpi](https://github.com/lesanpi) · lespinerua@gmail.com

## What I do

I work between the account and the release. Terraform and Terragrunt modules, OIDC pipelines instead of long-lived keys, Ansible applied by the pipeline so hosts are not edited by hand. Containers on ECS, Kubernetes, Cloud Run, or Nomad, chosen for the workload. Observability is part of the platform: OpenTelemetry, Prometheus, Grafana, and Loki, with k6 before a change is called safe.

On fintech platforms that means tenancy, a private network, WAF, and a disaster-recovery path that was designed, not a slide. The same practice covers microservice platforms, public APIs, background workers, and mobile release trains.

Next is consumption-side LLMOps: Bedrock and tracing for those calls. Not training clusters.

## Platform

Multi-tenant AWS delivery: a dedicated, isolated environment per tenant, Terraform modules, OIDC, services on ECS behind an ALB and AWS WAF. Ingestion with Kinesis Data Streams and Firehose into a data lake queried with Athena. API edge on API Gateway and Lambda. Static content and DNS on CloudFront. Cross-region disaster recovery on AWS and cross-cloud failover to GCP, with AWS DMS keeping databases in sync. On GCP: Cloud Run, Artifact Registry, Cloud Build, and Cloud Deploy.

Container platforms for microservice architectures on AWS, GCP, and Azure. Reusable Terraform modules, an internal VPN, and least-privilege operator access. Kubernetes where the system needs it. Nomad where a full cluster is the wrong tool. GCP services on Cloud Run, Cloud Build, Artifact Registry, and Cloud SQL. RabbitMQ and workers for background processing. EventBridge and Lambda for automations. DNS, firewalls, and CloudFront for static sites. Cloudflare and AWS WAF rules for DDoS.

## Delivery and observability

CI/CD on Jenkins, GitHub Actions, CodeBuild, CodePipeline, and Cloud Build. Trivy and Cypress on pull requests. Playwright on pull requests and live environments. SonarQube on quality. k6 for stress. FinOps reviews on the bill. Host configuration in versioned Ansible, applied by pipeline. Tracing with OpenTelemetry. Metrics and logs with Prometheus, Grafana, and Loki. Alarms on CPU, bottlenecks, and traffic spikes.

## Product

Internal secrets platform for engineering teams: GitHub OAuth, Node.js, Python, a Node.js SDK, and a Python CLI. APIs on API Gateway with a Python backend. Mobile apps in Flutter and Dart with Clean Architecture, GraphQL, PostgreSQL, and MongoDB, shipped for insurance, cinema ticketing, a crypto wallet, and lending. Release pipelines to the App Store, Google Play, TestFlight, and Firebase App Distribution. Custom ERP modules on Dynamics 365 with C#, plus Power Automate and Power BI.

## Stack

- AWS: ECS, EKS, Lambda, API Gateway, Kinesis, Firehose, Athena, SQS, SNS, EventBridge, CloudWatch, CloudFront, RDS, DMS, VPC, NAT, ALB, WAF, Route 53, CodeBuild, CodePipeline
- GCP: Cloud Run, Cloud Build, Cloud Deploy, Artifact Registry, Cloud SQL, VPC
- Azure, on client platforms next to AWS and GCP
- Platform: Terraform, Terragrunt, Ansible, Docker, Kubernetes, Nomad, RabbitMQ
- Delivery: GitHub Actions, Jenkins, CodePipeline, Cloud Build, SonarQube, Trivy
- Observability and test: OpenTelemetry, Prometheus, Grafana, Loki, k6, Playwright, Cypress
- Services: Python, FastAPI, Node.js, Java (Spring Boot), PostgreSQL, MongoDB, GraphQL
- Mobile: Flutter, Dart, Clean Architecture

## Education and certifications

- Master's in Information Systems, UCAB, 2023 – present. 
- Telecommunications Engineering, UCAB, 2017 – 2023.
- AWS Certified Solutions Architect – Associate.
- AWS Certified Cloud Practitioner.

## Contact

lespinerua@gmail.com · [LinkedIn](https://www.linkedin.com/in/lesanpi/) · +58 414 913 7341
