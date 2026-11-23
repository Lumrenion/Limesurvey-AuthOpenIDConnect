# AuthOpenIDConnect - LimeSurvey Auth Plugin

## Disclaimer
Original plugin by https://github.com/janmenzel

updated by olicha@worteks

## Updates
updated the compatibility in the config.xml file

### 1.2.0
- Added LimeSurvey 7 compatibility (config.xml)
- Upgraded jumbojett/openid-connect-php to ^1.0 (requires PHP >= 8.0, in line with LimeSurvey 7 which requires PHP >= 8.1)

## Requirements
- LimeSurvey 6.1+ or 7.x
- PHP >= 8.0

## Install

1. Download the plugin.

2. Install necessary dependencies via composer.
```
composer install
```

3. Zip the plugin with all dependencies installed.
```
zip -r AuthOpenIDConnect AuthOpenIDConnect/*
```

4. Install the plugin in LimeSurvey and fill in the necessary settings in order to connect to your ID Provider.

## Credits
Thanks to Michael Jett for providing the [OpenID Connect Client](https://github.com/jumbojett/OpenID-Connect-PHP)!
