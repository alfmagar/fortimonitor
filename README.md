# FortiGate Linux SSL VPN CLI Client monitor

Monitorizes FortiVPN on Linux client and automatically reconnects connection if detects a drop. 

Copy BIN folder files into /usr/bin folder and copy .service files in /etc/init.d/ and /etc/systemd/system. 

Edit fortimonitor and fortivpn bin files and modify scripts parameters to match your system needs.

Enable services using "systemctl enable fortimonitor.service" and "systemctl enable fortivpn.service". 

Then, execute "systemctl start fortimonitor.service" and "systemctl start fortivpn.service" to start both services. 

Can be used as a normal system daemon with service statements.