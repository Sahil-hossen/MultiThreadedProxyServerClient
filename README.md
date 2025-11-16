# Multi-Threaded Proxy Server with LRU Caching 🌐

A high-performance HTTP proxy server implementation in C featuring multi-threading support and intelligent caching for efficient web request handling.

## 🎯 Project Overview
This project implements a fully functional proxy server that handles multiple concurrent client requests using POSIX threads. It includes an LRU (Least Recently Used) caching mechanism to optimize performance and reduce network bandwidth consumption.

## ✨ Key Features
- **Multi-threaded Architecture**: Concurrent handling of multiple client requests using pthread library
- **LRU Cache Implementation**: Intelligent caching system to reduce redundant network requests
- **HTTP Request Parsing**: Complete parsing and processing of HTTP GET and CONNECT requests
- **Thread Synchronization**: Semaphores and mutex locks ensure thread-safe operations
- **Socket Programming**: TCP socket-based client-server communication
- **Error Handling**: Robust handling of various HTTP status codes and network errors

## 🛠️ Technologies & Concepts
- **Language**: C
- **Networking**: TCP/IP Sockets, HTTP Protocol
- **Concurrency**: POSIX Threads (pthread), Semaphores, Mutex Locks
- **Data Structures**: LRU Cache using Linked Lists
- **System Programming**: Socket system calls, file I/O

## 📋 System Requirements
- GCC Compiler (version 4.8 or higher)
- POSIX-compliant OS (Linux/Unix/macOS)
- pthread library
- Make utility


