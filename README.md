# TinyShield
Prevent taking screenshots on iOS

## Usage

First, add the project as a package with <strong>SPM</strong>(Swift package Manager):

Click on <strong>add packages</strong> and paste the repo's url (https://github.com/dianaayalag/TinyShield) on the search field and click on <strong>Add Package</strong> :)

Just create a view with

```
let tinyShieldView = TinyShieldView()
self.view.addSubview(tinyShieldView)
```

    
Since it inherits from UIView, you can easily add constraints or customize the view as you like.

When someone takes screenshots, everything inside of the TinyShieldView will be hidden.

## Acknowledges

If you like this tiny library, you can [buy me a coffee](https://paypal.me/dianaayalag) :)
