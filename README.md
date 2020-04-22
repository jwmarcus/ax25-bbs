### Configuration templates and admin scripts for the G8BPQ AX.25 Packet BBS

Please see the supporting documentation in the amateur-radio section of https://github.com/jwmarcus/guides/ for more information.

You will also need a copy of either the `linbpq` or the `pilinbpq` binary.

`pitnc_getparams`, `pitnc_setparams`, `linbpq`, and `pilinbpq` are Copyright of John Wiseman, G8BPQ. This repository only offers a mirror for personal project purposes. You should get the latest version and license information from [the LINBPQ site](http://www.cantab.net/users/john.wiseman/Documents/InstallingLINBPQ.htm).

You will also want to symlink the service file to your systemd folder with something like `sudo ln -s /home/pi/src/ax25-bbs/linbpq.service /etc/systemd/system/linbpq.service`. You can then enable the service at start with `sudo systemctl enable linbpq.service`. 
