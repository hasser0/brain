## Trap table

A trap table is an index that associates interrupt signals with its handling
code that allows to securely expose the OS API to developers.

For security, trap tables should be read only and set at boot time to prevent
malicious code to define their own API calls.

