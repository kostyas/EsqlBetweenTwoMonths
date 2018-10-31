# EsqlBetweenTwoMonths
#
#
#counts the amount between two months
#
#if you want to count the number of days, then you need to register in "EXTRACT" (DAYS FROM secondDate); 
#

#>>-EXTRACT--(--+-YEAR----------+--FROM--SourceDate--)----------><
#               +-MONTH---------+                        
#               +-DAY-----------+                        
#               +-HOUR----------+                        
#               +-MINUTE--------+                        
#               +-SECOND--------+                        
#               +-DAYS----------+                        
#               +-DAYOFYEAR-----+                        
#               +-DAYOFWEEK-----+                        
#               +-MONTHS--------+                        
#               +-QUARTEROFYEAR-+                        
#               +-QUARTERS------+                        
#               +-WEEKS---------+                        
#               +-WEEKOFYEAR----+                        
#               +-WEEKOFMONTH---+                        
#               '-ISLEAPYEAR----' 
