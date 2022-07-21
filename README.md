# kiosk-service
how to make a raspberry pi go into "kiosk mode"

automatically start chrome in fullscreen on restart, showing `http://localhost:8765` (changable in `kiosk.sh`)

# setup


 - `cp _lib_systemd_system_kiosk.service`
 - `service kiosk start`
 - done.
