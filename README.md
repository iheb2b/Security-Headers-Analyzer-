# Security Headers Analyzer 🛡️

A Python tool for analyzing and validating website security headers with color-coded output and detailed recommendations.

## 🚀 Features

- **Real-time Analysis**: Instant security header validation
- **Color-coded Output**: Easy-to-understand visual results
- **Detailed Reports**: Comprehensive security assessments
- **Smart Recommendations**: Actionable security improvements
- **Error Handling**: Robust connection and SSL error management
- **Browser Simulation**: Realistic request headers

## 🔍 Security Headers Checked

| Header | Purpose |
|--------|---------|
| `Strict-Transport-Security` | Enforces HTTPS connections |
| `Content-Security-Policy` | Controls resource loading |
| `X-Frame-Options` | Prevents clickjacking attacks |
| `X-Content-Type-Options` | Prevents MIME-type sniffing |
| `Referrer-Policy` | Controls referrer information |
| `Permissions-Policy` | Manages browser feature permissions |
| `X-XSS-Protection` | Mitigates XSS attacks |

## 📋 Requirements

```bash
requests>=2.31.0
colorama>=0.4.6
