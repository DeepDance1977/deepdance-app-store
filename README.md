# DeepDance App Store

Eigener Community-App-Store für Umbrel und 5tratumOS mit Apps von DeepDance:

- **`deepdance-dashboard`** – BSV Solo Mining Dashboard (Web-Dashboard für Bitcoin-SV-Node und Solo-Mining)
- **`deepdance-bitcoin-sv`** – Bitcoin SV Full Node (sauberer arm64-Node-Build)

## Einrichtung (5tratumOS / Umbrel)

1. In den Einstellungen deines 5tratumOS/Umbrel-Systems unter
   **"App Store" → "Community App Store hinzufügen"**
2. Diese Repo-URL eintragen:
   `https://github.com/DeepDance1977/deepdance-app-store`
3. Die Apps erscheinen danach im App Store zur Installation.

Alternativ per CLI auf dem Pi:
```bash
sudo ~/umbrel/scripts/repo add https://github.com/DeepDance1977/deepdance-app-store.git
sudo ~/umbrel/scripts/repo update
sudo ~/umbrel/scripts/app install deepdance-bitcoin-sv
sudo ~/umbrel/scripts/app install deepdance-dashboard
```
