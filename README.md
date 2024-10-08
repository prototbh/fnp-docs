# fnp API

**fnp** is a lightweight and simplified API for Fortnite, designed by me with the help of ChatGPT. It removes the complexity of the typical Fortnite API, allowing you to easily access Fortnite data without the overhead of dealing with large, cumbersome codebases.

## Why fnp?

Tired of dealing with bloated, over-engineered APIs just to retrieve Fortnite data? So was I. That’s why I built **fnp** — a simple, no-nonsense API to get the job done, fast and efficiently.

## Features

- **Lightweight**: Minimal overhead compared to the standard Fortnite API.
- **Easy to use**: Designed to be straightforward, so you don’t have to waste time with complex integrations.
- **Built for simplicity**: No unnecessary features, just the essentials to keep things moving.



To interact with the **fnp** API, you can use simple `GET` requests as shown below.
##


### Generating an Exchange Code

To generate an exchange code using an access token, send a `GET` request to the following URL:

URL: https://fnp-ka4a.onrender.com/exchange-get

Method: GET

Auth Required: Yes (bearer token in headers)

![Screenshot](https://raw.githubusercontent.com/prototbh/dksjhdskjhsdkjhdskds/refs/heads/main/image_2024-09-28_142725835.png)
##

### Generating Device auth (mainly used for bots)

To generate device auth, send a `GET` request to the following URL:

URL: https://fnp-ka4a.onrender.com/device-auth-get

Method: GET

Auth Required: Yes (bearer token in headers), (account id in headers)

![Screenshot](https://raw.githubusercontent.com/prototbh/dksjhdskjhsdkjhdskds/refs/heads/main/Screenshot%202024-09-28%20141905.png)
##

### Get user info from display name

To get info, send a `GET` request to the following URL:

URL: https://fnp-ka4a.onrender.com/user-lookup

Method: GET

Auth Required: Yes (bearer token in headers), (display name in headers)

![Screenshot](https://raw.githubusercontent.com/prototbh/dksjhdskjhsdkjhdskds/refs/heads/main/image_2024-09-28_144534957.png)
##

### Get token from device auth

To get token, send a `GET` request to the following URL:

URL: https://fnp-ka4a.onrender.com/device-auth-to-token

Method: GET

Auth Required: Yes (secret in headers), (device id in headers), (account id in headers)

![Screenshot](https://raw.githubusercontent.com/prototbh/dksjhdskjhsdkjhdskds/refs/heads/main/image_2024-09-28_210745651.png)
##

