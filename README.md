# Very basic automation script
A tiny, no-nonsense Python wrapper around Nmap. It runs a quick scan against a host, prints discovered ports and services to the console, and saves the results to a timestamped CSV for later review. Intended for lab use and learning—keep it out of production networks unless you have permission.

What it does

Runs an Nmap scan (via python-nmap) against a single host and ports.

Prints each found port with protocol, state and service name.

Writes results to scan_<timestamp>.csv.


# nmap_mini
nmap_mini is a lightweight recon script that runs nmap (via python-nmap or the CLI), parses XML output into structured JSON, performs optional banner grabs, and writes results to JSON and CSV. Designed for multithreaded runs and easy integration into pipelines — must be used only with explicit authorization.
