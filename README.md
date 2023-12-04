# Spiritul Crăciunului și de asemenea Anul Nou)
##### „Te-ai săturat să fii nevoit să scrii și să trimiți manual texte de Crăciun tuturor de Crăciun pentru a menține o relație bună cu ei? Vrei să fii persoana enervantă care este prima care trimite „La mulți ani” mesaje tuturor celor de pe lista ta de contacte exact la miezul nopții? Vrei să fii un băiat rău în acest sezon de Crăciun? Te-am acoperit."
  
Inspirat puternic de celălalt proiect, prezentând ***Spărgătorul de spirit de Crăciun***, un script python care trimite automat un mesaj personalizat de felicitare de Crăciun/Anul Nou, dintr-o listă de mesaje personalizată, la contactele selectate cu care doriți să mențineți relații bune, la un interval de timp dat pe Facebook Messenger, WhatsApp, Telegram sau prin SMS. E timpul să fim băieți răi de Crăciun. *Lucrează mai inteligent, nu mai greu.*

### Ce vei câștiga:
   - Mai mult timp petrecut cu noua pernă de corp pe care tocmai ai primit-o de Crăciun.
   - Mai mult timp petrecut furând șampania de Anul Nou de la oameni care sunt ocupați să-și trimită mesaje mesaje prietenilor.
   - Mențineți acele relații cu prietenii (dacă nu trimiteți felicitări la astfel de evenimente, ei vor ști că nu sunteți un prieten adevărat)
   - Magie

---
# Facebook Messenger:
### Instalare pe PC

Moș Crăciun se bazează pe reni pentru livrare, la fel și Christmas Spirit Breaker se bazează pe câteva lucruri, iată ce trebuie să faceți pentru a-i obține:
- Este necesar Python3, obțineți-l de [aici](https://www.python.org/downloads/)

###### Pentru Linux:
Rulați aceste comenzi în aplicația de terminal preferată
```sh
sudo apt-get install python3-pip
pip3 instalează fbchat bs4
clona git https://github.com/lorcalhost/ChristmasSpiritBreaker-andNewYearsToo.git
```
###### Pentru Windows
- Instalați și git de [aici](https://git-scm.com/download/win)
- Asigurați-vă că rulați toate comenzile din git
```sh
pip install fbchat bs4
clona git https://github.com/lorcalhost/ChristmasSpiritBreaker-andNewYearsToo.git
```

### Instalare pe Android
De pe *Android* vei putea rula doar versiunea Facebook Messenger, iată instrucțiunile:
- Mai întâi descărcați și instalați [Termux din Google Play Store](https://play.google.com/store/apps/details?id=com.termux)
- Apoi executați următoarele comenzi:
- ```termux-setup-storage``` și permiteți accesul la stocare
```sh
stocare CD/descărcări
pkg instalează python3 git
pip3 instalează fbchat solicită bs4 enum
clona git https://github.com/lorcalhost/ChristmasSpiritBreaker-andNewYearsToo.git
```
Vă rugăm să rețineți că de fiecare dată când reporniți dispozitivul, va trebui să rulați din nou comenzile din secțiunea *Cum se rulează*

---

# Telegramă:
### Instalare pe PC

Moș Crăciun se bazează pe reni pentru livrare, la fel și Christmas Spirit Breaker se bazează pe câteva lucruri, iată ce trebuie să faceți pentru a-i obține:
- Este necesar Python3, obțineți-l de [aici](https://www.python.org/downloads/)

###### Pentru Linux:
Rulați aceste comenzi în aplicația de terminal preferată
```sh
sudo apt-get install python3-pip
pip3 instalează telethon bs4
clona git https://github.com/lorcalhost/ChristmasSpiritBreaker-andNewYearsToo.git
```
###### Pentru Windows
- Instalați și git de [aici](https://git-scm.com/download/win)
- Asigurați-vă că rulați toate comenzile din git
```sh
pip install telethon bs4
clona git https://github.com/lorcalhost/ChristmasSpiritBreaker-andNewYearsToo.git
```

### Instalare pe Android
De pe *Android* vei putea rula doar versiunea Facebook Messenger, iată instrucțiunile:
- Mai întâi descărcați și instalați [Termux din Google Play Store](https://play.google.com/store/apps/details?id=com.termux)
- Apoi executați următoarele comenzi:
- ```termux-setup-storage``` și permiteți accesul la stocare
```sh
stocare CD/descărcări
pkg instalează python3 git
pip install fbchat solicită bs4 enum
clona git https://github.com/lorcalhost/ChristmasSpiritBreaker-andNewYearsToo.git
```
Vă rugăm să rețineți că de fiecare dată când reporniți dispozitivul, va trebui să rulați din nou comenzile din secțiunea *Cum se rulează*

---

# WhatsApp și SMS
### Instalare pe PC

Moș Crăciun se bazează pe reni pentru livrare, la fel și Christmas Spirit Breaker se bazează pe câteva lucruri, iată ce trebuie să faceți pentru a-i obține:
- Este necesar Python3, obțineți-l de [aici](https://www.python.org/downloads/)
- Chrome Driver obțineți-l de pe [aici](https://chromedriver.storage.googleapis.com/index.html?path=2.44/) și dezarhivați în folderul ```ChristmasSpiritBreaker-andNewYearsToo```
- Dacă doriți să configurați SMS-uri, va trebui să aveți [mesaje Google](https://play.google.com/store/apps/details?id=com.google.android.apps.messaging) pe telefonul dvs. Android

###### Pentru Linux:
Rulați aceste comenzi în aplicația de terminal preferată
```sh
sudo apt-get install python3-pip xclip
sudo pip3 instalează selenium bs4 pyperclip
clona git https://github.com/lorcalhost/ChristmasSpiritBreaker-andNewYearsToo.git
```
###### Pentru Windows
- Instalați și git de [aici](https://git-scm.com/download/win)
- Asigurați-vă că rulați toate comenzile din git
```sh
pip install selenium bs4 pyperclip
clona git https://github.com/lorcalhost/ChristmasSpiritBreaker-andNewYearsToo.git
```
##### Modul SMS nu este recomandat, este lent și cu probleme din cauza naturii Google Messages

---

# Cum să alergi
Mai întâi accesați directorul programului tastând în terminal:
- De pe **PC:** ```cd ChristmasSpiritBreaker-andNewYearsToo```
- Din **Android:** ```stocare CD/descărcări/ChristmasSpiritBreaker-andNewYearsToo```

Apoi rulați scriptul cu argumentul corespunzător:
- Pentru **versiunea WhatsApp**: ```python3 christmasSpiritBreaker.py -w``` sau ```python3 christmasSpiritBreaker.py whatsapp```
- Pentru **versiunea Messenger**: ```python3 christmasSpiritBreaker.py -m``` sau ```python3 christmasSpiritBreaker.py messenger```
- Pentru **versiunea SMS**: ```python3 christmasSpiritBreaker.py -s``` sau ```python3 christmasSpiritBreaker.py sms```
- Pentru **Versiunea Telegram**: ```python3 christmasSpiritBreaker.py -t``` sau ```python3 christmasSpiritBreaker.py telegram```

De asemenea, există și alte argumente precum:
- Pentru a deschide **ghidul utilizatorului**: ```python3 christmasSpiritBreaker.py -h``` sau ```python3 christmasSpiritBreaker.py help``` sau ```python3 christmasSpiritBreaker.py man```
- Pentru a **actualiza** scriptul: ```python3 christmasSpiritBreaker.py update```

**Pentru utilizatorii *Android*:** va trebui, de asemenea, să apăsați ```"ACQUIRE WAKELOCK"``` în notificarea Termux pentru a permite rularea scriptului în fundal fără ca procesul să fie oprit
***Momentan Android acceptă doar modul Facebook Messenger***
---

# Mesaje personalizate/contacte/configurare oră
Utilizatorii ***Android** ar putea dori să editeze fișierul ```config.py``` cu aplicația lor preferată de editare a textului, deoarece fișierul va fi în dosarul Descărcări al dispozitivelor lor*
  
Pur și simplu deschideți fișierul ```config.py``` cu aplicația de editare a textului preferată și urmați instrucțiunile de acolo, cred că le-am clarificat suficient

Dacă nu doriți să utilizați botul atât pentru Crăciun, cât și pentru Anul Nou, puteți dezactiva faturile individual, setând liniile la ```False```
```python
christmasModeEnabled = Adevărat # Schimbați în Fals pentru a dezactiva modul Crăciun
newYearsModeEnabled = Adevărat # Schimbați în Fals pentru a dezactiva modul de Anul Nou
```
###### Dacă tot nu puteți înțelege din fișierul config.py..
## Mesaje personalizate:


Înlocuiți mesajele dintre ```" "``` cu propriile dvs. mesaje personalizate, puteți adăuga și mai multe mesaje personalizate adăugând după ```"``` din ultimul mesaj o virgulă și un mesaj nou, întotdeauna în între ```" "```s.
Dacă vrem să adăugăm ```Mesaj personalizat nou``` la lista de mai jos
```python
christmas_messages = [„Crăciun Fericit!”]
```
Trebuie doar să o edităm astfel:
```python
christmas_messages = [„Crăciun fericit!”, „Mesaj personalizat nou”]
```
## Contacte personalizate:
**Important:**
  - Asigurați-vă că, dacă configurați contacte **WhatsApp** sau contacte **SMS**, le scrieți numele **așa cum apar în lista de contacte a telefonului**
  - Dacă utilizați **Messenger**, utilizați **numele de utilizator** messenger al contactului dvs.

Înlocuiți numele de contact între ```" "``` cu numele dvs. personalizate de contact, puteți adăuga, de asemenea, mai multe persoane de contact personalizate, adăugând după ```"``` ultimul contact o virgulă și un contact nou, întotdeauna între ```" "```s.
Dacă vrem să adăugăm ```Moș Crăciun``` la lista de mai jos
```python
christmas_contact_names = [„John McAfee”]
```
Trebuie doar să o edităm astfel:
```python
christmas_contact_names = [„John McAfee”, „Moș Crăciun”]
```
## Interval de timp personalizat:
**Mesajele de Crăciun** vor fi trimise pe *25 decembrie*
Mesajele de **Anul Nou** vor fi trimise pe *1 ianuarie*

Dacă vrem să schimbăm intervalul de timp de Crăciun, trebuie să edităm această linie:
```python
christmas_time_interval = ["08:00", "23:59"]
```
Dacă vrem să schimbăm intervalul de timp al anului nou, trebuie să edităm această linie:
```python
newYears_time_interval = ["00:00", "00:15"]
```

Asigurați-vă că **ora** este întotdeauna **două cifre**

## Configurare API Telegram
- Conectați-vă la nucleul dvs. Telegram: https://my.telegram.org.
- Accesați „Instrumente de dezvoltare API” și completați formularul.
- Creați o aplicație
- Veți obține parametrii `api_id` și `api_hash` necesari pentru autorizarea utilizatorului (pentru a pune în fișierul config.py).
---
**Dacă aveți probleme cu configurarea, nu ezitați să-mi trimiteți un mesaj pe whatsapp (![image](https://github.com/GrupulVerdeIT/Trimite-automat-mesaje-de-Cr-ciun-Anul-Nou-/assets/110493446/18524aff-ba1d-4cac-938d-e83aebe21970)
)**
