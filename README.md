## Task-8 Identify-and-Remove-Suspicious-Browser-Extension

# Objective:
Gain hands-on understanding of Virtual Private Networks (VPNs), including setup, verification of IP
change, analysis of benefits, limitations, encryption mechanisms, and practical
screenshots/documentation for submission.

# Step-by-Step Procedure:
- Step 1: Research and select a trusted VPN provider. (For this task, ProtonVPN Free was
chosen due to its good reputation and free tier.)
- Step 2: Create a free account on the official ProtonVPN website.
- Step 3: Download the official ProtonVPN client application for your operating system
(Windows/Linux/Mac).
- Step 4: Install the VPN client by following the on-screen instructions.
- Step 5: Open the ProtonVPN application and log in with your account credentials.
- Step 6: Select a nearby VPN server (for better performance) and click 'Connect'.
- Step 7: Verify successful connection – the VPN client should show 'Connected' along with the
new server location and IP.
- Step 8: Open an IP lookup service (such as whatismyipaddress.com) and take a screenshot of
your IP BEFORE connection.
- Step 9: After connecting to VPN, refresh the IP lookup page and take another screenshot. The
IP should now show the VPN server's location.
- Step 10: Visit an HTTPS website (like Gmail or Wikipedia) to ensure that the traffic is encrypted
and accessible through the VPN.
- Step 11: Run an internet speed test (optional) before and after connecting to VPN to measure
performance impact.
- Step 12: Document all steps, attach screenshots, and save them into the 'screenshots/' folder
for GitHub upload.
- Step 13: Write a detailed report (this document) covering observations, benefits, limitations,
and answers to common VPN interview questions.

# Observations:
- Before VPN: Public IP revealed ISP-assigned address (e.g., Chennai, India).
- After VPN: Public IP changed to VPN server region (e.g., Singapore).
- Performance: Observed ~10–15% speed drop and slight latency increase.
- Security: HTTPS worked as expected with encrypted tunnel, confirming secure transmission.

# Benefits of Using a VPN:
• Hides your public IP and masks your geographic location.
• Encrypts traffic between device and VPN server, preventing ISP snooping or Wi-Fi attackers.
• Provides safer browsing on public Wi-Fi networks.
• Enables bypassing of geo-restricted content in compliance with policies/laws.

# Limitations of VPN:
• Not complete anonymity; cookies and accounts can still track users.
• Performance slowdown due to encryption and routing overhead.
• VPN provider must be trusted; they could theoretically log activity.
• Some websites or services may block known VPN IP addresses.

# Encryption & Protocols:
VPNs use encryption algorithms like AES-256 or ChaCha20 to secure data in transit. Common
tunneling protocols include: OpenVPN (widely used and secure), WireGuard (modern, fast,
lightweight), and IKEv2/IPSec (mobile-friendly and stable)

# Conclusion
VPNs provide an additional privacy and security layer but must be used alongside safe browsing habits.
