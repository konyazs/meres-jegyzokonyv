
**VIZSGA JEGYZŐKÖNYV**

**Vizsgázó neve:** Szabolcsik Mátyás, Kónya Zsombor
**Dátum:** 2025.02.03.
**Helyszín:** Miskolc V3

---
### **1. A feladat**
- Földfelszíni digitális TV vételi rendszer kiépítése.

### **2. A feladatban használt eszközök**
| Műszer neve                                      | Típus       | Gyártási szám       |
| -------------------------------------------------| ------------| --------------------|
| LEMCO SCL-824CT                                  | LEMCO       |                     |
| MAG IPTV                                         | Set-top box |                     |
| METEK HDD                                        | METEK       |                     |
| P-2845F                                          | ISKRA       |                     |
| Archer C7                                        |TP-Link      |                     |



### **A vizsga folyamata**
- **A vizsga kezdete:** 11:54

- A miskolc városi tvre hangoljuk az adást mert ez adja a leggyengébb jelet, és ha ezen tökéletesen jön a jel akkor a többi is biztosan működik.
- Bekötjük az antennáról lejövő inputot az elosztóba és kapunk 4 outputot, amiket csatlakoztatunk a Lemkoba.
- Csatlakoztatjuk a Lemko Control portjára a laptop ethernet fészét
- Adunk a laptot ethernet fészének ip címet (192.168.1.1)
- Adunk a laptopnak egy átjárót ami a Lemko ip címe
- Csatlakozunk a Lemkora IP alapon (192.168.1.200)
- Rendezzük az inputokat
- Rendezzük és beállítjuk a csatornákat
  

### **Mérések és eredmények**

- **Input 1:** multiplex a  
- **Input 2:** multiplex b
- **Input 3:** multiplex e
- **Input 4:** Miskolc Városi TV
- **Jelerősség:** 52 dBµV  (Horizontális Dél-Nyugat 234fok Miskolci TV )
- **Moduláció:** Dvb-t/Qpsk/8K/ 1/32   
- **Modulation Error Ratio (MER):** [25] dB   
- **IPTV stream állapota:** [x] Megfelelő [ ] Nem megfelelő  
- **Hálózati késleltetés:** [] ms  
- **Csomagvesztés:** [] %
- **IPTV Stream elemzése:**
- **Multicast IP** 224.224.224.224
- **Multicast port tartomány**10001-10040
- **Páratartalom:** 68%
- **Hőmrséklet:** 5°C
- **Szélerősség:** 3,2m/s
- **Légnyomás** 1027mBar
- **Router konfig:**
-                    -Router Default IP 192.168.1.1
-                    -IP Deafult Gateway 192.168.1.1
-                    -DHCP konfig 192.168.1.100- 192.168.1.249
-                    -IGMP Snooping Protocol [ON]
-                    -Lan1--> Lan3 IPTV Bridge
- **Mag IPTV Konfig:**
- -Ethernet Auto DHCP Link Status[UpLink]
- -USB-ről átmásoltuk a csatorna listát
- 
---

### **Összegzés és értékelés**
  - én meg matyi, matyi meg én felváltva csináltuk, úgy hogy közben a másik végig segített Végére viszont eldobtuk a kanalat

**Vizsgáztató neve:** [Név]  
**Dátum:** [Dátum]  
**Aláírás:** [Aláírás]  

---

