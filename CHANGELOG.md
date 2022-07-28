
## changelog

#### 2022-07-27

1. remove `checkversion` and `updateversion`;
2. change cpu_cores method, only counter processor number;
3. infoprint if no swap space;
4. remove get_http_cli method;
5. fix mysql error log file path if log_error begin with `./`;
6. remove external ip info;
7. add read_only check if instance is not slave;
8. add binlog_row_image check when binlog format is ROW;
9. add server_id message output;
10. adjust storage table check, badprint if not InnoDB table;
11. adjust the max peak memory method, closer to reality;
12. badprint if slow log is OFF;
13. add more addtional info in some warn messages;
14. adjust thread pool size range;
15. adjust the calc rule of the innodb buffer pool size and instances number;
16. adjust innodb log file size method;
17. disable the cve check and mariadb galera check;
18. check sync_binlog when host is vm or physical;
19. check host ip whether in locals or not;
