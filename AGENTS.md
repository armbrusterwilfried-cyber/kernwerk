# Kernwerk Entwicklungsregeln

- Projekt: natives x86_64-UEFI-Betriebssystem
- Aktueller Ausgangspunkt: Stage42900 Framebuffer Guard
- Änderungen müssen reproduzierbar gebaut und dokumentiert werden.
- Keine Funktion als produktiv bezeichnen, solange sie nicht gebaut und getestet wurde.
- Bootkritische Änderungen benötigen serielle Diagnosemarken und einen QEMU/OVMF-Smoke-Test.
- Schutzvermerk in Projektdateien: Wilfried A.
