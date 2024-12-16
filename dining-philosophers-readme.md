# 🍽️ Dining Philosophers Problem 🧠

## 🌟 Overview

A classic concurrency challenge showcasing synchronization and resource sharing among philosophers.

## 🤔 Philosopher's Dilemma

Five philosophers sit at a circular table:
- 🍽️ Each needs two forks to eat
- 🧠 Alternating between eating and thinking
- 🤝 Sharing limited resources

### 👥 Philosophers
- 🇬🇷 Plato
- 🇬🇷 Socrates
- 🇬🇷 Aristotle
- 🇫🇷 Pascal
- 🇬🇧 Locke

## 🔒 Concurrency Mechanisms
- `sync.Mutex`: Fork synchronization
- `sync.WaitGroup`: Goroutine management
- 🚫 Deadlock prevention strategy

## 🏃 Run & Test

```bash
# Run the simulation
go run main.go

# Execute tests
go test
```

## 🧩 Key Challenges
- 🔀 Concurrent access to shared resources
- 📝 Preventing race conditions
- 🤝 Ensuring fair resource allocation

## 🌈 Learning Outcomes
- Concurrent programming principles
- Synchronization techniques
- Deadlock resolution strategies
