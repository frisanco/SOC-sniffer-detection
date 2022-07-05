# SOC-sniffer-detection

This tools is constructed to detect the common environment in which packet sniffers run. While results cannot be completely assured, the goal is to provide enough information as possible in order to assist with ongoing sniffer investigations.

The program will perform the following functions:

1. Find any PROMISC network interfaces on a local host machine
2. Find any running WIRESHARK processes
3. Find any running TCPDUMP processes
4. For hosts identified above, collect Host information (IP, Operating System, etc.), and
5. Build a report for further analysis and follow-up