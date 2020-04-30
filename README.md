# Mattermost Docker

This project allows building a simple docker image of Mattermost.
It does not include the databse.

The Mattermost configuration can be changed by setting MM_* environment variables, as explained in the Mattermost documentation:
> Find the setting in config.json. In this case, ServiceSettings.SiteURL.
>
> Add MM_ to the beginning and convert all characters to uppercase and replace the . with _. For example, MM_SERVICESETTINGS_SITEURL.
>
> The setting becomes export MM_SERVICESETTINGS_SITEURL="http://example.com".

https://docs.mattermost.com/administration/config-settings.html
