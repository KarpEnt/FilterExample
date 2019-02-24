# FilterExample

### Latest changes:
* Updated npm packages (security vulnerability detected in bootstrap >= 3.0.0, < 3.4.1 defined in package.json). 
* Solution target updated to .NET Core 2.2.

## Single-page application, built with:

* [ASP.NET Core](https://dotnet.microsoft.com/apps/aspnet) and [C#](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/index) for cross-platform server-side code 
* [React](https://reactjs.org/), [Redux](https://redux.js.org/), and [TypeScript](http://www.typescriptlang.org/) for client-side code
* [Webpack](https://webpack.github.io/) for building and bundling client-side resources
* [Bootstrap](https://getbootstrap.com/) for layout and styling
To help you get started, we've also set up:

## Update packages
To update all of the `npm` dependencies to their latest versions:
```sh
cd $(PROJECTS_ROOT_PATH)\FilterExample\source\SampleWebApp\SampleWebApp
npm i -g npm-check-updates
ncu -u
npm install
```

## Documentation & tutorials, useful links:

[ReactJS.NET Tutorial (ASP.NET Core)](https://reactjs.net/getting-started/tutorial.html)

[Redux: Usage with React](http://redux.js.org/docs/basics/UsageWithReact.html)

[TypeScript.](https://www.typescriptlang.org/docs/home.html)

[Gang of Four design patterns](http://www.dofactory.com/net/design-patterns), [examples in C#](https://github.com/abishekaditya/DesignPatterns "By Abishekaditya")

[Specification pattern](http://enterprisecraftsmanship.com/2016/02/08/specification-pattern-c-implementation/ "C# implementation By Vladimir Khorikov")

[Implementing Repository and Specification patterns using Linq](http://web.archive.org/web/20120205062215/http://codeinsanity.com/archive/2008/08/13/implementing-repository-and-specification-patterns-using-linq.aspx)

[Wzorzec projektowy Filtr i Specyfikacja](http://adam.wroclaw.pl/2014/11/wzorzec-projektowy-filtr-i-specyfikacja/ "PHP implementation")
