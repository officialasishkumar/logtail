# logTail 🐝 

logTail is a command-line utility for viewing the tail of files with an interactive terminal user interface. It allows you to monitor log files in real-time with features like live updates, search functionality, syntax highlighting, and easy navigation.

## Binary Files
Download binary files from [releases](https://github.com/officialasishkumar/logTail/releases)

## Installation
Make sure you have [go](https://go.dev/) installed on your system
```bash 
go install github.com/officialasishkumar/logTail@latest
```

## Usage
Basic usage:
Options:
- `-n <number>`: Set the number of lines to display (default: 6)
- `-f`: Enable follow mode to watch for new lines

Examples:
```bash
logTail -n 10 -f path/to/file.log
```
