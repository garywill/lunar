# lunar
Chinese lunar for Linux

Usage:

Solar->Lunar:	lunar [-u] [-h] [-b] [year month day [hour]]
		(in Solar Calendar, 24 hour clock)

Lunar->Solar:	lunar [-u] [-h] [-b] -i [-l] year month day [hour]
		(in Lunar Calendar, 24 hour clock)
		-l  means the month is a leap month ("run4 yue4")

		-u, --utf8  means output in hanzi (UTF-8)
		        -s  selects simplified Chinese for UTF-8
		        -t  selects traditional Chinese for UTF-8
		-h, --gb    means output in hanzi (GB)
		-5, --big5  means output in hanzi (Big5)

		-b          means output in "bitmap"
Date range: about 150 years from the Solar Date 1900.1.31
