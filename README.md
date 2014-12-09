## Tagesspiegel-paperboy

Tagesspiegel-paperboy is a command line tool to deliver your Tagesspiegel
newspaper freshly every day. Its CLI signature is as follows:

    usage: paperboy.py [-h] --user-agent USER_AGENT --output-directory
                       OUTPUT_DIRECTORY --kundennummer KUNDENNUMMER --plz PLZ
                       [--cookie-file COOKIE_FILE] [--debug] [--pdf] [--epub]
                       [--mobi]
    
    Tagesspiegel-paperboy delivers your Tagesspiegel newspaper freshly every day.
    
    optional arguments:
      -h, --help            show this help message and exit
      --user-agent USER_AGENT, -ua USER_AGENT
                            User agent you want paperboy to use.
      --output-directory OUTPUT_DIRECTORY, -o OUTPUT_DIRECTORY
                            Directory to store the PDFs of the downloaded
                            newspaper issues.
      --kundennummer KUNDENNUMMER, -k KUNDENNUMMER
                            Kundennummer (customer number) for your e-paper
                            subscription.
      --plz PLZ, -p PLZ     Postleitzahl (ZIP code) for your e-paper subscription.
      --cookie-file COOKIE_FILE, -c COOKIE_FILE
                            File to store the cookies in.
      --debug, -d           Increase verbosity.
      --pdf                 Download in PDF format.
      --epub                Download in ePub format.
      --mobi                Download in Mobi format.

It is written for Python 3.x and requires the modules
[requests](https://pypi.python.org/pypi/requests/) and
[beautifulsoup4](https://pypi.python.org/pypi/beautifulsoup4/).

