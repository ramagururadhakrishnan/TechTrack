# Wireless Communication - Bluetooth

This page details the Bluetooth Technology.

<p align="center">
   <img src="https://www.bluetooth.com/wp-content/themes/bluetooth/images/logos/bluetooth-logo-color-black.svg" alt="BT-Logo" width="240"/>
</p>

**Bluetooth** is a wireless communication technology used for _short-range communication_. Bluetooth derives the name from **Harald "Bluetooth" Gormsson**, King of Denmark and Norway (958 CE – 986 CE). 

## Bluetooth (BT)
   - **Introduced** : 1998
   - **Frequency** : 2.400 to 2.4835 GHz (ISM Band) 
   - **Channel Usage** : Adaptive Frequency Hoping Spread Spectrum (AFHSS)
   - **Standards** : IEEE 802.15.1 (no longer maintained)
   - **Maintained/Supported by** : Bluetooth Special Interest Group 
    
### BT Classic
   - **Channels** : 79 channels with 1 MHz spacing 
      - Range : 2402 MHz to 2480 MHz 
      - Guard Band : 2 MHz (Bottom) and 3.5 MHz (Top)
   - **Topology** : Point-to-point (Piconet)
   - **Modulation** : 
      - Gaussian Frequency Shift Keying (GFSK)
      - π/4 Differential Quaternary Phase Shift Keying (DQPSK)
      - 8-ary Differential Phase Shift Keying (8DPSK)
   - **Positioning Features** : None
   - **Pairing** : Required
   - **Internet Connection** : Through Gateways

### BT Low Energy (LE)
   - **Also Known as** : Wibree or BT Smart
   - **Available from** : Version 4.0
   - **Channels** : 40 channels with 2 MHz spacing 
      - 37 Data : C0 - 2.404 GHz to C10 - 2.424 GHz, C11 - 2.428 GHz to C36 - 2.478 GHz
      - 3 Advertising : C37 - 2.402 GHz, C38 - 2.426 GHz, C39 - 2.480 GHz
   - **Topology** : Point-to-point (Piconet), Point-to-Many (Broadcast) and Many-to-Many (Mesh)
   - **Modulation** : Gaussian Frequency Shift Keying (GFSK)
   - **Positioning Features** : 
      - Presence : Advertising
      - Proximity : Received Signal Strength Indicator (RSSI)
      - Direction :  Angle of Arrival (AoA) and Angle of Departure (AoD) 
      - Distance : TBD
   - **Pairing** : Not Required
   - **Internet Connection** : Through Gateways
  
## Versions

| Generation | Range | Year | Speed | 
|:----------:|:-----:|:----:|:-----:|
| 1.0 | upto 10 m | 1999 | 768 kbps - 1 Mbps | 
| 2.0 | upto 30 m	| 2005 | 3 Mbps | 
| 3.0 | upto 30 m |	2009 | 24 Mbps |	
| 4.0 | upto 60 m	| 2010 | 24 Mbps	 | 
| 5.0 | upto 240 m | 2016 | 48 Mbps	 | 

## Profiles 

  - Attribute Profile (ATT) [BLE]
  - Generic Audio/Video Distribution Profile (GAVDP) [Basis for A2DP and VDP]
  - Generic Access Profile (GAP) [Basis for all profiles]
  - Generic Attribute Profile (GATT) [BLE]
  - Health Device Profile (HDP)
  - Mesh Profile (MESH)
  - Message Access Profile (MAP)
  - Personal Area Networking Profile (PAN) [Previously LAN Access Profile (LAP) was used]
  - Video Distribution Profile (VDP)

##### Last Updated : 06 Feb 2022
