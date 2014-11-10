[![Build Status](https://travis-ci.org/renard/no-plymouth.svg?branch=master)](https://travis-ci.org/renard/no-plymouth)


Remove plymouth because who needs it on servers?

Compile:

	debuild --no-tgz-check -I.git -i'\.git/' -us -uc

Install:

	dpkg -i no-plymouth_1.0_all.deb
	dpkg -P plymouth

enjoy!
