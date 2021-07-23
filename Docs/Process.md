# Development Log/Roadmap

### C#/.NET + React
- Created project template using the [React-with-Redux ASP.NET Core command](https://docs.microsoft.com/en-us/aspnet/core/client-side/spa/react-with-redux?view=aspnetcore-5.0) `dotnet new reactredux`
  - The idea is to work with React for BiblioPile's frontend, and use C# to handle the backend (database, user authorization and authentication)
  - This needs to be a live web page, so my options are somewhat limited:
    - My preference is not to use a relational database
    - Firebase
      - [Tutorial 1](https://developer.okta.com/blog/2019/04/30/store-data-firebase-aspnet-mvc-csharp)
      - [Tutorial 2](https://blog-bertrand-thomas.devpro.fr/2019/10/24/api-authentication-with-asp-net-core-3-0-and-firebase/)