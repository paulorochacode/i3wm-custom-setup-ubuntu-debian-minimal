<h1>Costumization<h1>  
  
<h3>iptables</h3>
<h4>
sudo apt-get install iptables -y && </br>
sudo iptables-restore < iptablesRules && </br>
sudo apt-get install iptables-persistent -y
</h4></br>

<h3>i3wm</h3>

<h4>
sudo apt install i3 i3blocks -y && </br>
sudo rm -rf /home/l/.config/config && </br>
cd /home/l/.config </br>
!Dowload the config! </br>
sudo rm -rf /etc/i3blocks.conf && </br>
cd  /etc/ </br>
!Download the i3blocks.conf! </br>
WIN + SHIT + R
</h4></br>

<h3>UFW</h3>
<h4>sudo apt install ufw -y &&</br>
sudo ufw default deny && </br>
sudo apt-get install ufw && </br>
sudo ufw default deny outgoing &&
sudo ufw default deny incoming &&
sudo ufw allow out 80 &&
sudo ufw allow out 443 &&
sudo ufw allow out 53</h4>

<h3></h3>
<h4></h4>
