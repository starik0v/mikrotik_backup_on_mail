# mikrotik_backup_on_mail
Script for Mikrotik backup and send it on mail.

1) System -> Scripts -> + -> name script
2) Copy script from txt to Source field, insert your from|to accounts, smtp server name, pass for sender account.

To make it auto backup:
4) System -> Scheduler -> name backup_via_email, interval 7d 00:00:00
5) Copy to scheduler field On Event:
/system script run script_name
