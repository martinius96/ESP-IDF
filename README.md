# ESP-IDF - príkazy
* **idf.py menuconfig** - konfiguracia projektu - vstupnych parametrov, SSID...
* **idf.py build** - vytvor build všetkých projektov + bootloader, partition table
* **idf.py build app** - vytvor build projektu (aktuálny adresár)
* **idf.py app-flash** - rebuild appky a vypalenie ak sa zmenili zdrojove subory
* **idf.py app** - vytvor build projektu (aktuálny adresár)
* **idf.py -p PORT flash** - vypaliť projekt na port
* **idf.py app-flash** - vypaliť iba aplikaciu (bez bootloadera, partition table)
* **idf.py monitor** - serial monitor
* **idf.py flash monitor** - vypaliť projekt + monitor
* **idf.py erase_flash** - vymazanie flash pamäte
* **idf.py -p PORT erase_flash flash** - vymazanie flash pamäte + nove vypalenie 
