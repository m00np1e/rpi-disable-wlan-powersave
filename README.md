# Disable RPI wlan0 powersave on boot

To disable on boot you need to save the script in:
```/etc/network/if-up.d/wlan_powersave_off```

Set exec permissions:
```chmod +x /etc/network/if-up.d/wlan_powersave_off```
