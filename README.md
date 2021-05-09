# Opencore-ASRock-B460-Steel-Legend-i5-10400
Opencore EFI for ASRock B460 Steel Legend + Intel Core i5-10400

# Hackintosh-Intel-i5-10400-Asrock-B460M-Steel-Legend

# PC Specs
```
Mainboard: ASRock B460 Steel Legend
CPU: Intel® Core™ i5-10400
Ram: Patriot Viper 8Gb cas 16 bus 3000 (x2), Patriot Viper 8Gb cas 16 bus 3200 (x2). Total 32Gb.
VGA: Onboard Intel UHD 630
PSU: Corsair CV400W
SSD: WD Black SN750 (For Mac), Samsung 850EVO (For Windows)
Bluetooth: Ugreen Bluetooth USB Adapter
```

# Guide Hackintosh + OpenCore
- https://dortania.github.io/OpenCore-Desktop-Guide


# What Working
- iMessage
- Sleep
- Wake
- Audio (select internal speakers)
- Ethernet (> 1Gbps testing)
- Bluetooth: with Ugreen Bluetooth USB Adapter
- All USB ports (Full 3.0 + 2.0 + Type C)

# Note For You
Replace with your smbios and serial, or follow the guide at https://dortania.github.io/OpenCore-Post-Install/universal/iservices.html
smbios: iMac20,1
```
<dict>
  <key>AdviseWindows</key>
  <false/>
  <key>MLB</key>
  <string>DUMMYMLBXXX</string>
  <key>ProcessorType</key>
  <integer>1541</integer>
  <key>ROM</key>
  <data>ESIzRFVm</data>
  <key>SpoofVendor</key>
  <true/>
  <key>SystemProductName</key>
  <string>iMac20,1</string>
  <key>SystemSerialNumber</key>
  <string>DUMMYSERIAL</string>
  <key>SystemUUID</key>
  <string>DUMMY-UUID-XXX-YYY</string>
  <key>SystemMemoryStatus</key>
  <string>Auto</string>
  <key>MaxBIOSVersion</key>
  <false/>
</dict>
```
