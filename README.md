# Windows 1/11

1. Install(update) AppInstaller from Microsoft Store https://apps.microsoft.com/detail/9NBLGGH4NNS1?hl=en-us&gl=US

2. 
```shell
winget upgrade --all
```

3. restart Terminal

4. 
```shell
winget install git.git --silent --accept-source-agreements --accept-package-agreements
```

5.
```shell
winget install --scope machine -e --silent --accept-source-agreements --accept-package-agreements --id Microsoft.VisualStudioCode
```