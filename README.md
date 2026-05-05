# Static-Chan
**DISCLAIMER:** This project is for educational and security research purposes only. The user is solely responsible for compliance with local laws regarding radio interference, and the author assumes no liability for any misuse or legal consequences arising from this hardware.
This project is the most hacky vibes kinda I saw this in my youtube recommendation, its a 2.4ghz wifi and bluetooth jammer/deauther. It uses a esp32 and three nRF24L01+PA+LNA which makes it crazy at max power.

---
<div>&nbsp;</div>

<h2>Functionality Status and Reliability</h2>

<table>
  <thead>
    <tr>
      <th>Feature</th>
      <th>Status</th>
      <th>Reliability</th>
      <th>Notes</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Scanner</strong></td>
      <td>Stable</td>
      <td>High</td>
      <td>Reliably scans the 2.4 GHz band to detect active channels and nearby devices. Occasional misses in high-interference environments.</td>
    </tr>
    <tr>
      <td><strong>Analyzer</strong></td>
      <td>Stable</td>
      <td>High</td>
      <td>Provides useful insights into detected signals, but additional updates are needed for improved accuracy and detailed analysis.</td>
    </tr>
    <tr>
      <td><strong>Jammer</strong></td>
      <td>Stable</td>
      <td>High</td>
      <td>Basic jamming works but effectiveness varies by device type and signal strength. Testing on select channels is recommended.</td>
    </tr>
    <tr>
      <td><strong>BLE Jammer</strong></td>
      <td>Stable</td>
      <td>High</td>
      <td>Disrupts BLE devices inconsistently. Further improvements are needed to ensure stability and effectiveness across BLE variants.</td>
    </tr>
    <tr>
      <td><strong>BLE Spoofer</strong></td>
      <td>Stable</td>
      <td>Low</td>
      <td>Capable of simulating basic BLE signals but has limited compatibility. Best for controlled testing scenarios.</td>
    </tr>
    <tr>
      <td><strong>Sour Apple</strong></td>
      <td>Stable</td>
      <td>Low</td>
      <td>Specialized attack method with limited reliability; effective only under specific conditions. Further tuning is required.</td>
    </tr>
  </tbody>
</table>

---
### Features

- **Scanner** - Scans the 2.4GHz frequency band to detect active channels and devices.
- **Analyzer** - Analyzes the detected signals and provides detailed information about the activity.
- **Jammer** - Jams wireless communication on selected channels to test network robustness.
- **BLE Jammer** - Specifically targets Bluetooth Low Energy (BLE) devices to disrupt their communication.
- **BLE Spoofer** - Spoofs BLE devices to simulate various BLE signals for testing and research.
- **Sour Apple** - A specialized attack for testing security measures against specific wireless vulnerabilities.
- **Proto Kill Mode** - Proto Kill has evolved into a powerful tool for disrupting various protocols.
- **WiFi Scanner** - Scan for hidden and visible BLE devices
- **BLE Scanner** - List nearby Wi-Fi networks with extended details
- **Wi-Fi Deauthentication Attack** - Send deauthentication frames to disrupt client connectio


---
# Design
<img width="1253" height="663" alt="1777966827368-f2akwj" src="https://github.com/user-attachments/assets/c34bda91-0ee0-42bf-818a-06e273f71352" />

---
# Circuit Diagram
<img width="1280" height="720" alt="BLE JAMMER CIRCUICT DIAGRAM (1)" src="https://github.com/user-attachments/assets/2de8d360-3324-48a1-a4bc-0baf43381b54" />

---
# Robu.in Cart 
<img width="926" height="742" alt="1777965253854-lpq105" src="https://github.com/user-attachments/assets/0b7de671-9996-402a-a41b-67e686e3f9b0" />

---
# Amazon.in Cart
<img width="694" height="989" alt="1777970432657-n6p45b" src="https://github.com/user-attachments/assets/c342b03d-76a0-4f4b-99bf-3d0319b23c14" />


