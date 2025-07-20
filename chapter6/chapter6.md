Prefer clear boundaries, encapsulate data in objects and provide functions as a behaviors or use data structures when behavior is not needed. Avoid creating hybrids!
### Objects vs Data Structures
- Objects hide their data and expose behaivours by methods.
- Data structures expose their data and have no significant behavior.
- Objects should encapsulate data and provide methods but data structures should allow direct access to their fileds.

### The Law of Demeter (principle of least knowledge)
- Talk to friends, not to strangers.
- Never have a train wreck `a.getB().getC().operation()`

### Data Transfer Objects (DTO's)
Simple data conteiners without behavior. They are mostly used to transfer data between systems or layers. Commonly used when communicating with databases.
