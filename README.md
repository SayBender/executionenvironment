# execution_environment
Output from scripts that gathers execution environment information.
- system 1: Amazon AWS instance
SUDO_GID=1000
MAIL=/var/mail/USER
USER=USER
HOME=/home/ubuntu
SUDO_UID=1000
LOGNAME=USER
TERM=xterm-256color
USERNAME=USER
PATH=/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/snap/bin
LANG=C.UTF-8
LS_COLORS=rs=0:di=01;34:ln=01;36:mh=00:pi=40;33:so=01;35:do=01;35:bd=40;33;01:cd=40;33;01:or=40;31;01:mi=00:su=37;41:sg=30;43:ca=30;41:tw=30;42:ow=34;42:st=37;44:ex=01;32:*.tar=01;31:*.tgz=01;31:*.arc=01;31:*.arj=01;31:*.taz=01;31:*.lha=01;31:*.lz4=01;31:*.lzh=01;31:*.lzma=01;31:*.tlz=01;31:*.txz=01;31:*.tzo=01;31:*.t7z=01;31:*.zip=01;31:*.z=01;31:*.Z=01;31:*.dz=01;31:*.gz=01;31:*.lrz=01;31:*.lz=01;31:*.lzo=01;31:*.xz=01;31:*.zst=01;31:*.tzst=01;31:*.bz2=01;31:*.bz=01;31:*.tbz=01;31:*.tbz2=01;31:*.tz=01;31:*.deb=01;31:*.rpm=01;31:*.jar=01;31:*.war=01;31:*.ear=01;31:*.sar=01;31:*.rar=01;31:*.alz=01;31:*.ace=01;31:*.zoo=01;31:*.cpio=01;31:*.7z=01;31:*.rz=01;31:*.cab=01;31:*.wim=01;31:*.swm=01;31:*.dwm=01;31:*.esd=01;31:*.jpg=01;35:*.jpeg=01;35:*.mjpg=01;35:*.mjpeg=01;35:*.gif=01;35:*.bmp=01;35:*.pbm=01;35:*.pgm=01;35:*.ppm=01;35:*.tga=01;35:*.xbm=01;35:*.xpm=01;35:*.tif=01;35:*.tiff=01;35:*.png=01;35:*.svg=01;35:*.svgz=01;35:*.mng=01;35:*.pcx=01;35:*.mov=01;35:*.mpg=01;35:*.mpeg=01;35:*.m2v=01;35:*.mkv=01;35:*.webm=01;35:*.ogm=01;35:*.mp4=01;35:*.m4v=01;35:*.mp4v=01;35:*.vob=01;35:*.qt=01;35:*.nuv=01;35:*.wmv=01;35:*.asf=01;35:*.rm=01;35:*.rmvb=01;35:*.flc=01;35:*.avi=01;35:*.fli=01;35:*.flv=01;35:*.gl=01;35:*.dl=01;35:*.xcf=01;35:*.xwd=01;35:*.yuv=01;35:*.cgm=01;35:*.emf=01;35:*.ogv=01;35:*.ogx=01;35:*.aac=00;36:*.au=00;36:*.flac=00;36:*.m4a=00;36:*.mid=00;36:*.midi=00;36:*.mka=00;36:*.mp3=00;36:*.mpc=00;36:*.ogg=00;36:*.ra=00;36:*.wav=00;36:*.oga=00;36:*.opus=00;36:*.spx=00;36:*.xspf=00;36:
SUDO_COMMAND=./collect_environment.sh
SHELL=/bin/bash
SUDO_USER=ubuntu
PWD=/home/ubuntu
+ lsb_release -a
No LSB modules are available.
Distributor ID:	Ubuntu
Description:	Ubuntu 18.04.2 LTS
Release:	18.04
Codename:	bionic
+ uname -a
Linux ip-172-31-15-153 4.15.0-1044-aws #46-Ubuntu SMP Thu Jul 4 13:38:28 UTC 2019 x86_64 x86_64 x86_64 GNU/Linux
+ lscpu
Architecture:        x86_64
CPU op-mode(s):      32-bit, 64-bit
Byte Order:          Little Endian
CPU(s):              36
On-line CPU(s) list: 0-35
Thread(s) per core:  2
Core(s) per socket:  18
Socket(s):           1
NUMA node(s):        1
Vendor ID:           GenuineIntel
CPU family:          6
Model:               85
Model name:          Intel(R) Xeon(R) Platinum 8124M CPU @ 3.00GHz
Stepping:            4
CPU MHz:             1367.983
BogoMIPS:            5999.99
Hypervisor vendor:   KVM
Virtualization type: full
L1d cache:           32K
L1i cache:           32K
L2 cache:            1024K
L3 cache:            25344K
NUMA node0 CPU(s):   0-35
Flags:               fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush mmx fxsr sse sse2 ss ht syscall nx pdpe1gb rdtscp lm constant_tsc arch_perfmon rep_good nopl xtopology nonstop_tsc cpuid aperfmperf tsc_known_freq pni pclmulqdq monitor ssse3 fma cx16 pcid sse4_1 sse4_2 x2apic movbe popcnt tsc_deadline_timer aes xsave avx f16c rdrand hypervisor lahf_lm abm 3dnowprefetch invpcid_single pti fsgsbase tsc_adjust bmi1 hle avx2 smep bmi2 erms invpcid rtm mpx avx512f avx512dq rdseed adx smap clflushopt clwb avx512cd avx512bw avx512vl xsaveopt xsavec xgetbv1 xsaves ida arat pku ospke
+ cat /proc/meminfo
MemTotal:       72028872 kB
MemFree:        70186972 kB
MemAvailable:   70919008 kB
Buffers:           40636 kB
Cached:          1243748 kB
SwapCached:            0 kB
Active:           658900 kB
Inactive:         687268 kB
Active(anon):      62668 kB
Inactive(anon):       96 kB
Active(file):     596232 kB
Inactive(file):   687172 kB
Unevictable:           0 kB
Mlocked:               0 kB
SwapTotal:             0 kB
SwapFree:              0 kB
Dirty:                76 kB
Writeback:             0 kB
AnonPages:         61736 kB
Mapped:            60280 kB
Shmem:               876 kB
Slab:             285768 kB
SReclaimable:     169932 kB
SUnreclaim:       115836 kB
KernelStack:        8688 kB
PageTables:         4396 kB
NFS_Unstable:          0 kB
Bounce:                0 kB
WritebackTmp:          0 kB
CommitLimit:    36014436 kB
Committed_AS:     866900 kB
VmallocTotal:   34359738367 kB
VmallocUsed:           0 kB
VmallocChunk:          0 kB
HardwareCorrupted:     0 kB
AnonHugePages:         0 kB
ShmemHugePages:        0 kB
ShmemPmdMapped:        0 kB
CmaTotal:              0 kB
CmaFree:               0 kB
HugePages_Total:       0
HugePages_Free:        0
HugePages_Rsvd:        0
HugePages_Surp:        0
Hugepagesize:       2048 kB
DirectMap4k:      260064 kB
DirectMap2M:     5900288 kB
DirectMap1G:    67108864 kB
+ inxi -F -c0
./collect_environment.sh: 14: ./collect_environment.sh: inxi: not found
+ lsblk -a
NAME        MAJ:MIN RM  SIZE RO TYPE MOUNTPOINT
loop0         7:0    0 88.5M  1 loop /snap/core/7270
loop1         7:1    0   18M  1 loop /snap/amazon-ssm-agent/1455
loop2         7:2    0   97M  1 loop /snap/core/9289
loop3         7:3    0   18M  1 loop /snap/amazon-ssm-agent/1566
loop4         7:4    0        0 loop 
loop5         7:5    0        0 loop 
loop6         7:6    0        0 loop 
loop7         7:7    0        0 loop 
nvme0n1     259:0    0   30G  0 disk 
└─nvme0n1p1 259:1    0   30G  0 part /
+ lsscsi -s
./collect_environment.sh: 16: ./collect_environment.sh: lsscsi: not found
+ module list
./collect_environment.sh: 17: ./collect_environment.sh: module: not found
+ nvidia-smi
./collect_environment.sh: 18: ./collect_environment.sh: nvidia-smi: not found
+ lshw -short -quiet -sanitize
+ cat
H/W path    Device  Class      Description
==========================================
                    system     c5.9xlarge
/0                  bus        Motherboard
/0/0                memory     64KiB BIOS
/0/4                processor  Intel(R) Xeon(R) Platinum 8124M CPU @ 3.00GHz
/0/1                memory     68GiB System memory
/0/100              bridge     440FX - 82441FX PMC [Natoma]
/0/100/1            bridge     82371SB PIIX3 ISA [Natoma/Triton II]
/0/100/1.3          generic    82371AB/EB/MB PIIX4 ACPI
/0/100/3            display    Amazon.com, Inc.
/0/100/4            storage    Amazon.com, Inc.
/0/100/5    ens5    network    Elastic Network Adapter (ENA)

# packages in environment at /home/ubuntu/anaconda3/envs/AWS_LSTM:
#
# Name                    Version                   Build  Channel
_libgcc_mutex             0.1                        main  
_tflow_select             2.3.0                       mkl  
absl-py                   0.7.1                    py36_0  
astor                     0.8.0                    py36_0  
blas                      1.0                         mkl  
c-ares                    1.15.0            h7b6447c_1001  
ca-certificates           2019.5.15                     1  
certifi                   2019.6.16                py36_1  
cycler                    0.10.0                   py36_0  
dbus                      1.13.6               h746ee38_0  
expat                     2.2.6                he6710b0_0  
fontconfig                2.13.0               h9420a91_0  
freetype                  2.9.1                h8a8886c_1  
gast                      0.2.2                    py36_0  
glib                      2.56.2               hd408876_0  
google-pasta              0.1.7                      py_0  
grpcio                    1.16.1           py36hf8bcb03_1  
gst-plugins-base          1.14.0               hbbd80ab_1  
gstreamer                 1.14.0               hb453b48_1  
h5py                      2.9.0            py36h7918eee_0  
hdf5                      1.10.4               hb1b8bf9_0  
icu                       58.2                 h9c2bf20_1  
intel-openmp              2019.4                      243  
joblib                    0.13.2                   py36_0  
jpeg                      9b                   h024ee3a_2  
keras                     2.2.4                         0  
keras-applications        1.0.8                      py_0  
keras-base                2.2.4                    py36_0  
keras-preprocessing       1.1.0                      py_1  
kiwisolver                1.1.0            py36he6710b0_0  
libedit                   3.1.20181209         hc058e9b_0  
libffi                    3.2.1                hd88cf55_4  
libgcc-ng                 9.1.0                hdf63c60_0  
libgfortran-ng            7.3.0                hdf63c60_0  
libpng                    1.6.37               hbc83047_0  
libprotobuf               3.8.0                hd408876_0  
libstdcxx-ng              9.1.0                hdf63c60_0  
libuuid                   1.0.3                h1bed415_2  
libxcb                    1.13                 h1bed415_1  
libxml2                   2.9.9                hea5a465_1  
markdown                  3.1.1                    py36_0  
matplotlib                3.1.0            py36h5429711_0  
mkl                       2019.4                      243  
mkl-service               2.0.2            py36h7b6447c_0  
mkl_fft                   1.0.12           py36ha843d7b_0  
mkl_random                1.0.2            py36hd81dba3_0  
ncurses                   6.1                  he6710b0_1  
numpy                     1.16.4           py36h7e9f1db_0  
numpy-base                1.16.4           py36hde5b4d6_0  
openssl                   1.1.1c               h7b6447c_1  
pandas                    0.25.0           py36he6710b0_0  
pcre                      8.43                 he6710b0_0  
pip                       19.1.1                   py36_0  
protobuf                  3.8.0            py36he6710b0_0  
pyparsing                 2.4.0                      py_0  
pyqt                      5.9.2            py36h05f1152_2  
python                    3.6.9                h265db76_0  
python-dateutil           2.8.0                    py36_0  
pytz                      2019.1                     py_0  
pyyaml                    5.1.1            py36h7b6447c_0  
qt                        5.9.7                h5867ecd_1  
readline                  7.0                  h7b6447c_5  
scikit-learn              0.21.2           py36hd81dba3_0  
scipy                     1.3.0            py36h7c811a0_0  
setuptools                41.0.1                   py36_0  
sip                       4.19.8           py36hf484d3e_0  
six                       1.12.0                   py36_0  
sqlite                    3.29.0               h7b6447c_0  
tensorboard               1.14.0           py36hf484d3e_0  
tensorflow                1.14.0          mkl_py36h2526735_0  
tensorflow-base           1.14.0          mkl_py36h7ce6ba3_0  
tensorflow-estimator      1.14.0                     py_0  
termcolor                 1.1.0                    py36_1  
tk                        8.6.8                hbc83047_0  
tornado                   6.0.3            py36h7b6447c_0  
werkzeug                  0.15.4                     py_0  
wheel                     0.33.4                   py36_0  
wrapt                     1.11.2           py36h7b6447c_0  
xz                        5.2.4                h14c3975_4  
yaml                      0.1.7                had09818_2  
zlib                      1.2.11               h7b6447c_3 

- system 2: Author's PC
SUDO_GID=1001
MAIL=/var/mail/USER
USER=USER
COLORTERM=truecolor
SUDO_UID=1001
LOGNAME=USER
TERM=xterm-256color
USERNAME=USER
PATH=/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/snap/bin
DISPLAY=:0
LANG=en_US.UTF-8
LS_COLORS=rs=0:di=01;34:ln=01;36:mh=00:pi=40;33:so=01;35:do=01;35:bd=40;33;01:cd=40;33;01:or=40;31;01:mi=00:su=37;41:sg=30;43:ca=30;41:tw=30;42:ow=34;42:st=37;44:ex=01;32:*.tar=01;31:*.tgz=01;31:*.arc=01;31:*.arj=01;31:*.taz=01;31:*.lha=01;31:*.lz4=01;31:*.lzh=01;31:*.lzma=01;31:*.tlz=01;31:*.txz=01;31:*.tzo=01;31:*.t7z=01;31:*.zip=01;31:*.z=01;31:*.Z=01;31:*.dz=01;31:*.gz=01;31:*.lrz=01;31:*.lz=01;31:*.lzo=01;31:*.xz=01;31:*.zst=01;31:*.tzst=01;31:*.bz2=01;31:*.bz=01;31:*.tbz=01;31:*.tbz2=01;31:*.tz=01;31:*.deb=01;31:*.rpm=01;31:*.jar=01;31:*.war=01;31:*.ear=01;31:*.sar=01;31:*.rar=01;31:*.alz=01;31:*.ace=01;31:*.zoo=01;31:*.cpio=01;31:*.7z=01;31:*.rz=01;31:*.cab=01;31:*.wim=01;31:*.swm=01;31:*.dwm=01;31:*.esd=01;31:*.jpg=01;35:*.jpeg=01;35:*.mjpg=01;35:*.mjpeg=01;35:*.gif=01;35:*.bmp=01;35:*.pbm=01;35:*.pgm=01;35:*.ppm=01;35:*.tga=01;35:*.xbm=01;35:*.xpm=01;35:*.tif=01;35:*.tiff=01;35:*.png=01;35:*.svg=01;35:*.svgz=01;35:*.mng=01;35:*.pcx=01;35:*.mov=01;35:*.mpg=01;35:*.mpeg=01;35:*.m2v=01;35:*.mkv=01;35:*.webm=01;35:*.ogm=01;35:*.mp4=01;35:*.m4v=01;35:*.mp4v=01;35:*.vob=01;35:*.qt=01;35:*.nuv=01;35:*.wmv=01;35:*.asf=01;35:*.rm=01;35:*.rmvb=01;35:*.flc=01;35:*.avi=01;35:*.fli=01;35:*.flv=01;35:*.gl=01;35:*.dl=01;35:*.xcf=01;35:*.xwd=01;35:*.yuv=01;35:*.cgm=01;35:*.emf=01;35:*.ogv=01;35:*.ogx=01;35:*.aac=00;36:*.au=00;36:*.flac=00;36:*.m4a=00;36:*.mid=00;36:*.midi=00;36:*.mka=00;36:*.mp3=00;36:*.mpc=00;36:*.ogg=00;36:*.ra=00;36:*.wav=00;36:*.oga=00;36:*.opus=00;36:*.spx=00;36:*.xspf=00;36:
XAUTHORITY=/run/user/1001/gdm/Xauthority
SUDO_COMMAND=./collect_environment.sh
SHELL=/bin/bash
+ lsb_release -a
No LSB modules are available.
Distributor ID:	Ubuntu
Description:	Ubuntu 18.04.4 LTS
Release:	18.04
Codename:	bionic
+ uname -a
Linux 056207fz6t172 4.15.0-101-generic #102-Ubuntu SMP Mon May 11 10:07:26 UTC 2020 x86_64 x86_64 x86_64 GNU/Linux
+ lscpu
Architecture:        x86_64
CPU op-mode(s):      32-bit, 64-bit
Byte Order:          Little Endian
CPU(s):              4
On-line CPU(s) list: 0-3
Thread(s) per core:  1
Core(s) per socket:  4
Socket(s):           1
NUMA node(s):        1
Vendor ID:           GenuineIntel
CPU family:          6
Model:               60
Model name:          Intel(R) Xeon(R) CPU E3-1225 v3 @ 3.20GHz
Stepping:            3
CPU MHz:             2136.937
CPU max MHz:         3600.0000
CPU min MHz:         800.0000
BogoMIPS:            6385.08
Virtualization:      VT-x
L1d cache:           32K
L1i cache:           32K
L2 cache:            256K
L3 cache:            8192K
NUMA node0 CPU(s):   0-3
Flags:               fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush dts acpi mmx fxsr sse sse2 ss ht tm pbe syscall nx pdpe1gb rdtscp lm constant_tsc arch_perfmon pebs bts rep_good nopl xtopology nonstop_tsc cpuid aperfmperf pni pclmulqdq dtes64 monitor ds_cpl vmx smx est tm2 ssse3 sdbg fma cx16 xtpr pdcm pcid sse4_1 sse4_2 x2apic movbe popcnt tsc_deadline_timer aes xsave avx f16c rdrand lahf_lm abm cpuid_fault epb invpcid_single pti ssbd ibrs ibpb stibp tpr_shadow vnmi flexpriority ept vpid fsgsbase tsc_adjust bmi1 avx2 smep bmi2 erms invpcid xsaveopt dtherm ida arat pln pts md_clear flush_l1d
+ cat /proc/meminfo
MemTotal:        3945772 kB
MemFree:          151612 kB
MemAvailable:     565520 kB
Buffers:          154256 kB
Cached:           951928 kB
SwapCached:         6792 kB
Active:          2479488 kB
Inactive:         909688 kB
Active(anon):    2268228 kB
Inactive(anon):   620032 kB
Active(file):     211260 kB
Inactive(file):   289656 kB
Unevictable:          48 kB
Mlocked:              48 kB
SwapTotal:      15997944 kB
SwapFree:       15832056 kB
Dirty:               480 kB
Writeback:             0 kB
AnonPages:       2276300 kB
Mapped:           549748 kB
Shmem:            605268 kB
Slab:             254480 kB
SReclaimable:     200064 kB
SUnreclaim:        54416 kB
KernelStack:       12680 kB
PageTables:        69736 kB
NFS_Unstable:          0 kB
Bounce:                0 kB
WritebackTmp:          0 kB
CommitLimit:    17970828 kB
Committed_AS:   10076016 kB
VmallocTotal:   34359738367 kB
VmallocUsed:           0 kB
VmallocChunk:          0 kB
HardwareCorrupted:     0 kB
AnonHugePages:         0 kB
ShmemHugePages:        0 kB
ShmemPmdMapped:        0 kB
CmaTotal:              0 kB
CmaFree:               0 kB
HugePages_Total:       0
HugePages_Free:        0
HugePages_Rsvd:        0
HugePages_Surp:        0
Hugepagesize:       2048 kB
DirectMap4k:      236048 kB
DirectMap2M:     3864576 kB
DirectMap1G:           0 kB
+ inxi -F -c0
./collect_environment.sh: 14: ./collect_environment.sh: inxi: not found
+ lsblk -a
NAME   MAJ:MIN RM   SIZE RO TYPE MOUNTPOINT
loop0    7:0    0 255.6M  1 loop /snap/gnome-3-34-1804/33
loop1    7:1    0 160.2M  1 loop /snap/gnome-3-28-1804/116
loop2    7:2    0   2.4M  1 loop /snap/gnome-calculator/748
loop3    7:3    0 140.7M  1 loop /snap/gnome-3-26-1604/100
loop4    7:4    0  93.9M  1 loop /snap/core/9066
loop5    7:5    0   276K  1 loop /snap/gnome-characters/539
loop6    7:6    0   2.2M  1 loop /snap/gnome-system-monitor/148
loop7    7:7    0    97M  1 loop /snap/core/9289
loop8    7:8    0 242.4M  1 loop /snap/gnome-3-34-1804/27
loop9    7:9    0 156.7M  1 loop /snap/gnome-3-28-1804/110
loop10   7:10   0  14.8M  1 loop /snap/gnome-characters/495
loop11   7:11   0    55M  1 loop /snap/core18/1705
loop12   7:12   0   2.2M  1 loop /snap/gnome-system-monitor/145
loop13   7:13   0  62.1M  1 loop /snap/gtk-common-themes/1506
loop14   7:14   0   956K  1 loop /snap/gnome-logs/100
loop15   7:15   0   956K  1 loop /snap/gnome-logs/93
loop16   7:16   0  54.8M  1 loop /snap/gtk-common-themes/1502
loop17   7:17   0   2.4M  1 loop /snap/gnome-calculator/730
loop18   7:18   0 140.7M  1 loop /snap/gnome-3-26-1604/98
loop19   7:19   0    55M  1 loop /snap/core18/1754
loop20   7:20   0         0 loop 
sda      8:0    0 931.5G  0 disk 
├─sda1   8:1    0   500M  0 part 
├─sda2   8:2    0 465.3G  0 part 
├─sda3   8:3    0 458.1G  0 part 
├─sda4   8:4    0     1K  0 part 
└─sda5   8:5    0   7.6G  0 part [SWAP]
sdb      8:16   0 465.8G  0 disk 
├─sdb1   8:17   0   7.6G  0 part [SWAP]
├─sdb2   8:18   0     1K  0 part 
└─sdb5   8:21   0 458.1G  0 part /
sr0     11:0    1  1024M  0 rom  
+ lsscsi -s
./collect_environment.sh: 16: ./collect_environment.sh: lsscsi: not found
+ module list
./collect_environment.sh: 17: ./collect_environment.sh: module: not found
+ nvidia-smi
./collect_environment.sh: 18: ./collect_environment.sh: nvidia-smi: not found
+ lshw -short -quiet -sanitize
+ cat
H/W path        Device           Class          Description
===========================================================
                                 system         PowerEdge T20 (0620)
/0                               bus            0VD5HY
/0/0                             memory         64KiB BIOS
/0/39                            processor      Intel(R) Xeon(R) CPU E3-1225 v3 @ 3.20GHz
/0/39/3a                         memory         256KiB L1 cache
/0/39/3b                         memory         1MiB L2 cache
/0/39/3c                         memory         8MiB L3 cache
/0/3d                            memory         4GiB System Memory
/0/3d/0                          memory         DIMM [empty]
/0/3d/1                          memory         4GiB DIMM DDR3 Synchronous 1600 MHz (0.6 ns)
/0/3d/2                          memory         DIMM [empty]
/0/3d/3                          memory         DIMM [empty]
/0/100                           bridge         Xeon E3-1200 v3 Processor DRAM Controller
/0/100/2                         display        Xeon E3-1200 v3 Processor Integrated Graphics Controller
/0/100/14                        bus            8 Series/C220 Series Chipset Family USB xHCI
/0/100/14/0     usb3             bus            xHCI Host Controller
/0/100/14/0/4                    generic        A7000
/0/100/14/0/5                    input          Dell USB Entry Keyboard
/0/100/14/0/6                    input          USB Optical Mouse
/0/100/14/1     usb4             bus            xHCI Host Controller
/0/100/16                        communication  8 Series/C220 Series Chipset Family MEI Controller #1
/0/100/16.3                      communication  8 Series/C220 Series Chipset Family KT Controller
/0/100/19       eno1             network        Ethernet Connection I217-LM
/0/100/1a                        bus            8 Series/C220 Series Chipset Family USB EHCI #2
/0/100/1a/1     usb1             bus            EHCI Host Controller
/0/100/1a/1/1                    bus            USB hub
/0/100/1b                        multimedia     8 Series/C220 Series Chipset High Definition Audio Controller
/0/100/1c                        bridge         8 Series/C220 Series Chipset Family PCI Express Root Port #1
/0/100/1c.1                      bridge         8 Series/C220 Series Chipset Family PCI Express Root Port #2
/0/100/1c.1/0                    bridge         XIO2001 PCI Express-to-PCI Bridge
/0/100/1d                        bus            8 Series/C220 Series Chipset Family USB EHCI #1
/0/100/1d/1     usb2             bus            EHCI Host Controller
/0/100/1d/1/1                    bus            USB hub
/0/100/1f                        bridge         C226 Series Chipset Family Server Advanced SKU LPC Controller
/0/100/1f.2                      storage        8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]
/0/100/1f.3                      bus            8 Series/C220 Series Chipset Family SMBus Controller
/0/1            scsi0            storage        
/0/1/0.0.0      /dev/sda         disk           1TB TOSHIBA DT01ACA1
/0/1/0.0.0/1    /dev/sda1        volume         500MiB Windows NTFS volume
/0/1/0.0.0/2    /dev/sda2        volume         465GiB Windows NTFS volume
/0/1/0.0.0/3    /dev/sda3        volume         458GiB EXT4 volume
/0/1/0.0.0/4    /dev/sda4        volume         7811MiB Extended partition
/0/1/0.0.0/4/5  /dev/sda5        volume         7811MiB Linux swap volume
/0/2            scsi1            storage        
/0/2/0.0.0      /dev/sdb         disk           500GB HP SSD S700 500G
/0/2/0.0.0/1    /dev/sdb1        volume         7812MiB Linux swap volume
/0/2/0.0.0/2    /dev/sdb2        volume         458GiB Extended partition
/0/2/0.0.0/2/5  /dev/sdb5        volume         458GiB EXT4 volume
/0/3            scsi2            storage        
/0/3/0.0.0      /dev/cdrom       disk           DVD+-RW GTA0N
/1              wlx44a56e3ceced  network        Wireless interface
