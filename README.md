# cisco-ospf-enterprise-network
# Cisco Packet Tracer - Kéttelephelyes Vállalati Hálózat OSPF Dinamikus Routinggal

Ez a projekt egy továbbfejlesztett vállalati hálózati architektúrát mutat be Cisco Packet Tracer környezetben, amely kiegészíti az alapvető VLAN és Inter-VLAN routing ismereteket egy két routeres, dinamikus útvonalválasztásos (OSPF) szcenárióval.

## 🛠️ Megvalósított hálózati funkciók

* **VLAN szegmentáció és Inter-VLAN routing:** Helyi hálózatok (IT_Dept, HR_Dept, Management) kialakítása az `R1`-es routeren Router-on-a-Stick módszerrel.
* **Többtelephelyes topológia:** Két router (`R1` és `R2`) összekötése dedikált alhálózaton keresztül (`192.168.20.0/30`), egy központi és egy távoli telephely szimulációjához.
* **Dinamikus Routing (OSPF):** Az OSPF protokoll (Area 0) konfigurációja, amelynek köszönhetően a routerek automatikusan megosztják egymással a routing táblákat és felderítik a távoli hálózatokat (`192.168.30.0/24`).
* **Tesztelés:** Teljes körű kétirányú kapcsolat és ping teszt a különböző alhálózatok és telephelyek között.

## 📂 Fájlok a repóban

* **`ospf-vallalati-halozat.pkt`** - A teljes, futtatható Cisco Packet Tracer projektfájl.
* **`topologia.png`** - A hálózati topológia és az eszközök összeköttetésének képe.
