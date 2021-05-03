# Fetcher from https://receive-sms.cc/

This allow to quickly find the used and recently active phone for one off SMS
receiving

Produce the list of phones from the most fresh to the most polluted

*NOTE*: Site has a rate limiter, after a few runs of a script it is easy to
catch constant value 400 in the received field.

## Dependencies

Ruby 2.7 (untested with prior versions)

## Usage

```bash
bin/receive_sms
```
