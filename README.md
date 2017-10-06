## Website Performance Optimization portfolio project


### index.html
1.Clone this repo
2.run a local server

  ```bash
  $> cd /path/to/your-project-folder
  $> python -m SimpleHTTPServer 8080
  ```

3. Open a browser and visit localhost:8080
4. Download and install [ngrok](https://ngrok.com/) to the top-level of your project directory to make your local server accessible remotely.

  ``` bash
  $> cd /path/to/your-project-folder
  $> ./ngrok http 8080
  ```
5. Copy the public URL ngrok gives you and try running it through PageSpeed Insights!

* minify HTML.
* use media="print" for print css.
* put the CSS Inline the HTML file and import the font.
* compress all images using compressor.io.
* use responsivebreakpoints.com to resize pizzeria.jpg.

## pizza.html
1.Clone this repo
2.Locate pizza.html 
3.click on pizza.html
* Changed querySelectorAll() to getElementById or getElementsByClassName
* reduce number of pizza to 48
* make pizzaSize var instead of using document.getElementById("pizzaSize") every time
* add will change property to movingPizzas.
* use style.transform instead of style.left.
* put dx and offset outside of changePizzaSizes function because they all have the same size.
