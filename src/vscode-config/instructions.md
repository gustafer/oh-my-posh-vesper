install [this font](./JetBrainsMonoNerdFontMono-Regular.ttf)

either run on terminal:

```
cd AppData\Roaming\Code\User
explorer .
```

or ctrl+shift+p on vscode and 'profiles import profile' and then pick [this](./ustav.code-profile)

copy [this setting](settings.json) and replace on the folder

open powershell

```
code $profile
```

paste that and save

```
oh-my-posh.exe init pwsh --config 'https://raw.githubusercontent.com/gustafer/oh-my-posh-vesper/main/src/vesper-fancy.omp.json' | Invoke-Expression
```

