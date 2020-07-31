# ConfApp

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 10.0.3.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
"Front-End WebApp with Bootstrap" 

## Start App

Starting the App with intoduction to bootstrap components

## Bootstrap Grid System

Bootstrap uses a 12 column system to organize the grid
It's 3 major components are:
    Containers.
    Rows.
    Columns.

    <div class="container">
        <div class="row">
            <div class="col">
            1 of 2
            </div>
            <div class="col">
            2 of 2
            </div>
        </div>
        <div class="row">
            <div class="col">
            1 of 3
            </div>
            <div class="col">
            2 of 3
            </div>
            <div class="col">
            3 of 3
            </div>
        </div>
    </div>

## Fuild vs non Fuild Container

Fuild spans the whole page while non fuild centers in the middleware with a flexible width

    <div class="container-fuild">
            <div class="row">
                <div class="col">
                1 of 2
                </div>
                <div class="col">
                2 of 2
                </div>
            </div>
            <div class="row">
                <div class="col">
                1 of 3
                </div>
                <div class="col">
                2 of 3
                </div>
                <div class="col">
                3 of 3
                </div>
            </div>
        </div>

## Column Sizing

To display different size at different break points.

    .col-	.col-sm-	.col-md-	.col-lg-	.col-xl-
    
    <div class="col-sm">


## Style Content

Styling content using Bootstrap Content, Utility, and Typography classes.

## Utility

For paddings and margins.
For Setting the vertical and horizontal padding of an element.
pt-4 for padding top 1.5 rem
mb-4 applied a bottom margin 1.5 rem

    <div class="container pt-4">
    <h3 class="mb-4">About Full Stack Conf</h3>
    <h3 class="mb-4">Expert Speakers</h3>
    <img class="mb-4" src="../assets/img/pdx.jpg" alt="Portland">

Border Radius.

    <img class="mb-4 img-fluid rounded" src="../assets/img/pdx.jpg" alt="Portland">

Notation.
    m - for classes that set margin
    p - for classes that set padding
    Where sides is one of:

    t - for classes that set margin-top or padding-top
    b - for classes that set margin-bottom or padding-bottom
    l - for classes that set margin-left or padding-left
    r - for classes that set margin-right or padding-right
    x - for classes that set both *-left and *-right
    y - for classes that set both *-top and *-bottom
    blank - for classes that set a margin or padding on all 4 sides of the element
    Where size is one of:

    0 - for classes that eliminate the margin or padding by setting it to 0
    1 - (by default) for classes that set the margin or padding to $spacer * .25
    2 - (by default) for classes that set the margin or padding to $spacer * .5
    3 - (by default) for classes that set the margin or padding to $spacer
    4 - (by default) for classes that set the margin or padding to $spacer * 1.5
    5 - (by default) for classes that set the margin or padding to $spacer * 3
    auto - for classes that set the margin to auto

## Opting Images for responsive behaivor

Image fluid makes sure that the image is never bigger that is parent component
    
    <img class="mb-4 img-fluid" src="../assets/img/pdx.jpg" alt="Portland">

## Text size and centering

    <h1 class="display-4 text-center mx-5">Speakers</h1>

## Typography

To applie a grey font color we can use the text-muted

    <h3>
        Fancy display heading
        <small class="text-muted">With faded secondary text</small>
    </h3>


