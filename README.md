# Child Theme for Elementor Hello Theme
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
# Alternatively you can deploy without copying .git across
rm -rf .git 
# Copy your theme to production server
```
