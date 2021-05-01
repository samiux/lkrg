# Linux Kernel Runtime Guard (LKRG) Install Script

## Download scripts

```bash
sudo apt install git
git clone https://github.com/samiux/lkrg
cd lkrg
```

## Install Version 0.9.1 for Ubuntu 20.04 LTS

```bash
sudo chmod +x lkrg-0.9.1-install
sudo ./lkrg-0.9.1-install
```

## Uninstall Version 0.9.1 for Ubuntu 20.04 LTS

```bash
sudo chmod +x lkrg-0.9.1-uninstall
sudo ./lkrg-0.9.1-uninstall
```

## Stop LKRG

```bash
sudo systemctl stop lkrg
```

## Start or Restart LKRG

```bash
sudo systemctl start lkrg

sudo systemctl restart lkrg
```

## Known Issues

- Nil  

## Reference 

- [LKRG - Linux Kernel Runtime Guard -- Openwall (Developer)](https://www.openwall.com/lkrg/)  
- [LKRG - Linux Kernel Runtime Guard -- GitHub](https://github.com/openwall/lkrg)  
- [Linux Kernel Runtime Guard -- LinuxReviews](https://linuxreviews.org/Linux_Kernel_Runtime_Guard)  
- [Linux Kernel Runtime Guard 0.9.1 Is Released -- LinuxReviews](https://linuxreviews.org/Linux_Kernel_Runtime_Guard_0.9.1_Is_Released)  
