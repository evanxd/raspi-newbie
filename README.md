# Raspi Newbie
Docs for Raspberry Pi newbies.

## Headless Setup

### Setup Wi-Fi
Edit `/etc/wpa_supplicant/wpa_supplicant.conf`[1] to add the below Wi-Fi config.
```
network={
  ssid="network-ssid-name"
  psk="network-password"
}
```

[1]: http://blog.self.li/post/63281257339/raspberry-pi-part-1-basic-setup-without-cables
