# FullStory Session Recording URL - GTM Variable Template

## Description
This **Google Tag Manager (GTM) Variable Template** retrieves the **FullStory session recording URL** for the current user's session. The URL can be used for debugging, analytics, or tracking user sessions across different platforms.

## Repository Name
`fullstory-session-url-gtm`

## Features
- Automatically detects and supports different versions of the **FullStory SDK** to retrieve the session recording URL.
- Retrieves the **session recording URL** dynamically.
- Can be sent to **analytics platforms, logging systems, or other destinations**.

## Installation
1. Open **Google Tag Manager**.
2. Navigate to **Templates** → **New**.
3. Click **Import** and upload the `.tpl` file.
4. Save and publish the template.

## Example Output
Given an active FullStory session, the variable returns a URL like:
```
https://app.fullstory.com/ui/o-XXXXXX-na1/client-session/XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX
```
This URL links directly to the **user’s session recording** in **FullStory**.

## Usage
- Include this variable in **GTM tags** to capture session playback URLs.
- Send the URL to **CRM platforms, support teams, or analytics dashboards**.

## License
APACHE License

Developed by **Jude Nwachukwu Onyejekwe** for [**DumbData**](https://dumbdata.co/). where you can find more analytics resources in the **Measurement Resource Hub**.
