# Torrent File Exchange System – Socket Programming Project

This project simulates a simplified torrent-like file exchange system using **C socket programming**. It demonstrates how a central server can handle multiple client connections, allowing users to browse available files and download selected files concurrently.

## 📌 Features

- Multi-client support using `fork()` to handle concurrent connections
- Displays and shares server-side files with connected clients
- Clients can request specific files for download
- Logs all connection and transfer details for auditing
- Ensures reliable data transmission and session handling

## 🧰 Technologies Used

- C Programming Language
- Linux (Ubuntu-based setup)
- TCP/IP Socket Programming
- Multi-processing using `fork()`

## 🧪 Testing

Tested on a Unix-like host machine and Ubuntu client VMs:
- Server startup and listening confirmation
- Client connection and file request handling
- Multi-client concurrency
- File integrity verification after download
- Logging of connection and transfer details

## 📁 Project Structure

- `server.c` – Main server logic and socket handling
- `client.c` – Client-side interface and file retrieval
- `headers.h` – Shared header file
- Test cases and output screenshots included in the report

## 📄 Report

This repository includes the complete report in PDF format, outlining the implementation, test cases, and result logs.

