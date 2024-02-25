## Snowkelus-LibCore

#### ⚙️ Runtimes

- [@libphp/amazon-linux-2-v72](@libphp/amazon-linux-2-v72)
- [@libphp/amazon-linux-2-v73](@libphp/amazon-linux-2-v73)
- [@libphp/amazon-linux-2-v74](@libphp/amazon-linux-2-v74)
- [@libphp/amazon-linux-2-v80](@libphp/amazon-linux-2-v80)
- [@libphp/amazon-linux-2-v81](@libphp/amazon-linux-2-v81)
- [@libphp/amazon-linux-2-v82](@libphp/amazon-linux-2-v82)
- [@libphp/amazon-linux-2-v83](@libphp/amazon-linux-2-v83)

```js
import * as php from "@libphp/amazon-linux-2-v83";

// @libphp/amazon-linux-2-v82
// ├── dist
// │   └── *.js
// └── native
//     ├── lib
//     │   └── * (shared libs)
//     └── php
//         ├── modules
//         │   └── *.so (php modules)
//         ├── composer
//         ├── php.ini
//         ├── php
//         ├── php-cgi
//         ├── php-fpm
//         └── php-fpm.ini

php.getRoot(); // root folder
php.getComposer(); // composer bin
php.getPhpFiles(); // list of all PHP files
php.getPhpModulesFiles(); // list of all PHP modules
php.getSharedLibsFiles(); // list of all shared libs
php.getFiles(); // list of all related files
```

#### DOSS (Developer Open-Source Software): @snowkelus

* Now a Property of @snowkelus/libcore for @snowkelus/snowkelus-php (0.2.1)

#### CTTO (Credits to the Owner):

* Based on the works of Felix @f3l1x/libphp
