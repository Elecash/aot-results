# AotDemo

This project was generated with [angular-cli](https://github.com/angular/angular-cli) version 1.0.0-beta.24.

It's purpose is to determine size results of an Angular app compiled with AOT (Ahead-of-Time).

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
