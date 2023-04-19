# XHWNMP
An easy Nginx, MariaDB and PHP environment for Windows

XHWNMP.v0.6.0.x64

    nginx-1.24.0
            Path: .\Nginx\
            Config File: .\Nginx\nginx - Main.conf
    mariadb-10.5.5-utf8mb4
            Path: .\MariaDB\
            Config File: .\MariaDB\my.ini
            # init_connect='SET NAMES utf8mb4 COLLATE utf8mb4_general_ci;'
            # SHOW VARIABLES WHERE Variable_name LIKE 'character_set_%' OR Variable_name LIKE 'collation%';
    php-8.2.5(VS16 x64 Non Thread Safe)
            Path: .\PHP\
            Config File: .\PHP\php.ini

    Mariadb Password:
            root   20121221

    OutPut File Path:
            .\Output\Logs\
            .\Output\Error\
            .\Output\Session\
            .\Output\Temp\

Step 1: Modify the PHP .ini ; Modify the paths in session.save_path and upload_tmp_dir to absolute ;
Step 2: Run All.Run.cmd ;

http://FriBox.cn/
20230419
