[![Build Status](https://travis-ci.org/renard/no-plymouth.svg?branch=master)](https://travis-ci.org/renard/no-plymouth)
[![Tweet this](http://img.shields.io/badge/%20-Tweet-00aced.svg)](https://twitter.com/intent/tweet?tw_p=tweetbutton&via=renard_0&url=https%3A%2F%2Fgithub.com%2Frenard%2Fno-plymouth&text=Remove%20%23plymouth%20because%20who%20needs%20it%20on%20%40Ubuntu%20servers%3F)
[![Follow me on twitter](http://img.shields.io/badge/Twitter-Follow-00aced.svg)](https://twitter.com/intent/follow?region=follow_link&screen_name=renard_0&tw_p=followbutton)


Remove plymouth because who needs it on servers?

Compile:

	debuild --no-tgz-check -I.git -i'\.git/' -us -uc

Install:

	dpkg -i no-plymouth_1.0_all.deb
	dpkg -P plymouth

enjoy!
