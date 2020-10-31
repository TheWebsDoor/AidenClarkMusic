### Introduction

This template is built to create SFCC content asset with React and generate a
build folder with all assets / js /css and html ready for SFCC upload.

More instructions to come...

### Environment variables (.env)

Add the following environment variables within a .env file:
REACT_APP_ENV="< **store | upc** >"
REACT_APP_OCAPI_CLIENTID=< **Client ID provided by SFCC** >
REACT_APP_DEV_LOCALE="< **Locale to use while in development mode** (en_US, fr_CA, es_ES...) >"

### Image component

When using static images, please ensure you are using the dedicated Image component. This component ensure that the image source generated by SFCC with a caching functionality remains the same between the Server and the Client.
