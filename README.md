# 📷 MATLAB Aplikacija za Obradu Slika

## 📌 Opis projekta
Ovaj projekat predstavlja **MATLAB aplikaciju za obradu digitalnih slika** koristeći **App Designer** i **Image Processing Toolbox**.  
Cilj je da korisnicima omogući intuitivno istraživanje različitih tehnika obrade slike kroz interaktivni GUI i vizuelnu demonstraciju efekata algoritama.

---

## ✅ Uključeni algoritmi i fajlovi

### 🧩 Algoritmi / aplikacije
- **Bin.mlapp** – binarna segmentacija slike (thresholding)  
- **GaussianApp.mlapp** – primena Gaussovog filtera za uklanjanje šuma i zaglađivanje slike  
- **HarrisApp.mlapp** – Harris algoritam za detekciju ivica i uglova  
- **filterChooserApp.mlapp** – omogućava izbor i kombinovanje različitih filtera na slici  
- **home.mlapp** – glavni meni aplikacije koji vodi do svih algoritama  

### 🖼 Primeri slika
- **persijska-macka.jpg** – test primer slike  
- **c3-.jpg** – dodatni primer slike za demonstraciju  
- **untitled.png** – još jedan primer korišćen u testiranju  

---

## 🎯 Funkcionalnosti aplikacije
Korisnik može:  
- ✔ Učitati sliku (JPG, PNG, BMP)  
- ✔ Odabrati algoritam za obradu slike  
- ✔ Vizuelno uporediti originalnu i obrađenu sliku  
- ✔ Sačuvati rezultat obrade na svom računaru  

### 🔹 Specifične funkcije algoritama
- **Binarna segmentacija (Bin.mlapp)** – razdvaja objekte od pozadine  
- **Gaussian filter (GaussianApp.mlapp)** – uklanja šum i zaglađuje sliku  
- **Harris corner detection (HarrisApp.mlapp)** – detekcija ivica i uglova  
- **Filter Chooser (filterChooserApp.mlapp)** – omogućava kombinovanje različitih filtera i parametara  

---

## ⚙️ Tehnologije
- **MATLAB** (preporučena verzija R2022b ili novija)  
- **Image Processing Toolbox**  
- **App Designer** za kreiranje GUI aplikacija  

---

## 🚀 Pokretanje aplikacije
1. Otvorite projekat u **MATLAB-u**.  
2. Pokrenite `home.mlapp` u App Designer-u.  
3. Odaberite algoritam koji želite da testirate (Bin, Gaussian, Harris, Filter Chooser).  
4. Učitajte željenu sliku (npr. `persijska-macka.jpg`) i primenite obradu.  
5. Posmatrajte rezultate u realnom vremenu i uporedite efekat različitih filtera.  
