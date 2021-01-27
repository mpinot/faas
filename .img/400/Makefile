WIDTH?= $(notdir $(PWD))

_default: import resize

resize:
	sips -Z $(WIDTH) *.png

import:
	cp ../o/*png ./

