# Custom TAO Theme

To get this extension in your TAO installation, modify your root composer.json as follow:

## 1. Add the repository
```
"repositories": [
    ...,
    {
       "type": "vcs",
       "url": "https://github.com/infosign/tao-theme-base.git"
    }
],

```

## 2. Add the extension
```
require" : {
    ...,
    "infosign/tao-theme-base": "dev-master"
],

```

## 3. Update composer
```
composer update infosign/tao-theme-base --prefer-source
```

## 4. Install the extension via TAO user interface
