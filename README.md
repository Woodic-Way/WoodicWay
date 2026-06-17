Woodic V2Ray Collector v3.5.0 is an Android tool that collects available V2Ray, SOCKS, and HTTP/HTTPS proxy configurations from online sources and organizes them in one place for easy access and use.

It helps users quickly find and manage fresh proxy configs without manual searching. The app automatically fetches configurations from multiple sources, tests them for speed and latency using a 4-stage verification process, and displays only the working ones.

Key features include:
• Support for V2Ray protocols (VMess, VLESS, Trojan, Shadowsocks)
• Support for SOCKS4 and SOCKS5 proxies
• Support for HTTP and HTTPS proxies with 4-stage testing
• 4-stage HTTP test: TCP → CONNECT 200 → TLS Handshake → GET 204
• Real delay testing using libv2ray library for V2Ray/SOCKS
• Google gen_204 endpoint for HTTP testing
• Random selection testing from thousands of configs
• Clipboard import with auto-format conversion (supports IP:Port)
• Cache system for offline access
• Multiple updated sources (8+ SOCKS sources, 8+ HTTP sources, 5 V2Ray sources)
• High-speed testing with 40 threads for HTTP and 80 threads for TCPing
• Version 3.5.0 with optimized performance
