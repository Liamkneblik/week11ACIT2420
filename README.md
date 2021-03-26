# week11ACIT2420
instructions for running the weather script

you will need to put the files in this directory path:
  /home/vagrant/week-11

step 1: (Copy the wttr.service and timer to /etc/systemd/system)
      cp wttr.service /etc/systemd/system
      cp wttr.timer /etc/systemd/system
      
step 2: (start and enable the service and timers)
      sudo systemctl enable wttr.service
      sudo systemctl start wttr.service
      sudo systemctl enable wttr.timer
      sudo systemctl start wttr.timer
      sudo systemctl daemon-reload
