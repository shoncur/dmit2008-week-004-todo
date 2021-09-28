# Jimbits Starter Kit

 ## Pre Flight Check
__Install the required node modules__
```bash
  npm install
```

__To run the development server run__
```bash
  npm start
```  


__To run a production build run__
```bash
  npm run build
```


 ## CSS Styles
 It's up to you how you want to manage your css development. The kit support two style methods

### SCSS (default)
The kit is set up to work with scss. In order to get the Parcel bundler to compile your scss files on save you need to make sure that you link hte styles.scss file to the web document.

 ```html
    <link rel="stylesheet" href="scss/styles.scss">
 ```

 ### Vanilla CSS
To use plain old standerd css change the link element href attribute to point to the css file.

 ```html
    <link rel="stylesheet" href="css/your-styles.css">
 ```
 