# Raspi Newbie
Docs for Raspberry Pi newbies.

## Headless Setup

### Setup Wi-Fi
Edit `/etc/wpa_supplicant/wpa_supplicant.conf` to add the below Wi-Fi config.
```
network={
  ssid="network-ssid-name"
  psk="network-password"
}
```
