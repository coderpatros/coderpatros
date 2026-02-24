I work at the intersection of software engineering, product security, software supply chain transparency, and international standards development.

As a product security leader at ServiceNow, I manage a globally distributed team driving the maturity of secure software development practices for a platform trusted by over 8,100 customers, including 85% of the Fortune 500. My background spans hands-on secure design reviews and threat modeling, BSIMM assessments, and leading SSDF gap analyses that directly supported U.S. Federal Government contract assurance.

Beyond my day job, I co-lead the OWASP CycloneDX project — one of the world’s most widely adopted SBOM standards, now ratified as ECMA-424 by Ecma International. I built the project’s governance framework, developed key tooling, initiated the Transparency Exchange API, and helped shape government guidance on SBOM adoption across multiple international jurisdictions. I’ve presented on software supply chain security at events including CISA SBOM-a-rama, Lockheed Martin’s Code.LM (keynote), Homeland Security Week, Swiss Cyber Storm, FOSDEM, and AusCERT.

I also serve on the Executive Committee of Ecma International, the standards body behind ECMAScript (JavaScript), C#/.NET, and Office Open XML — contributing to the strategic oversight of technical committees shaping the future of software and system transparency, AI agent interoperability, and GPU shading languages.

---

# Project Highlights

## 🔗 OWASP CycloneDX Ecosystem

| Repository | Description |
|---|---|
| [CycloneDX/specification](https://github.com/CycloneDX/specification) | The full-stack Bill of Materials (BOM) standard covering SBOM, SaaSBOM, HBOM, AI/ML-BOM, CBOM, OBOM, MBOM, VDR, and more for software supply chain transparency and cyber risk reduction. |
| [CycloneDX/cyclonedx-cli](https://github.com/CycloneDX/cyclonedx-cli) | Cross-platform CLI tool for SBOM analysis, merging, diffing, and format conversions between CycloneDX formats. |
| [CycloneDX/cyclonedx-dotnet](https://github.com/CycloneDX/cyclonedx-dotnet) | .NET global tool and Docker image that generates CycloneDX SBOMs from .NET solutions and projects (`.sln`, `.csproj`, `.fsproj`, etc.). One of the most widely used SBOM generators in the .NET ecosystem. |
| [cyclonedx-dotnet-msbuild](https://github.com/coderpatros/cyclonedx-dotnet-msbuild) | An MSBuild task that automatically generates CycloneDX SBOMs during the build process, enabling seamless integration into existing .NET build pipelines. |
| [CycloneDX/cyclonedx-web-tool](https://github.com/CycloneDX/cyclonedx-web-tool) | Browser-based tool for viewing and working with CycloneDX BOMs, making SBOM data accessible without CLI tools. |
| [CycloneDX/cyclonedx-dotnet-library](https://github.com/CycloneDX/cyclonedx-dotnet-library/) | One of the few reference implementations of the CycloneDX standard, a .NET library to consume and produce CycloneDX Software Bill of Materials (SBOM). |
| [cyclonedx-verify](https://github.com/coderpatros/cyclonedx-verify) | A CLI tool that validates files against CycloneDX SBOMs, performing JSF signature validation, cryptographic hash verification, and untracked file detection. Supports Linux, macOS, and Windows across x64 and ARM64. |
| [cyclonedx-fortran-fpm](https://github.com/coderpatros/cyclonedx-fortran-fpm) | A CycloneDX SBOM generator for Fortran fpm projects. Parses `fpm.toml` manifests, recursively resolves Git dependencies, builds dependency graphs, and outputs CycloneDX 1.6 JSON. Written entirely in Fortran. |

---

## 🛠️ .NET Developer Tooling

| Repository | Description |
|---|---|
| [dotnet-outdated/dotnet-outdated](https://github.com/dotnet-outdated/dotnet-outdated) | A popular .NET global tool for displaying and automatically updating outdated NuGet packages in a project. Supports interactive prompts, transitive dependencies, version locking, and output in JSON/CSV/Markdown. |

---

## 🔐 Cryptographic Signing

| Repository | Description |
|---|---|
| [dotnet-jsf](https://github.com/coderpatros/dotnet-jsf) | The .NET library and CLI implementing [JSON Signature Format (JSF)](https://cyberphone.github.io/doc/security/jsf.html) — a scheme for embedding cryptographic signatures directly within JSON objects using JSON Canonicalization Scheme (RFC 8785). Supports 15 algorithms across ECDSA, RSA PKCS#1 v1.5, RSA-PSS, EdDSA, and HMAC families, with single signatures, multi-signatures, and signature chains. |

---

## 🖥️ Frontend Utilities

| Repository | Description |
|---|---|
| [environment-indicator](https://github.com/coderpatros/environment-indicator) | A lightweight, zero-dependency JavaScript library that adds a visual banner to web apps indicating the current environment (dev, UAT, staging, training, etc.). Configurable via query params, script attributes, or JS objects. Available via jsDelivr CDN. |

---
