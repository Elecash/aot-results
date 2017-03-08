# AotDemo

This project was generated with [angular-cli](https://github.com/angular/angular-cli) version 1.0.0-beta.24.

It's purpose is to determine size results of an Angular app compiled with AOT (Ahead-of-Time).

## Angular CLI 1.0.0-beta.24

ng serve (no tree-shaking, no aot)
---------------------
* inline: 5.7 KBs
* vendor: 3.2 MBs
* main: 10.9 KBs

ng serve --prod (no aot)
---------------------
* inline: 1.1 KBs
* vendor: 223 KBs
* main: 1.2 KBs

ng serve --prod --aot
---------------------
* inline: 1.1 KBs
* vendor: 124 KBs
* main: 3.7 KBs

## Angular CLI 1.0.0-rc.1

ng serve (no tree-shaking, no aot)
---------------------
* inline: 5.9 KBs
* styles: 10.1 KBs
* vendor: 3.3 MBs
* main: 11.2 KBs

ng serve --prod (aot is enabled by default)
-------------------------------------------
* inline: 1.1 KBs
* vendor: 151 KBs
* main: 3.4 KBs

ng serve --prod --aot
---------------------
* inline: 1.1 KBs
* vendor: 151 KBs
* main: 3.4 KBs
