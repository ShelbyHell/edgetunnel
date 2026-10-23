# 🚀 edgetunnel 2.1

<p align="center">
  <a href="./README.md"><b>简体中文</b></a> | <a href="./README_EN.md"><b>English</b></a>
</p>

![Admin Dashboard](./img.png)

[![Stars](https://img.shields.io/github/stars/cmliu/edgetunnel?style=flat-square&logo=github)](https://github.com/cmliu/edgetunnel/stargazers)
[![Forks](https://img.shields.io/github/forks/cmliu/edgetunnel?style=flat-square&logo=github)](https://github.com/cmliu/edgetunnel/network/members)
[![License](https://img.shields.io/github/license/cmliu/edgetunnel?style=flat-square)](https://github.com/cmliu/edgetunnel/blob/main/LICENSE)
[![Telegram](https://img.shields.io/badge/Telegram-Group-blue?style=flat-square&logo=telegram)](https://t.me/CMLiussss)
[![YouTube](https://img.shields.io/badge/YouTube-Channel-red?style=flat-square&logo=youtube)](https://www.youtube.com/watch?v=LeT4jQUh8ok)
[![zread](https://img.shields.io/badge/Ask_Zread-_.svg?style=flat-square&color=00b0aa&labelColor=000000&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB3aWR0aD0iMTYiIGhlaWdodD0iMTYiIHZpZXdCb3g9IjAgMCAxNiAxNiIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPHBhdGggZD0iTTQuOTYxNTYgMS42MDAxSDIuMjQxNTZDMS44ODgxIDEuNjAwMSAxLjYwMTU2IDEuODg2NjQgMS42MDE1NiAyLjI0MDFWNC45NjAxQzEuNjAxNTYgNS4zMTM1NiAxLjg4ODEgNS42MDAxIDIuMjQxNTYgNS42MDAxSDQuOTYxNTZDNS4zMTUwMiA1LjYwMDEgNS42MDE1NiA1LjMxMzU2IDUuNjAxNTYgNC45NjAxVjIuMjQwMUM1LjYwMTU2IDEuODg2NjQgNS4zMTUwMiAxLjYwMDEgNC45NjE1NiAxLjYwMDFaIiBmaWxsPSIjZmZmIi8%2BCjxwYXRoIGQ9Ik00Ljk2MTU2IDEwLjM5OTlIMi4yNDE1NkMxLjg4ODEgMTAuMzk5OSAxLjYwMTU2IDEwLjY4NjQgMS42MDE1NiAxMS4wMzk5VjEzLjc1OTlDMS42MDE1NiAxNC4xMTM0IDEuODg4MSAxNC4zOTk5IDIuMjQxNTYgMTQuMzk5OUg0Ljk2MTU2QzUuMzE1MDIgMTQuMzk5OSA1LjYwMTU2IDE0LjExMzQgNS42MDE1NiAxMy43NTk5VjExLjAzOTlDNS42MDE1NiAxMC42ODY0IDUuMzE1MDIgMTAuMzk5OSA0Ljk2MTU2IDEwLjM5OTlaIiBmaWxsPSIjZmZmIi8%2BCjxwYXRoIGQ9Ik0xMy43NTg0IDEuNjAwMUgxMS4wMzg0QzEwLjY4NSAxLjYwMDEgMTAuMzk4NCAxLjg4NjY0IDEwLjM5ODQgMi4yNDAxVjQuOTYwMUMxMC4zOTg0IDUuMzEzNTYgMTAuNjg1IDUuNjAwMSAxMS4wMzg0IDUuNjAwMUgxMy43NTg0QzE0LjExMTkgNS42MDAxIDE0LjM5ODQgNS4zMTM1NiAxNC4zOTg0IDQuOTYwMVYyLjI0MDFDMTQuMzk4NCAxLjg4NjY0IDE0LjExMTkgMS42MDAxIDEzLjc1ODQgMS42MDAxWiIgZmlsbD0iI2ZmZiIvPgo8cGF0aCBkPSJNNCAxMkwxMiA0TDQgMTJaIiBmaWxsPSIjZmZmIi8%2BCjxwYXRoIGQ9Ik00IDEyTDEyIDQiIHN0cm9rZT0iI2ZmZiIgc3Ryb2tlLXdpZHRoPSIxLjUiIHN0cm9rZS1saW5lY2FwPSJyb3VuZCIvPgo8L3N2Zz4K&logoColor=ffffff)](https://zread.ai/cmliu/edgetunnel)
[![Ask DeepWiki](https://deepwiki.com/badge.svg)](https://deepwiki.com/cmliu/edgetunnel)

---

## 📖 Overview

**edgetunnel** is a high-performance edge computing tunnel and proxy gateway built on top of Cloudflare Workers and Cloudflare Pages. It efficiently routes and decrypts network traffic, offering a modern web dashboard and versatile node management capabilities.

- 🖥️ **Live Demo**: [https://EDT-Pages.github.io/admin](https://EDT-Pages.github.io/admin)

### ✨ Key Features

- 🛡️ **Multiple Protocols**: Comprehensive support for VLESS, Trojan, and Shadowsocks protocols with deep end-to-end encryption.
- 📊 **Web Dashboard**: Built-in visual admin panel for live configuration changes, real-time logs, and Cloudflare traffic analytics.
- 🛠️ **Flexible Deployment**: Seamless deployment via Cloudflare Workers or Cloudflare Pages (Direct Zip Upload or Git integration).
- 🔄 **Subscription Engine**: Automatic subscription generation and conversion for popular proxy clients (Clash, Sing-box, Surge, Shadowrocket, etc.).
- ⚡ **Performance Acceleration**: Custom ProxyIP, SOCKS5/HTTP upstream chain proxying, and automated Clean IP (优选 IP) pool rotation.
- 🌐 **Cross-Platform**: Fully compatible with Windows, Android, iOS, macOS, Linux, and OpenWrt/soft-router firmware.

---

## 💡 Quick Start & Deployment

>[!TIP]
> 📖 **Comprehensive Step-by-Step Guide**: [edgetunnel Deployment Guide (Chinese)](https://cmliussss.com/p/edt2/)

>[!WARNING]
> ⚠️ **Fixing Error 1101**: [Video Explanation](https://www.youtube.com/watch?v=r4uVTEJptdE)

### ⚙️ Option 1: Cloudflare Workers Deployment

<details>
<summary><code><strong>「 Workers Deployment Walkthrough 」</strong></code></summary>

1. **Deploy CF Worker**:
   - Navigate to the Cloudflare dashboard and create a new Worker under **Workers & Pages**.
   - Copy the contents of [_worker.js](https://github.com/cmliu/edgetunnel/blob/main/_worker.js) and paste them into the Worker code editor, then deploy.
   - Go to **Settings** > **Variables** > **Environment Variables** > **Add variable**.
   - Set the variable name to **`ADMIN`** and enter your desired admin dashboard password, then click **Save**.

2. **Bind KV Namespace**:
   - Under **Settings** > **Bindings**, click **Add** > **KV Namespace**.
   - Set **Variable name** to **`KV`** (must be uppercase `KV`).
   - Select an existing KV namespace or create a new one, then save.

3. **Attach a Custom Domain**:
   - Go to the **Triggers** tab of your Worker and scroll down to **Custom Domains**.
   - Click **Add Custom Domain** and enter a subdomain routed through Cloudflare DNS (e.g., `vless.yourdomain.com`).
   - Wait for the SSL/TLS certificate to provision.

4. **Access Dashboard**:
   - Open `https://vless.yourdomain.com/admin` in your browser and log in with your `ADMIN` password.

</details>

### 🛠 Option 2: Cloudflare Pages Direct Upload (Recommended)

<details>
<summary><code><strong>「 Pages Direct Upload Walkthrough 」</strong></code></summary>

1. **Deploy CF Pages**:
   - Download the repository archive [main.zip](https://github.com/cmliu/edgetunnel/archive/refs/heads/main.zip) (and don't forget to star the repo!).
   - In the Cloudflare dashboard, go to **Workers & Pages** > **Create application** > **Pages** > **Upload assets**.
   - Enter your project name, upload the downloaded `main.zip` file, and click **Deploy site**.
   - Once deployed, click **Continue to project**.
   - Navigate to **Settings** > **Environment variables** > **Production** > **Add variable**.
   - Set variable name to **`ADMIN`** with your admin password, then click **Save**.
   - Go back to the **Deployments** tab, click **Create new deployment** on the right, re-upload `main.zip`, and click **Save and Deploy**.

2. **Bind KV Namespace**:
   - In **Settings** > **Bindings**, click **+ Add** > **KV Namespace**.
   - Set **Variable name** to **`KV`**.
   - Choose or create a KV namespace and click **Save**, then trigger a redeploy.

3. **Bind Custom CNAME Domain**: [Video Tutorial](https://www.youtube.com/watch?v=LeT4jQUh8ok&t=851s)
   - Go to the **Custom domains** tab in your Pages project and click **Set up a custom domain**.
   - Enter a dedicated subdomain (e.g., `edt.yourdomain.com` — do **not** use the apex root domain).
   - In your DNS provider, create a **CNAME** record for that subdomain pointing to `<your-project>.pages.dev` with DNS-only or Cloudflare proxy as required, then click **Activate domain**.

4. **Access Dashboard**:
   - Visit `https://edt.yourdomain.com/admin` and log in with your admin password.

</details>

### 🛠 Option 3: Cloudflare Pages + GitHub Deployment

<details>
<summary><code><strong>「 Pages + GitHub Walkthrough 」</strong></code></summary>

1. **Deploy CF Pages via Git**:
   - Fork this repository to your GitHub account.
   - In the Cloudflare dashboard, go to **Workers & Pages** > **Create application** > **Pages** > **Connect to Git**.
   - Select your forked `edgetunnel` repository and click **Begin setup**.
   - Under **Build and deployment settings**, open **Environment variables (advanced)** and click **Add variable**.
   - Set **`ADMIN`** with your chosen password, then click **Save and Deploy**.

2. **Bind KV Namespace**:
   - Once the first build finishes, navigate to **Settings** > **Bindings** > **+ Add** > **KV Namespace**.
   - Set **Variable name** to **`KV`**, select your namespace, and save.
   - Go to **Deployments** and click **Retry deployment**.

3. **Bind Custom Domain**:
   - Under **Custom domains**, click **Set up a custom domain** and add your subdomain (e.g., `edt.yourdomain.com`).
   - Follow Cloudflare's instructions to add the CNAME record pointing to `<project>.pages.dev`.

4. **Access Dashboard**:
   - Visit `https://edt.yourdomain.com/admin` and log in.

</details>

---

## 🔑 Environment Variables

| Variable | Required | Example | Description |
| :--- | :---: | :--- | :--- |
| **`ADMIN`** | ✅ | `MyPass123!` | Admin dashboard login password. |
| **`KEY`** | ❌ | `MySecretToken` | Fast subscription path key. Accessing `/<KEY>` immediately returns subscription nodes. |
| **`UUID`** | ❌ | `90cd4a77-141a-43c9-991b-08263cfe9c10` | Fixed user UUID. Must be in valid **UUIDv4** format. |
| **`PROXYIP`** | ❌ | `proxyip.cmliussss.net:443` | Global custom Cloudflare reverse proxy IP (ProxyIP). |
| **`URL`** | ❌ | `https://cloudflare-error-page-3th.pages.dev` | Decoy homepage address (URL or `1101` for mock Cloudflare Error 1101 page). |
| **`GO2SOCKS5`** | ❌ | `blog.example.com`,`*.ip111.cn`,`*google.com` | Domains routed through SOCKS5 (`*` for global, comma-separated). |
| **`LANG`** | ❌ | `en` or `zh` | Language switcher for API responses and subscription node names (`en` for English, `zh` for Chinese, default: `zh`). |
| **`DEBUG`** | ❌ | `1` or `true` | **Developer Mode**: enables verbose console logging (`console.log`). |
| **`OFF_LOG`** | ❌ | `1` or `true` | Disables KV request logging when set to `1` or `true` (logging is enabled by default). |
| **`BEST_SUB`** | ❌ | `1` or `true` | Enables clean subscription generator upstream functionality. |
| **`PRELOAD_RACE_DIAL`** | ❌ | `1` or `true` | Enables preloaded TCP racing dial for lower initial latency. |
| **`TCP_CONCURRENT_DIAL`** | ❌ | `2` | Number of concurrent TCP dialing attempts (default `2`). |
| **`PROXY_CONCURRENT_DIAL`** | ❌ | `1` | Number of concurrent proxy dialing attempts (default `1`). Higher values speed up connection at the expense of more frequent IP rotations. |

---

## 🔧 Advanced Routing & Dynamic Path Usage

If you need to change the **Subscription TOKEN** and the **Authentication UUID**:
1. Changing the `ADMIN` or `KEY` variables deterministically derives a new token and UUID.
2. Specifying the `UUID` variable explicitly locks the UUID and subscription token (must be standard UUIDv4).

### Dynamic Upstream Routing via URL Paths

The tunnel supports dynamically switching the underlying proxy backend by encoding parameters directly in the request path:

- **Custom ProxyIP**:
  ```url
  /proxyip=proxyip.cmliussss.net
  /?proxyip=proxyip.cmliussss.net
  ```

- **Upstream SOCKS5 Proxy**:
  ```url
  /socks5=user:password@127.0.0.1:1080
  /?socks5=user:password@127.0.0.1:1080
  /socks://dXNlcjpwYXNzd29yZA==@127.0.0.1:1080 (activates global SOCKS5)
  /socks5://user:password@127.0.0.1:1080 (activates global SOCKS5)
  ```

- **Upstream HTTP Proxy**:
  ```url
  /http=user:password@127.0.0.1:8080
  /http://user:password@127.0.0.1:8080 (activates global HTTP proxy)
  ```

- **Trojan Fallback**:
  *(Used when pairing with a self-hosted Trojan upstream without WebSocket/TLS, transparently passing UDP traffic)*
  ```url
  /trojan=1.1.1.1:1234
  ```

---

## 💻 Supported Clients

| Platform | Recommended Clients |
| :--- | :--- |
| **Windows** | [v2rayN](https://github.com/2dust/v2rayN/releases), [Hiddify](https://github.com/hiddify/hiddify-app/releases), [FlClash](https://github.com/chen08209/FlClash/releases), [mihomo-party](https://github.com/mihomo-party-org/clash-party/releases), [Clash Verge Rev](https://github.com/clash-verge-rev/clash-verge-rev/releases), [Karing](https://github.com/KaringX/karing/releases), [Bettbox](https://github.com/appshubcc/Bettbox/releases) |
| **Android** | [v2rayNG](https://github.com/2dust/v2rayNG/releases), [ClashMetaForAndroid](https://github.com/MetaCubeX/ClashMetaForAndroid/releases/), [FlClash](https://github.com/chen08209/FlClash/releases), [Hiddify](https://github.com/hiddify/hiddify-app/releases), [NekoBox](https://github.com/MatsuriDayo/NekoBoxForAndroid/releases), [Karing](https://github.com/KaringX/karing/releases), [Bettbox](https://github.com/appshubcc/Bettbox/releases) |
| **iOS** | Surge, Shadowrocket, Stash, [Hiddify](https://github.com/hiddify/hiddify-app/releases), Loon, Egern, [Karing](https://karing.app/), Quantumult X |
| **macOS** | [FlClash](https://github.com/chen08209/FlClash/releases), [mihomo-party](https://github.com/mihomo-party-org/clash-party/releases), [Clash Verge Rev](https://github.com/clash-verge-rev/clash-verge-rev/releases), Surge, [Karing](https://karing.app/) |
| **HarmonyOS** | [ClashBox](https://github.com/xiaobaigroup/ClashBox/releases) |

---

## ⭐ Star History

![Stargazers over time](https://github.com/cmliu/cmliu/blob/main/star/edgetunnel.svg)

---

## 🙏 Acknowledgements & Credits

### 💖 Sponsors
Cloud servers maintaining the [Subscription Conversion Service](https://sub.cmliussss.net/):
- [Yuusei Network](https://yuusei.io/)
- [VMRack](https://www.vmrack.net?ref_code=5Zk7eNhbgL7)

### 🛠 Open Source Projects & References
- [zizifn/edgetunnel](https://github.com/zizifn/edgetunnel)
- [3Kmfi6HP/EDtunnel](https://github.com/6Kmfi6HP/EDtunnel)
- [SHIJS1999/cloudflare-worker-vless-ip](https://github.com/SHIJS1999/cloudflare-worker-vless-ip)
- [Stanley-baby](https://github.com/Stanley-baby)
- [ACL4SSR](https://github.com/ACL4SSR/ACL4SSR/tree/master/Clash/config)
- [Workers/Pages Metrics](https://t.me/zhetengsha/3382)
- [Mingyu](https://github.com/ymyuuu/workers-vless)
- [ToiCF/CF-Workers-HTTPS](https://github.com/ToiCF/CF-Workers-HTTPS)
- [ToiCF/CF-Workers-TURN](https://github.com/ToiCF/CF-Workers-TURN)
- [ToiCF/CF-Workers-SoftEther](https://github.com/ToiCF/CF-Workers-SoftEther)
- [eooce](https://github.com/eooce/Cloudflare-proxy)
- [Sukka](https://ip.skk.moe/)
- [zhangtaile](https://github.com/cmliu/edgetunnel/pull/999)
- [1345695](https://github.com/1345695/edcloudwasm)
- [ToiCF/GrainTCP](https://github.com/ToiCF/GrainTCP)
- [xream](https://github.com/cmliu/edgetunnel/pull/1359)

---

## ⚠️ Disclaimer

1. This project ("edgetunnel") is intended strictly for **educational, scientific research, and personal security testing purposes**.
2. Users must strictly comply with local laws and regulations when using or downloading this code.
3. The author assumes no responsibility for any misuse or legal consequences arising from the operation of this software.
4. The project is provided "as-is", without warranties or liability for any direct or indirect damages.
5. It is recommended to dismantle or delete test deployments within 24 hours after verification.

---

**If you find this project helpful, please consider leaving a Star 🌟 — it is greatly appreciated!**
