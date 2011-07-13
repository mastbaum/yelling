Yelling
=======

Introduction
------------
Often, we yell at our computers. Sometimes, however, we need our computers to yell at us. Or others. Or other computers. Sometimes, we even want a computer to yell at itself.

yelling is a tiny Python module that provides a common interface to many forms of digital yelling, including email, SMS, HTTP GET and POST, and logging, among others. It is intended to simplify and diversify feedback from headless, long-running, or system monitoring applications.

Features
--------
* Logging to File (yelling.log)
* Email (yelling.email): smtplib
* SMS (yelling.sms): smtplib
  * (yelling.sms_carriers()) provides a list of carrier options
* HTTP POST (yelling.http_post): urllib

