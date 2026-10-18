# Third-Party Notices & Licenses

This document contains licensing notices and acknowledgments for third-party fonts, icons, software components, and external runtime tools utilized by or recommended for **VinylWave**.

---

## 1. Font Awesome 6 Free Solid

- **Component:** TrueType Icon Font (`FontAwesome.ttf`)
- **Font Family:** Font Awesome 6 Free Solid (Version 6.7.2)
- **Copyright:** Copyright (c) Font Awesome (https://fontawesome.com)
- **License:** **SIL Open Font License 1.1 (OFL-1.1)**
- **Upstream URL:** https://fontawesome.com/license/free

### SIL OPEN FONT LICENSE Version 1.1 - 26 February 2007

#### PREAMBLE
The goals of the Open Font License (OFL) are to stimulate worldwide development of collaborative font projects, to support the font creation efforts of academic and linguistic communities, and to provide a free and open framework in which fonts may be shared and improved in partnership with others.

The OFL allows the licensed fonts to be used, studied, modified and redistributed freely as long as they are not sold by themselves. The fonts, including any derivative works, can be bundled, embedded, redistributed and/or sold with any software provided that any reserved names are not used by derivative works. The fonts and derivatives, however, cannot be released under any other type of license. The requirement for fonts to remain under this license does not apply to any document created using the fonts or their derivatives.

#### PERMISSION & CONDITIONS
Permission is hereby granted, free of charge, to any person obtaining a copy of the Font Software, to use, study, copy, merge, embed, modify, redistribute, and sell modified and unmodified copies of the Font Software, subject to the following conditions:

1. Neither the Font Software nor any of its individual components, in Original or Modified Versions, may be sold by itself.

2. Original or Modified Versions of the Font Software may be bundled, redistributed and/or sold with any software, provided that each copy contains the above copyright notice and this license. These can be included either as stand-alone text files, human-readable headers or in the appropriate machine-readable metadata fields within text or binary files as long as those fields can be easily viewed by the user.

3. No Modified Version of the Font Software may use the Reserved Font Name(s) unless prominent written permission is granted by the corresponding Copyright Holder. This restriction only applies to the primary font name as presented to the users.

4. The name(s) of the Copyright Holder(s) or the Author(s) of the Font Software shall not be used to promote, endorse or advertise any Modified Version, except to acknowledge the contribution(s) of the Copyright Holder(s) and the Author(s) or with their explicit written permission.

5. The Font Software, modified or unmodified, in part or in whole, must be distributed entirely under this license, and must not be distributed under any other license. The requirement for fonts to remain under this license does not apply to any document created using the Font Software.

#### DISCLAIMER
THE FONT SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO ANY WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT OF COPYRIGHT, PATENT, TRADEMARK, OR OTHER RIGHT. IN NO EVENT SHALL THE COPYRIGHT HOLDER BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, INCLUDING ANY GENERAL, SPECIAL, INDIRECT, INCIDENTAL, OR CONSEQUENTIAL DAMAGES, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE USE OR INABILITY TO USE THE FONT SOFTWARE OR FROM OTHER DEALINGS IN THE FONT SOFTWARE.

---

## 2. Lucide Icons

- **Component:** UI Vector Icon Geometries
- **Origin:** Lucide Icon Project (https://lucide.dev)
- **Copyright:** Copyright (c) Lucide Contributors (https://github.com/lucide-icons/lucide)
- **License:** **ISC License**
- **Upstream URL:** https://github.com/lucide-icons/lucide/blob/main/LICENSE

### ISC License

Copyright (c) Lucide Contributors

Permission to use, copy, modify, and/or distribute this software for any purpose with or without fee is hereby granted, provided that the above copyright notice and this permission notice appear in all copies.

THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES WITH REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.

---

## 3. TLSFix (Runtime Tweak Prerequisite)

- **Component:** HTTPS TLS 1.2+ connectivity patch for legacy iOS 6.0–10.3.4
- **Developer:** @nfzerox (https://github.com/nfzerox/TLSFix)
- **License:** **MIT License**
- **Note:** TLSFix is an independent Cydia Substrate runtime tweak required on jailbroken legacy iOS devices to allow secure HTTPS connections to YouTube streaming endpoints. It is not bundled inside the application binary.

---

## 4. Theos Build System (External Toolchain)

- **Component:** Cross-compilation harness & packaging toolchain
- **Origin:** Theos Project (https://theos.dev)
- **License:** **GNU General Public License v3.0 (GPLv3)**
- **Note:** Theos was utilized strictly as an external build environment; no copyleft runtime libraries or proprietary stubs were linked into the compiled binary.
