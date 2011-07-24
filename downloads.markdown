---
layout: default
title: CorrugatedIron Downloads
heading: Down<strong>loads</strong>
subheading: Get you some code!
menuitem: Downloads
---

Current Version
---------------

CorrugatedIron has just reached its first ever release milestone and is proudly sitting at [v0.1.0][released_source]. If you're keen to get your hands on it you have quite a few options:

* Grab the source directly from our Github repository ([development][] | [stable][released_source]).
* Download the [v0.1.0 binaries][released_binaries].
* Download a v0.1.0 source archive ([tar][] | [zip][]).
* Install the CorrugatedIron [Nuget package][nuget] directly into your project via Nuget.

If you're a user of Visual Studio the easiest option is to install the Nuget package. This can be done via the Nuget Package Management GUI, or from the Package Manager Console:

    PM > Install-Package Corrugatediron

Sample Applications
-------------------

If you're anything like us, you'll appreciate a few sample applications to base your code off even if the [documentation][] is really good. For that reason we've provided a few sample applications to get you started.

The sample applications can be found in our [samples repository][samples]. The samples include:

* A [Session State Provider][session_state] provider which uses CorrugatedIron to store ASP.NET session state in Riak.
* A .NET client for [Sean Cribbs][]' chat application, [YakRiak][].
* A generic sample application which shows many of CorrugatedIron's features and demonstrates how to configure and wire-up CorrugatedIron using:
    * [Autofac][]
    * [Ninject][]
    * [StructureMap][]
    * [TinyIoC][]
    * [Unity][]

[released_source]: https://github.com/DistributedNonsense/CorrugatedIron/tree/v0.1.0 "v0.1.0 source"
[released_binaries]: https://github.com/DistributedNonsense/CorrugatedIron/downloads/CorrugatedIron-v0.1.0.zip "v0.1.0 binaries"
[development]: https://github.com/DistributedNonsense/CorrugatedIron/tree/develop "Development branch"
[tar]: https://github.com/DistributedNonsense/CorrugatedIron/tarball/v0.1.0 "v0.1.0 source tarball"
[zip]: https://github.com/DistributedNonsense/CorrugatedIron/zipball/v0.1.0 "v0.1.0 source zip"
[nuget]: http://www.nuget.org/List/Packages/CorrugatedIron "Nuget Package"
[samples]: https://github.com/DistributedNonsense/CorrugatedIron.Samples "Samples"
[session_state]: http://msdn.microsoft.com/en-us/library/aa478952.aspx "Session State Providers"
[Unity]: http://unity.codeplex.com/ "Unity IoC"
[Autofac]: http://code.google.com/p/autofac/ "Autofac IoC"
[Ninject]: http://ninject.org/ "Ninject IoC"
[TinyIoC]: https://github.com/grumpydev/TinyIoC "TinyIoC"
[StructureMap]: http://structuremap.net/structuremap/ "StructureMap IoC"
[Sean Cribbs]: http://twitter.com/seancribbs "Sean Cribbs @ Twitter"
[YakRiak]: https://github.com/seancribbs/yakriak "YakRiak - a Riak-based Chat application"