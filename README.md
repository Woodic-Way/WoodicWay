Woodic V2Ray Collector V4.0.1
A powerful Android tool for collecting, testing, and managing V2Ray, SOCKS, and HTTP/HTTPS proxy configurations from online sources.

📖 About

Woodic V2Ray Collector v4.0.3 is an advanced Android application that automatically fetches, tests, and organizes available V2Ray, SOCKS, and HTTP/HTTPS proxy configurations from multiple online sources. It eliminates the need for manual searching and provides users with ready-to-use, high-quality proxy configurations.

The app employs a sophisticated multi-stage testing process to ensure only reliable and fast configurations are presented to the user.

✨ Key Features

🔄 Multi-Protocol Support

· V2Ray Protocols: VMess, VLESS, Trojan, Shadowsocks
· SOCKS Proxies: SOCKS4 and SOCKS5
· HTTP/HTTPS Proxies: Full HTTP and HTTPS support with advanced testing

🧪 Advanced Testing Engine

· 4-Stage HTTP Test: TCP Connection → CONNECT 200 → TLS Handshake → GET 204
· Real Delay Testing: Uses libv2ray library for accurate V2Ray/SOCKS latency measurement
· Google gen_204 Endpoint: Standard HTTP testing for reliable results
· High-Performance Testing:
  · 40 threads for HTTP testing
  · 80 threads for TCPing
  · 15-30 concurrent threads for V2Ray testing

📊 Smart Configuration Management

· Random Selection Testing: Tests random subsets from thousands of configs
· Duplicate Removal: Automatic detection and removal of duplicate configurations
· Cache System: Offline access to previously fetched configurations
· Clipboard Import: Auto-format conversion (supports IP:Port format)

🔗 Multiple Updated Sources

· 8+ SOCKS Sources (SOCKS4 & SOCKS5)
· 8+ HTTP Sources (HTTP & HTTPS)
· 5+ V2Ray Sources (VMess, VLESS, Trojan, Shadowsocks)
· Regular Updates: Sources are frequently updated for fresh configurations


V2Ray Sources (5+ sources)
├── Hamed Service
├── V2RayRoot (VLESS, VMess, SS)
├── Farid-Karimi (VMess, VLess, Trojan)
├── DukeMehdi
└── ConfigForge

SOCKS Sources (8+ sources)
├── Proxifly (SOCKS5, SOCKS4)
├── iplocate (SOCKS5, SOCKS4)
├── stormsia
├── ProxyScraper
└── r00tee

HTTP Sources (8+ sources)
├── TheSpeedX
├── ShiftyTR
├── mmpx222
├── jetkai
├── clarketm
└── iplocate

🔒 Privacy & Security

· All configurations are fetched from public sources
· No personal data is collected
· All testing is performed locally on your device
· No tracking or analytics

---

🙏 Credits & Libraries

This project uses several open-source libraries:

· V2ray-Android by dev7dev - Core V2Ray implementation
· Xray-core by XTLS - Xray core engine

📞 Contact & Support

Telegram Channel: @WoodicWay
Issues: GitHub Issues

🌟 Star History

If you find this project useful, please give it a ⭐ on GitHub!

📌 Disclaimer

This tool is for educational and research purposes only. Users are responsible for complying with all applicable laws and regulations regarding proxy usage in their region.

Made with ❤️ by @WoodicWay
