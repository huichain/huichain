### Hi, I'm Hui Chan

Software engineer transitioning into **smart contract security and Web3 tooling**, with public Foundry PoCs, audit-style writeups, and security tooling on GitHub.

**Background**

- **C++** — Camera/graphics pipelines where bugs are expensive (timing, memory, numerical edge cases)
- **C#** — Machine-vision tooling where correctness and failure modes matter in production
- **Current work** — Solidity security research: Foundry PoCs, patched implementations, and structured findings (see repos below)

**Now building in public**

- Foundry vulnerability modules with exploit PoCs, fixes, and audit-style reports
- Public repos: [smart-contract-security-lab](https://github.com/huichain/smart-contract-security-lab) and [contract-risk-scanner](https://github.com/huichain/contract-risk-scanner)
- **Current focus:** upgradeable proxy risks (`delegatecall`, unprotected `initialize`, storage layout)

---

#### Featured Projects

**[smart-contract-security-lab](https://github.com/huichain/smart-contract-security-lab)**  
Foundry-based vulnerability lab: exploit PoCs, fixes, and audit-style writeups.

- **Done:** Reentrancy · Access Control · Signature Replay · Oracle Manipulation (`15` tests, `4` reports)
- **In progress:** Upgradeable Proxy — minimal EIP-1967-style proxy + unprotected `initialize` PoC (`2` tests; `17` total in repo)
- **Next:** storage layout upgrade bug, fixes, and `reports/05-upgradeable-proxy.md`

**[contract-risk-scanner](https://github.com/huichain/contract-risk-scanner)**  
Lightweight CLI for pattern-based Solidity risk checks (MVP / side project).

- **Live:** `tx.origin` authorization detection

---

#### Tech

`Solidity` · `Foundry` · `EVM` · `Python` · `Security Research` · `C#` · `C++`

---

#### Connect

- X (Twitter): [@vividhui](https://x.com/vividhui)
- GitHub: [huichain](https://github.com/huichain)
