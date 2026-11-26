# Serafym Somin

**Cloud Security · DevSecOps · Trust Boundaries**

I'm an independent security engineer focused on the boundaries between components, identities and data.

I developed **Layered Boundary Matrices** — a source-first method that turns trust boundaries into security rules, test scenarios and verifiable evidence. I first applied it to AI-agent audits, then extended it to application and cloud infrastructure CI/CD.

## How I work

**Source code → Interaction graph → Trust boundaries → Security rules → Scenarios → Evidence**

- Map where data and authority cross component boundaries.
- Define what must be allowed and what must be refused.
- Test each rule from several directions and check the actual resulting state.
- Bring these checks into CI, with source coverage review, change-based matrix selection and clear failure reports.

AI helps analyze architecture and prepare checks. Deterministic code evaluates the evidence and returns the test verdict.

## Projects

- **[EKS Boundary Matrix CI](https://github.com/Sera5imSec/eks-boundary-matrix-ci)** — security checks across Terraform, IAM, Docker/OCI, ECR and Kubernetes, integrated with GitHub Actions. Includes source coverage review, evidence reports and separate manual source mutation tests. [Project workflow](https://github.com/Sera5imSec/eks-boundary-matrix-ci/blob/main/docs/WORKFLOW.md).
- **[RealWorld AppSec CI](https://github.com/Sera5imSec/realworld-appsec-ci)** — executable checks for authentication, authorization, input handling and database integrity in a Go/Gin application.
- **AI-agent security research:** [smolagents](https://github.com/Sera5imSec/smolagents-agent-matrices) and [Browser Use](https://github.com/Sera5imSec/browser-use-agent-matrices) — source-derived boundary matrices for agent state, tool use, browser policies and sensitive-data handling.

## Technologies

Terraform · AWS · IAM · Docker/OCI · Kubernetes · GitHub Actions · Go · Python · JavaScript/Node.js

**Open to Cloud Security / DevSecOps roles and technical collaborations.**

[sera5im@proton.me](mailto:sera5im@proton.me)
