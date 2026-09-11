# Отчет по практической работе №2

* **Выполнил студент группы:** [Впишите группу]
* **ФИО:** [Впишите Фамилию Имя Отчество]

---
### 🛠️ Этап 1. Характеристики виртуальной машины
* **Используемый гипервизор:** [Например: Oracle VirtualBox] <!-- MARKER_HYPERVISOR -->
* **Выделенный объем ОЗУ (RAM):** [Например: 2048 MB] <!-- MARKER_RAM -->

---
### 📸 Этап 2. Скриншот установленной ОС
![Рабочий стол ОС](image.png) <!-- MARKER_IMAGE -->

---
### 💻 Этап 3. Системные логи диагностики оборудования
```text
[lscpu
Architecture:            x86_64
  CPU op-mode(s):        32-bit, 64-bit
  Address sizes:         39 bits physical, 48 bits virtual
  Byte Order:            Little Endian
CPU(s):                  1
  On-line CPU(s) list:   0
Vendor ID:               GenuineIntel
  Model name:            12th Gen Intel(R) Core(TM) i5-12400
    BIOS Model name:       CPU @ 0.0GHz
    BIOS CPU family:     0
    CPU family:          6
    Model:               151
    Thread(s) per core:  1
    Core(s) per socket:  1
    Socket(s):           1
    Stepping:            5
    BogoMIPS:            4992,00
    Flags:               fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge
                          mca cmov pat pse36 clflush mmx fxsr sse sse2 ht sys
                         call nx rdtscp lm constant_tsc rep_good nopl xtopolo
                         gy nonstop_tsc cpuid tsc_known_freq pni pclmulqdq mo
                         nitor ssse3 fma cx16 pcid sse4_1 sse4_2 x2apic movbe
                          popcnt aes xsave avx f16c rdrand hypervisor lahf_lm
                          abm 3dnowprefetch invpcid_single pti fsgsbase bmi1 
                         avx2 bmi2 invpcid rdseed adx clflushopt sha_ni arat 
                         md_clear flush_l1d arch_capabilities
Virtualization features: 
  Hypervisor vendor:     KVM
  Virtualization type:   full
Caches (sum of all):     
  L1d:                   48 KiB (1 instance)
  L1i:                   32 KiB (1 instance)
  L2:                    1,3 MiB (1 instance)
  L3:                    18 MiB (1 instance)
NUMA:                    
  NUMA node(s):          1
  NUMA node0 CPU(s):     0
Vulnerabilities:         
  Itlb multihit:         KVM: Mitigation: VMX unsupported
  L1tf:                  Mitigation; PTE Inversion
  Mds:                   Mitigation; Clear CPU buffers; SMT Host state unknow
                         n
  Meltdown:              Mitigation; PTI
  Mmio stale data:       Not affected
  Retbleed:              Not affected
  Spec store bypass:     Vulnerable
  Spectre v1:            Mitigation; usercopy/swapgs barriers and __user poin
                         ter sanitization
  Spectre v2:            Mitigation; Retpolines, STIBP disabled, RSB filling,
                          PBRSB-eIBRS Not affected
  Srbds:                 Not affected
  Tsx async abort:       Not affected
                                      ]
```
<!-- MARKER_LOG -->
