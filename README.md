## acpi_dump_info
A small acpi info dump utility originally written by [Peter Wu](https://github.com/Lekensteyn).
Can check out the original repo [here](https://github.com/Lekensteyn/acpi-stuff).

Has been patched to build on linux kernel 5.6.0 and higher.

## build instructions

```bash
git clone https://github.com/MatthewWertman/acpi_dump_info.git
cd acpi_dump_info
make
sudo make load
cat /proc/acpi/dump_info
```
