# Arch Linux basic commands - pacman
## Search in database for a specific package
```bash
pacman -Ss <package_name>
```

## Install sepecfic package
```bash
sudo pacman -Ss <package_name>
```

## Update specfici package
```bash
sudo pacman -S <package_name>
```

## Update existing packages
```bash
sudo pacman -Syu
```

## Update existing packages force
```bash
sudo pacman -Syyu
```

## Remove specific package
```bash
sudo pacman -R <package_name>
```

## Search for a specific package on you computer or installed
```bash
pacman -Qi <package name>
```

## Show all installed packages
```bash
pacman -Q
```