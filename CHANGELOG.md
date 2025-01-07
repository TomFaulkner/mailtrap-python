## [3.0.0] - 2025-01-07
- Add async send method
- Switches out httpx for requests
- Removes support for Python < 3.9
- Adds support up to 3.13
- Tests for client are currently broken due to dependence upon `responses` library, which is specific to `requests`
## [2.0.1] - 2023-05-18
- Add User-Agent header to all requests

## [2.0.0] - 2023-03-11

- Initial release of the official mailtrap.io API client.
- This release is a completely new library, incompatible with v1.
- Send mails using the new Mailtrap Sending API.

## [1.0.1] - 2020-10-03

- Renamed to [Sendria](https://github.com/msztolcman/sendria). An SMTP server that makes all received mails accessible via a web interface and REST API.
