CodeIgniter Helper - Get Country Name from Country Code 
========================================================

This is a simple CodeIgniter helper file to retrieve the country name of the provided country code (ISO).

Usage:

1. Add country_helper.php file to app/helpers folder.
2. In your code do the following,

   <?php

   $this->load->helper('country');
   
   $country_name = get_country_name(COUNTRY_CODE);
