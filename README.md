# MySQL BACKUP TOOL

@ Describe: This tool is written both `Bash Shell` and `Python` code. For `Bash Shell` I prefer to run locally with CRONTAB for best PERFORMENT. Using `Python` code for backup `Remote MySQL Server` to your local!!!

@author:        NIGHT BARRON                                                        
@date:          27/04/2021                                                         
                                                                                    
@Default BACKUP DIRECTORY: `~/sql_backup/<YYmmDD>/<dbname>.sql.gz    `               
                                                                                    
@RESTORE from backup:                                                           
- CREATE DATABASE as THE SAME as LOST!!                                        
- `gunzip < [backupfile.sql.gz] | mysql -u [uname] -p[pass] [dbname]`    

@Donate me at: Vietcombank (Vietnam), Bank Number: 1020471229
                                                                                      