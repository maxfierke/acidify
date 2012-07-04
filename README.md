# Acidify by TeamAcid
## What is Acidify?
Acidify is a tool for building Android builds. It allows easy switching between build types and setting up everything that is needed to build Android.

That said, it is a tool designed for people that are already building Android but want to be able to switch between CM7, CM9, and AOKP easily. It's primarily a convenience tool for TeamAcid developers.
## Can I use Acidify?
Of course you can use Acidify! Be aware that it grabs manifests from us (TeamAcid) so in its unmodified state you'll only be able to build Android the way we build Android. As of 0.2.4, however, there are configurable options that allow building for any device. Simply specify any local manifest URLs and the device name in the script.
## What do I need to use Acidify?
**Short Answer:** A POSIX-compliant machine with bash which is capable of compiling Android.

**Long Answer:** Currently, you need a machine running version 10.10 of Ubuntu or higher to use every *feature* available in Acidify. Until people contribute code aimed at other distributions and versions, some features (such as grabbing needed packages) may be unavailable. The core features such as initializing the build environment, switching between build types, or building Android itself should theoretically work on any platform running bash and which has all the packages installed that are required to build Android.
## How do I install Acidify
Download a tarball of acidify or clone the repository. Put it somewhere safe and run <code>acidify setup</code>. That will install all the required packages for building Android (if you're on Ubuntu) and it will create a soft link to acidify in ~/bin so that you can access acidify from any directory (assuming ~/bin is in your PATH).
## How do I use Acidify?
Run <code>acidify usage</code> for an explaination on how Acidify may be used.
## Can I modify or redistribute Acidify?
Yes, you can! Acidify is licensed under the GNU General Public License version 3 (or greater). You can modify it and redistribute it under the terms of the license.
See LICENSE for more information.
## I found a bug with Acidify. Will you fix it?
For sure! Make an issue in the issue tracker to tell us about it.
## I found a bug with Acidify and I fixed it. Do you want it?
We would love it! Submit a pull request.
## I wanted X feature, so I implemented it. Do you want it?
Potentially. Submit a pull request and we can discuss it there.
