# Project Title
![](https://img.shields.io/badge/swift-3.0.1-green.svg)
![](https://img.shields.io/badge/VIPER-generamba-orange.svg)

ASRambaViperTemplate - generamba templates for generate VIPER module for Swift projects.

## Getting Started
![VIPER arch](https://shagaleevalexey.github.io/iOS_Viper.png)

1. [Install Generamba from Rambler](https://github.com/rambler-digital-solutions/Generamba)
2) [Initialize Generamba](https://github.com/rambler-digital-solutions/Generamba/wiki/Available-Commands#basic-generamba-configuration) in your project's folder and install templates from this repo

3) Open terminal and execute this in the same project's folder: 
```bash
$ generamba gen ModuleName ASRambaViper
```

The new VIPER Module will be generated in your project's folder with structure:
```
Module
  ├── View
  │    └── ModuleView.swift
  ├── Presenter
  │    └── ModulePresenter.swift
  ├── Interactor
  │    └── ModuleInteractor.swift
  ├── Router
  │    └── ModuleRouter.swift
  ├── Wireframe
  │    └── ModuleWireframe.swift
  └── Protocols
       └── ModuleProtocols.swift