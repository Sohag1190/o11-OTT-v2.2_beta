
---

# O11 OTT v2.2 Beta  ![Badge](https://hitscounter.dev/api/hit?url=https%3A%2F%2Fgithub.com%2FSohag1190%2Fo11-OTT-v2.2_beta&label=Vistors&icon=github&color=%23198754&message=&style=flat&tz=UTC)

**O11 OTT v2.2_b1 Streamer – Patched Free Release**

This repository provides a patched version of the O11 OTT v2.2_b1 streamer, making it freely available for testing and deployment. It is forked from DRMStuff/o11-OTT-v2.2b1 [(github.com in Bing)](https://www.bing.com/search?q="https%3A%2F%2Fgithub.com%2FDRMStuff%2Fo11-OTT-v2.2b1").

---

## Features
- Patched O11 OTT v2.2_b1 streamer
- Ready-to-run binary (`o11_v22b1-DRMStuff`)
- Systemd service file (`o11_v2.service`) for automated execution
- Free and open distribution for community use

---

## Installation

Clone the repository:
```bash
git clone https://github.com/Sohag1190/o11-OTT-v2.2_beta
cd o11-OTT-v2.2_beta
```

Make the binary executable:
```bash
chmod +x o11_v22b1-DRMStuff
```

Run the streamer:
```bash
./o11_v22b1-DRMStuff
```

---

## Systemd Service Setup

To run automatically via systemd:

1. Copy the service file:
   ```bash
   sudo cp o11_v2.service /etc/systemd/system/
   ```

2. Reload systemd:
   ```bash
   sudo systemctl daemon-reload
   ```

3. Enable and start the service:
   ```bash
   sudo systemctl enable --now o11_v2.service
   ```

4. Check status:
   ```bash
   sudo systemctl status o11_v2.service
   ```

---

## Repository Contents
- `README.md` – Documentation
- `o11_v2.service` – Systemd unit file
- `o11_v22b1-DRMStuff` – Patched streamer binary

---

## Notes
- This release is intended for testing and educational purposes.
- Contributions and forks are welcome.
- No official releases or packages are published yet.



