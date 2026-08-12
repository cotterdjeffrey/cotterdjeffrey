# Jeff Cotter

**Junior Cloud / Software Engineer · Google Cloud ACE Certified**

[![Google Cloud ACE](https://images.credly.com/size/150x150/images/08096465-cbfc-4c3e-93e5-93c5aa61f23e/image.png)](https://www.credly.com/badges/a8089afa-7957-4380-9689-dd033552250d)

Career changer building cloud-native systems end to end — infrastructure, backend, and applied LLM/RAG.

`Python` · `Terraform` · `GCP` · `GKE / Kubernetes` · `Docker` · `FastAPI` · `React` · `Claude API`

📍 Chicago, IL · open to remote · [LinkedIn](https://linkedin.com/in/cotterdjeffrey)

---

### Projects

[**gcp-infrastructure**](https://github.com/cotterdjeffrey/gcp-infrastructure) — Production-grade GCP platform defined in Terraform: private GKE Autopilot, Cloud SQL, 4 CI/CD pipelines, Prometheus + Grafana, and defense-in-depth security (Pod Security Admission, default-deny network policies, secrets via the Secrets Store CSI driver + Workload Identity). Hosts the RAG service below. Validated via `terraform plan` + kubeconform — zero cloud spend.

[**rag-doc-assistant**](https://github.com/cotterdjeffrey/rag-doc-assistant) — Retrieval-augmented Q&A over a document set with citations. Two-stage retrieval — vector search + cross-encoder reranking — with an evaluation harness (hit@k, MRR) to measure quality. Runs locally (Ollama + ChromaDB + React) and is packaged as a containerized service for the GCP platform above (Claude API + pgvector on Cloud SQL).
