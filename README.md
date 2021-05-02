# sms_sender (smpp 3.4)

1. Use CentOS 7 (kernel 3.10).
2. Compiler GCC must be installed (exists at CentOS 7 Minimal install).
3. Use locale=en_US.UTF-8.
4. Put file "sms_sender.zip" to /opt (or another dir).
5. "cd /opt" + "unzip sms_sender.zip".
6. "cd /opt/sms_sender" + "chmod +x sms_sender_1.exe".
7. For run "./ sms_sender_1.exe".
8. Fill the configuration file "/opt/sms_sender/sms_sender.cfg".
9. For stop (example for all services) "./sms_sender_1.exe stop".
10. For restart "./sms_sender_1.exe restart".
11. For reload configuration "./sms_sender_1.exe reload_cfg".
12. For use systemd "./sms_sender_1.exe use_systemd" and follow instructions.

For create sms_sender_0dsm.exe just "cd /dir_with_sms_sender_1.exe" + "cp sms_sender_1.exe sms_sender_0dsm.exe".

For create sms_sender_0rx.exe just "cd /dir_with_sms_sender_1.exe" + "cp sms_sender_1.exe sms_sender_0rx.exe".

