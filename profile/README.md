## Welcome

This is the Github organisation for the code-coverage tool called OpenCover, a code-coverage tool for the .NET framework that would work for both 32 and 64 bit applications.

# Brief History

OpenCover was created in 2011 to create a code-coverage tool for the .NET platform that would support both 32 and 64 bit applications running on Windows OSs ([read more...](https://blog.many-monkeys.com/posts/open_cover_first_beta_release/)) after I got frustrated trying to upgrade [PartCover](https://sourceforge.net/projects/partcover/) to be both 32 and 64 bit cabable.

We decided to stop development in 2021 after our priorities changed and that we wouldn't be able to support the effort required to perform the major uplift to support .NET Core ([read more...](https://blog.many-monkeys.com/posts/night-night-opencover/)). 

Though I don't use .NET nowadays I know of teams using it to test .NET Full Framework and .NET Core apps on the Windows OS and it is still available to download [via Nuget](https://www.nuget.org/packages/OpenCover). Because it is still in active use we decided to keep the repository available but froze it by archiving it.

# Project Naming

Using `Cover` was a fairly obvious starting point for a code-coverage tool. There is a pattern of .NET tools using the prefix `N` for tools but there was already a commercial code-coverage tool called NCover(*), so taking inspiration from a UK collegue and his [OpenWrap](https://serialseb.com/blog/2010/10/20/creating-a-new-project-with-openwrap/) tool and that the project was open source, I adpted the prefix `Open` and so `OpenCover` was born.

(*) also started off as open source, but later went commercial and was the trigger, so I believe, that caused the original authors to create [PartCover](https://sourceforge.net/projects/partcover/).
