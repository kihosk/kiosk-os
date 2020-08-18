# test-ansible

## Prepare kiosk device
```bash
sudo ansible-pull --url https://github.com/kihosk/kiosk-os prepare.yml
```

## Update kiosk device to latest from master
```bash
sudo ansible-pull --url https://github.com/kihosk/kiosk-os update.yml
```

## Update kiosk device to certain tag
```bash
sudo ansible-pull --url https://github.com/kihosk/kiosk-os update.yml -C <tagname>
sudo ansible-pull --url https://github.com/kihosk/kiosk-os update.yml -C v0.0.51

```
