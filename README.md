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

## Pinout
![Raspi Pinout](https://camo.githubusercontent.com/d9f1750573f26ed2de3274333560b0430dbd3405/68747470733a2f2f7777772e656c656d656e7431342e636f6d2f636f6d6d756e6974792f736572766c65742f4a697665536572766c65742f70726576696577426f64792f37333935302d3130322d31302d3333393330302f7069335f6770696f2e706e67)

[1]: http://blog.self.li/post/63281257339/raspberry-pi-part-1-basic-setup-without-cables
