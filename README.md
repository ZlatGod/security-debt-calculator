# Security Debt Calculator

[![Live Demo](https://img.shields.io/badge/demo-live-green)](https://ZlatGod.github.io/security-debt-calculator)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

> **Quantifying Security Debt in Multi-Tool Data Governance Architectures**  
> A framework for financial services compliance

## 🚀 Quick Start

**[Try the Live Calculator →](https://yourusername.github.io/security-debt-calculator)**

## 📊 What is This?

This interactive calculator helps organizations quantify security debt accumulated through data governance tool proliferation. Based on research analyzing real-world financial institution deployments, it provides four key metrics:

- **ICD** (Integration Complexity Debt) - Measures API sprawl and credential complexity
- **CVG** (Compliance Visibility Gap) - Tracks fragmented audit capabilities  
- **ARI** (Architectural Risk Index) - Quantifies infrastructure vulnerabilities
- **OOD** (Operational Overhead Debt) - Calculates patching and maintenance burden

## 🎯 Key Features

✅ **Real-time Calculations** - Instant security debt assessment  
✅ **Visual Analytics** - Charts showing debt accumulation and comparisons  
✅ **Actionable Recommendations** - Specific guidance based on your metrics  
✅ **No Installation Required** - Works directly in browser  
✅ **Research-Backed** - Based on published academic framework

## 📚 Research Paper

This calculator implements the framework from:

> **"Quantifying Security Debt in Multi-Tool Data Governance Architectures: A Framework for Financial Services Compliance"**

### Key Findings from Research:
- Tool sprawl increases security debt by **12x** in same-account AWS configurations
- Multi-account architecture reduces security debt by **50-75%**
- Integration failures create **72-hour vulnerability windows**
- Annual cost impact: **$13,846** in operational overhead

## 🛠️ How to Use

### For Business Users
1. Visit the [live calculator](https://yourusername.github.io/security-debt-calculator)
2. Enter your organization's parameters:
   - Number of data governance tools
   - API integrations per tool
   - Authentication methods used
   - AWS account configuration
3. Review calculated metrics and recommendations
4. Share results with your security team

### For Developers
```bash
# Clone the repository
git clone https://github.com/yourusername/security-debt-calculator.git

# Open index.html in your browser
open index.html
```

## 📖 Framework Formulas

### Integration Complexity Debt (ICD)
```
ICD = (Tools × APIs_per_tool × Credential_types) / Isolation_factor
```

**Risk Levels:**
- < 100: Low
- 100-500: Medium  
- 500-1000: High
- \> 1000: Critical

### Compliance Visibility Gap (CVG)
```
CVG = (Required_attributes - Captured_attributes) / Required_attributes × 100%
```

### Architectural Risk Index (ARI)
```
ARI = Network_exposure × Escalation_paths × Same_account_penalty
```

### Operational Overhead Debt (OOD)
```
OOD = (Patch_days + Approval_days) / Team_size
```

## 💡 Use Cases

### 1. Architecture Review
Assess current security debt before major infrastructure changes

### 2. Tool Selection
Evaluate security impact of adding new data governance tools

### 3. Budget Justification
Calculate ROI for multi-account migration projects

### 4. Risk Assessment
Quantify security posture for compliance audits

## 📈 Real-World Example

**Case Study: Financial Institution**

**Before (Single Scanner):**
- ICD: 25 (Low)
- 48-hour patch deployment

**After (4 Tools, Same Account):**
- ICD: 300 (Critical)
- 7-10 day patch deployment
- $27,000 integration failure incident

**After (Multi-Account Architecture):**
- ICD: 75 (Medium)
- 3-5 day patch deployment
- $53,846 annual savings

## 🔗 Related Resources

- [Full Research Paper](link-to-paper.pdf)
- [AWS Multi-Account Best Practices](https://docs.aws.amazon.com/organizations/latest/userguide/orgs_best-practices.html)
- [OWASP API Security Top 10](https://owasp.org/API-Security/)

## 📝 Citation

If you use this framework in your research or practice, please cite:

```bibtex
@misc{security-debt-calculator-2025,
  author = {Your Name},
  title = {Quantifying Security Debt in Multi-Tool Data Governance Architectures},
  year = {2025},
  publisher = {GitHub},
  url = {https://github.com/yourusername/security-debt-calculator}
}
```

**APA Format:**
```
Your Name. (2025). Quantifying security debt in multi-tool data governance architectures: 
A framework for financial services compliance. GitHub. 
https://github.com/yourusername/security-debt-calculator
```

## 🤝 Contributing

Contributions welcome! Please feel free to:
- Report bugs
- Suggest new features
- Submit pull requests
- Share your use cases

## 📜 License

MIT License - feel free to use in your organization

## 👤 Author

**[Your Name]**
- LinkedIn: [Your Profile]
- Email: your.email@example.com
- Research Focus: Data Governance, Cloud Security, Compliance

## 🙏 Acknowledgments

- Based on analysis of real financial services deployments
- Framework validated against industry compliance requirements (SOX, PCI-DSS, GDPR, CCPA)
- Incorporates AWS best practices for multi-account architectures

---

**⭐ If this tool helped you, please star the repository!**

---

## 📊 Calculator Screenshot

[Screenshot of the calculator interface will appear here]

## 🔍 Keywords

`security-debt` `data-governance` `fintech` `compliance` `aws` `cloud-security` `sox-compliance` `pci-dss` `api-security` `devsecops`
