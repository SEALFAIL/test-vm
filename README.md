![SEALFAIL logo](logo-transparent.png) 

# SEALFAIL TEST VM

This repository contains the necessary scripts and data to test a SEALFAIL ISO.

A Docker container running libvirtd is started, from which a QEMU VM is created, using the machine configuration provided in `sealfail.xml`. The VM is then executed.

## Dependencies

TBD

## Usage

Run the `test_vm.sh` script:

`# chmod +x test_vm.sh && ./test_vm.sh`

## Repository structure

```
./test-vm
```

## Contributing

Refer to the SEALFAIL project [documentation repository](https://github.com/SEALFAIL/Documentation) for information regarding contributions.

## Code of conduct (COC)

Contributors are to follow the code of conduct (COC) located at the SEALFAIL project [documentation repository](https://github.com/SEALFAIL/Documentation).
