# 📷 MATLAB Aplikacija za obradu slika

## 📌 Opis projekta
Ovaj projekat predstavlja **MATLAB aplikaciju za obradu digitalnih slika** koristeći **App Designer** i **Image Processing Toolbox**.  
Cilj je da korisnicima omogući intuitivno istraživanje različitih tehnika obrade slike kroz interaktivni GUI i vizuelnu demonstraciju efekata algoritama.

---

## ✅ Uključeni algoritmi i fajlovi

### 🧩 Glavni delovi aplikacije
- **home.mlapp** – početna stranica aplikacije, vodi korisnika do izbora filtera i algoritama  
- **filterChooserApp.mlapp** – stranica na kojoj korisnik bira koji algoritam ili filter želi da primeni na sliku  

### 🧩 Algoritmi
- **Bin.mlapp** – binarna segmentacija slike (thresholding)  
- **GaussianApp.mlapp** – primena Gaussovog filtera za uklanjanje šuma i zaglađivanje slike  
- **HarrisApp.mlapp** – Harris algoritam za detekciju ivica i uglova  

### 🖼 Primeri slika
- **persijska-macka.jpg** – test primer slike  
- **c3-.jpg** – dodatni primer slike za demonstraciju  

---

## 🎯 Funkcionalnosti aplikacije
Korisnik može:  
- ✔ Učitati sliku (JPG, PNG, BMP)  
- ✔ Odabrati algoritam ili filter za obradu slike (sa stranice `filterChooserApp.mlapp`)  
- ✔ Vizuelno uporediti originalnu i obrađenu sliku  
- ✔ Sačuvati rezultat obrade na svom računaru  

### 🔹 Specifične funkcije algoritama
- **Binarna segmentacija (Bin.mlapp)** – razdvaja objekte od pozadine  
- **Gaussian filter (GaussianApp.mlapp)** – uklanja šum i zaglađuje sliku  
- **Harris corner detection (HarrisApp.mlapp)** – detekcija ivica i uglova  

---

## ⚙️ Tehnologije
- **MATLAB** (preporučena verzija R2022b ili novija)  
- **Image Processing Toolbox**  
- **App Designer** za kreiranje GUI aplikacija  

---

## 🚀 Pokretanje aplikacije
1. Otvorite projekat u **MATLAB-u**.  
2. Pokrenite `home.mlapp` – početnu stranicu aplikacije.  
3. Sa početne stranice otvorite `filterChooserApp.mlapp`, gde se bira željeni algoritam ili filter.  
4. Učitajte željenu sliku (npr. `persijska-macka.jpg`) i primenite obradu.  
5. Posmatrajte rezultate u realnom vremenu i uporedite efekat različitih algoritama i filtera.  

---


