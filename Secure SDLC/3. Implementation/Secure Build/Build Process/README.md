# Pre-Commit Stage
## Linters

### Javascript
https://eslint.org/

https://www.npmjs.com/package/eslint-plugin-security

### Typescript
https://typescript-eslint.io/getting-started

https://www.npmjs.com/package/tslint-config-security

## Secrets Scan
https://pre-commit.com/index.html#install

https://github.com/gitleaks/gitleaks#pre-commit

https://github.com/trufflesecurity/truffleHog#pre-commit-hook

https://github.com/thoughtworks/talisman#pre-commit

## IDE Plugin

### VS Code - Scan per File:

**HCL AppScan CodeSweep**

https://marketplace.visualstudio.com/items?itemName=HCLTechnologies.hclappscancodesweep

- scan seluruh code ketika sebuah file source code di save

- setelah dicoba banyak "positif rate" nya dan lebih banyak nemuin celah dari tool sejenis yg lain

- tidak bisa scan lebih dari satu file sekaligus, atau scan keseluruhan project/repo

**SonarLint**

https://marketplace.visualstudio.com/items?itemName=SonarSource.sonarlint-vscode

- Suggestion/feedback code security muncul mulai programmer melakukan coding di VS Code (realtime), dan muncul pada tab "PROBLEMS" 

- menurut percobaan, sedikit nemu security code problem dibanding HCL AppScan CodeSweep
 
- tidak bisa scan lebih dari satu file sekaligus, atau scan keseluruhan project/repo.

### VS Code - Scan Entire Codebase:

**Snyk Security - Code, Open Source Dependencies, IaC Configurations**

https://marketplace.visualstudio.com/items?itemName=snyk-security.snyk-vulnerability-scanner

- tools yg dibutuhkan "Snyk Open Source" + "Snyck CLI"

- Otomatis langsung nge-scan keseluruhan codes di repo/project yg lagi dibuka, bisa trigger manual juga pakai tombol di plugin tag nya

https://b-kms.bpbatam.go.id/link/636#bkmrk---sudah-include-open
 
- Sudah include Open Source Security (SCA) scan, code security scan, dan code quality scan.

### VS Code - Software Compotition Analysis (SCA), Scan Entire Codebase:

**Code Project Scanner**

https://marketplace.visualstudio.com/items?itemName=mk2000.code-project-scanner

- Bisa scan entire project dengan tab plugin tersendiri menggunakan OWASP Dependency-Check tool.