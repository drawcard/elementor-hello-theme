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
# Copy your theme to production server
```
