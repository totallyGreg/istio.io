---
title: ISTIO-SECURITY-2023-003
subtitle: 安全公告
description: Envoy 上报的 CVE 漏洞。
cves: [CVE-2023-35941,CVE-2023-35942,CVE-2023-35943,CVE-2023-35944]
cvss: "7.5"
vector: "CVSS:3.1/AV:N/AC:L/PR:N/UI:N/S:U/C:N/I:N/A:H"
releases: ["1.16.0 以及之前的所有版本", "1.16.0 到 1.16.6", "1.17.0 到 1.17.4", "1.18.0 到 1.18.1"]
publishdate: 2023-07-25
keywords: [CVE]
skip_seealso: true
---

{{< security_bulletin >}}

## CVE

### Envoy CVE {#envoy-cves}

- __CVE-2023-35941__:
  (CVSS Score 8.6, High)：OAuth2 凭证滥用永久有效性。
- __CVE-2023-35942__:
  (CVSS Score 6.5, Moderate)：由于侦听器耗尽而导致 gRPC 访问日志崩溃。
- __CVE-2023-35943__:
  (CVSS Score 6.3, Moderate)：删除原始头信息时，CORS 过滤器发生段错误。
- __CVE-2023-35944__:
  (CVSS Score 8.2, High)：Envoy 中大小写混合情况的 HTTP 请求和响应处理不正确。

## 我受到影响了吗？{#am-i-impacted}

如果您接受来自不受信来源的 HTTP/2 流量，则您会受到影响，这种情况适用于大多数用户。
如果您使用公共互联网上公开的网关，要特别注意您可能已经受到了影响。
