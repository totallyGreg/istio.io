---
title: 发布 Istio 1.16.7
linktitle: 1.16.7
subtitle: 补丁发布
description: Istio 1.16.7 补丁发布。
publishdate: 2023-07-25
release: 1.16.7
---

该版本修复了于 7 月 25 日发布的 [ISTIO-SECURITY-2023-003](/zh/news/security/istio-security-2023-003)
中阐述的安全漏洞。

本发布说明描述了 Istio 1.16.6 和 Istio 1.16.7 之间的不同之处。

该版本为 Istio 1.16 的最后一个版本。

{{< relnote >}}

## 安全更新 {#security-update}

- __CVE-2023-35941__:
  (CVSS Score 8.6, High)：OAuth2 凭证滥用永久有效性。
- __CVE-2023-35942__:
  (CVSS Score 6.5, Moderate)：由于侦听器耗尽而导致 gRPC 访问日志崩溃。
- __CVE-2023-35943__:
  (CVSS Score 6.3, Moderate)：删除原始头信息时，CORS 过滤器发生段错误。
- __CVE-2023-35944__:
  (CVSS Score 8.2, High)：Envoy 中大小写混合情况的 HTTP 请求和响应处理不正确。
