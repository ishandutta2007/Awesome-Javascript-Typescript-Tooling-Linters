# Awesome-Javascript-Typescript-Tooling-Linters

# Awesome-Javascript-Typescript-Tooling-Linters

Top Javascript Typescript Tooling Linters (Opensource) 🌟 Star if you like it! 🌟

A curated list of top JavaScript and TypeScript linters, high-speed Rust/Zig formatters, static analysis engines, type checkers, and developer code-quality toolchains—featuring commercial SaaS/Hosted platforms alongside their open-source equivalents.

---

## Table of Contents

- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source Equivalents & Tools](#open-source-equivalents--tools)
  - [Next-Gen High-Speed Linters & All-in-One Toolchains](#next-gen-high-speed-linters--all-in-one-toolchains)
  - [Standard JavaScript & TypeScript Linters](#standard-javascript--typescript-linters)
  - [Code Formatters & Style Enforcers](#code-formatters--style-enforcers)
  - [Static Analysis, Dead Code & Architecture Linters](#static-analysis-dead-code--architecture-linters)
  - [Type Checkers, Compilers & AST Parsers](#type-checkers-compilers--ast-parsers)
- [Contributing](#contributing)

---

## SaaS/Hosted Platforms

Commercial, cloud-hosted code quality platforms, automated PR review services, and managed continuous inspection suites.

* **[SonarQube Cloud (SonarCloud)](https://sonarsource.com)** - Enterprise cloud-based code quality and static application security testing (SAST) platform with deep JavaScript/TypeScript rule sets.
* **[DeepSource](https://deepsource.com)** - Automated cloud code health and static analysis platform detecting bugs, anti-patterns, and security vulnerabilities on every pull request.
* **[Codacy](https://codacy.com)** - Managed DevSecOps platform automating code reviews, ESLint/Biome rule enforcement, code coverage, and technical debt tracking.
* **[CodeClimate Quality](https://codeclimate.com)** - Cloud-hosted automated code review service providing maintainability ratings, test coverage, and linter orchestration.
* **[Qodana (JetBrains)](https://jetbrains.com)** - Commercial code quality and static analysis platform bringing WebStorm/IntelliJ JavaScript & TypeScript inspections into CI/CD pipelines.
* **[Biome / ESLint / Prettier Hosted CI Services (Trunk.io / MegaLinter Cloud)](https://trunk.io)** - Managed developer experience platforms orchestrating hosted linting, formatting, and hermetic toolchain caching across repositories.
* **[Snyk Code](https://snyk.io)** - Real-time cloud static analysis tool identifying security flaws and code quality issues in JavaScript and TypeScript codebases.

---

## Open-Source Equivalents & Tools

Free and open-source software (FOSS) linters, ultra-fast Rust/C++ formatters, static analyzers, dead-code detectors, and TypeScript toolchains.

### Next-Gen High-Speed Linters & All-in-One Toolchains

* **[Oxc & Oxlint (oxc-project)](https://github.com)** - Collection of high-performance JavaScript and TypeScript tools written in Rust, featuring `oxlint` (50–100x faster than ESLint), parsers, and transformers.
* **[tsrs (oxc-project)](https://github.com)** - Open-source Rust-based TypeScript tooling and compiler infrastructure experiment within the Oxidation Compiler ecosystem.
* **[Biome](https://github.com)** - Fast, unified open-source formatter and linter for JavaScript, TypeScript, JSX, JSON, CSS, and GraphQL written in Rust (successor to Rome Tools).
* **[Rome Tools (Archived Predecessor to Biome)](https://github.com)** - Pioneering open-source unified JavaScript/TypeScript toolchain written in Rust that laid the architectural foundation for Biome.
* **[Quick-lint-js](https://github.com)** - Ultra-fast C++ JavaScript and TypeScript linter finding bugs in real time with instant editor feedback and zero configuration.
* **[Deno Lint & Deno Fmt](https://github.com)** - Blazingly fast, built-in Rust-powered linter and dprint-backed formatter integrated into the open-source Deno runtime.

### Standard JavaScript & TypeScript Linters

* **[ESLint](https://github.com)** - The industry-standard, pluggable open-source linter for JavaScript and TypeScript with the largest ecosystem of community rules and plugins.
* **[TypeScript-ESLint](https://github.com)** - Monorepo providing the tooling and parser that enables ESLint and Prettier to understand and lint TypeScript syntax and type information.
* **[StandardJS](https://github.com)** - Zero-configuration, opinionated JavaScript style guide, linter, and automatic code fixer built on ESLint.
* **[XO](https://github.com)** - Opinionated, zero-config open-source JavaScript/TypeScript code linter enforcing strict code quality rules out of the box.
* **[JSHint](https://github.com)** - Classic, lightweight community-driven static analysis tool detecting errors and potential problems in JavaScript code.

### Code Formatters & Style Enforcers

* **[Prettier](https://github.com)** - The foundational opinionated code formatter supporting JavaScript, TypeScript, JSX, CSS, HTML, Markdown, and JSON.
* **[dprint](https://github.com)** - Pluggable, configurable, ultra-fast code formatting platform written in Rust with WebAssembly plugins for TypeScript, JavaScript, and JSON.
* **[Prettierd](https://github.com)** - Persistent background daemon for Prettier delivering near-instant editor formatting speeds by eliminating Node.js startup overhead.
* **[ESLint Stylistic](https://github.com)** - Community-maintained collection of formatting and stylistic rules for ESLint across JavaScript, TypeScript, and JSX.

### Static Analysis, Dead Code & Architecture Linters

* **[Knip](https://github.com)** - Comprehensive open-source tool for finding unused files, dependencies, and exports in JavaScript and TypeScript monorepos.
* **[dependency-cruiser](https://github.com)** - Validate and visualize dependencies in JS/TS projects, enforcing architectural boundaries and detecting circular imports.
* **[Madge](https://github.com)** - Developer tool for generating visual graphs of module dependencies, finding circular dependencies, and inspecting CommonJS/ESM trees.
* **[ts-prune / Unimported](https://github.com)** - Lightweight open-source CLI utilities for identifying dead exports and orphaned files in TypeScript projects.
* **[SonarQube Community Build](https://github.com)** - Open-source self-hosted continuous code quality and static analysis server supporting JavaScript and TypeScript.
* **[Semgrep](https://github.com)** - Fast, open-source static analysis engine for finding bugs and enforcing custom security/code standards across JS/TS codebases.

### Type Checkers, Compilers & AST Parsers

* **[TypeScript (tsc)](https://github.com)** - Microsoft's open-source strongly typed programming language and compiler that builds on JavaScript.
* **[SWC (Speedy Web Compiler)](https://github.com)** - Super-fast TypeScript/JavaScript compiler, parser, and minifier written in Rust powering Next.js, Parcel, and Deno.
* **[tsgo (TypeScript Native Port)](https://github.com-go)** - Official native port of the TypeScript compiler and type checker written in Go for 10x faster type checking.
* **[tsc-files / Type-Coverage](https://github.com)** - Open-source CLI tools for checking type coverage percentages and running targeted TypeScript checks.
* **[Publint](https://github.com)** - Open-source linter for npm packages verifying `package.json` exports, TypeScript declarations, and ESM/CJS compatibility.
* **[Are The Types Wrong? (attw)](https://github.com)** - Open-source tool analyzing npm package contents to catch subtle TypeScript module resolution and `.d.ts` issues.

---

## Contributing

Contributions are welcome! Feel free to open a Pull Request to add more open-source JavaScript/TypeScript linters, Rust/Go toolchains, formatters, or static analyzers.

1. Fork the repository.
2. Add your project under the appropriate category with a concise description.
3. Submit a Pull Request.
