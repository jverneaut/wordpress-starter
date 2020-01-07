# WordPress Starter Theme

This project serves as a blank WordPress theme to build upon. It is ACF-ready and includes **sass** and **es6** support via **webpack**.

Usefull Bootstrap styles are also included in `scss/vendors/_bootstrap.scss` (grid, utilities, etc.).

### Usage

```sh
# Download WordPress Starter Theme
cd /wp-content/themes
git clone https://github.com/jverneaut/wordpress-starter
mv wordpress-starter <MY_THEME_NAME>

# Install dependencies
cd <MY_THEME_NAME>
npm install

# Dev
npm run start

# Build
npm run build
```
