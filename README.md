# GemmaVerify: Autonomous Air-Gapped AppSec & Deterministic Remediation Engine

> Deterministic Local Code-Intelligence & Secure Vulnerability Remediation for Air-Gapped Environments.

---

## ” Installation & Usage

```bash
git clone https://github.com/abdlamid88-droid/GemmaVerify-AppSec.git
cd GemmaVerify-AppSec
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python main.py
```

---

## 🏆 Key Features
1. Zero Exfiltration: Runs fully air-gapped locally.
2. Supply-Chain Shield: Blocks hallucinated packages via AST dependency whitelisting.
3. Deterministic Sandbox: 3-gate automated verification (AST, Types, Pytest).
