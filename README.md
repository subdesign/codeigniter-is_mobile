## Codeigniter mobile browser detection helper

## Usage

1. Autoload or manually load mobile_helper.php

2. In the constructor

    	if( is_mobile() )
      	{
	  		redirect('http://mobile.mysite.com');
      	}