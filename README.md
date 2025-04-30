# ip2nslookup

This runner queries the DNS Lookup API for a provided IP address using the `nslookup` command.

## Functionality

1.  **Build:** The runner first updates the package list and installs the `dnsutils` package, which includes the `nslookup` utility.
2.  **Input:** It expects a single input: an IP address.
3.  **Execution:** It then executes the command `nslookup <ip_address>`, where `<ip_address>` is the IP address provided by the user.