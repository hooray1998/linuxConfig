# dnf
> Package management utility for RHEL, Fedora, and CentOS (replaces yum)
- **Install a new package:**
sudo dnf install `package`
- **Install a new package and assume yes to all questions:**
sudo dnf -y install `package`
- **Remove a package:**
sudo dnf remove `package`
- **Upgrade installed packages to newest available versions:**
sudo dnf upgrade
- **List installed packages:**
dnf list --installed
- **Search packages via keyword:**
sudo dnf search `keyword`
- **Find which packages provide a given value:**
sudo dnf provides `value`
