---
layout: post
title: "Starcie z rzeczywistością: 17 Mb/s u dziadków kontra mój domowy stack sieciowy"
---

![Test łącza - Speedtest](/assets/images/image_b23fe7.png)

Wyjazd w teren to zawsze brutalny test dla moich przyzwyczajeń. Na co dzień w moim homelabie korzystam z dobrodziejstw **Unbound** i **Pi-hole**, co sprawia, że internet "po prostu działa" szybko i bez reklam. U dziadków zderzyłem się z łączem 17 Mb/s i standardowymi DNS-ami dostawcy.

### Moje obserwacje:

* **Opóźnienia (Latency):** Bez lokalnego cache'owania zapytań DNS, każda strona ładowała się o sekundy wolniej. To uświadamia, jak ogromną robotę robi Unbound w domowej sieci.
* **Czystość sieci:** Brak Pi-hole'a przypomniał mi, jak agresywne potrafią być dzisiejsze reklamy, które na słabym łączu dodatkowo pożerają cenne pasmo.
* **Docenić swoje:** Ten wyjazd to najlepsze potwierdzenie, że czas poświęcony na konfigurację własnej infrastruktury sieciowej nie jest czasem straconym.

### Wnioski:

Możesz mieć światłowód, ale bez optymalizacji po stronie DNS i tak nie wykorzystasz jego potencjału. Wracam do domu z jeszcze większym zapałem do tuningu moich kontenerów.

![Wykres zapytań DNS](/assets/images/image_b23fed.png)
