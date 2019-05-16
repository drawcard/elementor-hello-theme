# Child Theme for Elementor Hello Theme

## For standard installations

```
# Requires wp-cli
# Inside wp-content/themes folder
wp theme install hello-elementor 
wp theme install https://github.com/drawcard/hello-elementor-theme/archive/child-theme.zip --activate
```

## For more complex development purposes (eg editing & compiling CSS styles)
```
# On the dev server
cd project/wp-content/themes/
git clone -b child-theme --single-branch https://github.com/drawcard/hello-elementor-theme hello-elementor-child
wp theme activate elementor-hello-theme-child
cd elementor-hello-child
npm install
# Edit theme SCSS in /assets/custom/
grunt styles
# Get prepared to copy over to production
# optional, removes git versioning data for security purposes
# Alternatively you can deploy without copying .git & node_modules across with WP DB Migrate Pro
rm -rf .git node_modules/
# Copy your theme to production server
```
