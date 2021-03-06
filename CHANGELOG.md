# [Changelog](https://github.com/yola/opensrs/releases)

## 2.1.0
* Add `OpenSRS.list_domains()`
* Add `Domain.to_dict()`

## 2.0.0
* Add `OpenSRS.iterate_domains()`
* Add `Domain` model
* Start to depend on `demands` and `python-dateutil`
* Move out tests from the package

## 1.1.1
* Fix wrong types in API call (`enable/disable_domain_auto_renewal`).

## 1.1.0
* Add methods to enable/disable domain auto-renewal.

## 1.0.2
* Add special handling in contact update for CA domains

## 1.0.1
* Added more auto-renewed TLDs (.at and .fr) ([#9][9])

[9]: https://github.com/yola/opensrs/pull/9

## 1.0.0
* Decided it's stable enough for 1.0.0
* Added more auto-renewed TLDs (.za and .dk) ([#6][6])

[6]: https://github.com/yola/opensrs/pull/6

## 0.1.0
* Renamed `get_transfers_away` to `get_transferred_away_domains`
* Now `get_transferred_away_domains` accepts optional `domain` param
    to narrow search to the given domain
