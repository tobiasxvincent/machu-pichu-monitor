# machu-pichu-monitor
Machu Picchu Circuit 2B availability monitor
name: Machu Picchu Monitor

on:

  workflow_dispatch:

  schedule:

    - cron: "7,22,37,52 * * * *"

jobs:

  monitor:

    runs-on: ubuntu-latest

    steps:

      - name: Test

        run: |

          echo "Machu Picchu Monitor läuft!"

          echo "Gesucht wird:"

          echo "3 Personen"

          echo "Circuit 2B"

          echo "16.–19. Oktober 2026"