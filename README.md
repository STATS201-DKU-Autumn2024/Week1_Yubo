# System Configuration Report

## CPU Information
- **Architecture**: x86_64
- **CPU op-mode(s)**: 32-bit, 64-bit
- **Address sizes**: 46 bits physical, 48 bits virtual
- **Byte Order**: Little Endian
- **CPU(s)**: 2
- **On-line CPU(s) list**: 0, 1
- **Vendor ID**: GenuineIntel
- **Model name**: Intel(R) Xeon(R) CPU @ 2.20GHz
- **CPU family**: 6
- **Model**: 79
- **Thread(s) per core**: 2
- **Core(s) per socket**: 1
- **Socket(s)**: 1
- **Stepping**: 0
- **BogoMIPS**: 4399.99

### CPU Flags
`fpu`, `vme`, `de`, `pse`, `tsc`, `msr`, `pae`, `mce`, `cx8`, `apic`, `sep`, `mtrr`, `pge`, `mca`, `cmov`, `pat`, `pse36`, `clflush`, `mmx`, `fxsr`, `sse`, `sse2`, `ss`, `ht`, `syscall`, `nx`, `pdpe1gb`, `rdtscp`, `lm`, `constant_tsc`, `rep_good`, `nopl`, `xtopology`, `nonstop_tsc`, `cpuid`, `tsc_known_freq`, `pni`, `pclmulqdq`, `ssse3`, `fma`, `cx16`, `pcid`, `sse4_1`, `sse4_2`, `x2apic`, `movbe`, `popcnt`, `aes`, `xsave`, `avx`, `f16c`, `rdrand`, `hypervisor`, `lahf_lm`, `abm`, `3dnowprefetch`, `invpcid_single`, `ssbd`, `ibrs`, `ibpb`, `stibp`, `fsgsbase`, `tsc_adjust`, `bmi1`, `hle`, `avx2`, `smep`, `bmi2`, `erms`, `invpcid`, `rtm`, `rdseed`, `adx`, `smap`, `xsaveopt`, `arat`, `md_clear`, `arch_capabilities`

### Cache Information
- **L1d cache**: 32 KiB (1 instance)
- **L1i cache**: 32 KiB (1 instance)
- **L2 cache**: 256 KiB (1 instance)
- **L3 cache**: 55 MiB (1 instance)

### NUMA Information
- **NUMA node(s)**: 1
- **NUMA node0 CPU(s)**: 0,1

### Vulnerabilities
- **Gather data sampling**: Not affected
- **Itlb multihit**: Not affected
- **L1tf**: Mitigation; PTE Inversion
- **Mds**: Vulnerable; SMT Host state unknown
- **Meltdown**: Vulnerable
- **Mmio stale data**: Vulnerable
- **Reg file data sampling**: Not affected
- **Retbleed**: Vulnerable
- **Spec rstack overflow**: Not affected
- **Spec store bypass**: Vulnerable
- **Spectre v1**: Vulnerable: __user pointer sanitization and usercopy barriers only; no swapgs barriers
- **Spectre v2**: Vulnerable; IBPB: disabled; STIBP: disabled; PBRSB-eIBRS: Not affected; BHI: Vulnerable (Syscall hardening enabled)
- **Srbds**: Not affected
- **Tsx async abort**: Vulnerable

## GPU Information
- No GPU found.

## Memory Information
- **Total Memory**: 12 GiB
- **Used Memory**: 1.1 GiB
- **Free Memory**: 6.9 GiB
- **Shared Memory**: 1.0 MiB
- **Buffer/Cache**: 4.7 GiB
- **Available Memory**: 11 GiB
- **Swap Memory**: 0B (No swap space)

## Disk Space Information
| Filesystem      | Size | Used | Available | Use% | Mounted on              |
|-----------------|------|------|-----------|------|-------------------------|
| overlay         | 226G | 38G  | 189G      | 17%  | /                       |
| tmpfs           | 64M  | 0    | 64M       | 0%   | /dev                    |
| shm             | 5.8G | 0    | 5.8G      | 0%   | /dev/shm                |
| /dev/root       | 2.0G | 1.2G | 820M      | 59%  | /usr/sbin/docker-init   |
| tmpfs           | 6.4G | 112K | 6.4G      | 1%   | /var/colab              |
| /dev/sda1       | 233G | 57G  | 176G      | 25%  | /etc/hosts              |
| tmpfs           | 6.4G | 0    | 6.4G      | 0%   | /proc/acpi              |
| tmpfs           | 6.4G | 0    | 6.4G      | 0%   | /proc/scsi              |
| tmpfs           | 6.4G | 0    | 6.4G      | 0%   | /sys/firmware           |

## Python Information
- **Python Version**: 3.10.12

## Installed Packages
| Package          | Version   |
|------------------|-----------|
| absl-py          | 1.4.0     |
| accelerate       | 0.34.2    |
| aiohttp          | 3.10.10   |
| ...              | ...       |
| transformers     | 4.44.2    |
| wordcloud        | 1.9.3     |
| xgboost          | 2.1.1     |
| yfinance         | 0.2.46    |
