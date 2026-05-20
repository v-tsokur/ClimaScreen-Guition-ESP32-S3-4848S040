# Guition ESP32-S3 4848S040 Climate Panel

Minimal ESPHome/LVGL firmware for the Guition ESP32-S3 4848S040 display.

This project has been trimmed down to a single climate-control page. All other pages, widgets, translations, documentation images, and unused visual assets have been removed.
Based on Copyright (c) 2024 Alexey Titov

## Configuration

- Main entry point: `src/main.yaml`
- Climate widget: `src/widgets/climate/climate.yaml`
- Display name, climate entity, and shared icons: `src/common/substitutions.yaml`

Update `climate_entity` in `src/common/substitutions.yaml` to match your Home Assistant climate entity.
