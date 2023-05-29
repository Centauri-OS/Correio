# **Introducing**
## "Hermes" is a package manager used in the Centauri-OS distribution. It is made in POSIX Shell, open-source, and completely free.
# **Why Hermes?**
## Hermes was the messenger of the gods in Greek mythology, known for his speed and ability to transport messages and objects from one place to another. Likewise, a package manager is responsible for transporting and managing software packages from one place to another.
# **How does Hermes work?**
**Some basic Hermes commands are:**
```
- createpkg - .tpkg package builder.
- pkginstall - .tpkg package installer.
- pkgremove - Package Remover (safely).
```
**createpkg commands:**
```
-c package_name creates the package
-v see the verbosity of the package builder
create (extended version of -c)
```
**pkginstall commands:**
```
install (install the package)
```
#
# How to install?
**Locate where Hermes was downloaded, usually you can install it with:**
```
git clone https://github.com/Centauri-OS/Hermes
```
**After you have found Hermes has been downloaded, login as root and move the files responsible for the packages to the /usr/sbin folder with:**
```
chmod +x createpkg pkginstall pkgremove
cp -v createpkg pkginstall pkgremove /usr/sbin
```
After that, you are already able to install packages in your linux distribution, **in Centauri-OS, you don't need to do this tutorial.**
<details>
<summary>Tips</summary>
To create, install and remove packages you will normally be asked for root access.
</details>
