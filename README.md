# kasz

## Jak wysłać projekt komuś, kto nie ma konta na GitHub / How to share the project with someone who doesn't have a GitHub account

Poniżej znajdziesz kilka sposobów na udostępnienie tego projektu bez konieczności posiadania konta na GitHub.
Below are several ways to share this project without requiring a GitHub account.

---

### Sposób 1: Pobierz jako ZIP ze strony GitHub / Download as ZIP from GitHub

1. Wejdź na stronę repozytorium: `https://github.com/dnajindaio/kasz`
2. Kliknij zielony przycisk **Code** (Kod) w prawym górnym rogu.
3. Wybierz **Download ZIP**.
4. Prześlij pobrany plik `.zip` odbiorcy przez e-mail, Dysk Google, WeTransfer lub inny serwis wymiany plików.

---

1. Go to the repository page: `https://github.com/dnajindaio/kasz`
2. Click the green **Code** button in the top-right corner.
3. Select **Download ZIP**.
4. Send the downloaded `.zip` file to the recipient via email, Google Drive, WeTransfer, or any other file-sharing service.

---

### Sposób 2: Utwórz archiwum lokalnie (git archive) / Create an archive locally (git archive)

Jeśli masz repozytorium sklonowane na swoim komputerze, możesz wygenerować archiwum ZIP za pomocą Gita:

```bash
git archive --format=zip --output=kasz.zip HEAD
```

Plik `kasz.zip` zostanie utworzony w bieżącym katalogu. Prześlij go odbiorcy.

---

If you have the repository cloned locally, you can generate a ZIP archive using Git:

```bash
git archive --format=zip --output=kasz.zip HEAD
```

A `kasz.zip` file will be created in the current directory. Send it to the recipient.

---

### Sposób 3: Skopiuj pliki ręcznie / Copy files manually

Możesz również skopiować pliki projektu do nowego folderu i skompresować go do `.zip` za pomocą eksploratora plików (Windows/macOS/Linux), a następnie przesłać plik.

---

You can also copy the project files into a new folder, compress it into a `.zip` using your file explorer (Windows/macOS/Linux), and send the resulting file.

---

### Sposób 4: Serwisy do przesyłania plików / File-sharing services

Jeśli plik jest duży, możesz skorzystać z jednego z poniższych serwisów do bezpłatnego przesłania pliku:

- [WeTransfer](https://wetransfer.com/) — do 2 GB za darmo, bez rejestracji
- [Google Drive](https://drive.google.com/) — wymaga konta Google
- [Dropbox](https://www.dropbox.com/) — wymaga konta Dropbox
- [send.vis.ee](https://send.vis.ee/) — szyfrowany, bez rejestracji

---

If the file is large, you can use one of the following free file-sharing services:

- [WeTransfer](https://wetransfer.com/) — up to 2 GB for free, no registration needed
- [Google Drive](https://drive.google.com/) — requires a Google account
- [Dropbox](https://www.dropbox.com/) — requires a Dropbox account
- [send.vis.ee](https://send.vis.ee/) — encrypted, no registration needed
