# Заметки о JavaScript

Для просмотра заметок используйте JupyterLab с ядром [.NET Interactive](https://github.com/dotnet/interactive) или Visual Studio Code с расширением [.NET Interactive Notebooks](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.dotnet-interactive-vscode).

В JupyterLab примеры работают веселей.

## Przygotowanie otoczenia

**Baza**:

```
sudo apt install python3 python-is-python3 python3-pip
pip install jupyterlab
pip install notebook
```

**.NET Interactive**:

Instaluj [.NET 6 SDK](https://dotnet.microsoft.com/en-us/download/dotnet/6.0).

```
dotnet tool install -g Microsoft.dotnet-interactive
dotnet interactive jupyter install
```

## Linki

* [.NET Interactive](https://github.com/dotnet/interactive)
* [Using HTML and JavaScript with .NET Interactive](https://github.com/dotnet/interactive/blob/main/docs/javascript-overview.md)
