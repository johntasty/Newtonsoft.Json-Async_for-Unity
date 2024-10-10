# Async Newtonsoft.Json for Unity

Json.NET is a popular high-performance JSON framework for .NET

This package is a fork of Newtonsoft.Json containing custom builds targeting
standalone, portable (UWP, WP8), and AOT targets such as all IL2CPP builds
(iOS, WebGL, Android, Windows, Mac OS X, et.al).

## Versioning format

_Staying with JamesNK's version syntax, but with a twist :dizzy:_

Based off JamesNK's versioning, but with the addition of two digits on the last
segment. This is for Newtonsoft.Json-for-Unity to be able to have independent
releases, at the same time still being easy to see which version of Json.NET
it's based of.

![explanation of version][version-explanation.png]

Where official Json.NET 12.0.1 becomes Newtonsoft.Json-for-Unity 12.0.1*xx*.

## Changelog

Please see the [CHANGELOG.md][changelog.md] file inside this package.


Find your version in the list of tags: https://github.com/johntasty/Newtonsoft.Json-Async_for-Unity/tags

Open <project>/Packages/manifest.json, add the package in the list of dependencies, replacing the tag after the hash sign (#) with your version of choice.

À la:
```
{
  "dependencies": {
    "async.newtonsoft.json-for-unity": "https://github.com/johntasty/Newtonsoft.Json-Async_for-Unity.git#10.0.0",

    /* ... rest of Unity packages ... */
  }
}
Done!
```

---

This package is licensed under The MIT License (MIT)

Copyright (c) 2019 Kalle Jillheden (jilleJr)  
<https://github.com/jilleJr/Newtonsoft.Json-for-Unity>

See full copyrights in [LICENSE.md][license.md] inside repository

[license.md]: https://github.com/jilleJr/Newtonsoft.Json-for-Unity/blob/master/LICENSE.md
[changelog.md]: https://github.com/jilleJr/Newtonsoft.Json-for-Unity/blob/master/CHANGELOG.md
[version-explanation.png]: https://github.com/jilleJr/Newtonsoft.Json-for-Unity/raw/ce23d98230673744d73656b4c4f6bc1f9989c37a/Doc/version-explanation.png
[openupm]: https://openupm.com/packages/jillejr.newtonsoft.json-for-unity/
[openupm-icon.png]: https://github.com/jilleJr/Newtonsoft.Json-for-Unity/raw/c43046bc4763c0a5d3b0164a4f0a92e40de9d10e/Doc/icons/openupm-icon-16.png
[wiki-installation-via-openupm]: https://github.com/jilleJr/Newtonsoft.Json-for-Unity/wiki/Installation-via-OpenUPM
[wiki-installation-via-upm]: https://github.com/jilleJr/Newtonsoft.Json-for-Unity/wiki/Installation-via-UPM
[wiki-installation-via-git-in-upm]: https://github.com/jilleJr/Newtonsoft.Json-for-Unity/wiki/Installation-via-Git-in-UPM
