csharp-container-101
==

## Usage

This assumes you already have the Dev Containers installed in VSCode.

1. Start Docker (on a Mac: `open -a Docker`)
2. Open the project in Visual Studio Code (VS Code)
3. Click: **Reopen in Container**
4. Select: **View / Terminal** (may already be open)
5. In the VSCode Terminal window run this command:
```sh
dotnet run
```

## How this project was created:

1. Create a project folder and cd to it
2. Open the project in VS Code
3. Open the Command Palette (**Cmd+Shift+P** on a Mac)
4. Type in **Dev Containers: Add Dev Container Configuration Files ...**
5. Select **C#** and go through the steps
6. Press **Reopen in Container** when prompted
7. Open up the VSCode Terminal window:  **View / Terminal** on a Mac
8. Create a new console project:
```sh
dotnet new console
```
9. Run the project:
```sh
dotnet run
```
10. Add a .gitignore file
```sh
dotnet new gitignore
```


## References

* [How to use Microsoft Dev Containers (Visual Studio Code, Python)](https://scriptable.com/how-to-use-microsoft-dev-containers-python/)
* [How to Install Dotnet on a Mac (.NET, CSharp)](https://scriptable.com/how-to-install-dotnet-on-a-mac/)

