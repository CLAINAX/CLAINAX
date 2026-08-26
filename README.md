

* 🔭 I’m currently working on my server's environment (through Tailscale)

<img width="506" height="452" alt="Screenshot_20260408_185607" src="https://github.com/user-attachments/assets/86c8d4e4-817d-44bc-a3fc-9a54b4a8665f" />
<img width="1785" height="588" alt="Screenshot_20260408_185718" src="https://github.com/user-attachments/assets/e59a64f8-bac1-4124-b945-1f6af1eb5a84" />



* 🌱 I’m currently learning AI optimizing stuff

* UPDATE 03/06/2026
  * Implementation of 2 nvidia p4000
  * Joplin service (to link notes)
  * Cryptomator's mnemonic password implemented on Nextcloud
  * Builed in mnemonic password from Nextcloud's enabled
  * Doom added into Nextcloud's users



* UPDATE 02/07/2026
  * Implemented 2x NVIDIA RTX 5060 Ti (16 GB each).

  * Set up gaming service room with VPN-connected consoles.

  * AI automation via n8n, integrating Anthropic, Ollama, an SQL database, Gmail, and WhatsApp.

  * Deployed a self-hosted LanguageTool server.
  
  * Added level 2 in Python's game.
<img width="1567" height="916" alt="image" src="https://github.com/user-attachments/assets/ecd65ece-9854-4a01-89d5-f5962dc97d10" />
<img width="892" height="537" alt="image" src="https://github.com/user-attachments/assets/c846b35c-f550-4863-89b6-1cf662a8c079" />
<img width="892" height="508" alt="image" src="https://github.com/user-attachments/assets/8a1bd813-e71c-4569-a733-3b91002ab41e" />
<img width="987" height="633" alt="image" src="https://github.com/user-attachments/assets/bd2c650e-085a-4530-88ce-196b988165c3" />
<img width="542" height="447" alt="image" src="https://github.com/user-attachments/assets/38a463fa-2b88-47ad-bb62-9abf774632dd" />



* UPDATE - 2026-08-26
 * Hardware & AI
     * Merged 2x NVIDIA RTX 5060 Ti for local AI coding/debugging (qwen2.5-coder:32b-instruct-q4_K_M, 32.8B) via Ollama. VRAM load is split to minimize PCIe 4.0 x4 bottlenecks, achieving ~20 tokens/sec.
 
     * Removed server case for better airflow.

 * Virtualization & APIs
     * Added WhisperVM to run Quadro P4000 drivers and patch NVIDIA's NVENC limits (unlocking unlimited concurrent video encoding streams).

 * OS: Ubuntu Server 24.04 LTS

     * CPU / RAM: 2 vCPU / 3 GB

     * Storage: 30 GB .qcow2

     * GPU: 1x NVIDIA Quadro P4000 (Exclusive PCI Passthrough)

     * Network: Default virtual network (accessible via local IP/SSH)

     * Access: VNC (port 5999) and serial console

     * Added FastAPI interface linking the VM service with ElevenLabs voices.

 * Security & Access
     * Hardened security: closed open backdoors and integrated Authentik.

     * Configured advanced mnemonic access tokens for all ComfyUI users.

 * Self-Hosted Services
     * Added utility services: Bitwarden, Paperless, Stirling PDF, and IT-Tools.

     * Deployed and automated media stack: Jellyfin, Radarr, Sonarr, Jellyseerr, Bazarr, qBittorrent, and Prowlarr.
  
* 📫 How to reach me: eric.esquirolj4@gmail.com
