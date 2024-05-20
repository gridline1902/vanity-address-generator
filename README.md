# Solana Vanity Address Generator

This guide explains how to set up your environment and generate a vanity address using the Solana CLI.

## Prerequisites
- Windows 10 or 11
- PowerShell
- WSL (Windows Subsystem for Linux)
- Ubuntu
- Rust
- Solana CLI

## Steps

### 1. Install WSL
Enable WSL on your Windows machine using powershell:
```wsl --install```

### 2. Install Linux distro [I chose Ubuntu]
```wsl --install -d Ubuntu```

### 3. Install Rust
```curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh -s -- -y```

### 4. Install Solana CLI
```sh -c "$(curl -sSfL https://release.solana.com/stable/install)"```

### 5. Generate Vanity Address
```solana-keygen grind --starts-with mic:1```