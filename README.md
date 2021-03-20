# TH001Management
## Radzen 
- Nav
  - new App1, with NuGet Radzen.Blazor 3.1.6, to prevent
    -  'Radzen' could not be found 
    -  'RadzenSidebar' could not be found 
    -  'RadzenBody' could not be found 
     
  - 可以自主收起的機制, simply copy MainLayout.razor, to have 3 errors to solve 
    -  'ExampleService' could not be found 
        - Startup.ConfigureServices   services.AddScoped&lt;ExampleService>();
    -  'ThemeState' could not be found
    -  'Example' could not be found



- Auth
- Tabs
- Grid


https://blazor.radzen.com/get-started
