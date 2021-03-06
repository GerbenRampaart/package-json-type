> # package-json-type

## Index

### Interfaces

* [IAuthor](interfaces/iauthor.md)
* [IBinMap](interfaces/ibinmap.md)
* [IBugs](interfaces/ibugs.md)
* [IConfig](interfaces/iconfig.md)
* [IDependencyMap](interfaces/idependencymap.md)
* [IDirectories](interfaces/idirectories.md)
* [IEngines](interfaces/iengines.md)
* [IPackageJson](interfaces/ipackagejson.md)
* [IPublishConfig](interfaces/ipublishconfig.md)
* [IRepository](interfaces/irepository.md)
* [IScriptsMap](interfaces/iscriptsmap.md)

### Type aliases

* [CPU](globals.md#cpu)
* [OS](globals.md#os)
* [SPDXLicenseID](globals.md#spdxlicenseid)
* [SPDXLicenseIDApproved](globals.md#spdxlicenseidapproved)

## Type aliases

###  CPU

Ƭ **CPU**: *"arm" | "arm64" | "ia32" | "mips" | "mipsel" | "ppc" | "ppc64" | "s390" | "s390x" | "x32" | "x64"*

*Defined in [index.ts:716](https://github.com/ajaxlab/package-json-type/blob/5df272e/src/index.ts#L716)*

It checks against `process.arc`.

**`see`** https://docs.npmjs.com/files/package.json#cpu

**`see`** https://yarnpkg.com/en/docs/package-json#toc-cpu

**`see`** https://nodejs.org/api/process.html#process_process_arch

___

###  OS

Ƭ **OS**: *"aix" | "android" | "darwin" | "freebsd" | "linux" | "openbsd" | "sunos" | "win32" | "cygwin"*

*Defined in [index.ts:734](https://github.com/ajaxlab/package-json-type/blob/5df272e/src/index.ts#L734)*

You can specify which operating systems your module will run on

**`see`** https://docs.npmjs.com/files/package.json#os

**`see`** https://yarnpkg.com/en/docs/package-json#toc-os

**`see`** https://nodejs.org/api/process.html#process_process_platform

___

###  SPDXLicenseID

Ƭ **SPDXLicenseID**: *"Abstyles" | "Adobe-2006" | "Adobe-Glyph" | "ADSL" | "Afmparse" | "AGPL-1.0-only" | "AGPL-1.0-or-later" | "Aladdin" | "AMDPLPA" | "AML" | "AMPAS" | "ANTLR-PD" | "Apache-1.0" | "APAFML" | "Bahyph" | "Barr" | "Beerware" | "BitTorrent-1.0" | "BitTorrent-1.1" | "Borceux" | "BSD-1-Clause" | "BSD-2-Clause-FreeBSD" | "BSD-2-Clause-NetBSD" | "BSD-3-Clause-Attribution" | "BSD-3-Clause-Clear" | "BSD-3-Clause-LBNL" | "BSD-3-Clause-No-Nuclear-License" | "BSD-3-Clause-No-Nuclear-License-2014" | "BSD-3-Clause-No-Nuclear-Warranty" | "BSD-4-Clause" | "BSD-4-Clause-UC" | "BSD-Protection" | "BSD-Source-Code" | "bzip2-1.0.5" | "bzip2-1.0.6" | "Caldera" | "CC-BY-1.0" | "CC-BY-2.0" | "CC-BY-2.5" | "CC-BY-3.0" | "CC-BY-4.0" | "CC-BY-NC-1.0" | "CC-BY-NC-2.0" | "CC-BY-NC-2.5" | "CC-BY-NC-3.0" | "CC-BY-NC-4.0" | "CC-BY-NC-ND-1.0" | "CC-BY-NC-ND-2.0" | "CC-BY-NC-ND-2.5" | "CC-BY-NC-ND-3.0" | "CC-BY-NC-ND-4.0" | "CC-BY-NC-SA-1.0" | "CC-BY-NC-SA-2.0" | "CC-BY-NC-SA-2.5" | "CC-BY-NC-SA-3.0" | "CC-BY-NC-SA-4.0" | "CC-BY-ND-1.0" | "CC-BY-ND-2.0" | "CC-BY-ND-2.5" | "CC-BY-ND-3.0" | "CC-BY-ND-4.0" | "CC-BY-SA-1.0" | "CC-BY-SA-2.0" | "CC-BY-SA-2.5" | "CC-BY-SA-3.0" | "CC-BY-SA-4.0" | "CC0-1.0" | "CDDL-1.1" | "CDLA-Permissive-1.0" | "CDLA-Sharing-1.0" | "CECILL-1.0" | "CECILL-1.1" | "CECILL-2.0" | "CECILL-B" | "CECILL-C" | "CERN-OHL-1.1" | "CERN-OHL-1.2" | "ClArtistic" | "CNRI-Jython" | "CNRI-Python-GPL-Compatible" | "Condor-1.1" | "copyleft-next-0.3.0" | "copyleft-next-0.3.1" | "CPOL-1.02" | "Crossword" | "CrystalStacker" | "Cube" | "curl" | "D-FSL-1.0" | "diffmark" | "DOC" | "Dotseqn" | "DSDP" | "dvipdfm" | "eGenix" | "ErlPL-1.1" | "EUPL-1.0" | "Eurosym" | "FreeImage" | "FSFAP" | "FSFUL" | "FSFULLR" | "FTL" | "GFDL-1.1-only" | "GFDL-1.1-or-later" | "GFDL-1.2-only" | "GFDL-1.2-or-later" | "GFDL-1.3-only" | "GFDL-1.3-or-later" | "Giftware" | "GL2PS" | "Glide" | "Glulxe" | "gnuplot" | "GPL-1.0-only" | "GPL-1.0-or-later" | "gSOAP-1.3b" | "HaskellReport" | "HPND-sell-variant" | "IBM-pibs" | "ICU" | "IJG" | "ImageMagick" | "iMatix" | "Imlib2" | "Info-ZIP" | "Intel-ACPI" | "Interbase-1.0" | "JasPer-2.0" | "JPNIC" | "JSON" | "LAL-1.2" | "LAL-1.3" | "Latex2e" | "Leptonica" | "LGPLLR" | "Libpng" | "libpng-2.0" | "libtiff" | "Linux-OpenIB" | "LPPL-1.0" | "LPPL-1.1" | "LPPL-1.2" | "LPPL-1.3a" | "MakeIndex" | "MIT-advertising" | "MIT-CMU" | "MIT-enna" | "MIT-feh" | "MITNFA" | "mpich2" | "MTLL" | "Mup" | "NBPL-1.0" | "Net-SNMP" | "NetCDF" | "Newsletr" | "NLOD-1.0" | "NLPL" | "NOSL" | "Noweb" | "NPL-1.0" | "NPL-1.1" | "NRL" | "OCCT-PL" | "ODbL-1.0" | "ODC-By-1.0" | "OFL-1.0" | "OGL-UK-1.0" | "OGL-UK-2.0" | "OGL-UK-3.0" | "OLDAP-1.1" | "OLDAP-1.2" | "OLDAP-1.3" | "OLDAP-1.4" | "OLDAP-2.0" | "OLDAP-2.0.1" | "OLDAP-2.1" | "OLDAP-2.2" | "OLDAP-2.2.1" | "OLDAP-2.2.2" | "OLDAP-2.3" | "OLDAP-2.4" | "OLDAP-2.5" | "OLDAP-2.6" | "OLDAP-2.7" | "OLDAP-2.8" | "OML" | "OpenSSL" | "OPL-1.0" | "OSL-1.1" | "PDDL-1.0" | "PHP-3.01" | "Plexus" | "psfrag" | "psutils" | "Qhull" | "Rdisc" | "RHeCos-1.1" | "RSA-MD" | "Ruby" | "SAX-PD" | "Saxpath" | "SCEA" | "Sendmail" | "Sendmail-8.23" | "SGI-B-1.0" | "SGI-B-1.1" | "SGI-B-2.0" | "SISSL-1.2" | "SMLNJ" | "SMPPL" | "SNIA" | "Spencer-86" | "Spencer-94" | "Spencer-99" | "SugarCRM-1.1.3" | "SWL" | "TAPR-OHL-1.0" | "TCL" | "TCP-wrappers" | "TMate" | "TORQUE-1.1" | "TOSL" | "TU-Berlin-1.0" | "TU-Berlin-2.0" | "Unicode-DFS-2015" | "Unicode-DFS-2016" | "Unicode-TOU" | "Unlicense" | "Vim" | "VOSTROM" | "W3C-19980720" | "W3C-20150513" | "Wsuipa" | "WTFPL" | "X11" | "Xerox" | "XFree86-1.1" | "xinetd" | "xpp" | "XSkat" | "YPL-1.0" | "YPL-1.1" | "Zed" | "Zend-2.0" | "Zimbra-1.3" | "Zimbra-1.4" | "zlib-acknowledgement" | "ZPL-1.1" | "ZPL-2.1"*

*Defined in [index.ts:748](https://github.com/ajaxlab/package-json-type/blob/5df272e/src/index.ts#L748)*

SPDX License IDs which are not OSI approved.

**`see`** https://spdx.org/licenses/

___

###  SPDXLicenseIDApproved

Ƭ **SPDXLicenseIDApproved**: *"0BSD" | "AAL" | "AFL-1.1" | "AFL-1.2" | "AFL-2.0" | "AFL-2.1" | "AFL-3.0" | "AGPL-3.0-only" | "AGPL-3.0-or-later" | "Apache-1.1" | "Apache-2.0" | "APL-1.0" | "APSL-1.0" | "APSL-1.1" | "APSL-1.2" | "APSL-2.0" | "Artistic-1.0" | "Artistic-1.0-cl8" | "Artistic-1.0-Perl" | "Artistic-2.0" | "BSD-2-Clause" | "BSD-2-Clause-Patent" | "BSD-3-Clause" | "BSL-1.0" | "CATOSL-1.1" | "CDDL-1.0" | "CECILL-2.1" | "CNRI-Python" | "CPAL-1.0" | "CPL-1.0" | "CUA-OPL-1.0" | "ECL-1.0" | "ECL-2.0" | "EFL-1.0" | "EFL-2.0" | "Entessa" | "EPL-1.0" | "EPL-2.0" | "EUDatagrid" | "EUPL-1.1" | "EUPL-1.2" | "Fair" | "Frameworx-1.0" | "GPL-2.0-only" | "GPL-2.0-or-later" | "GPL-3.0-only" | "GPL-3.0-or-later" | "HPND" | "Intel" | "IPA" | "IPL-1.0" | "ISC" | "LGPL-2.0-only" | "LGPL-2.0-or-later" | "LGPL-2.1-only" | "LGPL-2.1-or-later" | "LGPL-3.0-only" | "LGPL-3.0-or-later" | "LiLiQ-P-1.1" | "LiLiQ-R-1.1" | "LiLiQ-Rplus-1.1" | "LPL-1.0" | "LPL-1.02" | "LPPL-1.3c" | "MirOS" | "MIT" | "MIT-0" | "Motosoto" | "MPL-1.0" | "MPL-1.1" | "MPL-2.0" | "MPL-2.0-no-copyleft-exception" | "MS-PL" | "MS-RL" | "Multics" | "NASA-1.3" | "Naumen" | "NCSA" | "NGPL" | "Nokia" | "NPOSL-3.0" | "NTP" | "OCLC-2.0" | "OFL-1.1" | "OGTSL" | "OSET-PL-2.1" | "OSL-1.0" | "OSL-2.0" | "OSL-2.1" | "OSL-3.0" | "PHP-3.0" | "PostgreSQL" | "Python-2.0" | "QPL-1.0" | "RPL-1.1" | "RPL-1.5" | "RPSL-1.0" | "RSCPL" | "SimPL-2.0" | "SISSL" | "Sleepycat" | "SPL-1.0" | "UPL-1.0" | "VSL-1.0" | "W3C" | "Watcom-1.0" | "Xnet" | "Zlib" | "ZPL-2.0"*

*Defined in [index.ts:804](https://github.com/ajaxlab/package-json-type/blob/5df272e/src/index.ts#L804)*

SPDX License IDs which are approved by OSI.

**`see`** https://spdx.org/licenses/