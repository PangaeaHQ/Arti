# Arti-Swift 🧅

This repository provides a Swift Package interface for **Arti**, the next-generation implementation of the Tor protocol in Rust. It enables Pangaea and other decentralized clients to route traffic through the Tor network for enhanced privacy and censorship resistance.

## Features
- **Anonymous Routing**: Native support for Tor onion services.
- **Swift-First API**: Abstracts the complexity of the underlying Rust implementation.
- **Decentralized Focus**: Optimized for peer-to-peer applications needing global connectivity fallbacks.

## Installation
Add this to your `Package.swift` dependencies:
```swift
.package(url: "https://github.com/PangaeaHQ/Arti.git", branch: "main")
