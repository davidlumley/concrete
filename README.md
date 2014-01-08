# Concrete

A simple, responsive, twelve column grid framework.

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

[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/davidlumley/concrete/trend.png)](https://bitdeli.com/free "Bitdeli Badge")
