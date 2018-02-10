# test_mconf
Test mconf on windows platform, but the keys, e.g. KEY_ESC, KEY_BACKSPACE, are not work.

+ conf
    - load default config

        ```
        conf --defconfig=xxx.config ./Kconfig
        ```

    - save defconfig
        ```
        conf --savedefconfig .\xx_defconfig %./Kconfig
        ```
