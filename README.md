# MySQL BACKUP TOOL
                                                                                      
@AUTHOR:        NIGHTBARRON                                                        
@DATE:          27/04/2021                                                         
                                                                                    
@Default BACKUP DIRECTORY: ~/sql_backup/<YYmmDD>/<dbname>.sql.gz                   
                                                                                    
@RESTORE FROM BACKUP:                                                           
- CREATE DATABASE as THE SAME as LOST!!                                        
- `gunzip < [backupfile.sql.gz] | mysql -u [uname] -p[pass] [dbname]`           
                                                                                      