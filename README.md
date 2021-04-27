# MySQL BACKUP TOOL

#!/bin/bash

#########################################################################################
\#                                                                                       #
\#   #AUTHOR:        NIGHTBARRON                                                         #
\#   #DATE:          27/04/2021                                                          #
\#   #CRON:                                                                              #
\#       # example cron for daily db backup @ 9:15 am                                    #
\#       # min  hr mday month wday user-name command                                     #
\#       # 15   9  *    *     *    root      /path_to_file/mysql_backup.sh               #
\#                                                                                       #
\#   #Default BACKUP DIRECTORY: ~/sql_backup/<YYmmDD>/<dbname>.sql.gz                    #
\#                                                                                       #
\#   #RESTORE FROM BACKUP                                                                #
\#       # CREATE DATABASE as THE SAME as LOST!!                                         #
\#       #$ gunzip < [backupfile.sql.gz] | mysql -u [uname] -p[pass] [dbname]            #
\#                                                                                       #
#########################################################################################