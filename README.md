# oh-my-posh-template
oh-my-posh Template
![Sceenshot](https://github.com/shahmarasy/oh-my-posh-template/blob/main/oh-my-posh.png?raw=true)
pwsh: Microsft.PowerShell_profile
```
oh-my-posh init pwsh --config "$env:POSH_THEMES_PATH\shahmarasy.omp.json" | Invoke-Expression
```

bash: .bashrc
```bashrc
...
eval "$(oh-my-posh init bash --config  /root/themes/shahmarasy.omp.json)"
```
fish: config.fish
```
...
oh-my-posh init fish --config  /root/themes/shahmarasy.omp.json | source
```


