# SpotPricePolybar
Polybar Module: Spot Price of Silver (AG), Gold (AU), Palladium (PD), and Platinum (PT)

Prices are scraped from www.kitco.com

# Module Example

	[module/silver_spot]   
	type = custom/script
	format-prefix = "(AG) "
	exec = /usr/bin/bash $HOME/.config/polybar/my_modules/spot_price_bash.sh "AG"
	interval = 60
	tail = true
