# ContentFileTest
Test the nuget package ContentFilesExample

The repository https://github.com/NuGet/Samples contains an example Nuget package that implements the new `contentFiles` tags 
and should import files and resources into a project. I built this simple solution to test this package.

I documented the problems I had in [this issue](https://github.com/NuGet/Samples/issues/21) on that solution.

In summary:
- [ ] ContentFiles were ignored by old-style `csproj` Framework projects
- [ ] Upgrading Framework projects to the new `csproj` format did not fix this
- [ ] Upgraded projects could not find the source folder as encoding had mangled the names
- [ ] the `/images/` folder in the Nuget package was not created

Comments/corrections/suggestions are welcome, either in the issues here or as comments to issue 21 linked above.


