 
**Másodrendű Aluláteresztő Szűrő Mérése**

### 1. Bevezetés
A mérés célja egy másodrendű aluláteresztő szűrő frekvencia-válaszának vizsgálata. A szűrő egy egységnyi erősítésű aktív szűrő, amelyet operációs erősítővel és passzív komponensekkel (ellenállások és kondenzátorok) építettek. A célunk annak meghatározása, hogy a szűrő hogyan viselkedik különböző frekvenciák mellett, különös figyelmet fordítva a vágási frekvenciára és a szűrő erősítésére.

### 2. Eszközök és Komponensek
- **Szimulátor**: Falstad Szimulátor 
- **Komponensek**:
  - Operációs erősítő (op-amp)
  - Ellenállások (R1, R2)
  - Kondenzátorok (C1, C2)
  - Feszültségforrás (AC jel)
  

### 3. Mérési Paraméterek
- **Frekvenciatartomány**: 10 Hz-től 100 kHz-ig.
- **Vágási frekvencia (fc)**: A vágási frekvenciát (ahol az erősítés 3 dB-el csökken) mérjük és összehasonlítjuk a számított értékkel.
- **Erősítés mérése**: Az erősítést az alábbi frekvenciákon kell mérni: 10 Hz, 100 Hz, 1 kHz, 10 kHz, 100 kHz.
- **Fázisválasz**: Mérd meg a fázist a különböző frekvenciákon, hogy megvizsgáld, hogyan változik a szűrő fázisválasza.

### 4. Mérési Eljárás
1. **Beállítás**: Csatlakoztass egy AC feszültségforrást a bemeneti oldalhoz. Állítsd be a bemeneti jel amplitúdóját 1 V-ra (RMS).
2. **Frekvencia változtatása**:
   - Kezdj el kísérletezni a bemeneti jel frekvenciájával.
   - Mérj adatokat az alábbi frekvenciákon: 10 Hz, 100 Hz, 1 kHz, 10 kHz, 100 kHz.
3. **Erősítés mérése**:
   - Minden egyes frekvencián mérd meg az output feszültséget, majd számold ki az erősítést (A = V_out / V_in).
   - Külön figyelmet kell fordítani a vágási frekvenciánál (ahol az erősítés 3 dB-el csökken).
4. **Fázismérés**:
   - Használj oszcilloszkópot a bemeneti és kimeneti jel fáziskülönbségének mérésére.
   - Jegyezd fel a fáziseltolódást a különböző frekvenciákon.

### 5. Várható Eredmények
- **Vágási frekvencia**: A szűrő vágási frekvenciáját \( f_c \) a számított értékeknek megfelelően meghatározzuk. Az elméleti értékek a következőképpen alakulnak:
  \[
  f_c = \frac{1}{2 \pi \sqrt{R1 R2 C1 C2}}
  \]
- **Frekvenciaválasz**: Az alacsony frekvenciákon az erősítésnek 1 körülinek kell lennie (unity gain). A magas frekvenciákon az erősítés 3 dB-el csökken a vágási frekvenciánál.
- **Fázisválasz**: A fázis a vágási frekvencia környékén –90°-ra csökkenhet, és a magas frekvenciák felé tovább csökkenhet.

### 6. Adatok Nyilvántartása
- Rögzítsd a mérési eredményeket az alábbi táblázatokban:

| Frekvencia (Hz) | Bem. feszültség (V) | Kimenő feszültség (V) | Erősítés (A) | Fáziseltolódás (°) |
|-----------------|---------------------|-----------------------|--------------|---------------------|
| 10 Hz           | 1 V                 | X V                   | X            | X                   |
| 100 Hz          | 1 V                 | X V                   | X            | X                   |
| 1 kHz           | 1 V                 | X V                   | X            | X                   |
| 10 kHz          | 1 V                 | X V                   | X            | X                   |
| 100 kHz         | 1 V                 | X V                   | X            | X                   |

### 7. Elemzés
- **Vágási frekvencia ellenőrzése**: Az erősítés értékeit összehasonlítjuk az elméleti számításokkal. A vágási frekvencián az erősítés 3 dB-el csökken az alacsony frekvenciához képest.
- **Fázisválasz elemzése**: A fázisválasz átvizsgálása segít meghatározni, hogy a szűrő hogyan befolyásolja a jelek fázisát a különböző frekvenciákon.

### 8. Következtetések
- A mérés alapján meghatározhatjuk a szűrő pontos vágási frekvenciáját és viselkedését a különböző frekvenciákon.
- Összevethetjük a szimulációval és a gyakorlatban elvárt eredményeket.

