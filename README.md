# Arch Linux – Практическо ръководство

Практическо ръководство за Arch Linux на български език.

## Съдържание
- Инсталация на Arch Linux
- Конфигурация на системата
- Графични среди
- Основни команди и работа със системата
- Приложение А: Arch User Repository (AUR)
- Приложение B: System Maintenance в Arch Linux
- Приложение C: Btrfs snapshots и Timeshift
- Приложение D: Backups и възстановяване
- Приложение E: UEFI Secure Boot

## Build (PDF)
```bash
pandoc "archlinux-практическо ръководство.md" --pdf-engine=xelatex --include-in-header=preamble.tex --include-before-body=titlepage.tex -V documentclass=book -V classoption=oneside -V top-level-division=chapter -V papersize=A5 -V geometry:margin=2.5cm -o Arch_Linux_Prak_Rakovodstvo_BG.pdf

