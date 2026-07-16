# Security policy for this example repository

This repository contains documentation and non-production examples only.

Do not commit:

- passwords, tokens, private keys or certificates;
- real IP addresses, hostnames or internal domains;
- employee names or account identifiers;
- production inventory;
- vCenter, AD, DNS, CMDB or monitoring credentials;
- screenshots from administrative consoles;
- unredacted logs or configuration files.

Before publishing a fork:

1. run a secret scanner;
2. search Git history, not only the current files;
3. replace all environment-specific values;
4. validate that screenshots contain no metadata or hidden text;
5. obtain security and legal approval when required.

Report accidental exposure through the private security channel of the repository owner, not a public issue.
