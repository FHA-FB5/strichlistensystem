<h1 align="center">Welcome to strichlistensystem 👋</h1>
<p>
  <a href="https://github.com/fsr5-fhaachen/strichlistensystem/blob/main/LICENSE" target="_blank">
    <img alt="License: MIT" src="https://img.shields.io/github/license/fsr5-fhaachen/strichlistensystem" />
  </a>
  <a href="https://twitter.com/fsr5_fhaachen" target="_blank">
    <img alt="Twitter: fsr5_fhaachen" src="https://img.shields.io/twitter/follow/fsr5_fhaachen.svg?style=social" />
  </a>
</p>

> Tally system for the first week of the Department of Electrical Engineering and Information Technology at FH Aachen - University of Applied Sciences.

## main

<a href="https://github.com/fsr5-fhaachen/strichlistensystem/actions/workflows/ci.yml" target="_blank">
  <img alt="CI" src="https://github.com/fsr5-fhaachen/strichlistensystem/actions/workflows/ci.yml/badge.svg" />
</a>

## dev

<a href="https://github.com/fsr5-fhaachen/strichlistensystem/actions/workflows/ci.yml" target="_blank">
  <img alt="CI dev" src="https://github.com/fsr5-fhaachen/strichlistensystem/actions/workflows/ci.yml/badge.svg?branch=dev" />
</a>

## Install

Clone the repository and install the dependencies:

```sh
git clone git@github.com:fsr5-fhaachen/strichlistensystem.git
cd strichlistensystem
npm install
composer install
```

Copy .env.example to .env and fill in the database credentials.

```sh
cp .env.example .env
```

Generate the application key:

```sh
php artisan key:generate
```

Run the migrations:

```sh
php artisan migrate
```

## Usage

### development

For development, you can use the built-in PHP server:

```sh
php artisan serve
```

and the vite dev server:

```sh
npm run dev
```

### type generation

To generate the typescript types for the frontend, run:

```sh
php artisan typescript:generate
```

### linting

You can lint the code with the following commands:

```sh
npm run lint
php artisan fixer:fix --dry-run -vvv
```

and try to fix the errors with:

```sh
npm run lint:fix
php artisan fixer:fix -vvv
```

### testing

You can run the tests with:

```sh
vendor/bin/phpunit
```

### build

You can build the application with:

```sh
npm run build
```

## Authors

👤 **Titus Kirch (main author)**

- Website: https://tkirch.dev/
- LinkedIn: [Titus Kirch](https://www.linkedin.com/in/tituskirch/)
- Twitter: [@TitusKirch](https://twitter.com/TitusKirch)
- Github: [@TitusKirch](https://github.com/TitusKirch)

👤 **Benedikt Haas (main author)**

- LinkedIn: [Benedikt Haas](https://www.linkedin.com/in/benedikt-haas-ab698924a/)
- Github: [@BenediktHaas96](https://github.com/BenediktHaas96)

👤 **Simon Ostendorf**

- LinkedIn: [Simon Ostendorf](https://www.linkedin.com/in/simonostendorf/)
- Github: [@simonostendorf](https://github.com/simonostendorf)

Show here to see the full list of [contributors](https://github.com/fsr5-fhaachen/strichlistensystem/graphs/contributors) who participated in this project.

## 🤝 Contributing

Contributions, issues and feature requests are welcome!<br />Feel free to check [issues page](https://github.com/fsr5-fhaachen/strichlistensystem/issues).

## Show your support

Give a ⭐️ if this project helped you!

## 📝 License

Copyright © 2022 [fsr5-fhaachen](https://github.com/fsr5-fhaachen).<br />
This project is [MIT](https://github.com/fsr5-fhaachen/strichlistensystem/blob/main/LICENSE) licensed.