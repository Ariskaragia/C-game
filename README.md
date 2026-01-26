# Platform Game (C++ / SGG)

## Περιγραφή
Platform game υλοποιημένο σε C++ με χρήση της βιβλιοθήκης Simple Graphics Library (SGG).
Ο παίκτης κινείται σε πίστες, αποφεύγει κινδύνους/εχθρούς και συλλέγει αντικείμενα/πόντους μέχρι τον τερματισμό.


ΤΟ ΠΑΙΧΝΙΔΙ ΣΕ exe ΕΙΝΑΙ ΣΕ ΑΥΤΟ ΤΟ ΛΙΝΚ: 

https://drive.google.com/drive/folders/139hDW1rk8Ve4RNRketUQtg8IqduB2T-X?usp=sharing


ΤΟ ΠΑΙΧΝΙΔΙ ΠΩΣ ΛΕΙΤΟΥΡΓΕΙ ΣΕ ΒΙΝΤΕΟ : 

https://drive.google.com/drive/folders/1eb8iypLsaKMm2lIRRxjP6GGNvT2VUmUc?usp=sharing

ΤΑ ASSETS ΤΟΥ ΠΑΙΧΝΙΔΙΟΥ :

https://drive.google.com/drive/folders/15CjyO5DqDTh--OqfuaoyZaU_vWwlAEpQ?usp=sharing

## Requirements
- Windows
- Visual Studio (π.χ. 2019/2022)
- SGG headers: `graphics.h`, `scancodes.h` (όπως δίνεται στο μάθημα)

## Build / Run (Visual Studio)
1. Άνοιξε το `.sln`
2. Build σε `Debug` ή `Release`
3. Τρέξε το παιχνίδι
4. Βεβαιώσου ότι ο φάκελος `assets` βρίσκεται δίπλα στο `.exe` (δηλ. `.\assets`)

## Controls (ενδεικτικά)
- A/D ή ←/→ : κίνηση
- Space : άλμα
- Esc : έξοδος / pause (αν υπάρχει)

## Project Structure (ενδεικτικά)
- `GameObject` (base class): `init()`, `update(dt)`, `draw()`
- `GameState`: κεντρική ροή παιχνιδιού, levels, score, πρόσβαση σε player κλπ.
- `Player`, `Enemy`, `Level`, `UI` ως derived κλάσεις

## Links
- Full project (source): (βάλε το link)
- Executable (exe): (βάλε το link)
- Gameplay video: (βάλε το link)
- Assets: (βάλε το link)

## Notes
Αν τα assets δεν περιλαμβάνονται στο zip λόγω μεγέθους, υπάρχει αρχείο `assets_link.txt`
με σύνδεσμο και σχετικό path `.\assets`.
