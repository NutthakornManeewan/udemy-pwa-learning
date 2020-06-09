# Manifest properties
'''
{
    "name": "String name",      Long name of app
    "short_name": "String",     Short name of app
    "start_url": "/index.html", start up page
    "scope": ".",               Which page included in PWA
    "display": "standalone",    Should it look like a standalone app?
    "background_color": "#ffffff" 
    "theme_color": "#ffffff"    Theme color (top bar in task switcher)
    "description": "Some string", description information.
    "dir": "ltr"                Read direction of your app (Left to right: ltr)
    "lang": "en-US",            Main language of application
    "orientation": "portrait-primary",  Set default orientation
    "icons": [
        {
            "src": "/path/to/image",
            "type": "image/png"
            "sizes": "48x48"
        }
    ],
    "related_applications": [
        {
            "platform": "play",
            "url": "https://play.google.com......",
            "id": "com.example.app1"
        }
    ]
}
'''