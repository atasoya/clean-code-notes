Concurrency seperates *what* code does from *when* it runs.

### Debunking Popular Concurrency Myths 
- Concurrency doesnt **always** make code faster.
- It changes how your system is structured
- Frameworks won't magically make your code thread safe

### Main Risks
- Race conditions
- Deadlocks
- Hard to reproduce bugs again

### Clean Concurrency
- Share as little data as possbile
- Prefer immutable or copied data
