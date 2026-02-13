# Go Packet Shredder

High-performance network packet fuzzer written in Go.

## Features

- **Packet Fuzzing**: Generate malformed network packets
- **High Performance**: Go concurrency for fast packet generation
- **Protocol Support**: TCP, UDP, ICMP fuzzing
- **Custom Payloads**: Configurable payload generation
- **Analysis Integration**: Output for network analysis tools

## Usage

### Build

```bash
go build -o shredder main.go
```

### Run

```bash
./shredder
```

## Project Structure

```
go-packet-shredder/
├── main.go           # Main application
├── pkg/              # Package implementations
├── README.md         # This file
└── .github/
    └── workflows/
        └── ci.yml   # CI/CD pipeline
```

## Requirements

- Go 1.21+
- libpcap (optional for raw socket access)

## Disclaimer

**Educational Use Only**: This tool is for network security learning and authorized testing only.

## License

MIT
