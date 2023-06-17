# MyShutDownBatch
Just a nice way to shut your down PC



To start this Batch-file properly, just add it to your Desktop and double klick it to shut down.



Comand description:


msg * /W "Press OK to CONFIRM SHUTDOWN" //asks you to confirm shutdown

shutdown -s -t 5 -c "SHUTDOWN CONFIRMED" // shuts your system down after 5 seconds; sending the message "SHUTDOWN CONFIRMED"

msg * /W "Press OK to CANCEL SHUTDOWN" asks you if you want to cancel; will still shutdown if no action recived

shutdown -a cancels shutdown if comand above was klicked "OK"
