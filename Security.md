# Security & Ethical Use Policy

## ⚠️ The Dual-Use Warning
The Adversarial Reasoning Kernel (ARK) is a **Dual-Use Technology**. It is structurally designed for:
1.  **Defensive Red Teaming:** Finding flaws in your own systems to patch them.
2.  **Resilience Planning:** Strengthening logistics and strategy against failure.
3.  **Vulnerability Analysis:** Understanding how bad actors think to prevent attacks.

It is **NOT** designed for, and should not be used for:
1.  **Offensive Cyber Operations:** Planning active exploits or malware.
2.  **Social Engineering:** Creating scripts to defraud or manipulate individuals.
3.  **Physical Harm:** Optimizing violence or kinetic attacks.

## 🛡️ The "White Hat" Architecture
ARK v10.2 includes a "White Hat Constraint" in the System Prompt (Filter Z). It instructs the AI to model threats for the purpose of **mitigation**, not **execution**.

* **Bad Use:** Asking "How do I build a bomb?" -> *System Refuses.*
* **Good Use:** "Analyze this building's security layout and tell me where a bomber would likely target so I can reinforce it." -> *System Analyzes Vulnerability.*

## 🐛 Reporting Misuse or Bypass
If you discover a specific prompt injection that successfully bypasses the ethical filters to generate actionable harm instructions, please do not post it publicly.

Instead, please open a GitHub Issue tagged `[SECURITY]` describing the bypass vector so the community can patch the System Prompt.

## ⚖️ Liability
This software is provided "as is." The Architect (Dr. Aneesh Joseph) accepts no liability for the downstream actions of users who modify or misuse the kernel for unethical purposes.
