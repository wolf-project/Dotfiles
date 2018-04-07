<pre id="taag_font_DeltaCorpsPriest1" style="float:left;" class="fig-ansi" contenteditable="true"> </pre>
# My Arch Linux Dotfiles - i3WM + Bumblebee_status

![I3][screenshot1]
![I3][screenshot2]

[screenshot1]:https://github.com/wolf-project/Dotfiles/blob/master/screenshots/screen1.png
[screenshot2]:https://github.com/wolf-project/Dotfiles/blob/master/screenshots/screen2.png

# Instalation and dependencies

pacman -S i3 i3blocks dmenu lm_sensors nitrogen

yaourt -S ttf-inconsolata ttf-font-awesome ttf-dejavu terminus-font-ttf terminus-font lemonbar-git i3-gaps-git
	
$ git clone git://github.com/tobi-wan-kenobi/bumblebee-status

$ unzip bumblebee-status.zip

Move to you directorie <strong> /home/your-user/.config/i3/ </strong>  or <strong>/root/.config/i3/</strong>

Edit the i3 configuration (config) on /home/your-user/.config/config or /root/.config/i3/config
  
  add this command on you i3 "config" 
  
  <strong> 
	
	bar {
	status_command = <path to bumblebee-status/bumblebee-status> -m <list of modules> -p <list of module parameters> -t <theme>
	}
</strong>

# Got a problem ? 

	Please, submit a issue.
	E-mail wolfsecurity@protonmail.com
	Facebook www.facebook.com/ConsuegraVictor
	
# Bumblebee_status - credits	
	Bumblebee_status author git://github.com/tobi-wan-kenobi/
	Check the code ! 
