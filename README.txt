= SyslogLogger

Documentation :: http://docs.seattlerb.org/SyslogLogger
Source        :: https://github.com/seattlerb/sysloglogger
Bugtracker    :: https://github.com/seattlerb/sysloglogger/issues

== DESCRIPTION

SyslogLogger is a Logger replacement that logs to syslog.  It is almost
drop-in with a few differences.

== FEATURES

* Works like Logger
* Logs to syslog(3) mapping Logger levels to syslog(3) levels

== SYNOPSIS

  require 'syslog_logger'

  logger = SyslogLogger.new 'your_application_name'

  logger.info 'did something cool'

== INSTALL

  gem install SyslogLogger

You may need to configure your syslog.conf to place application logs in a
particular file.  See SyslogLogger for details.

== LICENSE

(The MIT License)

Copyright (c) Eric Hodel

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

