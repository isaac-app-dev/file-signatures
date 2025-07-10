| Offset | Extension | Description | Python3 Hex Signature |
|--------|-----------|-------------|:------------------------|
| 0 | txt others | UTF-16BE byte order mark, commonly seen in text files. [ 28 ] [ 29 ] [ 30 ] | `b"\xFE\xFF"` |
| 0 | - | JKS Javakey Store [ 32 ] | `b"\xFE\xED\xFE\xED"` |
| 0 | zoo | Zoo (file format) | `b"\x5A\x4F\x4F"` |
| 0 | exe | DOS ZM executable and its descendants (rare) | `b"\x5A\x4D"` |
| 0 | txt others | UTF-32LE byte order mark for text [ 28 ] [ 30 ] | `b"\xFF\xFE\x00\x00"` |
| 0 | txt others | UTF-16LE byte order mark, commonly seen in text files. [ 28 ] [ 29 ] [ 30 ] | `b"\xFF\xFE"` |
| 0 | mp3 | MPEG-1 Layer 3 file without an ID3 tag or with an ID3v 1 tag (which is appended at the end of the file) | `b"\xFF\xFB\xFF\xF3\xFF\xF2"` |
| 0 | - | UTF-EBCDIC byte order mark for text [ 31 ] [ 30 ] | `b"\xDD\x73\x66\x73"` |
| 0 | jpg jpeg | JPEG raw or in the JFIF or Exif file format [ 17 ] | `b"\xFF\xD8\xFF\xDB"` |
| 0 | jp2 j2k jpf jpm jpg2 j2c jpc jpx mj2 | JPEG 2000 format [ 18 ] | `b"\xFF\x4F\xFF\x51"` |
| 0 | jpg jpeg | JPEG raw or in the JFIF or Exif file format [ 17 ] | `b"\xFF\xD8\xFF\xEE"` |
| 0 | jpg jpeg | JPEG raw or in the JFIF or Exif file format [ 17 ] | `b"\xFF\xD8\xFF\xE0\x00\x10\x4A\x46\x49\x46\x00\x01"` |
| 0 | jpg jpeg | JPEG raw or in the JFIF or Exif file format [ 17 ] | `b"\xFF\xD8\xFF\xE1\x??\x??\x45\x78\x69\x66\x00\x00"` |
| 0 | jpg | JPEG raw or in the JFIF or Exif file format [ 17 ] | `b"\xFF\xD8\xFF\xE0"` |
| 0 | xz tar.xz | XZ compression utility using LZMA2 compression | `b"\xFD\x37\x7A\x58\x5A\x00"` |
| 0 | jxl | Image encoded in the JPEG XL format [ 89 ] | `b"\xFF\x0A"` |
| 0 | pbt pdt pea peb pet pgt pict pjt pkt pmt | PhotoCap Template | `b"\x78\x56\x34"` |
| 0 | zlib | Best Compression (with preset dictionary) | `b"\x78\xF9"` |
| 0 | zlib | Best Compression (no preset dictionary) | `b"\x78\xDA"` |
| 0 | dpx | SMPTE DPX image | `b"\x58\x50\x44\x53\x(\xlittle-endian\xformat)"` |
| 0 | zlib | Default Compression (no preset dictionary) | `b"\x78\x9C"` |
| 0 | dcr | Adobe Shockwave [ 81 ] [ 82 ] [ 83 ] | `b"\x58\x46\x49\x52\x??\x??\x??\x??\x4D\x44\x47\x46\x(little-endian)"` |
| 0 | dir dxr drx | Macromedia Director file format [ 84 ] [ 82 ] [ 83 ] | `b"\x58\x46\x49\x52\x??\x??\x??\x??\x33\x39\x56\x4D\x(little-endian)"` |
| 0 | xar | eXtensible ARchive format [ 51 ] | `b"\x78\x61\x72\x21"` |
| 0 | zlib | No Compression (with preset dictionary) | `b"\x78\x20"` |
| 0 | zlib | No Compression (no preset dictionary) | `b"\x78\x01"` |
| 0 | zlib | Best speed (no preset dictionary) | `b"\x78\x5E"` |
| 0 | zlib | Best speed (with preset dictionary) | `b"\x78\x7D"` |
| 0 | zlib | Default Compression (with preset dictionary) | `b"\x78\xBB"` |
| 0 | woff | WOFF File Format 1.0 [ 63 ] | `b"\x77\x4F\x46\x46"` |
| 0 | woff2 | WOFF File Format 2.0 [ 64 ] | `b"\x77\x4F\x46\x32"` |
| 0 | - | Resource file Visionaire 3.x Engine | `b"\x56\x49\x53\x33"` |
| 0 | vhdx | Windows Virtual PC Windows 8 Virtual Hard Disk file format | `b"\x76\x68\x64\x78\x66\x69\x6C\x65"` |
| 0 | exr | OpenEXR image | `b"\x76\x2F\x31\x01"` |
| 0 | pcv | PhotoCap Vector | `b"\x55\x55\xAA\xAA"` |
| 0 | tox | Open source portable voxel file [ 57 ] | `b"\x74\x6F\x78\x33"` |
| 0 | TDF$ | Telegram Desktop File | `b"\x54\x44\x46\x24"` |
| 0 | TDEF | Telegram Desktop Encrypted File | `b"\x54\x44\x45\x46"` |
| 0 | - | Microsoft Tape Format | `b"\x54\x41\x50\x45"` |
| 0 | ?? _ | Microsoft compressed file in Quantum format, used prior to Windows XP. File can be decompressed using Extract.exe or Expand.exe distributed with earlier versions of Windows. After compression, the last character of the original filename extension is replaced with an underscore , e.g. ‘Setup.exe’ becomes ‘Setup.ex_’. | `b"\x53\x5A\x44\x44\x88\xF0\x27\x33"` |
| 0 | ??_ | Windows 9x Compressed File | `b"\x53\x5A\x44\x44"` |
| 0 | sqlitedb sqlite db | SQLite Database [ 5 ] | `b"\x53\x51\x4C\x69\x74\x65\x20\x66\x6F\x72\x6D\x61\x74\x20\x33\x00"` |
| 0 | bin | Amazon Kindle Update Package [ 6 ] | `b"\x53\x50\x30\x31"` |
| 0 | ssp | SmartSniff Packets File [ 22 ] | `b"\x53\x4D\x53\x4E\x46\x32\x30\x30"` |
| 0 | fits | Flexible Image Transport System ( FITS ) [ 41 ] | `b"\x53\x49\x4D\x50\x4C\x45\x20\x20\x3D\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x20\x54"` |
| 0 | rc | RCFile columnar file format | `b"\x53\x45\x51\x36"` |
| 0 | dpx | SMPTE DPX image | `b"\x53\x44\x50\x58\x(\xbig-endian\xformat)"` |
| 0 | rs | QuickZip rs compressed archive [ 79 ] [ 80 ] | `b"\x52\x53\x56\x4B\x44\x41\x54\x41"` |
| 0 | - | Compressed file using Rob Northen Compression (version 1 and 2) algorithm [ 14 ] | `b"\x52\x4E\x43\x01\x52\x4E\x43\x02"` |
| 0 | - | Vormetric Encryption DPM Version 2.1 Header [ 96 ] | `b"\x52\x4b\x4d\x43\x32\x31\x30"` |
| 0 | dir dxr drx | Macromedia Director file format [ 84 ] [ 82 ] [ 83 ] | `b"\x52\x49\x46\x58\x??\x??\x??\x??\x4D\x56\x39\x33\x(big-endian)"` |
| 0 | dcr | Adobe Shockwave [ 81 ] [ 82 ] [ 83 ] | `b"\x52\x49\x46\x58\x??\x??\x??\x??\x46\x47\x44\x4D\x(big-endian)"` |
| 0 | webp | Google WebP image file, where ?? ?? ?? ?? is the file size. More information on WebP File Header | `b"\x52\x49\x46\x46\x??\x??\x??\x??\x57\x45\x42\x50"` |
| 0 | wav | Waveform Audio File Format [ 38 ] | `b"\x52\x49\x46\x46\x??\x??\x??\x??\x57\x41\x56\x45"` |
| 0 | vdr | VirtualDub | `b"\x52\x49\x46\x46\x??\x??\x??\x??\x56\x44\x52\x4d"` |
| 0 | trd | TrID | `b"\x52\x59\x46\x46\x??\x??\x??\x??\x54\x52\x49\x44"` |
| 0 | shw | Corel SHOW! 5.0 | `b"\x52\x49\x46\x46\x??\x??\x??\x??\x73\x68\x77\x35"` |
| 0 | shw | Corel SHOW! 4.0 | `b"\x52\x49\x46\x46\x??\x??\x??\x??\x73\x68\x77\x34"` |
| 0 | shr | Corel SHOW! 5.0 player | `b"\x52\x49\x46\x46\x??\x??\x??\x??\x73\x68\x72\x35"` |
| 0 | shb | Corel SHOW! 5.0 background | `b"\x52\x49\x46\x46\x??\x??\x??\x??\x73\x68\x62\x35"` |
| 0 | mmm | MacroMind Multimedia Movie or Microsoft Multimedia Movie | `b"\x52\x49\x46\x46\x??\x??\x??\x??\x52\x4d\x4d\x50"` |
| 0 | qcp | Qualcomm PureVoice file format | `b"\x52\x49\x46\x46\x??\x??\x??\x??\x51\x4C\x43\x4D"` |
| 0 | cda | .cda file | `b"\x52\x49\x46\x46\x??\x??\x??\x??\x43\x44\x44\x41"` |
| 0 | avi | Audio Video Interleave video format [ 39 ] | `b"\x52\x49\x46\x46\x??\x??\x??\x??\x41\x56\x49\x20"` |
| 0 | ani | Animated cursor | `b"\x52\x49\x46\x46\x??\x??\x??\x??\x41\x43\x4F\x4E"` |
| 0 | dat hiv | Windows Registry file | `b"\x72\x65\x67\x66"` |
| 0 | eml | Email Message var5 [ citation needed ] | `b"\x52\x65\x63\x65\x69\x76\x65\x64\x3A"` |
| 0 | rar | Roshal ARchive compressed archive v5.00 onwards [ 24 ] | `b"\x52\x61\x72\x21\x1A\x07\x01\x00"` |
| 0 | rar | Roshal ARchive compressed archive v1.50 onwards [ 23 ] | `b"\x52\x61\x72\x21\x1A\x07\x00"` |
| 0 | - | Report Builder file from Digital Metaphors | `b"\x52\x41\x46\x36\x34"` |
| 0 | qoi | QOI - The “Quite OK Image Format” [ 19 ] | `b"\x71\x6f\x69\x66"` |
| 0 | qcow | qcow file format | `b"\x51\x46\x49"` |
| 0 | psafe3 | Password Gorilla Password Database | `b"\x50\x57\x53\x33"` |
| 0 | pwrdata | SAP Power Monitor (version 1.1.0 and higher) data file | `b"\x70\x77\x72\x64\x61\x74\x61"` |
| 0 | ppk | PuTTY private key file version 3 | `b"\x50\x75\x54\x54\x59\x2D\x55\x73\x65\x72\x2D\x4B\x65\x79\x2D\x46\x69\x6C\x65\x2D\x33\x3A"` |
| 0 | ppk | PuTTY private key file version 2 | `b"\x50\x75\x54\x54\x59\x2D\x55\x73\x65\x72\x2D\x4B\x65\x79\x2D\x46\x69\x6C\x65\x2D\x32\x3A"` |
| 0 | dat | Windows Files And Settings Transfer Repository [ 52 ] See also USMT 3.0 (Win XP) [ 53 ] and USMT 4.0 (Win 7) [ 54 ] User Guides | `b"\x50\x4D\x4F\x43\x43\x4D\x4F\x43"` |
| 0 | grp | Windows 3.x Program Manager Program Group file format | `b"\x50\x4D\x43\x43"` |
| 0 | zip aar apk docx epub ipa jar kmz maff msix odp ods odt pk3 pk4 pptx usdz vsdx xlsx xpi whl | zip file format and formats based on it, such as EPUB , JAR , ODF , OOXML | `b"\x50\x4B\x03\x04\x50\x4B\x05\x06\x(empty\xarchive)\x50\x4B\x07\x08\x(spanned\xarchive)"` |
| 0 | - | Apache Parquet columnar file format | `b"\x50\x41\x52\x31"` |
| 0 | ppm | Portable Pixmap binary | `b"\x50\x36\x0A"` |
| 0 | pgm | Portable Gray Map binary | `b"\x50\x35\x0A"` |
| 0 | pbm | Portable bitmap binary | `b"\x50\x34\x0A"` |
| 0 | ppm | Portable Pixmap ASCII | `b"\x50\x33\x0A"` |
| 0 | pgm | Portable Gray Map ASCII | `b"\x50\x32\x0A"` |
| 0 | pbm | Portable bitmap ASCII | `b"\x50\x31\x0A"` |
| 0 | otf | OpenType font [ 90 ] | `b"\x4F\x54\x54\x4F"` |
| 0 | orc | Apache ORC (Optimized Row Columnar) file format | `b"\x4F\x52\x43"` |
| 0 | ogg oga ogv | Ogg , an open source media container format | `b"\x4F\x67\x67\x53"` |
| 0 | ucas | Unreal Engine Compressed Asset Storage file | `b"\x8C\x0A\x00"` |
| 0 | avro | Apache Avro binary file format | `b"\x4F\x62\x6A\x01"` |
| 0 | oar | OAR file archive format, where ?? is the format version. | `b"\x4F\x41\x52\x??"` |
| 0 | pcap | Libpcap File Format [ 2 ] | `b"\xD4\xC3\xB2\xA1\x(\xlittle-endian\x)"` |
| 0 | nui nup | nuru ASCII/ANSI image and palette files [ 15 ] | `b"\x4E\x55\x52\x55\x49\x4D\x47\x4E\x55\x52\x55\x50\x41\x4C"` |
| 0 | nes | Nintendo Entertainment System ROM file [ 55 ] | `b"\x4E\x45\x53\x1A"` |
| 0 | nes | Nintendo Entertainment System image file | `b"\x4E\x45\x53"` |
| 0 | exe dll mui sys scr cpl ocx ax iec ime rs tsp fon efi | DOS MZ executable and its descendants (including NE and PE ) | `b"\x4D\x5A"` |
| 0 | mid midi | MIDI sound file [ 43 ] | `b"\x4D\x54\x68\x64"` |
| 0 | wim swm esd | Windows Imaging Format file | `b"\x4D\x53\x57\x49\x4D\x00\x00\x00\xD0\x00\x00\x00\x00"` |
| 0 | hl7 | Health Level Seven (HL7) Standard for electronic data exchange [1] | `b"\x4D\x53\x48\x7C\x42\x53\x48\x7C"` |
| 0 | cab | Microsoft Cabinet file | `b"\x4D\x53\x43\x46"` |
| 0 | tif tiff | BigTIFF [ 11 ] | `b"\x4D\x4D\x00\x2B\x(big-endian)"` |
| 0 | tif tiff | Tagged Image File Format (TIFF) [ 10 ] | `b"\x4D\x4D\x00\x2A\x(big-endian)"` |
| 0 | MLV | Magic Lantern Video file [ 58 ] | `b"\x4D\x4C\x56\x49"` |
| 0 | stg | "SEAN : Session Analysis" Training file. Also used in compatible software "Rpw : Rowperfect for Windows" and "RP3W : ROWPERFECT3 for Windows". | `b"\x4D\x49\x4C\x20"` |
| 0 | m | M2 Archive, used by game developer M2 | `b"\x6D\x64\x66\x00"` |
| 0 | mgw | Nintendo Game & Watch image file | `b"\x6D\x61\x69\x6E\x2E\x62\x73"` |
| 0 | pcap | Libpcap File Format (nanosecond-resolution) [ 2 ] | `b"\x4D\x3C\xB2\xA1\x(little-endian)"` |
| 0 | lz | lzip compressed file [ 20 ] | `b"\x4C\x5A\x49\x50"` |
| 0 | evt | Windows Event Viewer file format | `b"\x4C\x66\x4C\x65"` |
| 0 | ??_ | Windows 3.1x Compressed File | `b"\x4B\x57\x41\x4A"` |
| 0 | pak | Capcom RE Engine game data archives | `b"\x4B\x50\x4B\x41"` |
| 0 | vmdk | VMDK files [ 45 ] [ 46 ] | `b"\x4B\x44\x4D"` |
| 0 | icm | ICC profile | `b"\x4B\x43\x4D\x53"` |
| 0 | - | Preferred Executable Format | `b"\x4A\x6F\x79\x21"` |
| 0 | wad | internal WAD (main resource file of Doom ) [ 7 ] | `b"\x49\x57\x41\x44"` |
| 0 | - | Mach-O binary (reverse byte ordering scheme, 64-bit) [ 33 ] | `b"\xCF\xFA\xED\xFE"` |
| 0 | - | Mach-O binary (reverse byte ordering scheme, 32-bit) [ 33 ] | `b"\xCE\xFA\xED\xFE"` |
| 0 | chm | MS Windows HtmlHelp Data | `b"\x49\x54\x53\x46\x03\x00\x00\x00\x60\x00\x00\x00"` |
| 0 | isz | Compressed ISO image | `b"\x49\x73\x5A\x21"` |
| 0 | cab | InstallShield CAB Archive File | `b"\x49\x53\x63\x28"` |
| 0 | idx | AmiBack Amiga Backup index file | `b"\x49\x4E\x44\x58"` |
| 0 | tif tiff | BigTIFF [ 11 ] | `b"\x49\x49\x2B\x00\x(little-endian)"` |
| 0 | cr2 | Canon RAW Format Version 2 [ 12 ] Canon's RAW format is based on TIFF. [ 13 ] | `b"\x49\x49\x2A\x00\x10\x00\x00\x00\x43\x52"` |
| 0 | tif tiff | Tagged Image File Format (TIFF) [ 10 ] | `b"\x49\x49\x2A\x00\x(little-endian)"` |
| 0 | mp3 | MP3 file with an ID3v2 container | `b"\x49\x44\x33"` |
| 0 | icns | Apple Icon Image format | `b"\x69\x63\x6e\x73"` |
| 0 | txt others | UTF-8 byte order mark , commonly seen in text files. [ 28 ] [ 29 ] [ 30 ] | `b"\xEF\xBB\xBF"` |
| 0 | rpm | RedHat Package Manager (RPM) package [ 4 ] | `b"\xED\xAB\xEE\xDB"` |
| 0 | lep | Lepton compressed JPEG image [ 67 ] | `b"\xCF\x84\x01"` |
| 0 | hazelrules | Noodlesoft Hazel [ 95 ] | `b"\x48\x5a\x4c\x52\x00\x00\x00\x18"` |
| 0 | grib grib2 | Gridded data (commonly weather observations or forecasts) in the WMO GRIB or GRIB2 format [ 87 ] | `b"\x47\x52\x49\x42"` |
| 0 | xcf | XCF (file format) | `b"\x67\x69\x6D\x70\x20\x78\x63\x66"` |
| 0 | gif | Image file encoded in the Graphics Interchange Format (GIF) [ 9 ] | `b"\x47\x49\x46\x38\x37\x61\x47\x49\x46\x38\x39\x61"` |
| 0 | g64 | Commodore 64 1541 disk image (G64 format) | `b"\x47\x53\x52\x2D\x31\x35\x34\x31"` |
| 0 | swf | Adobe Flash .swf | `b"\x46\x57\x53"` |
| 0 | cr3 |  | `b"\x66\x74\x79\x70\x63\x72\x78\x43\x52"` |
| 0 | flv | Flash Video file | `b"\x46\x4C\x56"` |
| 0 | flif | Free Lossless Image Format | `b"\x46\x4C\x49\x46"` |
| 0 | flp | FL Studio Project File | `b"\x46\x4C\x68\x64"` |
| 0 | flac | Free Lossless Audio Codec [ 42 ] | `b"\x66\x4C\x61\x43"` |
| 0 | class | Java class file , Mach-O Fat Binary | `b"\xCA\xFE\xBA\xBE"` |
| 0 | Ex01 | EnCase EWF version 2 format | `b"\x45\x56\x46\x32"` |
| 0 | e01 | EnCase EWF version 1 format | `b"\x45\x56\x46"` |
| 0 | toast | Roxio Toast disc image file | `b"\x45\x52\x02\x00\x00\x00"` |
| 0 | ez2 | Emulator Emaxsynth samples | `b"\x45\x4D\x58\x32"` |
| 0 | ez3 iso | Emulator III synth samples | `b"\x45\x4D\x55\x33"` |
| 0 | evtx | Windows Event Viewer XML file format | `b"\x45\x6C\x66\x46\x69\x6C\x65"` |
| 0 | p25 obt | PhotoCap Object Templates | `b"\x65\x87\x78\x56"` |
| 0 | com | CP/M 3 and higher with overlays [ 27 ] | `b"\xC9"` |
| 0 | drc | 3D model compressed with Google Draco [ 86 ] | `b"\x44\x52\x41\x43\x4F"` |
| 0 | pl | Interleaf PrinterLeaf / WorldView document format (now Broadvision QuickSilver) | `b"\xD0\x4F\x50\x53"` |
| 0 | doc xls ppt msi msg | Compound File Binary Format , a container format defined by Microsoft COM. It can contain the equivalent of files and directories. It is used by Windows Installer and for documents in older versions of Microsoft Office . [ 44 ] It can be used by other programs as well that rely on the COM and OLE API's. | `b"\xD0\xCF\x11\xE0\xA1\xB1\x1A\xE1"` |
| 0 | dex | Dalvik Executable | `b"\x64\x65\x78\x0A\x30\x33\x35\x00"` |
| 0 | - | Windows Update Binary Delta Compression file [ 59 ] | `b"\x44\x43\x4D\x01\x50\x41\x33\x30\x50\x41\x33\x30"` |
| 0 | daa | Direct Access Archive PowerISO | `b"\x44\x41\x41"` |
| 0 | swf | Adobe Flash .swf | `b"\x43\x57\x53"` |
| 0 | voc | Creative Voice file | `b"\x43\x72\x65\x61\x74\x69\x76\x65\x20\x56\x6F\x69\x63\x65\x20\x46\x69\x6C\x65\x1A\x1A\x00"` |
| 0 | crx | Google Chrome extension [ 47 ] or packaged app [ 48 ] | `b"\x43\x72\x32\x34"` |
| 0 | vhd | Windows Virtual PC Virtual Hard Disk file format [ 85 ] | `b"\x63\x6F\x6E\x65\x63\x74\x69\x78"` |
| 0 | P00 (P01, P02,...) | Commodore 64 binary file (source: *.P00 format for Power64 emulator ) | `b"\x43\x36\x34\x46\x69\x6C\x65\x00"` |
| 0 | t64 | Commodore 64 tape image | `b"\x43\x36\x34\x20\x74\x61\x70\x65\x20\x69\x6D\x61\x67\x65\x20\x66\x69\x6C\x65"` |
| 0 | crt | Commodore 64 cartridge image | `b"\x43\x36\x34\x20\x43\x41\x52\x54\x52\x49\x44\x47\x45\x20\x20\x20"` |
| 0 | bz2 | Compressed file using Bzip2 algorithm | `b"\x42\x5A\x68"` |
| 0 | lzfse | LZFSE - Lempel-Ziv style data compression algorithm using Finite State Entropy coding. OSS by Apple. [ 70 ] | `b"\x62\x76\x78\x32"` |
| 0 | plist | Binary Property List file | `b"\x62\x70\x6C\x69\x73\x74"` |
| 0 | bpg | Better Portable Graphics format [ 16 ] | `b"\x42\x50\x47\xFB"` |
| 0 | alias | macOS file Alias [ 73 ] ( Symbolic link ) | `b"\x62\x6F\x6F\x6B\x00\x00\x00\x00\x6D\x61\x72\x6B\x00\x00\x00\x00"` |
| 0 | bmp dib | BMP file, a bitmap format used mostly in the Windows world | `b"\x42\x4D"` |
| 0 | blend | Blender File Format [ 88 ] | `b"\x42\x4C\x45\x4E\x44\x45\x52"` |
| 0 | bac | AmiBack Amiga Backup data file | `b"\x42\x41\x43\x4B\x4D\x49\x4B\x45\x44\x49\x53\x4B"` |
| 0 | djvu djv | DjVu document The following byte is either 55 ( U ) for single-page or 4D ( M ) for multi-page documents. | `b"\x41\x54\x26\x54\x46\x4F\x52\x4D\x??\x??\x??\x??\x44\x4A\x56"` |
| 0 | e57 | ASTM E57 3D file format | `b"\x41\x53\x54\x4d\x2d\x45\x35\x37"` |
| 0 | arc | Capcom MT Framework game data archives | `b"\x41\x52\x43"` |
| 0 | arc cdx | FreeArc file | `b"\x41\x72\x43"` |
| 0 | fh8 | FreeHand 8 document [ 49 ] [ 50 ] | `b"\x41\x47\x44\x33"` |
| 0 | aff | Advanced Forensics Format | `b"\x41\x46\x46"` |
| 0 | sys | Crowdstrike Channel File | `b"\xaa\xaa\xaa\xaa"` |
| 0 | DBA | Palm Desktop Calendar Archive | `b"\xBE\xBA\xFE\xCA"` |
| 0 | cpio | cpio archive file [ 21 ] | `b"\x30\x37\x30\x37\x30\x37"` |
| 0 | flm | FL Studio Mobile Project File | `b"\x31\x30\x4C\x46"` |
| 0 | psd | Photoshop Document file, Adobe Photoshop 's native file format | `b"\x38\x42\x50\x53"` |
| 0 | 7z | 7-Zip File Format | `b"\x37\x7A\xBC\xAF\x27\x1C"` |
| 0 | kdb | KDB file | `b"\x37\x48\x03\x02\x00\x00\x00\x00\x58\x35\x30\x39\x4B\x45\x59"` |
| 0 | vpk | VPK file, used to store game data for some Source Engine games | `b"\x34\x12\xAA\x55"` |
| 0 | asf wma wmv | Advanced Systems Format [ 37 ] | `b"\x30\x26\xB2\x75\x8E\x66\xCF\x11\xA6\xD9\x00\xAA\x00\x62\xCE\x6C"` |
| 0 | der | DER encoded X.509 certificate | `b"\x30\x82"` |
| 0 | cin | Kodak Cineon image | `b"\x80\x2A\x5F\xD7"` |
| 0 | - | System Deployment Image , a disk image format used by Microsoft | `b"\x24\x53\x44\x49\x30\x30\x30\x31"` |
| 0 | none, .axf, .bin, .elf, .o, .out, .prx, .puff, .ko, .mod, .so | Executable and Linkable Format [ 25 ] | `b"\x7F\x45\x4C\x46"` |
| 0 | tde | Tableau Datasource | `b"\x20\x02\x01\x62\xA0\x1E\xAB\x07\x02\x00\x00\x00"` |
| 0 | z tar.z | compressed file (often tar zip) using Lempel-Ziv-Welch algorithm | `b"\x1F\x9D"` |
| 0 | z tar.z | Compressed file (often tar zip) using LZH algorithm | `b"\x1F\xA0"` |
| 0 | gz tar.gz | GZIP compressed file [ 60 ] | `b"\x1F\x8B"` |
| 0 | luac | Lua bytecode [ 72 ] | `b"\x1B\x4C\x75\x61"` |
| 0 | mkv mka mks mk3d webm | Matroska media container, including WebM | `b"\x1A\x45\xDF\xA3"` |
| 0 | sib | Sibelius Music - Score file | `b"\x0F\x53\x49\x42\x45\x4C\x49\x55\x53"` |
| 0 | txt others | SCSU byte order mark for text [ 31 ] [ 30 ] | `b"\x0E\xFE\xFF"` |
| 0 | wks | DeskMate Worksheet | `b"\x0E\x57\x4B\x53"` |
| 0 | nri | Nero CD Compilation | `b"\x0E\x4E\x65\x72\x6F\x49\x53\x4F"` |
| 0 | cdb | MikroTik WinBox Connection Database (Address Book) | `b"\x0D\xF0\x1D\xC0"` |
| 0 | doc | DeskMate Document file | `b"\x0D\x44\x4F\x43"` |
| 0 | wallet | MultiBit Bitcoin wallet file | `b"\x0A\x16\x6F\x72\x67\x2E\x62\x69\x74\x63\x6F\x69\x6E\x2E\x70\x72"` |
| 0 | pcapng | PCAP Next Generation Dump File Format [ 3 ] | `b"\x0A\x0D\x0D\x0A"` |
| 0 | skf | SkinCrafter skin file | `b"\x07\x53\x4B\x46"` |
| 0 | dtd | DesignTools 2D Design file | `b"\x07\x64\x74\x32\x64\x64\x74\x64"` |
| 0-65535 (run-in) | mxf | Material Exchange Format file | `b"\x06\x0E\x2B\x34\x02\x05\x01\x01\x0D\x01\x02\x01\x01\x02"` |
| 0 | cwk | AppleWorks 6 document | `b"\x06\x07\xE1\x00\x42\x4F\x42\x4F\x06\x07\xE1\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x01"` |
| 0 | indd | Adobe InDesign document | `b"\x06\x06\xED\xF5\xD8\x1D\x46\xE5\xBD\x31\xEF\xE7\xFE\x74\xB7\x1D"` |
| 0 | cwk | AppleWorks 5 document | `b"\x05\x07\x00\x00\x42\x4F\x42\x4F\x05\x07\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x01"` |
| 0 | hdf4 h4 | Data stored in version 4 of the Hierarchical Data Format . | `b"\x0E\x03\x13\x01"` |
| 0 | lz4 | LZ4 Frame Format [ 61 ] Remark: LZ4 block format does not offer any magic bytes. [ 62 ] | `b"\x04\x22\x4D\x18"` |
| 0 | dss | Digital Speech Standard (Olympus, Grundig, & Phillips) v3 | `b"\x03\x64\x73\x73"` |
| 0 | adx | Approach index file | `b"\x03\x00\x00\x00\x41\x50\x50\x52"` |
| 0 | dss | Digital Speech Standard (Olympus, Grundig, & Phillips) v2 | `b"\x02\x64\x73\x73"` |
| 0 | cwk | Claris Works word processing doc | `b"\x02\x00\x5a\x57\x52\x54\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00"` |
| 0 | drw | Micrografx vector graphic file | `b"\x01\xFF\x02\x04\x03\x02"` |
| 0 | wasm | WebAssembly binary format [ 66 ] | `b"\x00\x61\x73\x6D"` |
| 0 | TDA | Palm Desktop Calendar Archive | `b"\x00\x01\x44\x54"` |
| 0 | DBA | Palm Desktop To Do Archive | `b"\x00\x01\x42\x44"` |
| 0 | mdb | Microsoft Access Database | `b"\x00\x01\x00\x00\x53\x74\x61\x6E\x64\x61\x72\x64\x20\x4A\x65\x74\x20\x44\x42"` |
| 0 | accdb | Microsoft Access 2007 Database | `b"\x00\x01\x00\x00\x53\x74\x61\x6E\x64\x61\x72\x64\x20\x41\x43\x45\x20\x44\x42"` |
| 0 | mny | Microsoft Money file | `b"\x00\x01\x00\x00\x4D\x53\x49\x53\x41\x4D\x20\x44\x61\x74\x61\x62\x61\x73\x65"` |
| 0 | ttf tte dfont | TrueType font | `b"\x00\x01\x00\x00\x00"` |
| 0 | - | Palm Desktop Data File ( Access format) | `b"\x00\x01\x00\x00"` |
| 0 | txt others | UTF-32BE byte order mark for text [ 28 ] [ 30 ] | `b"\x00\x00\xFE\xFF"` |
| 0 | qxd | Quark Express document | `b"\x00\x00\x49\x49\x58\x50\x52\x(\xlittle-endian\x)\x00\x00\x4D\x4D\x58\x50\x52\x(\xbig-endian\x)"` |
| 0 | 123 | Lotus 1-2-3 spreadsheet (v9) file | `b"\x00\x00\x1A\x00\x05\x10\x04"` |
| 0 | wk4 wk5 | Lotus 1-2-3 spreadsheet (v4, v5) file | `b"\x00\x00\x1A\x00\x02\x10\x04\x00\x00\x00\x00\x00"` |
| 0 | wk3 | Lotus 1-2-3 spreadsheet (v3) file | `b"\x00\x00\x1A\x00\x00\x10\x04\x00\x00\x00\x00\x00"` |
| 0 | - | Amiga Hunk executable file | `b"\x00\x00\x03\xF3"` |
| 0 | wk1 | Lotus 1-2-3 spreadsheet (v1) file | `b"\x00\x00\x02\x00\x06\x04\x06\x00\x08\x00\x00\x00\x00\x00"` |
| 0 | m2p vob mpg mpeg | MPEG Program Stream (MPEG-1 Part 1 (essentially identical) and MPEG-2 Part 1) | `b"\x00\x00\x01\xBA"` |
| 0 | mpg mpeg | MPEG-1 video and MPEG-2 video (MPEG-1 Part 2 and MPEG-2 Part 2) | `b"\x00\x00\x01\xB3"` |
| 0 | ico | Computer icon encoded in ICO file format [ 8 ] | `b"\x00\x00\x01\x00"` |
| 0 | jxl | Image encoded in the JPEG XL format [ 89 ] | `b"\x00\x00\x00\x0C\x4A\x58\x4C\x20\x0D\x0A\x87\x0A"` |
| 0 | jp2 j2k jpf jpm jpg2 j2c jpc jpx mj2 | JPEG 2000 format [ 18 ] | `b"\x00\x00\x00\x0C\x6A\x50\x20\x20\x0D\x0A\x87\x0A"` |
| 0 | PIC PIF SEA YTR | IBM Storyboard bitmap file Windows Program Information File Mac Stuffit Self-Extracting Archive IRIS OCR data file | `b"\x00"` |
| 0 | - | Serialized Java Data [ 93 ] | `b"\xAC\xED"` |
| 0 | rbxl | Roblox place file [ 71 ] | `b"\x3C\x72\x6F\x62\x6C\x6F\x78\x21"` |
| 0 | vdi | VirtualBox Virtual Hard Disk file format | `b"\x3C\x3C\x3C\x20\x4F\x72\x61\x63\x6C\x65\x20\x56\x4D\x20\x56\x69\x72\x74\x75\x61\x6C\x42\x6F\x78\x20\x44\x69\x73\x6B\x20\x49\x6D\x61\x67\x65\x20\x3E\x3E\x3E"` |
| 0 | wmf | Windows Metafile | `b"\xD7\xCD\xC6\x9A"` |
| 0 | - | UTF-7 byte order mark for text [ 31 ] [ 30 ] | `b"\x2B\x2F\x76\x38\x2B\x2F\x76\x39\x2B\x2F\x76\x2B\x2B\x2F\x76\x2F"` |
| 0 | arj | ARJ | `b"\x60\xEA"` |
| 0 | png | Image encoded in the Portable Network Graphics format [ 26 ] | `b"\x89\x50\x4E\x47\x0D\x0A\x1A\x0A"` |
| 0 | pdf | PDF document [ 36 ] | `b"\x25\x50\x44\x46\x2D"` |
| 0 | eps epsf | Encapsulated PostScript file version 3.1 [ 35 ] | `b"\x25\x21\x50\x53\x2D\x41\x64\x6F\x62\x65\x2D\x33\x2E\x31\x20\x45\x50\x53\x46\x2D\x33\x2E\x30"` |
| 0 | eps epsf | Encapsulated PostScript file version 3.0 [ 34 ] | `b"\x25\x21\x50\x53\x2D\x41\x64\x6F\x62\x65\x2D\x33\x2E\x30\x20\x45\x50\x53\x46\x2D\x33\x2E\x30"` |
| 0 | ps | PostScript document | `b"\x25\x21\x50\x53"` |
| 0 | m3u m3u8 | Multimedia playlist | `b"\x23\x45\x58\x54\x4D\x33\x55"` |
| 0 | - | Modulefile for Environment Modules [ 91 ] | `b"\x23\x25\x4D\x6F\x64\x75\x6C\x65"` |
| 0 | vbe | VBScript Encoded script | `b"\x23\x40\x7E\x5E"` |
| 0 | hdr | Radiance High Dynamic Range image file | `b"\x23\x3F\x52\x41\x44\x49\x41\x4E\x43\x45\x0A"` |
| 0 | sil | Audio compression format developed by Skype | `b"\x23\x21\x53\x49\x4C\x4B\x0A"` |
| 0 | amr | Adaptive Multi-Rate ACELP (Algebraic Code Excited Linear Prediction) Codec, commonly audio format with GSM cell phones. | `b"\x23\x21\x41\x4D\x52"` |
| 0 | - | Script or data to be passed to the program following the shebang (#!) [ 1 ] | `b"\x23\x21"` |
| 0 | dsp | Microsoft Developer Studio project file | `b"\x23\x20\x4D\x69\x63\x72\x6F\x73\x6F\x66\x74\x20\x44\x65\x76\x65\x6C\x6F\x70\x65\x72\x20\x53\x74\x75\x64\x69\x6F"` |
| 0 | vmdk | VMware 4 Virtual Disk description file (split disk) | `b"\x23\x20\x44\x69\x73\x6B\x20\x44\x65\x73\x63\x72\x69\x70\x74\x6F"` |
| 0 | xpm | X PixMap | `b"\x2F\x2A\x20\x58\x50\x4D\x20\x2A\x2F"` |
| 0 | rtf | Rich Text Format | `b"\x7B\x5C\x72\x74\x66\x31"` |
| 0 | Identifier | Microsoft Zone Identifier for URL Security Zones [ 74 ] [ 75 ] | `b"\x5B\x5A\x6F\x6E\x65\x54\x72\x61\x6E\x73\x66\x65\x72\x5D"` |
| 0 | zst | Zstandard compress [ 77 ] [ 78 ] | `b"\x28\xB5\x2F\xFD"` |
| 0 | toast | Roxio Toast disc image file | `b"\x8B\x45\x52\x02\x00\x00\x00"` |
| 0 | - | U-Boot / uImage. Das U-Boot Universal Boot Loader. [ 68 ] | `b"\x27\x05\x19\x56"` |
| 0 | au snd | Au audio file format | `b"\x2E\x73\x6E\x64"` |
| 0 | pgp | PGP file [ 76 ] | `b"\x85\x??\x??\x03"` |
| 0 | arc | ARC archive file | `b"\x1a\x08"` |
| 0 | hlp | Windows 3.x/95/98 Help file | `b"\x3F\x5F"` |
| 0 | pcap | Libpcap File Format [ 2 ] | `b"\xA1\xB2\xC3\xD4\x(\xbig-endian\x)"` |
| 0 | pcap | Libpcap File Format (nanosecond-resolution) [ 2 ] | `b"\xA1\xB2\x3C\x4D\x(big-endian)"` |
| 0 | pst | Microsoft Outlook Personal Storage Table file | `b"\x21\x42\x44\x4E"` |
| 0 | deb | linux deb file | `b"\x21\x3C\x61\x72\x63\x68\x3E\x0A"` |
| 0 | slob | Slob (sorted list of Object storages ) is a read-only, compressed data store with dictionary-like interface [ 92 ] | `b"\x21\x2D\x31\x53\x4C\x4F\x42\x1F"` |
| 0 | cnt | Windows 3.x - Windows 95 Help Contents | `b"\x3a\x42\x61\x73\x65\x20"` |
| 0 | sml | Smile file | `b"\x3A\x29\x0A"` |
| 0 | utoc | Unreal Engine Table of Contents file | `b"\x2D\x3D\x3D\x2D\x2D\x3D\x3D\x2D\x2D\x3D\x3D\x2D\x2D\x3D\x3D\x2D"` |
| 0 | pub | OpenSSH public key file | `b"\x2D\x2D\x2D\x2D\x2D\x42\x45\x47\x49\x4E\x20\x53\x53\x48\x32\x20\x4B\x45\x59\x2D\x2D\x2D\x2D\x2D"` |
| 0 | key pem | PEM encoded X.509 PKCS#1 RSA private key | `b"\x2D\x2D\x2D\x2D\x2D\x42\x45\x47\x49\x4E\x20\x52\x53\x41\x20\x50\x52\x49\x56\x41\x54\x45\x20\x4B\x45\x59\x2D\x2D\x2D\x2D\x2D"` |
| 0 | key pem | PEM encoded X.509 PKCS#8 private key | `b"\x2D\x2D\x2D\x2D\x2D\x42\x45\x47\x49\x4E\x20\x50\x52\x49\x56\x41\x54\x45\x20\x4B\x45\x59\x2D\x2D\x2D\x2D\x2D"` |
| 0 | asc | Armored PGP public key | `b"\x2d\x2d\x2d\x2d\x2d\x42\x45\x47\x49\x4e\x20\x50\x47\x50\x20\x50\x55\x42\x4c\x49\x43\x20\x4b\x45\x49\x20\x42\x4c\x4f\x43\x4b\x2d\x2d\x2d\x2d\x2d"` |
| 0 | - | OpenSSH private key file | `b"\x2D\x2D\x2D\x2D\x2D\x42\x45\x47\x49\x4E\x20\x4F\x50\x45\x4E\x53\x53\x48\x20\x50\x52\x49\x56\x41\x54\x45\x20\x4B\x45\x59\x2D\x2D\x2D\x2D\x2D"` |
| 0 | key pem | PEM encoded X.509 PKCS#1 DSA private key | `b"\x2D\x2D\x2D\x2D\x2D\x42\x45\x47\x49\x4E\x20\x44\x53\x41\x20\x50\x52\x49\x56\x41\x54\x45\x20\x4B\x45\x59\x2D\x2D\x2D\x2D\x2D"` |
| 0 | crt pem | PEM encoded X.509 certificate | `b"\x2D\x2D\x2D\x2D\x2D\x42\x45\x47\x49\x4E\x20\x43\x45\x52\x54\x49\x46\x49\x43\x41\x54\x45\x2D\x2D\x2D\x2D\x2D"` |
| 0 | csr pem | PEM encoded X.509 Certificate Signing Request | `b"\x2D\x2D\x2D\x2D\x2D\x42\x45\x47\x49\x4E\x20\x43\x45\x52\x54\x49\x46\x49\x43\x41\x54\x45\x20\x52\x45\x51\x55\x45\x53\x54\x2D\x2D\x2D\x2D\x2D"` |
| 0 | - | OpenGL Iris Perfomer .PFB (Performer Fast Binary) [ 94 ] | `b"\xDB\x0A\xCE\x00"` |
| 0afterBOM | xml ( EBCDIC ) | eXtensible Markup Language [ 29 ] [ 65 ] | `b"\x4C\x6F\xA7\x94\x93\x40"` |
| 0afterBOM | xml ( UTF-32BE ) | eXtensible Markup Language [ 29 ] [ 65 ] | `b"\x00\x00\x00\x3C\x00\x00\x00\x3F\x00\x00\x00\x78\x00\x00\x00\x6D\x00\x00\x00\x6C\x00\x00\x00\x20"` |
| 0afterBOM | xml ( UTF-16BE ) | eXtensible Markup Language [ 29 ] [ 65 ] | `b"\x00\x3C\x00\x3F\x00\x78\x00\x6D\x00\x6C\x00\x20"` |
| 0afterBOM | xml ( UTF-32LE ) | eXtensible Markup Language [ 29 ] [ 65 ] | `b"\x3C\x00\x00\x00\x3F\x00\x00\x00\x78\x00\x00\x00\x6D\x00\x00\x00\x6C\x00\x00\x00\x20\x00\x00\x00"` |
| 0afterBOM | xml ( UTF-16LE ) | eXtensible Markup Language [ 29 ] [ 65 ] | `b"\x3C\x00\x3F\x00\x78\x00\x6D\x00\x6C\x00\x20"` |
| 0afterBOM | xml ( UTF-8 or other 8-bit encodings) | eXtensible Markup Language [ 29 ] [ 65 ] | `b"\x3C\x3F\x78\x6D\x6C\x20"` |
| 2 | lzh | Lempel Ziv Huffman archive file Method 5 (8 KiB sliding window) | `b"\x00"*2 + b"\x2D\x6C\x68\x35\x2D"` |
| 2 | lzh | Lempel Ziv Huffman archive file Method 0 (No compression) | `b"\x00"*2 + b"\x2D\x6C\x68\x30\x2D"` |
| 00xBC0x178...(every 188th byte) | ts tsv tsa mpg mpeg | MPEG Transport Stream (MPEG-2 Part 1) [ 69 ] | `b"\x47"` |
| 00x1000 | - | Mach-O binary (64-bit) | `b"\xFE\xED\xFA\xCF"` |
| 00x1000 | - | Mach-O binary (32-bit) | `b"\xFE\xED\xFA\xCE"` |
| 0any | yuvn yuv iff | IFF YUV Image | `b"\x46\x4F\x52\x4D\x??\x??\x??\x??\x59\x55\x56\x4E"` |
| 0any | smus smu mus iff | IFF Simple Musical Score | `b"\x46\x4F\x52\x4D\x??\x??\x??\x??\x53\x4D\x55\x53"` |
| 0any | ilbm lbm ibm iff | IFF Interleaved Bitmap Image | `b"\x46\x4F\x52\x4D\x??\x??\x??\x??\x49\x4C\x42\x4D"` |
| 0any | ftxt iff | IFF Formatted Text | `b"\x46\x4F\x52\x4D\x??\x??\x??\x??\x46\x54\x58\x54"` |
| 0any | faxx fax iff | IFF Facsimile Image | `b"\x46\x4F\x52\x4D\x??\x??\x??\x??\x46\x41\x58\x58"` |
| 0any | iff | Amiga Fantavision Movie | `b"\x46\x4F\x52\x4D\x??\x??\x??\x??\x46\x41\x4E\x54"` |
| 0any | cmus mus iff | IFF Musical Score | `b"\x46\x4F\x52\x4D\x??\x??\x??\x??\x43\x4D\x55\x53"` |
| 0any | anim iff | IFF CEL Animation | `b"\x46\x4F\x52\x4D\x??\x??\x??\x??\x41\x4E\x49\x4D"` |
| 0any | anbm iff | IFF Animated Bitmap | `b"\x46\x4F\x52\x4D\x??\x??\x??\x??\x41\x4E\x42\x4D"` |
| 0any | aiff aif aifc snd iff | Audio Interchange File Format | `b"\x46\x4F\x52\x4D\x??\x??\x??\x??\x41\x49\x46\x46"` |
| 0any | acbm iff | Amiga Contiguous Bitmap | `b"\x46\x4F\x52\x4D\x??\x??\x??\x??\x41\x43\x42\x4D"` |
| 0any | 8svx 8sv svx snd iff | IFF 8-Bit Sampled Voice | `b"\x46\x4F\x52\x4D\x??\x??\x??\x??\x38\x53\x56\x58"` |
| 4 | mp4 | MPEG-4 video file | `b"\x00"*4 + b"\x66\x74\x79\x70\x4D\x53\x4E\x56"` |
| 4 | mp4 | ISO Base Media file (MPEG-4) | `b"\x00"*4 + b"\x66\x74\x79\x70\x69\x73\x6F\x6D"` |
| 4 | heic | High Efficiency Image Container (HEIC) | `b"\x00"*4 + b"\x66\x74\x79\x70\x68\x65\x69\x63\x66\x74\x79\x70\x6d"` |
| 4 | 3gp 3g2 | 3rd Generation Partnership Project 3GPP and 3GPP2 multimedia files | `b"\x00"*4 + b"\x66\x74\x79\x70\x33\x67"` |
| 7 | ace | ACE (compressed file format) [ citation needed ] | `b"\x00"*7 + b"\x2A\x2A\x41\x43\x45\x2A\x2A"` |
| 8 | sdb | Windows customized database | `b"\x00"*8 + b"\x73\x64\x62\x66"` |
| 8 | - | DuckDB database file (source: Source code ) | `b"\x00"*8 + b"\x44\x55\x43\x4B"` |
| 11 | PDB | PalmPilot Database/Document File | `b"\x00"*11 + b"\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00"` |
| 128 | dcm | DICOM Medical File Format | `b"\x00"*128 + b"\x44\x49\x43\x4D"` |
| 257 | tar | tar archive [ 56 ] | `b"\x00"*257 + b"\x75\x73\x74\x61\x72\x00\x30\x30\x75\x73\x74\x61\x72\x20\x20\x00"` |
| 344 | hdr | Header file of a .hdr/.img pair in NIfTI format, used extensively in biomedical imaging. | `b"\x00"*344 + b"\x6E\x69\x31\x00"` |
| 344 | nii | Single file NIfTI format, used extensively in biomedical imaging. | `b"\x00"*344 + b"\x6E\x2B\x31\x00"` |
| 0x80010x88010x9001 | iso | ISO9660 CD/DVD image file [ 40 ] | `b"\x43\x44\x30\x30\x31"` |
| 0x165A4 | d64 | Commodore 64 1541 disk image (D64 format) | `b"\xA0\x32\x41\xA0\xA0\xA0"` |
| 0x5EAC9 | cdi | CD-i CD image file | `b"\x43\x44\x30\x30\x31"` |
| 0x61819 | d81 | Commodore 64 1581 disk image (D81 format) | `b"\xA0\x33\x44\xA0\xA0"` |
| end–512 | dmg | Apple Disk Image file | `b"\x6B\x6F\x6C\x79"` |
| 0, 512, 1024, 2048, ... | hdf5 h5 | Data stored in version 5 of the Hierarchical Data Format . | `b"\x89\x48\x44\x46\x0D\x0A\x1A\x0A"` |
