# Awesome JavaScript & TypeScript Tooling & Linters ⚡🔍

<p align="center">
  <img src="./assets/banner.svg" alt="Awesome JavaScript &amp; TypeScript Tooling &amp; Linters Banner" width="100%" />
</p>

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a><a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Javascript-Typescript-Tooling-Linters/stargazers"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Javascript-Typescript-Tooling-Linters?style=social" alt="GitHub Stars" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Javascript-Typescript-Tooling-Linters/network/members"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Javascript-Typescript-Tooling-Linters?style=social" alt="GitHub Forks" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Javascript-Typescript-Tooling-Linters/issues"><img src="https://img.shields.io/github/issues/ishandutta2007/Awesome-Javascript-Typescript-Tooling-Linters?style=flat-square&color=blue" alt="GitHub Issues" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Javascript-Typescript-Tooling-Linters/blob/main/LICENSE"><img src="https://img.shields.io/badge/License-MIT-green.svg?style=flat-square" alt="License: MIT" /></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

<p align="center">
  <strong>A curated catalogue of high-speed Rust/Zig formatters, industrial-strength JavaScript and TypeScript linters, AST parsers, static analysis security tools (SAST), dead-code analyzers, and cloud code quality platforms.</strong> 🌟 Star if you find it helpful! 🌟
</p>

---

## 📑 Table of Contents
- [Sector Overview & Market Dynamics 📊](#sector-overview--market-dynamics-)
- [SaaS / Hosted Platforms ☁️](#saas--hosted-platforms-️)
- [Open-Source Linters, Formatters & Toolchains 🛠️](#open-source-linters-formatters--toolchains-️)
- [Star History 📈](#star-history-)
- [Support & Community 💖](#support--community-)
- [Contributing 🤝](#contributing-)
- [License 📄](#license-)

---

## Sector Overview & Market Dynamics 📊

The global static code analysis and code quality software market is currently valued at approximately **$1.15B to $2.15B** (projected to reach over **$4B to $6B+ by the early 2030s** at an estimated CAGR of **8%–12%**). The sector is **moderately concentrated yet fiercely contested** at the top by enterprise security and inspection incumbents (such as SonarSource, Snyk, Synopsys, and JetBrains), alongside a **highly fragmented long-tail** (accounting for >50% of the market) fueled by rapid developer adoption of open-source Rust toolchains (Oxc, Biome), local AST parsers, and emerging AI-native PR review assistants.

---

## SaaS / Hosted Platforms ☁️

Commercial, cloud-hosted code quality platforms, automated PR review services, and managed continuous inspection suites, sorted in descending order by company valuation/estimated scale.

| Platform | Description | Starting Tier Pricing | Free Tier Limits | Company Scale (Valuation / Revenue) |
| :--- | :--- | :--- | :--- | :--- |
| **[Snyk Code](https://snyk.io)** | Real-time cloud static analysis tool identifying security flaws and code quality issues in JavaScript and TypeScript codebases. | **Team Plan:** $25/contributing developer/month (billed monthly or annually) | **Free forever:** 100 tests/month for Snyk Code (SAST), 200 tests/month for SCA, 300 tests/month for IaC; unlimited scans for public/open-source repos. | **~$7.4B valuation** ($300M+ ARR) |
| **[SonarQube Cloud (SonarCloud)](https://sonarsource.com)** | Enterprise cloud-based code quality and static application security testing (SAST) platform with deep JavaScript/TypeScript rule sets. | **Team Plan:** $34/month (covers up to 100,000 Lines of Code) | **Free forever:** Up to 50,000 Lines of Code (LOC) for private repositories; unlimited LOC for public/open-source projects. | **~$4.7B valuation** (~$175M+ ARR) |
| **[Qodana (JetBrains)](https://jetbrains.com)** | Commercial code quality and static analysis platform bringing WebStorm/IntelliJ JavaScript & TypeScript inspections into CI/CD pipelines. | **Ultimate Plan:** $5.00/contributor/month ($60/contributor/year, min. 3 contributors = $15/month) | **Community Plan (Free forever):** Basic language linters (Java, Python, .NET, C/C++) with unlimited lines of code; excludes JS/TS. **Free Trial:** 60-day full-access free trial for Ultimate/Ultimate Plus (includes full JS/TS inspections). | **~$650M–$700M+ ARR** (Bootstrapped profitable leader, estimated multi-billion valuation) |
| **[CodeClimate Quality (Qlty Software)](https://codeclimate.com)** | Cloud-hosted automated code review service providing maintainability ratings, test coverage, and linter orchestration. | **Pro Tier:** $20/contributor/month | **Free forever:** Unlimited public and private repositories, 1,000 analysis minutes/month, and 100 AI autofixes/month. | **~$200M valuation** (~$12M–$25M ARR) |
| **[Trunk Check / CI (Trunk.io)](https://trunk.io)** | Managed developer experience platform orchestrating hosted linting, formatting, and hermetic toolchain caching across repositories. | **Team Tier:** $18/committer/month | **Free forever:** Up to 5 active committers on private repositories, 1M test spans/committer/month; free for open-source repositories. | **~$100M valuation** ($25M Series A raised) |
| **[Codacy](https://codacy.com)** | Managed DevSecOps platform automating code reviews, ESLint/Biome rule enforcement, code coverage, and technical debt tracking. | **Team Plan:** $18/developer/month (billed annually) or $21/developer/month (billed monthly) | **Developer Plan (Free forever):** IDE/CLI extensions & local quality/security scans for individuals; full Team plan features free for open-source repositories. 14-day free trial on private repos. | **~$32.5M venture funding** (~$7M–$18M ARR) |
| **[DeepSource](https://deepsource.com)** | Automated cloud code health and static analysis platform detecting bugs, anti-patterns, and security vulnerabilities on every pull request. | **Team Plan:** $12/team member/month (billed annually) or $15/month | **Free forever:** Up to 3 private repositories and 3 team members, 3 SCA targets; unlimited public repositories (capped at 1,000 analysis runs and 1,000 formatting runs/month). 14-day free trial. | **~$3M–$10M venture funding** (~$2M–$3M ARR) |

---

## Open-Source Linters, Formatters & Toolchains 🛠️

Free and open-source software (FOSS) linters, ultra-fast Rust/Zig/C++ formatters, static analyzers, dead-code detectors, and TypeScript compilers. Ranked in descending order by GitHub stargazers count:

1. **[TypeScript](https://github.com/microsoft/TypeScript)** [![GitHub stars](https://img.shields.io/github/stars/microsoft/TypeScript?style=social&color=white)](https://github.com/microsoft/TypeScript/stargazers) 📘
   Microsoft's foundational typed superset of JavaScript that compiles to clean JavaScript with industrial-grade static type analysis and diagnostics.

2. **[Prettier](https://github.com/prettier/prettier)** [![GitHub stars](https://img.shields.io/github/stars/prettier/prettier?style=social&color=white)](https://github.com/prettier/prettier/stargazers) 💅
   The industry-standard, opinionated code formatter supporting JavaScript, TypeScript, JSX, CSS, HTML, Markdown, and JSON.

3. **[SWC](https://github.com/swc-project/swc)** [![GitHub stars](https://img.shields.io/github/stars/swc-project/swc?style=social&color=white)](https://github.com/swc-project/swc/stargazers) ⚡
   Super-fast Rust-based TypeScript/JavaScript compiler, transformer, and minifier powering Next.js, Parcel, and Deno.

4. **[StandardJS](https://github.com/standard/standard)** [![GitHub stars](https://img.shields.io/github/stars/standard/standard?style=social&color=white)](https://github.com/standard/standard/stargazers) 📏
   Zero-configuration, opinionated JavaScript style guide, linter, and automatic code fixer built on ESLint.

5. **[ESLint](https://github.com/eslint/eslint)** [![GitHub stars](https://img.shields.io/github/stars/eslint/eslint?style=social&color=white)](https://github.com/eslint/eslint/stargazers) 🔍
   The foundational, pluggable static analysis and linting engine for JavaScript and TypeScript with the largest community rule ecosystem in the world.

6. **[Biome](https://github.com/biomejs/biome)** [![GitHub stars](https://img.shields.io/github/stars/biomejs/biome?style=social&color=white)](https://github.com/biomejs/biome/stargazers) 🌳
   Fast, unified Rust-written formatter and linter for JavaScript, TypeScript, JSX, JSON, CSS, and GraphQL (successor to Rome Tools).

7. **[Oxc & Oxlint](https://github.com/oxc-project/oxc)** [![GitHub stars](https://img.shields.io/github/stars/oxc-project/oxc?style=social&color=white)](https://github.com/oxc-project/oxc/stargazers) 🦀
   Suite of high-performance JavaScript and TypeScript tools written in Rust, featuring `oxlint` (50–100x faster than ESLint), parsers, and transformers.

8. **[Rome Tools (Archived Predecessor)](https://github.com/rome/tools)** [![GitHub stars](https://img.shields.io/github/stars/rome/tools?style=social&color=white)](https://github.com/rome/tools/stargazers) 🏛️
   Pioneering open-source unified JavaScript/TypeScript toolchain in Rust that laid the architectural foundation for Biome.

9. **[Semgrep](https://github.com/semgrep/semgrep)** [![GitHub stars](https://img.shields.io/github/stars/semgrep/semgrep?style=social&color=white)](https://github.com/semgrep/semgrep/stargazers) 🛡️
   Fast, polyglot static analysis engine for finding vulnerabilities, enforcing secure coding standards, and running custom AST queries across JS/TS repos.

10. **[TypeScript-ESLint](https://github.com/typescript-eslint/typescript-eslint)** [![GitHub stars](https://img.shields.io/github/stars/typescript-eslint/typescript-eslint?style=social&color=white)](https://github.com/typescript-eslint/typescript-eslint/stargazers) 🧩
    The essential tooling and AST parser monorepo enabling ESLint and Prettier to inspect and enforce typed rules in TypeScript codebases.

11. **[Knip](https://github.com/webpro-nl/knip)** [![GitHub stars](https://img.shields.io/github/stars/webpro-nl/knip?style=social&color=white)](https://github.com/webpro-nl/knip/stargazers) ✂️
    Comprehensive, ultra-fast CLI tool for discovering unused files, dead exports, and orphaned dependencies in JavaScript and TypeScript monorepos.

12. **[SonarQube Community Build](https://github.com/SonarSource/sonarqube)** [![GitHub stars](https://img.shields.io/github/stars/SonarSource/sonarqube?style=social&color=white)](https://github.com/SonarSource/sonarqube/stargazers) 🏰
    Open-source self-hosted continuous inspection and code quality server delivering static analysis and security checks for JavaScript and TypeScript.

13. **[Madge](https://github.com/pahen/madge)** [![GitHub stars](https://img.shields.io/github/stars/pahen/madge?style=social&color=white)](https://github.com/pahen/madge/stargazers) 🕸️
    Developer tool for generating visual module dependency graphs, identifying circular dependencies, and inspecting CommonJS/ESM project architecture.

14. **[JSHint](https://github.com/jshint/jshint)** [![GitHub stars](https://img.shields.io/github/stars/jshint/jshint?style=social&color=white)](https://github.com/jshint/jshint/stargazers) 📜
    Classic, lightweight community static analysis tool detecting errors and potential anti-patterns in JavaScript applications.

15. **[XO](https://github.com/xojs/xo)** [![GitHub stars](https://img.shields.io/github/stars/xojs/xo?style=social&color=white)](https://github.com/xojs/xo/stargazers) 🎯
    Opinionated, zero-config JavaScript and TypeScript linter with strict defaults, enforcing clean syntax and consistency without configuration fatigue.

16. **[dependency-cruiser](https://github.com/sverweij/dependency-cruiser)** [![GitHub stars](https://img.shields.io/github/stars/sverweij/dependency-cruiser?style=social&color=white)](https://github.com/sverweij/dependency-cruiser/stargazers) 🧭
    Validate and visualize module dependencies in JS/TS projects, enforcing strict architectural boundaries and detecting circular imports.

17. **[eslint-plugin-import](https://github.com/import-js/eslint-plugin-import)** [![GitHub stars](https://img.shields.io/github/stars/import-js/eslint-plugin-import?style=social&color=white)](https://github.com/import-js/eslint-plugin-import/stargazers) 📦
    Standard ESLint plugin intended to support linting of ES2015+ (ES6+) import/export syntax and prevent file path and export naming issues.

18. **[eslint-plugin-unicorn](https://github.com/sindresorhus/eslint-plugin-unicorn)** [![GitHub stars](https://img.shields.io/github/stars/sindresorhus/eslint-plugin-unicorn?style=social&color=white)](https://github.com/sindresorhus/eslint-plugin-unicorn/stargazers) 🦄
    More than 100+ powerful, opinionated ESLint rules to enforce modern conventions, eliminate code smells, and write cleaner JavaScript and TypeScript.

19. **[dprint](https://github.com/dprint/dprint)** [![GitHub stars](https://img.shields.io/github/stars/dprint/dprint?style=social&color=white)](https://github.com/dprint/dprint/stargazers) 🚀
    Pluggable, configurable, ultra-fast code formatting engine written in Rust with WebAssembly plugins for TypeScript, JavaScript, and JSON.

20. **[ts-prune](https://github.com/nadeesha/ts-prune)** [![GitHub stars](https://img.shields.io/github/stars/nadeesha/ts-prune?style=social&color=white)](https://github.com/nadeesha/ts-prune/stargazers) 🗑️
    Lightweight CLI utility for finding unused and dead exports across TypeScript codebases.

21. **[ESLint Stylistic](https://github.com/eslint-stylistic/eslint-stylistic)** [![GitHub stars](https://img.shields.io/github/stars/eslint-stylistic/eslint-stylistic?style=social&color=white)](https://github.com/eslint-stylistic/eslint-stylistic/stargazers) 🎨
    Community-maintained monorepo for formatting and stylistic rules in ESLint across JavaScript, TypeScript, and JSX.

22. **[Are The Types Wrong? (attw)](https://github.com/arethetypeswrong/arethetypeswrong.github.io)** [![GitHub stars](https://img.shields.io/github/stars/arethetypeswrong/arethetypeswrong.github.io?style=social&color=white)](https://github.com/arethetypeswrong/arethetypeswrong.github.io/stargazers) ❓
    CLI and web analyzer detecting subtle TypeScript module resolution pitfalls, package export mismatches, and broken `.d.ts` declaration maps.

23. **[Quick-lint-js](https://github.com/quick-lint/quick-lint-js)** [![GitHub stars](https://img.shields.io/github/stars/quick-lint/quick-lint-js?style=social&color=white)](https://github.com/quick-lint/quick-lint-js/stargazers) 🏎️
    Blazing-fast C++ JavaScript and TypeScript linter finding bugs in real-time with instant editor feedback and zero configuration.

24. **[Deno Lint](https://github.com/denoland/deno_lint)** [![GitHub stars](https://img.shields.io/github/stars/denoland/deno_lint?style=social&color=white)](https://github.com/denoland/deno_lint/stargazers) 🦕
    Rust-powered linter for JavaScript and TypeScript extracted from the Deno runtime for lightning-fast standalone linting.

25. **[Publint](https://github.com/bluwy/publint)** [![GitHub stars](https://img.shields.io/github/stars/bluwy/publint?style=social&color=white)](https://github.com/bluwy/publint/stargazers) 📮
    Linter for npm packages verifying `package.json` exports, TypeScript declarations, and modern ESM/CJS compatibility.

26. **[prettierd](https://github.com/fsouza/prettierd)** [![GitHub stars](https://img.shields.io/github/stars/fsouza/prettierd?style=social&color=white)](https://github.com/fsouza/prettierd/stargazers) 💨
    Persistent background daemon for Prettier delivering near-instant editor formatting speeds by eliminating Node.js startup overhead.

27. **[tsc-files](https://github.com/gustavopch/tsc-files)** [![GitHub stars](https://img.shields.io/github/stars/gustavopch/tsc-files?style=social&color=white)](https://github.com/gustavopch/tsc-files/stargazers) 📁
    Lightweight CLI tool to run `tsc` type checking selectively on git staged files without full monorepo overhead.

---

## Star History 📈
[![Star History Chart](https://www.star-history.com/svg?repos=ishandutta2007/Awesome-Javascript-Typescript-Tooling-Linters&type=date&legend=top-left)](https://www.star-history.com/#ishandutta2007/Awesome-Javascript-Typescript-Tooling-Linters&type=date&legend=top-left)

---

## Support & Community 💖

Thank you so much for exploring and using **Awesome JavaScript & TypeScript Tooling & Linters**! 🙌

If you find this curated collection helpful for your projects, workflows, or developer tooling explorations, please consider supporting the project:
* 🌟 **Star the repository** to help others discover it on GitHub.
* 🍴 **Fork the repo** to contribute your own favorite tools, linters, or insights.
* 📢 **Share with your colleagues** and dev community on X / Twitter, LinkedIn, and Discord.
* ☕ **Buy a coffee or sponsor ongoing maintenance:** Visit the [Sponsor Dashboard on GitHub Sponsors](https://github.com/sponsors/ishandutta2007) to help support future maintenance and open-source tooling projects!

---

## Contributing 🤝

Contributions are welcome! Feel free to open a Pull Request to add more open-source JavaScript/TypeScript linters, Rust/Go toolchains, formatters, or static analyzers.

1. Fork the repository.
2. Add your project under the appropriate category with a concise description and correct repository link.
3. Submit a Pull Request.

---

## License 📄

This project is licensed under the [MIT License](LICENSE).
