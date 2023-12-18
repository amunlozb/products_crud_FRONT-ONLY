# Front End for my Web Application Project

This is the front-end side that will be used in [my ecommerce web application project](https://github.com/amunlozb/products_crud/).
It's developed using SASS files in a completely modular manner, for higher simplicity and ease of use, as well as maintenance.

## Technologies Used

- HTML
- CSS
- SASS

## Project Structure

```plaintext
FRONT
|   catalog.html
|   home.html
|   login.html
|   main.css
|   main.css.map
|   main.scss
|
+---base
|       _variables.scss
|
+---components
|       _buttons.scss
|       _cards.scss
|
+---img
|   |   button.png
|   |   coffe-banner.png
|   |   coffee-logo.png
|   |
|   +---banner
|   |       promo-banner.png
|   |
|   +---features
|   |       feature-chart.png
|   |       feature-clock.png
|   |       feature-graph.png
|   |       feature-laptop.png
|   |       feature-mail.png
|   |       feature-person.png
|   |
|   \---products
|           product-img1.jpeg
|           product-img2.jpeg
|           product-img3.jpeg
|           product-img4.jpeg
|           product-img5.png
|           product-img6.png
|           product-img7.jpeg
|
+---layout
|       _footer.scss
|       _header.scss
|       _main-content.scss
|       _sidebar.scss
|
\---views
        _catalog.scss
        _home.scss
        _register.scss
```

## License

This project is licensed under the MIT License.

All the images were generated by Stable Diffusion XL, a deep learning, text-to-image model, and are licensed under the [CreativeML Open RAIL-M License](https://huggingface.co/spaces/CompVis/stable-diffusion-license).
