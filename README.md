# Arch Linux – Практическо ръководство

Практическо ръководство за Arch Linux на български език.

## Съдържание
- Инсталация
- Конфигурация
- Графични среди
- Основни команди и работа със системата
- Приложение А: Arch User Repository (AUR)
- Приложение B: System Maintenance в Arch Linux
- Приложение C: Backups и възстановяване

## Build (PDF)
```bash
pandoc 'archlinux-практическо ръководство.md' --include-before-body=titlepage.tex --include-in-header=preamble.tex --pdf-engine=xelatex -V documentclass=book -o 'archlinux-практическо ръководство.pdf'

