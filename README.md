# Threat_Hunting

Check 1 -          Scheduled Tasks

Check 2 -          Browser History

Check 3 -          Recent View

Check 4 -          Task View

Check 5 -          Network  Activity (task list )
                                      netstat -nbf
                                      netstat -nbf | find "5500"

Check 6 -          recent (command) if deleted run this command ==> 
.\LECmd.exe -d C:\Users\Administrator\AppData\Roaming\Microsoft\Windows\Recent --csvf Parsed-LNK.csv --csv C:\Users\Administrator\Desktop


Check 7 -         Use HackBar or System Infomer

Check 8 -         StartUp