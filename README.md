RoundCube S/MIME verification plugin - rc_smime
===============================================

Roundcube webmail plugin to verify S/MIME messages.  

This is a fork of rc_smime (made by Sandor Takacs - https://github.com/Takika/rc_smime) with updated design/gfx (to look more nice in my opinion) and fixes by @kochichi (https://github.com/kochichi) that made it work with Roundcube 1.5 and PHP8.  
Also i've added Polish translation.
  
Installation
============
- Clone from github:
    HomeRoundCubeFolder/plugins$ git clone [https://github.com/nicrame/rc_smime.git](https://github.com/nicrame/rc_smime.git)
    
- Or use composer
     HomeRoundCubeFolder$ composer require nicrame/rc_smime:dev-master
     
 NOTE: Answer **N** when composer ask you about plugin activation)

- Activate the plugin into HomeRoundCubeFolder/config/config.inc.php:
    $config['plugins'] = array('rc_smime');
