# Apache Arrow (apache-arrow)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Apache Arrow is a cross-language development platform for in-memory analytics developed by the Apache Software Foundation. It specifies a standardized, language-independent columnar memory format for flat and nested data, organized for efficient analytic operations on modern hardware including CPUs and GPUs. Arrow provides computational libraries in C++, Java, Python (PyArrow), R, Go, Rust, JavaScript, C#, Ruby, Julia, and Swift, along with zero-copy streaming messaging via IPC and a high-performance data transfer framework called Arrow Flight (built on gRPC).

**URL:** [https://arrow.apache.org/](https://arrow.apache.org/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

 - Analytics, Apache, Columnar Format, Data, gRPC, In-Memory, IPC, Open Source, Python

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Apache Arrow Flight RPC
Arrow Flight is a high-performance RPC framework built on gRPC for transferring large datasets using the Arrow columnar format. Flight SQL extends Flight with a SQL-over-Arrow interface for database query execution.

**Human URL:** [https://arrow.apache.org/docs/format/Flight.html](https://arrow.apache.org/docs/format/Flight.html)

#### Tags

 - Data Transfer, gRPC, RPC

#### Properties

- [Documentation](https://arrow.apache.org/docs/format/Flight.html)
- [APIReference](https://arrow.apache.org/docs/format/FlightSql.html)

### Apache Arrow Libraries
Arrow provides native libraries in C++, Java, Python (PyArrow), R, Go, Rust, JavaScript, C#, Ruby, Julia, and Swift for reading, writing, and processing columnar data in the Arrow in-memory format.

**Human URL:** [https://arrow.apache.org/docs/](https://arrow.apache.org/docs/)

#### Tags

 - Data Processing, Libraries, SDK

#### Properties

- [Documentation](https://arrow.apache.org/docs/)
- [APIReference](https://arrow.apache.org/docs/python/api.html)

### Apache Arrow Format Specification
The Apache Arrow columnar format specification defines the binary layout for in-memory columnar data, including the IPC format for streaming and file-based data exchange.

**Human URL:** [https://arrow.apache.org/docs/format/Columnar.html](https://arrow.apache.org/docs/format/Columnar.html)

#### Tags

 - Format, IPC, Specification

#### Properties

- [Documentation](https://arrow.apache.org/docs/format/Columnar.html)
- [Specification](https://arrow.apache.org/docs/format/Versioning.html)

## Common Properties

- [GitHubOrganization](https://github.com/apache)
- [GitHubRepository (arrow)](https://github.com/apache/arrow)
- [GitHubRepository (arrow-rs)](https://github.com/apache/arrow-rs)
- [GitHubRepository (arrow-java)](https://github.com/apache/arrow-java)
- [GitHubRepository (arrow-go)](https://github.com/apache/arrow-go)
- [GitHubRepository (arrow-js)](https://github.com/apache/arrow-js)
- [Documentation](https://arrow.apache.org/)
- [GettingStarted](https://arrow.apache.org/docs/python/getstarted.html)
- [Support](https://arrow.apache.org/community/)
- [TermsOfService](https://www.apache.org/licenses/)
- [ChangeLog](https://arrow.apache.org/blog/)
- [PyArrow (Python)](https://pypi.org/project/pyarrow/)
- [Apache Arrow Java (Maven)](https://search.maven.org/artifact/org.apache.arrow/arrow-vector)
- [Arrow-rs (Rust, crates.io)](https://crates.io/crates/arrow)
- [Arrow Go](https://pkg.go.dev/github.com/apache/arrow/go/v15)
- [Apache Arrow JavaScript (npm)](https://www.npmjs.com/package/apache-arrow)

## Features

| Name | Description |
|------|-------------|
| Columnar In-Memory Format | Standardized language-independent columnar memory layout for efficient analytic operations with zero-copy access. |
| Arrow Flight RPC | High-performance gRPC-based framework for transferring large Arrow datasets between services with minimal serialization overhead. |
| Flight SQL | Extension of Arrow Flight providing a SQL query execution interface over the Arrow Flight protocol. |
| Zero-Copy IPC | Inter-process communication via shared memory and memory-mapped files, enabling zero-copy data sharing across process boundaries. |
| Multi-Language Support | Native libraries for C++, Java, Python, R, Go, Rust, JavaScript, C#, Ruby, Julia, and Swift. |
| Vectorized Computation | SIMD-optimized compute functions for analytical operations on Arrow arrays and tables. |
| Parquet Integration | First-class support for reading and writing Apache Parquet files via the Arrow columnar format. |
| Dataset API | Unified Dataset API for reading partitioned datasets from local filesystems, S3, GCS, and HDFS. |
| GPU Support | CUDA integration for zero-copy data sharing between CPU and GPU memory via the CUDA Arrow device. |
| Extension Types | Custom extension types for encoding domain-specific data using the Arrow format. |

## Use Cases

| Name | Description |
|------|-------------|
| Analytics Data Exchange | Share large analytical datasets between Python, R, Java, and other runtimes without serialization overhead. |
| Database Query Results | Return query results from databases in Arrow format for fast analytics without Python/Java deserialization. |
| Data Pipeline Acceleration | Accelerate ETL and data processing pipelines using columnar computation and SIMD optimizations. |
| Machine Learning Feature Stores | Store and serve ML features in Arrow format for efficient batch and real-time feature retrieval. |
| High-Throughput Data Services | Build high-throughput data microservices using Arrow Flight for efficient bulk data transfer over gRPC. |
| Cross-Language Data Sharing | Share in-memory data between Python pandas/polars, Java, and Rust applications with zero-copy semantics. |

## Integrations

| Name | Description |
|------|-------------|
| Apache Parquet | Native read/write support for Parquet columnar file format, the most common big data storage format. |
| Apache Spark | Spark uses Arrow for Python UDF execution and pandas-on-Spark operations via PyArrow. |
| pandas | Deep integration with pandas DataFrames via PyArrow's to_pandas() and from_pandas() conversions. |
| DuckDB | DuckDB uses Arrow as its primary in-memory data format for zero-copy query result exchange. |
| Polars | Polars DataFrame library is built on Arrow and supports zero-copy interop with Arrow arrays. |
| ADBC (Arrow Database Connectivity) | Arrow Database Connectivity provides an Arrow-native database driver interface analogous to ODBC/JDBC. |
| Delta Lake | Delta Lake integrates with Arrow for reading and writing Delta table data in columnar format. |
| Ray | Ray distributed computing framework uses Arrow for shared-memory object storage between workers. |

## Vocabulary

- [Apache Arrow Vocabulary](vocabulary/apache-arrow-vocabulary.yaml) — Domain taxonomy mapping 6 resources, 6 actions, and 2 personas for Arrow Flight RPC and in-memory analytics

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
