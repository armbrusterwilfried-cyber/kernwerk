# Kernwerk Roadmap

## Aktuelle Basis

- Stage42900 Framebuffer Guard
- UEFI-x86_64
- GOP-Desktop und Framebuffer-Prüfungen
- UEFI-Dateisystem-Selbsttest
- UEFI-Netzwerkerkennung und NetMon-Grundlage

## Phase 1: Reproduzierbare Entwicklungsbasis

- [ ] Stage42900-Quellbaum vollständig importieren
- [ ] reproduzierbares Buildskript
- [ ] QEMU/OVMF-Smoke-Test
- [ ] CI-Artefakte mit SHA-256
- [ ] serielle Bootmarken als Testvertrag

## Phase 2: Kernel-Grundlagen

- [ ] ExitBootServices und eigene Laufzeitumgebung
- [ ] Physical Memory Manager
- [ ] Virtual Memory Manager
- [ ] Interrupts, APIC/x2APIC und Timer
- [ ] präemptiver Scheduler
- [ ] SMP-Start weiterer CPUs

## Phase 3: Geräte und Speicher

- [ ] PCI/PCIe-Konfiguration
- [ ] MMIO, DMA und IRQ-Abstraktionen
- [ ] AHCI
- [ ] NVMe
- [ ] USB-Grundstack
- [ ] VFS und Mount-Modell

## Phase 4: Netzwerk

- [ ] Ethernet-Treiber mit Realtek-Schwerpunkt
- [ ] ARP, IPv4 und ICMP
- [ ] DHCP und DNS
- [ ] UDP und TCP
- [ ] TLS und HTTPS

## Phase 5: Desktop und Userland

- [ ] Prozessmodell und Usermode
- [ ] Fensterverwaltung und echtes Multitasking
- [ ] Dateimanager und Drag-and-Drop
- [ ] Browser-Grundlage
- [ ] Audio, Video und Bildformate

Jeder Punkt gilt erst als abgeschlossen, wenn Build, Test und Dokumentation im Repository vorhanden sind.

Schutzvermerk: Wilfried A.
