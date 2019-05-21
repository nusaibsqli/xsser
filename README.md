  ![XSSer](https://xsser.03c8.net/xsser/zika1.png "XSSerBanner")

=================================================================== 

 Cross Site "Scripter" (aka XSSer) is an automatic -framework- to detect, exploit and report XSS vulnerabilities.

 XSSer is released under the GPLv3. You can find the full license text
in the [COPYING](./xsser/doc/COPYING) file.

----------

 + Web:  https://xsser.03c8.net

----------

  ![XSSer](https://xsser.03c8.net/xsser/zika2.png "XSSerManifesto")

#### Installing:

----------
    
    git clone https://github.com/4k4xs4pH1r3/xsser.git && cd xsser
    

 XSSer runs on many platforms. It requires Python and the following libraries:

    - python-pycurl - Python bindings to libcurl
    - python-xmlbuilder - create xml/(x)html files - Python 2.x
    - python-beautifulsoup - error-tolerant HTML parser for Python
    - python-geoip - Python bindings for the GeoIP IP-to-country resolver library

 On Debian-based systems (ex: Kali, Ubuntu, ParrotSec), run: 

    sudo apt-get install python-pycurl python-xmlbuilder python-beautifulsoup python-geoip -y

 On other systems such as:  ArchLinux, Fedora, etc... also run:

       pip install geoip 

####  Source libs:

       * Python: https://www.python.org/downloads/
       * PyCurl: http://pycurl.sourceforge.net/
       * PyBeautifulSoup: https://pypi.python.org/pypi/BeautifulSoup
       * PyGeoIP: https://pypi.python.org/pypi/GeoIP

----------

#### Run xsser gui

      ./xsser --gtk

####  Screenshots:

  ![XSSer](https://xsser.03c8.net/xsser/url_generation.png "XSSerSchema")

  ![XSSer](https://xsser.03c8.net/xsser/zika3.png "XSSerAdvanced")

  ![XSSer](https://xsser.03c8.net/xsser/zika4.png "XSSerGeoMap")

