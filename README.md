# Wireshark-analysis
# Task 5: Capture and Analyze Network Traffic Using Wireshark

## Objective
To capture live packets and identify basic protocols and traffic types.

## Tools Used
- Wireshark 

## Steps Performed
1. Installed Wireshark and started packet capture on the Wi-Fi interface.
2. Generated traffic by:
   - Pinging google.com
   - Visiting example.com
   - Using email client
3. Stopped capture after 1 minute.
4. Applied filters to identify protocols.

## Protocols Identified
- **DNS**: Used for domain name resolution (e.g., `A`, `AAAA`, `PTR` queries).
- **HTTP**: Communication with websites (GET and POST requests observed).
- **TCP**: Underlying transport for HTTP and other protocols.
- **ICMP**: Ping requests/replies.
