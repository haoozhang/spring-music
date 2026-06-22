# Security Assessment Report

**Generated:** 2026-06-22T06:51:30.0000000Z

## Summary

| Metric | Count |
|--------|-------|
| Total Findings | 45 |
| CVE Vulnerabilities | 40 |
| CWE Vulnerabilities | 5 |
| Total Rules Assessed | 59 |
| Rules Passed | 54 |

### By Severity

| Severity | Count |
|----------|-------|
| mandatory | 40 |
| optional | 3 |
| potential | 2 |

## CVE Findings (Dependency Vulnerabilities)

### CVE-2025-41249: Spring Framework annotation detection mechanism may result in improper authorization
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** build.gradle

[CVE-2025-41249](https://github.com/advisories/GHSA-jmp9-x22r-554x): Spring Framework annotation detection mechanism may result in improper authorization

Severity: HIGH

Affected dependencies:
  - org.springframework:spring-core:6.0.13 (declared at build.gradle)

### CVE-2025-22235: Spring Boot EndpointRequest.to() creates wrong matcher if actuator endpoint is not exposed
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** build.gradle:25

[CVE-2025-22235](https://github.com/advisories/GHSA-rc42-6c7j-7h5r): Spring Boot EndpointRequest.to() creates wrong matcher if actuator endpoint is not exposed

Severity: HIGH

Affected dependencies:
  - org.springframework.boot:spring-boot:3.1.5 (declared at build.gradle:25)

### CVE-2024-22262: Spring Framework URL Parsing with Host Validation
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** build.gradle

[CVE-2024-22262](https://github.com/advisories/GHSA-2wrp-6fg6-hmc5): Spring Framework URL Parsing with Host Validation

Severity: HIGH

Affected dependencies:
  - org.springframework:spring-web:6.0.13 (declared at build.gradle)

Recommended fix:
  - Upgrade org.springframework:spring-web to 5.3.34 or later

### CVE-2024-22259: Spring Framework URL Parsing with Host Validation Vulnerability
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** build.gradle

[CVE-2024-22259](https://github.com/advisories/GHSA-hgjh-9rj2-g67j): Spring Framework URL Parsing with Host Validation Vulnerability

Severity: HIGH

Affected dependencies:
  - org.springframework:spring-web:6.0.13 (declared at build.gradle)

Recommended fix:
  - Upgrade org.springframework:spring-web to 6.1.5 or later

### CVE-2024-22243: Spring Web vulnerable to Open Redirect or Server Side Request Forgery
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** build.gradle

[CVE-2024-22243](https://github.com/advisories/GHSA-ccgv-vj62-xf9h): Spring Web vulnerable to Open Redirect or Server Side Request Forgery

Severity: HIGH

Affected dependencies:
  - org.springframework:spring-web:6.0.13 (declared at build.gradle)

Recommended fix:
  - Upgrade org.springframework:spring-web to 6.1.4 or later

### CVE-2023-6378: logback serialization vulnerability
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** build.gradle

[CVE-2023-6378](https://github.com/advisories/GHSA-vmq6-5m68-f53m): logback serialization vulnerability

Severity: HIGH

Affected dependencies:
  - ch.qos.logback:logback-classic:1.4.11 (declared at build.gradle)
  - ch.qos.logback:logback-core:1.4.11 (declared at build.gradle)

Recommended fix:
  - Upgrade ch.qos.logback:logback-classic to 1.4.12 or later
  - Upgrade ch.qos.logback:logback-core to 1.4.12 or later

### CVE-2022-1471: SnakeYaml Constructor Deserialization Remote Code Execution
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** build.gradle

[CVE-2022-1471](https://github.com/advisories/GHSA-mjmj-j48q-9wg2): SnakeYaml Constructor Deserialization Remote Code Execution

Severity: HIGH

Affected dependencies:
  - org.yaml:snakeyaml:1.33 (declared at build.gradle)

Recommended fix:
  - Upgrade org.yaml:snakeyaml to 2.0 or later

### CVE-2026-41284: Apache Tomcat: Unbounded read in WebDAV LOCK and  PROPFIND handling
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** build.gradle

[CVE-2026-41284](https://github.com/advisories/GHSA-gx5v-xp9w-j4cg): Apache Tomcat: Unbounded read in WebDAV LOCK and  PROPFIND handling

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:10.1.15 (declared at build.gradle)

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.118 or later

### CVE-2026-43512: Apache Tomcat - Digest authenticator will authenticate any unknown user
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** build.gradle

[CVE-2026-43512](https://github.com/advisories/GHSA-h6fc-48rj-7qqh): Apache Tomcat - Digest authenticator will authenticate any unknown user

Severity: CRITICAL

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:10.1.15 (declared at build.gradle)

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.118 or later

### CVE-2026-43513: Apache Tomcat: LockOutRealm treats user names as case-sensitive
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** build.gradle

[CVE-2026-43513](https://github.com/advisories/GHSA-5mp6-jrq3-r938): Apache Tomcat: LockOutRealm treats user names as case-sensitive

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:10.1.15 (declared at build.gradle)

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.118 or later

### CVE-2026-43515: Apache Tomcat - Security constraints not correctly applied
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** build.gradle

[CVE-2026-43515](https://github.com/advisories/GHSA-5m62-pw8w-7w9f): Apache Tomcat - Security constraints not correctly applied

Severity: CRITICAL

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:10.1.15 (declared at build.gradle)

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.118 or later

### CVE-2026-41293: Apache Tomcat - HTTP/2 request headers not validated
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** build.gradle

[CVE-2026-41293](https://github.com/advisories/GHSA-r29c-68gh-xp6x): Apache Tomcat - HTTP/2 request headers not validated

Severity: CRITICAL

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:10.1.15 (declared at build.gradle)

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.118 or later

### CVE-2026-42498: Apache Tomcat - WebSocket authentication header exposure
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** build.gradle

[CVE-2026-42498](https://github.com/advisories/GHSA-fv25-8xcx-gqjc): Apache Tomcat - WebSocket authentication header exposure

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:10.1.15 (declared at build.gradle)

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.118 or later

### CVE-2026-34483: Apache Tomcat has an Improper Encoding or Escaping of Output vulnerability in the JsonAccessLogValve
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** build.gradle

[CVE-2026-34483](https://github.com/advisories/GHSA-rv64-5gf8-9qq8): Apache Tomcat has an Improper Encoding or Escaping of Output vulnerability in the JsonAccessLogValve

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:10.1.15 (declared at build.gradle)

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.116 or later

### CVE-2026-24880: Apache Tomcat has an HTTP Request/Response Smuggling vulnerability
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** build.gradle

[CVE-2026-24880](https://github.com/advisories/GHSA-563x-q5rq-57qp): Apache Tomcat has an HTTP Request/Response Smuggling vulnerability

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:10.1.15 (declared at build.gradle)

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.116 or later

### CVE-2026-24734: Apache Tomcat has an Improper Input Validation vulnerability
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** build.gradle

[CVE-2026-24734](https://github.com/advisories/GHSA-mgp5-rv84-w37q): Apache Tomcat has an Improper Input Validation vulnerability

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:10.1.15 (declared at build.gradle)

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 11.0.18 or later

### CVE-2025-55752: Apache Tomcat Vulnerable to Relative Path Traversal
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** build.gradle

[CVE-2025-55752](https://github.com/advisories/GHSA-wmwf-9ccg-fff5): Apache Tomcat Vulnerable to Relative Path Traversal

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:10.1.15 (declared at build.gradle)

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 11.0.11 or later

### CVE-2025-48989: Apache Tomcat Improper Resource Shutdown or Release vulnerability
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** build.gradle

[CVE-2025-48989](https://github.com/advisories/GHSA-gqp3-2cvr-x8m3): Apache Tomcat Improper Resource Shutdown or Release vulnerability

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:10.1.15 (declared at build.gradle)

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 11.0.10 or later

### CVE-2025-53506: Apache Tomcat Coyote vulnerable to Denial of Service via excessive HTTP/2 streams
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** build.gradle

[CVE-2025-53506](https://github.com/advisories/GHSA-25xr-qj8w-c4vf): Apache Tomcat Coyote vulnerable to Denial of Service via excessive HTTP/2 streams

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:10.1.15 (declared at build.gradle)

### CVE-2025-52520: Apache Tomcat Catalina is vulnerable to DoS attack through bypassing of size limits
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** build.gradle

[CVE-2025-52520](https://github.com/advisories/GHSA-wr62-c79q-cv37): Apache Tomcat Catalina is vulnerable to DoS attack through bypassing of size limits

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:10.1.15 (declared at build.gradle)

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 11.0.9 or later

### CVE-2025-48988: Apache Tomcat - DoS in multipart upload
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** build.gradle

[CVE-2025-48988](https://github.com/advisories/GHSA-h3gc-qfqq-6h8f): Apache Tomcat - DoS in multipart upload

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:10.1.15 (declared at build.gradle)

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 11.0.8 or later

### CVE-2025-24813: Apache Tomcat: Potential RCE and/or information disclosure and/or information corruption with partial PUT
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** build.gradle

[CVE-2025-24813](https://github.com/advisories/GHSA-83qj-6fr2-vhqg): Apache Tomcat: Potential RCE and/or information disclosure and/or information corruption with partial PUT

Severity: CRITICAL

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:10.1.15 (declared at build.gradle)

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 11.0.3 or later

### CVE-2024-56337: Apache Tomcat Time-of-check Time-of-use (TOCTOU) Race Condition vulnerability
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** build.gradle

[CVE-2024-56337](https://github.com/advisories/GHSA-27hp-xhwr-wr2m): Apache Tomcat Time-of-check Time-of-use (TOCTOU) Race Condition vulnerability

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:10.1.15 (declared at build.gradle)

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 11.0.2 or later

### CVE-2024-38819: Spring Framework Path Traversal vulnerability
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** build.gradle

[CVE-2024-38819](https://github.com/advisories/GHSA-g5vr-rgqm-vf78): Spring Framework Path Traversal vulnerability

Severity: HIGH

Affected dependencies:
  - org.springframework:spring-webmvc:6.0.13 (declared at build.gradle)

Recommended fix:
  - Upgrade org.springframework:spring-webmvc to 6.1.14 or later

### CVE-2024-50379: Apache Tomcat Time-of-check Time-of-use (TOCTOU) Race Condition vulnerability
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** build.gradle

[CVE-2024-50379](https://github.com/advisories/GHSA-5j33-cvvr-w245): Apache Tomcat Time-of-check Time-of-use (TOCTOU) Race Condition vulnerability

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:10.1.15 (declared at build.gradle)

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 11.0.2 or later

### CVE-2024-38816: Path traversal vulnerability in functional web frameworks
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** build.gradle

[CVE-2024-38816](https://github.com/advisories/GHSA-cx7f-g6mp-7hqm): Path traversal vulnerability in functional web frameworks

Severity: HIGH

Affected dependencies:
  - org.springframework:spring-webmvc:6.0.13 (declared at build.gradle)

Recommended fix:
  - Upgrade org.springframework:spring-webmvc to 6.1.13 or later

### CVE-2024-34750: Apache Tomcat - Denial of Service
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** build.gradle

[CVE-2024-34750](https://github.com/advisories/GHSA-wm9w-rjj3-j356): Apache Tomcat - Denial of Service

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:10.1.15 (declared at build.gradle)

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 11.0.0-M21 or later

### CVE-2023-46589: Apache Tomcat Improper Input Validation vulnerability
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** build.gradle

[CVE-2023-46589](https://github.com/advisories/GHSA-fccv-jmmp-qg76): Apache Tomcat Improper Input Validation vulnerability

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:10.1.15 (declared at build.gradle)

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 11.0.0-M11 or later

### CVE-2023-34053: Spring Framework vulnerable to denial of service
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** build.gradle

[CVE-2023-34053](https://github.com/advisories/GHSA-v94h-hvhg-mf9h): Spring Framework vulnerable to denial of service

Severity: HIGH

Affected dependencies:
  - org.springframework:spring-webmvc:6.0.13 (declared at build.gradle)

Recommended fix:
  - Upgrade org.springframework:spring-webmvc to 6.0.14 or later

### CVE-2026-50010: Netty: Wrapping plain trust manager silently disables hostname verification
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** build.gradle

[CVE-2026-50010](https://github.com/advisories/GHSA-c653-97m9-rcg9): Netty: Wrapping plain trust manager silently disables hostname verification

Severity: HIGH

Affected dependencies:
  - io.netty:netty-handler:4.1.97.Final (declared at build.gradle)

Recommended fix:
  - Upgrade io.netty:netty-handler to 4.2.15.Final or later

### CVE-2026-45416: Netty: SNI handler pre-allocates up to 16 MiB from nine attacker bytes
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** build.gradle

[CVE-2026-45416](https://github.com/advisories/GHSA-x4gw-5cx5-pgmh): Netty: SNI handler pre-allocates up to 16 MiB from nine attacker bytes

Severity: HIGH

Affected dependencies:
  - io.netty:netty-handler:4.1.97.Final (declared at build.gradle)

Recommended fix:
  - Upgrade io.netty:netty-handler to 4.2.15.Final or later

### CVE-2026-44249: Netty has an IPv6 Subnet Filter Bypass via Incorrect Comparator Masking
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** build.gradle

[CVE-2026-44249](https://github.com/advisories/GHSA-3qp7-7mw8-wx86): Netty has an IPv6 Subnet Filter Bypass via Incorrect Comparator Masking

Severity: HIGH

Affected dependencies:
  - io.netty:netty-handler:4.1.97.Final (declared at build.gradle)

Recommended fix:
  - Upgrade io.netty:netty-handler to 4.2.15.Final or later

### CVE-2026-42583: Netty Lz4FrameDecoder is vulnerable to resource exhaustion 
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** build.gradle

[CVE-2026-42583](https://github.com/advisories/GHSA-mj4r-2hfc-f8p6): Netty Lz4FrameDecoder is vulnerable to resource exhaustion 

Severity: HIGH

Affected dependencies:
  - io.netty:netty-codec:4.1.97.Final (declared at build.gradle)

Recommended fix:
  - Upgrade io.netty:netty-codec to 4.1.133.Final or later

### CVE-2025-24970: SslHandler doesn't correctly validate packets which can lead to native crash when using native SSLEngine
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** build.gradle

[CVE-2025-24970](https://github.com/advisories/GHSA-4g8c-wm8x-jfhw): SslHandler doesn't correctly validate packets which can lead to native crash when using native SSLEngine

Severity: HIGH

Affected dependencies:
  - io.netty:netty-handler:4.1.97.Final (declared at build.gradle)

Recommended fix:
  - Upgrade io.netty:netty-handler to 4.1.118.Final or later

### CVE-2026-42198: pgjdbc: Unbounded PBKDF2 iterations in SCRAM authentication allows CPU exhaustion DoS
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** build.gradle:39

[CVE-2026-42198](https://github.com/advisories/GHSA-98qh-xjc8-98pq): pgjdbc: Unbounded PBKDF2 iterations in SCRAM authentication allows CPU exhaustion DoS

Severity: HIGH

Affected dependencies:
  - org.postgresql:postgresql:42.6.0 (declared at build.gradle:39)

Recommended fix:
  - Upgrade org.postgresql:postgresql to 42.7.11 or later

### CVE-2026-22733: Spring Boot has an Authentication Bypass under Actuator CloudFoundry endpoints
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** build.gradle:26

[CVE-2026-22733](https://github.com/advisories/GHSA-mgvc-8q2h-5pgc): Spring Boot has an Authentication Bypass under Actuator CloudFoundry endpoints

Severity: HIGH

Affected dependencies:
  - org.springframework.boot:spring-boot-starter-actuator:3.1.3 (declared at build.gradle:26)

Recommended fix:
  - Upgrade org.springframework.boot:spring-boot-starter-actuator to 4.0.4 or later

### CVE-2025-59250: JDBC Driver for SQL Server has improper input validation issue
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** build.gradle:40

[CVE-2025-59250](https://github.com/advisories/GHSA-m494-w24q-6f7w): JDBC Driver for SQL Server has improper input validation issue

Severity: HIGH

Affected dependencies:
  - com.microsoft.sqlserver:mssql-jdbc:11.2.3.jre17 (declared at build.gradle:40)

Recommended fix:
  - Upgrade com.microsoft.sqlserver:mssql-jdbc to 11.2.4.jre11 or later

### CVE-2024-1597: org.postgresql:postgresql vulnerable to SQL Injection via line comment generation
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** build.gradle:39

[CVE-2024-1597](https://github.com/advisories/GHSA-24rp-q3w6-vc56): org.postgresql:postgresql vulnerable to SQL Injection via line comment generation

Severity: CRITICAL

Affected dependencies:
  - org.postgresql:postgresql:42.6.0 (declared at build.gradle:39)

Recommended fix:
  - Upgrade org.postgresql:postgresql to 42.2.28 or later

### CVE-2023-22102: MySQL Connectors takeover vulnerability
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** build.gradle:38

[CVE-2023-22102](https://github.com/advisories/GHSA-m6vm-37g8-gqvh): MySQL Connectors takeover vulnerability

Severity: HIGH

Affected dependencies:
  - com.mysql:mysql-connector-j:8.0.33 (declared at build.gradle:38)

Recommended fix:
  - Upgrade com.mysql:mysql-connector-j to 8.2.0 or later

### CVE-2022-45868: Password exposure in H2 Database 
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** build.gradle:37

[CVE-2022-45868](https://github.com/advisories/GHSA-22wj-vf5f-wrvj): Password exposure in H2 Database 

Severity: HIGH

Affected dependencies:
  - com.h2database:h2:2.1.214 (declared at build.gradle:37)

Recommended fix:
  - Upgrade com.h2database:h2 to 2.2.220 or later

## CWE Findings (Code-Level Vulnerabilities)

### CWE-477: Use of Obsolete Function
- **Category:** Code Quality
- **Severity:** optional
- **Story Points:** 1
- **Files:** src/main/java/org/cloudfoundry/samples/music/repositories/AlbumRepositoryPopulator.java

In AlbumRepositoryPopulator.java, raw types are used for CrudRepository at lines 29 and 38 (e.g., 'CrudRepository albumRepository' and 'private void populate(CrudRepository repository)'). Raw types are an obsolete Java feature that bypasses generic type safety, flagged by the Java compiler with unchecked warnings. This indicates the code has not been updated to modern Java generics practices.

### CWE-567: Unsynchronized Access to Shared Data in a Multithreaded Context
- **Category:** Concurrency & Synchronization
- **Severity:** potential
- **Story Points:** 5
- **Files:** src/main/java/org/cloudfoundry/samples/music/web/ErrorController.java

ErrorController is a Spring @RestController, which is a singleton by default and shared across all request threads. The field 'private List<int[]> junk = new ArrayList<>()' (line 15) is a mutable instance variable with no synchronization. The fillHeap() method (lines 23-29) writes to this shared list in a while(true) loop without synchronization, allowing concurrent requests to race on the same unsynchronized ArrayList.

### CWE-820: Missing Synchronization
- **Category:** Concurrency & Synchronization
- **Severity:** potential
- **Story Points:** 8
- **Files:** src/main/java/org/cloudfoundry/samples/music/web/ErrorController.java

In ErrorController (line 15), the instance field 'private List<int[]> junk = new ArrayList<>()' is shared across concurrent HTTP request threads since the controller is a Spring singleton. The fillHeap() method (lines 23-29) accesses and modifies this list in a tight loop without any synchronization mechanism (no synchronized block, no volatile, no concurrent collection). Concurrent requests invoking this endpoint would race on the unsynchronized ArrayList.

### CWE-732: Incorrect Permission Assignment for Critical Resource
- **Category:** Credentials & Secrets
- **Severity:** optional
- **Story Points:** 5
- **Files:** src/main/resources/application.yml

In application.yml (lines 7-9), all Spring Boot Actuator endpoints are exposed publicly via 'management.endpoints.web.exposure.include: "*"'. Additionally, 'management.endpoint.health.show-details: always' exposes sensitive internal health details to all users. This allows unauthenticated access to sensitive endpoints such as /actuator/env (environment variables and configuration), /actuator/beans (application context), /actuator/heapdump, and others that may reveal internal system details.

### CWE-798: Use of Hard-coded Credentials
- **Category:** Credentials & Secrets
- **Severity:** optional
- **Story Points:** 5
- **Files:** src/main/resources/application.yml

In application.yml (line 47), the PostgreSQL database username 'postgres' is hardcoded in the 'postgres' profile configuration ('username: postgres'). Hardcoded credentials in configuration files checked into version control can be exposed to anyone with repository access and cannot be rotated without code changes.
