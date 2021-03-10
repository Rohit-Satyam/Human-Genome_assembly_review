**1. MitoZ**
Here is the .yml file (mitoz.yml) that's required to install mitoz. Read more from [here](https://github.com/linzhi2013/MitoZ/blob/master/version_2.3/INSTALL.md#33-install-dependency-with-conda-command)
```bash
name: mitoz
channels:
  - etetoolkit
  - conda-forge
  - bioconda
  - defaults
dependencies:
  - _libgcc_mutex=0.1=conda_forge
  - _openmp_mutex=4.5=0_gnu
  - alsa-lib=1.1.5=h516909a_1002
  - argtable2=2.13=0
  - biopython=1.76=py36h516909a_0
  - blast=2.9.0=h20b68b9_1
  - boost=1.68.0=py36h8619c78_1001
  - boost-cpp=1.68.0=h11c811c_1000
  - bwa=0.7.17=hed695b0_7
  - bzip2=1.0.8=h516909a_2
  - ca-certificates=2019.11.28=hecc5488_0
  - certifi=2019.11.28=py36_0
  - circos=0.69.8=0
  - clustalo=1.2.4=h4346872_0
  - curl=7.65.3=hf8cf82a_0
  - dbus=1.13.6=he372182_0
  - dialigntx=1.0.2=hdce4c0c_0
  - ete3=3.1.1=pyhf5214e1_0
  - ete_toolchain=3.0.0=h73706c9_0
  - expat=2.2.9=he1b5a44_2
  - fasttree=2.1=hdfd2403_0
  - fontconfig=2.13.1=he4413a7_1000
  - freetype=2.10.0=he983fc9_1
  - gettext=0.19.8.1=hc5be6a0_1002
  - giflib=5.2.1=h516909a_1
  - glib=2.58.3=py36h6f030ca_1002
  - gmp=6.2.0=he1b5a44_1
  - gnutls=3.6.5=hd3a4fd2_1002
  - gst-plugins-base=1.14.5=h0935bb2_1
  - gstreamer=1.14.5=h36ae1b5_1
  - hmmer=3.1b2=3
  - icu=58.2=hf484d3e_1000
  - infernal=1.1.1=0
  - iqtree=1.5.5=he390d98_0
  - jpeg=9c=h14c3975_1001
  - kalign=2.03=h29c49b8_0
  - krb5=1.16.4=h2fd8d38_0
  - lcms2=2.9=hbd6801e_1
  - libblas=3.8.0=14_openblas
  - libcblas=3.8.0=14_openblas
  - libcurl=7.65.3=hda55be3_0
  - libedit=3.1.20170329=hf8c457e_1001
  - libffi=3.2.1=he1b5a44_1006
  - libgcc=7.2.0=h69d50b8_2
  - libgcc-ng=9.2.0=h24d8f2e_2
  - libgd=2.2.5=h0d07dcb_1005
  - libgfortran-ng=7.3.0=hdf63c60_4
  - libgomp=9.2.0=h24d8f2e_2
  - libiconv=1.15=h516909a_1005
  - libidn11=1.34=h1cef754_0
  - liblapack=3.8.0=14_openblas
  - libopenblas=0.3.7=h5ec1e0e_6
  - libpng=1.6.37=hed695b0_0
  - libssh2=1.8.2=h22169c7_2
  - libstdcxx-ng=9.2.0=hdf63c60_2
  - libtiff=4.1.0=hc3755c2_3
  - libuuid=2.32.1=h14c3975_1000
  - libwebp=1.0.2=h56121f0_5
  - libxcb=1.13=h14c3975_1002
  - libxml2=2.9.9=hea5a465_1
  - libxslt=1.1.33=h7d1a2b0_0
  - lxml=3.8.0=py36_0
  - lz4-c=1.8.3=he1b5a44_1001
  - mafft=6.861=h7f9ae3c_0
  - muscle=3.8.31=he5e28f3_0
  - ncurses=6.1=hf484d3e_1002
  - nettle=3.4.1=h1bed415_1002
  - numpy=1.17.5=py36h95a1406_0
  - openjdk=11.0.1=h600c080_1018
  - openssl=1.1.1d=h516909a_0
  - paml=4.8=h48adae2_0
  - pcre=8.43=he1b5a44_0
  - perl=5.26.2=h516909a_1006
  - perl-archive-tar=2.32=pl526_0
  - perl-autoloader=5.74=pl526_2
  - perl-bioperl=1.7.2=pl526_11
  - perl-carp=1.38=pl526_3
  - perl-clone=0.42=pl526h516909a_0
  - perl-common-sense=3.74=pl526_2
  - perl-compress-raw-bzip2=2.087=pl526he1b5a44_0
  - perl-compress-raw-zlib=2.087=pl526hc9558a2_0
  - perl-config-general=2.63=pl526_0
  - perl-digest-perl-md5=1.9=pl526_1
  - perl-dynaloader=1.25=pl526_1
  - perl-exporter=5.72=pl526_1
  - perl-exporter-tiny=1.002001=pl526_0
  - perl-extutils-makemaker=7.36=pl526_1
  - perl-font-ttf=1.06=pl526_0
  - perl-gd=2.71=pl526he860b03_0
  - perl-io-compress=2.087=pl526he1b5a44_0
  - perl-io-string=1.08=pl526_3
  - perl-io-zlib=1.10=pl526_2
  - perl-json=4.02=pl526_0
  - perl-json-xs=2.34=pl526h6bb024c_3
  - perl-list-moreutils=0.428=pl526_1
  - perl-list-moreutils-xs=0.428=pl526_0
  - perl-math-bezier=0.01=pl526_1
  - perl-math-round=0.07=pl526_1
  - perl-math-vecstat=0.08=pl526_1
  - perl-module-implementation=0.09=pl526_2
  - perl-module-runtime=0.016=pl526_1
  - perl-number-format=1.75=pl526_3
  - perl-params-validate=1.29=pl526h14c3975_1
  - perl-pathtools=3.75=pl526h14c3975_1
  - perl-readonly=2.05=pl526_0
  - perl-regexp-common=2017060201=pl526_0
  - perl-scalar-list-utils=1.52=pl526h516909a_0
  - perl-set-intspan=1.19=pl526_1
  - perl-statistics-basic=1.6611=pl526_2
  - perl-svg=2.84=pl526_0
  - perl-text-format=0.59=pl526_2
  - perl-threaded=5.26.0=0
  - perl-time-hires=1.9760=pl526h14c3975_1
  - perl-try-tiny=0.30=pl526_1
  - perl-types-serialiser=1.0=pl526_2
  - perl-xml-parser=2.44=pl526h4e0c4b3_7
  - perl-xsloader=0.24=pl526_0
  - perl-yaml=1.29=pl526_0
  - phylobayes=4.1c=hac87e47_0
  - phyml=20160115.patched=hee5dff1_0
  - pip=20.0.2=py36_1
  - pmodeltest=1.4=py36h545a9a4_0
  - pthread-stubs=0.4=h14c3975_1001
  - pyqt=5.9.2=py36hcca6a23_4
  - python=3.6.7=h357f687_1006
  - qt=5.9.7=h52cfd70_2
  - raxml=8.2.11=h6db2ed4_0
  - readline=8.0=hf8c457e_0
  - samtools=1.3.1=h0592bc0_6
  - scipy=1.4.1=py36h921218d_0
  - setuptools=45.1.0=py36_0
  - sip=4.19.8=py36hf484d3e_0
  - six=1.14.0=py36_0
  - slr=1.4.3=h69822e3_0
  - sqlite=3.30.1=hcee41ef_0
  - t_coffee=11.00=h99d273f_0
  - tbl2asn=25.7=0
  - tk=8.6.10=hed695b0_0
  - trimal=1.4=h87cb4c3_0
  - wheel=0.34.2=py36_0
  - xorg-fixesproto=5.0=h14c3975_1002
  - xorg-inputproto=2.3.2=h14c3975_1002
  - xorg-kbproto=1.0.7=h14c3975_1002
  - xorg-libice=1.0.10=h516909a_0
  - xorg-libsm=1.2.3=h84519dc_1000
  - xorg-libx11=1.6.9=h516909a_0
  - xorg-libxau=1.0.9=h14c3975_0
  - xorg-libxdmcp=1.1.3=h516909a_0
  - xorg-libxext=1.3.4=h516909a_0
  - xorg-libxfixes=5.0.3=h516909a_1004
  - xorg-libxi=1.7.10=h516909a_0
  - xorg-libxrender=0.9.10=h516909a_1002
  - xorg-libxtst=1.2.3=h516909a_1002
  - xorg-recordproto=1.14.2=h516909a_1002
  - xorg-renderproto=0.11.1=h14c3975_1002
  - xorg-xextproto=7.3.0=h14c3975_1002
  - xorg-xproto=7.0.31=h14c3975_1007
  - xz=5.2.4=h14c3975_1001
  - zlib=1.2.11=h516909a_1006
  - zstd=1.4.4=h3b9ef0a_1
```

```bash
conda env create -n mitozEnv -f mitoz.yml
conda activate mitozEnv
conda install -c etetoolkit ete3
conda install -c bioconda tbl2asn
```
2. Norgal
```bash
git clone https://bitbucket.org/kosaidtu/norgal.git
cd norgal
vim ~/.bashrc
export PATH="/home/genome1/mitochondria_assembly/tools/norgal:$PATH"
norgal.py -h
```
3. mitoMaker
MitoMaker is dependent on python2.7
```bash
wget https://master.dl.sourceforge.net/project/mitomaker/mitoMaker_1.14.tar.gz
conda create -n py2.7 python=2.7
conda activate py2.7
python test.py
```
4. mitobim
```bash
wget https://excellmedia.dl.sourceforge.net/project/mira-assembler/MIRA/stable/mira_4.0.2_linux-gnu_x86_64_static.tar.bz2

bunzip2 -d mira_4.0.2_linux-gnu_x86_64_static.tar.bz2
tar xf mira_4.0.2_linux-gnu_x86_64_static.tar
cd mira_4.0.2_linux-gnu_x86_64_static/bin
vim ~/.bashrc
export PATH="/home/genome1/mitochondria_assembly/tools/mira_4.0.2_linux-gnu_x86_64_static/bin:$PATH"
source ~/.bashrc
```
5. Novoplasty
6. Getorganelle
```bash
conda create -n getorganelle
conda activate getorganelle
conda install -c bioconda getorganelle
```

7. IGOA
```
conda create -n ioga python=2 wget matplotlib biopython
conda activate ioga
pip install wget
pip install matplotlib
pip install biopython
```