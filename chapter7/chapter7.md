**Use exceptions rather than return codes**

### Write try-catch-finally first
- This will ensure we don't forget to handle errors

### Provide context with exceptions
- Include messages that describe the problem and it's context for future debugging

### Never return null
- Use empty objects or special cases instead

### Never pass null
- 'null' leads to bad code
- Try to avoid it unless it is absolutely necessary

### Convert expections into meaningfull domain errors
- We should wrap low level exceptions into higher level ones to avoid leaking internal details
