usage: console.py [-p PORT] [-b BAUD] [--rtscts] [-t] [-f] [--file] [-v] [-r]
                  [-l] [-o LOG_DIRNAME] [--logfilename LOGFILENAME]
                  [--expand-json] [--skip-metadata] [--sort-keys]
                  [-i INITLOGLEVEL] [-u] [--error] [--log-console] [-h] [-V]

Swift Console

optional arguments:
  -p PORT, --port PORT  specify the serial port to use.
  -b BAUD, --baud BAUD  specify the baud rate to use.
  --rtscts              Enable Hardware Flow Control (RTS/CTS).
  -t, --tcp             Use a TCP connection instead of a local serial port.
                        If TCP is selected, the port is interpreted as
                        host:port
  -f, --ftdi            use pylibftdi instead of pyserial.
  --file                Read with a filedriver rather than pyserial.
  -v, --verbose         print extra debugging information.
  -r, --reset           reset device after connection.
  -l, --log             serialize SBP messages to autogenerated log file.
  -o LOG_DIRNAME, --log-dirname LOG_DIRNAME
                        directory in which to create logfile.
  --logfilename LOGFILENAME
                        filename to use for log. Default filename with date
                        and timestamp is used otherwise.
  --expand-json         Expand fields in JSON logs
  --skip-metadata       Omit metadata from JSON logs.
  --sort-keys           Sort JSON log elements by keys.
  -i INITLOGLEVEL, --initloglevel INITLOGLEVEL
                        Set log level filter.
  -u, --update          don't prompt about firmware/console updates.
  --error               Do not swallow exceptions.
  --log-console         Log console stdout/err to file.
  -h, --help            Show usage help in a GUI popup.
  -V, --version         show program's version number and exit

