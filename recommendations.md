# 🔐 Wi-Fi Security Recommendations

Following the security assessment of my home Wi-Fi network, here are the key recommendations to improve protection:

## 1. Strengthen Wi-Fi Credentials
- Ensure the Wi-Fi password is long, complex, and not found in common dictionaries.
- Avoid using birthdates, names, or common patterns.

## 2. Close Unused Ports
- Port 80 was found open on a local device; disable this service if not in use.
- Regularly scan for exposed services using Nmap.

## 3. Monitor Device Access
- Enable MAC address filtering to allow only known devices.
- Periodically review connected devices through the router's admin panel.

## 4. Secure IoT Devices
- Change default login credentials on all smart home devices.
- Isolate them on a guest or VLAN network, if possible.

## 5. Update Firmware
- Keep the router firmware up to date to patch known vulnerabilities.

## 6. Enable Guest Network
- Visitors should connect to a guest network that is separate from the primary home network.

## 7. Regular Monitoring
- Use tools like Wireshark and Nmap monthly to check for unusual traffic or new devices.

By implementing these steps, home networks can be made significantly more secure against common cyber threats.
