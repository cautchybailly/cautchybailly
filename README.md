# Cautchy Bailly

**Cloud Engineer · AWS · Terraform · Serverless security**

I build whole AWS environments in Terraform and (then tear them down again when and where appropriate). That means serverless APIs behind WAF, Cognito identity with edge-enforced RBAC, event-driven pipelines, and Bedrock agents that detect threats, respond to them and write the compliance paperwork.

Before this I spent five years in enterprise support (Michelin, GE), working identity, incidents and root cause at scale. So I build things that someone else has to operate at 2 a.m. I can do that in English, French or Spanish.

🔗 [thatcautchyguy.com](https://thatcautchyguy.com) · AWS Solutions Architect – Associate · Terraform Associate (in progress), 

---

### Featured work

| Project | What it does | Stack |
|---|---|---|
| [**aws-waf-soar-platform**](https://github.com/cautchybailly/aws-waf-soar-platform) | WAF logs → Bedrock analysis → threat correlation → automated SOAR incidents, an executive PDF briefing, and compliance evidence mapped to NIST CSF 2.0 / CIS v8 / PCI DSS 4.0 / ISO 27001. Five Terraform modules. | Terraform, WAFv2, Lambda, Bedrock, DynamoDB, EventBridge, S3 |
| [**secure-serverless-api**](https://github.com/cautchybailly/secure-serverless-api) | Zero-bypass REST API: regional WAF, Cognito MFA, group RBAC, a custom JWT authorizer at the edge, token telemetry and an unused-token detector. | Terraform, API Gateway, Cognito, Lambda (Python/Node), SNS |
| [**flightsearch**](https://github.com/cautchybailly/flightsearch) | Self-contained Bash CLI for flight search on the Amadeus API. | Bash, REST APIs |

### How I build

- **No bypass paths.** If a WAF is in the design, every route goes through it.
- **Failure modes get engineered out.** I don't leave them for someone to document later.
- **Modules, wired outputs to inputs, validated one at a time.** Each one gets `plan`, `apply` and `destroy` before the next.
- **READMEs someone can follow.** Requirements, steps, artifacts, teardown and troubleshooting are always there.

### Toolbox

`AWS` `Terraform` `Python` `Node.js` `Bash` `Lambda` `API Gateway` `WAFv2` `Cognito` `DynamoDB` `EventBridge` `Bedrock` `IAM` `CloudWatch` `Git`
Currently going deeper on: `Kubernetes` `Grafana` `Prometheus`

📫 cautchy@proton.me · [LinkedIn](https://www.linkedin.com/in/cautchybailly)

<!--
**cautchybailly/cautchybailly** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
