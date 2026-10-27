### Hi, I'm Aleksandr 👋

Java developer contributing to [Apache Ignite](https://github.com/apache/ignite). At MIPT I do research in empirical software engineering and work as a teaching assistant on a Java course.

#### What I work on in Apache Ignite

- **Rolling upgrade (IEP-132)**: version checks on node join, `control.sh` commands, distributed processes during an upgrade, compatibility tests on testcontainers.
- **Performance statistics**: new operation types and system views in the profiling report, including the [ignite-extensions](https://github.com/apache/ignite-extensions) module.
- **Message compatibility**: moving discovery and communication messages to generated serializers, and checking their wire format on CI.
- **JDK 17/21**: compilation, tests and runtime fixes, e.g. lost profiling records on JDK 21 caused by [JDK-8323782](https://bugs.openjdk.org/browse/JDK-8323782).

[Merged PRs in apache/ignite](https://github.com/apache/ignite/pulls?q=is%3Apr+is%3Amerged+author%3Achesnokoff) ·
[in apache/ignite-extensions](https://github.com/apache/ignite-extensions/pulls?q=is%3Apr+is%3Amerged+author%3Achesnokoff) ·
[JIRA tickets](https://issues.apache.org/jira/issues/?jql=project%20%3D%20IGNITE%20AND%20assignee%20%3D%20chesnokoff%20AND%20resolution%20in%20(Fixed%2C%20Done))

#### Research

I study software quality on large samples of open-source code: how structural metrics, change history and static analysis findings relate to each other.

- A. Chesnokov, D. Kovalev. [JOSSeph: A reproducible, reusable, and extensible pipeline for large-scale extraction of software quality metrics from open-source Java projects](https://doi.org/10.1016/j.softx.2026.102965). *SoftwareX* (Elsevier), 35, 102965, 2026. Code: [chesnokoff/josseph](https://github.com/chesnokoff/josseph)

#### Other projects

- [Apache Ignite abbreviation plugin](https://github.com/apache/ignite-abbrev-plugin): IntelliJ IDEA plugin, revived for JDK 17 and released 4.0.0

#### Contact

[LinkedIn](https://www.linkedin.com/in/chesnokoff) · chesnokoff239@gmail.com
