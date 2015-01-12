# Concrete

A simple, responsive, ultra lightweight twelve column grid framework.


Concrete is designed to be easy to read, simple to use, and small in file size.

It's currently:
* **2402** bytes or
* **709** bytes gzipped

## Usage

Concrete's grid is build using `columns` classes which are inside of a `row` class.

The `row` class encapsulates the `columns`. As Concrete uses a twelve column grid, the `twelve columns` class will take up the whole of the row.

    <div class='row'>
      <div class='twelve columns'>
      </div>
    </div>

You can mix it up however you like though.

    <div class='row'>
      <div class='four columns'>
      </div>
      <div class='eight columns'>
      </div>
    </div>

You can put a `row` class inside of a `column` class in order to nest `columns`.

    <div class='row'>
      <div class='four columns'>
      </div>
      <div class='eight columns'>
        <div class='row'>
          <div class='six columns'>
          </div>
          <div class='six columns'>
          </div>
        </div>
      </div>
    </div>

You can also [see it in action](http://davidlumley.github.io/concrete/).

## Contributing

If you're eager to contribute to Concrete's development, please fork it, create a feature branch, then make a pull request.

### Converting SASS/SCSS to CSS

You'll need to ensure ruby is installed.

* `gem install bundler` - to install bundler
* `bundle install` - to install sass
* `sass --watch ./scss:./css -t compressed` - to watch the files in the SCSS directory for changes, and compile them into `concrete.css`
