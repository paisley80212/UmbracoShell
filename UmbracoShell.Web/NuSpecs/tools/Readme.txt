A note about running Umbraco v5 from Visual Studio.

Before running or debugging the project you need to configure the web application project to use IIS Express.
Right click on the web application project and select Properties -> Click Web tab and check the "Use Local IIS Web Server" radiobutton and either "Use IIS Express" or "Override application root URL" checkbox.

It is not possible running Umbraco v5 from Visual Studio with the built-in Cassini.

If you don't have IIS Express installed we recommend you install it or set up a new site in IIS that point to the web applications project folder.

- Umbraco