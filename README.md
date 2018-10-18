# banner-notebooks

Banner is an [enterprise resource planning system](https://www.etsu.edu/banner/) used by various higher education institutions in Tennessee.

The repostiory contains a collection of Jupyter notebooks for queries against Banner's web-based query system.

Examples include

- Check course list: checks a list of known courses to see if they will be offered in a given semester


Each notebook is mostly self-contained but may require installing [NuGet packages](https://docs.microsoft.com/en-us/nuget/tools/nuget-exe-cli-reference), which are units of deployment for .NET libraries. Because the library paths are hard coded in the notebooks, you may need to change the corresponding line as well.