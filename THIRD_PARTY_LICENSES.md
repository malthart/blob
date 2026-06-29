# Third-Party Licenses

Blob bundles the following open-source components. Their license notices are
reproduced below as required.

---

## Sparkle

Used for in-app software updates. Distributed inside `Blob.app` as
`Sparkle.framework`. Licensed under the MIT license.

```
Copyright (c) 2006-2013 Andy Matuschak.
Copyright (c) 2009-2013 Elgato Systems GmbH.
Copyright (c) 2011-2014 Kornel Lesiński.
Copyright (c) 2015-2017 Mayur Pawashe.
Copyright (c) 2014 C.W. Betts.
Copyright (c) 2014 Petroules Corporation.
Copyright (c) 2014 Big Nerd Ranch.
All rights reserved.

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
the Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
```

Sparkle also bundles several smaller components under their own permissive
licenses — bsdiff/bspatch (© 2003-2005 Colin Percival), sais-lite
(© 2008-2010 Yuta Mori), a portable Ed25519 implementation
(© 2015 Orson Peters), and SUSignatureVerifier (© 2011 Mark Hamlin). The full
text of every notice ships inside `Sparkle.framework`'s own `LICENSE` file and
is available at https://github.com/sparkle-project/Sparkle/blob/2.x/LICENSE .

---

## SwiftTerm

Used for the interactive container `exec` terminal. Distributed inside
`Blob.app`. Licensed under the MIT license.

```
Copyright (c) 2019-2022 Miguel de Icaza (https://github.com/migueldeicaza)
Copyright (c) 2017-2019, The xterm.js authors (https://github.com/xtermjs/xterm.js)
Copyright (c) 2014-2016, SourceLair Private Company (https://www.sourcelair.com)
Copyright (c) 2012-2013, Christopher Jeffrey (https://github.com/chjj/)

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
```

---

## swift-argument-parser

Apache License 2.0, © Apple Inc. and the Swift project authors. This is a
transitive dependency of Sparkle's command-line release tools
(`generate_appcast`, `generate_keys`) used only at build time — it is **not**
linked into or distributed inside `Blob.app`. Full text:
https://github.com/apple/swift-argument-parser/blob/main/LICENSE.txt
