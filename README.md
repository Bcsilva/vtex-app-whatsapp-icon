# Whatsapp icon (VTEX External App)

## Install

For installing the external app `vendor.vtex-app-whatsapp-icon@0.x`, keep in mind the app is currently linked to the vendor account. Then, access the store store-theme via repository, and use the following command line:

``` js
    vtex install vendor.vtex-app-whatsapp-icon@0.x
```

## Settings

After installing the application, check the VTEX store account apps to find the **Whatsapp icon (VTEX External App)** among the installed apps. There you can configure the following fields:

- Toggle active/inactive
- Whatsapp link url
- Whatsapp icon image (by default it uses a SVG icon)

It's not necessary to declare the component on store-theme, because it's normally rendered before `<body>` tag closure in the store pages.

## Uninstall

On the store account, via command line:
``` js
    vtex uninstall vendor.vtex-app-whatsapp-icon@0.x
```