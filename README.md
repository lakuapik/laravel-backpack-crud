# Backpack CRUD v4.1

> :Note: [Laravel backpack v4.1 does not support laravel v9.0](https://github.com/Laravel-Backpack/CRUD/pull/4094#issuecomment-1047471991)

This is a version of backpack v4.1 which i add support for laravel ^9.0.

Each release of backpack v4.1 will be sync into 4.1-L9 branch.

## Installation

Uninstall previous installed backpack

```
$ composer remove backpack/crud
```

Add this to your composer.json file

```jsonc
{
    repositories: [
        {
            "type": "vcs",
            "url": "https://github.com/lakuapik/laravel-backpack-crud-4.1"
        }
    ]
}
```

Then run:

```bash
$ composer require backpack/crud:dev-4.1-L9
```

----

<br>
<p align="center">
    <a href="https://backpackforlaravel.com" title="Backpack Logo"><img src="https://backpackforlaravel.com/presentation/img/backpack/logos/backpack_logo_color.png" style="max-width: 600px"></a>
<p>

<p align="center">
    <a href="https://backpackforlaravel.com/" title="Backpack Screenshots Spread"><img src="https://backpackforlaravel.com/presentation/img/backpack/backpack_hero_screenshots.png"></a>
</p>

<p align="center">
    <br>
    <a href="https://packagist.org/packages/backpack/crud" title="Latest Version on Packagist"><img src="https://img.shields.io/packagist/v/backpack/crud.svg?style=flat-square"></a>
    <a href="https://packagist.org/packages/backpack/crud" title="Total Downloads"><img src="https://img.shields.io/packagist/dt/backpack/crud.svg?style=flat-square"></a>
    <a href="https://github.com/Laravel-Backpack/CRUD/commits/master" title="Last commit"><img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/laravel-backpack/crud"></a>
    <a href="https://scrutinizer-ci.com/g/laravel-backpack/crud" title="Quality Score"><img src="https://img.shields.io/scrutinizer/g/laravel-backpack/crud.svg?style=flat-square"></a>
    <a href="https://travis-ci.org/Laravel-Backpack/CRUD" title="Build Status"><img src="https://img.shields.io/travis/Laravel-Backpack/CRUD/master.svg?style=flat-square"></a>
    <a href="https://styleci.io/repos/53581270" title="Style CI"><img src="https://styleci.io/repos/53581270/shield"></a>
    <a href="https://scrutinizer-ci.com/g/laravel-backpack/crud/code-structure" title="Coverage Status"><img src="https://img.shields.io/scrutinizer/coverage/g/laravel-backpack/crud.svg?style=flat-square"></a>
    <a href="LICENSE.md" title="Software License"><img src="https://img.shields.io/badge/License-dual-blue"></a>
    <a href="https://github.com/the-whole-fruit/manifesto"><img src="https://img.shields.io/badge/writing%20standard-the%20whole%20fruit-brightgreen" title="We believe writing good code is not only about writing good code. It’s also about the words around it. We aims to deliver both: code and words."></a>
    <br><br>
    <a href="https://backpackforlaravel.com/">Website</a> | 
    <a href="https://backpackforlaravel.com/docs/">Documentation</a> | 
    <a href="https://backpackforlaravel.com/addons">Add-ons</a> | 
    <a href="https://backpackforlaravel.com/pricing">Pricing</a> |
    <a href="https://backpackforlaravel.com/need-freelancer-or-development-team">Services</a> | 
    <a href="https://stackoverflow.com/questions/tagged/backpack-for-laravel">Stack Overflow</a> | 
    <a href="https://www.reddit.com/r/BackpackForLaravel/">Reddit</a> | 
    <a href="https://backpackforlaravel.com/articles">Blog</a> | 
    <a href="https://backpackforlaravel.com/newsletter">Newsletter</a>
</p>


Quickly build an admin interface for your Eloquent models. Then customize every little detail. Among its features:

- List operation
   - 24+ column types
   - 1-1, 1-n and n-n relationships
   - table view with search, pagination
   - click column header to sort by it
   - custom buttons
   - details row
   - bulk actions
   - easily create new column types
   - easily overwrite an existing column type
- Create / Update operations
   - 50+ field types
   - back-end validation using Laravel Form Requests
   - translatable models (multi-language)
   - have multiple fields per line
   - split fields into tabs
- Delete / Bulk Delete operations
- Clone / Bulk Clone operations
- Reorder operation
- Revisions operation (audit log)

But professionals don't love Backpack just because it's feature-packed. They also love it because it's ridiculously easy to overwrite a functionality. Generally, you just need to create a function with the right name or create a blade file with the right name. Yes, it can be _that_ easy. See why thousands of Laravel professionals have been using Backpack, every day, since 2016.

## Screenshots

![https://user-images.githubusercontent.com/1032474/86720524-c5a1d480-c02d-11ea-87ed-d03b0197eb25.gif](https://user-images.githubusercontent.com/1032474/86720524-c5a1d480-c02d-11ea-87ed-d03b0197eb25.gif)

The GIF above should give you with a good idea about what Backpack will help you build. But you can also see it in action in our [live demo](https://demo.backpackforlaravel.com/admin), to get a deeper understanding of how Backpack admin panels look & feel and the amount of features it provides.

## Getting started

Start with the ["Getting Started" series](https://backpackforlaravel.com/docs/4.0/introduction) in our docs. We try to nudge you towards creating a Backpack acccount, but you don't _need_ one, if you're just trying it out.

Alternatively, if you don't have 20 minutes right now, subscribe to our [drip email tutorial](https://backpackforlaravel.com/getting-started-emails). You'll receive one email per day, for 5 days, 5 minutes each. By the end, you'll be familiar with how Backpack works, and be able to create admin panels for your Laravel apps.

> ### Security updates and breaking changes
> If you're using Backpack in production, please **[subscribe to the Backpack Newsletter](http://backpackforlaravel.com/newsletter)** so you can find out about any security updates, breaking changes or major features. We never _ever_ share your email with anyone & we try to send as few emails as possible (1-4 emails per year). We hate unsolicited email too. But... you know... you're building an admin panel, security _should_ be something you're up-to-date with.

## Install

Installation guides:
- [Install Backpack 4.1 on Laravel 6, 7 or 8](https://backpackforlaravel.com/docs/4.1/installation) - recommended;
- [Install Backpack 4.0 on Laravel 5.8, 6 or 7](https://backpackforlaravel.com/docs/4.0/installation) - last feature update was 21st Apr 2020;
- [Install Backpack 3.6 on Laravel 5.8 or 6.x](https://backpackforlaravel.com/docs/3.6/installation) - last feature update was 17th Sep 2019;
- [Install Backpack 3.5 on Laravel 5.5, 5.6, 5.7](https://backpackforlaravel.com/docs/3.5/installation) - last feature update was 27th Feb 2019;
- [Install Backpack 3.x on Laravel 5.4](https://laravel-backpack.readme.io/docs/install-on-laravel-54) - last feature update was 27 Sep 2017;
- [Install Backpack 3.x on Laravel 5.3](https://laravel-backpack.readme.io/docs/installation-on-laravel-53) - last feature update was 02 Feb 2017;
- [Install Backpack 3.x on Laravel 5.2](https://laravel-backpack.readme.io/docs/installation) - deprecated, lacks a lot of features;

## Change Log

For the current release (4.1.x) please see [the Releases tab](https://github.com/Laravel-Backpack/CRUD/releases). For previous versions (Backpack <=4.0.x), please see our old [CHANGELOG](CHANGELOG.md) file.

## Contributing Guidelines

This project stands by [The Whole Fruit Manifesto](https://github.com/the-whole-fruit/manifesto). We believe that “_writing good code_” is not only about “_writing good code_”. It’s also about the words around it. That’s why, to make sure your contribution is well received, we ask you to [read and keep in mind the ONE=MOR framework and guidelines](https://github.com/the-whole-fruit/manifesto) when writing comment blocks, PR titles, PR descriptions, and in general, when writing to our community. 

For tasks & details about how you can help our project, please see [CONTRIBUTING](CONTRIBUTING.md).

## Security

If you discover any security related issues, please email hello@backpackforlaravel.com instead of using the issue tracker. Alternatively, please disclose the issue on [huntr.dev](https://huntr.dev/) to also get a small bounty ($25-40).

> It's _heavily_ recommended that you **[subscribe to the Backpack Newsletter](http://backpackforlaravel.com/newsletter)** so you can find out about any security updates, breaking changes or major features. We send an email about 3-4 emails per year. Sometimes less.

## Credits

- [Cristian Tabacitu](http://tabacitu.ro) - creator & lead maintainer;
- [Pedro Martins](https://github.com/pxpm) - maintainer;
- [António Almeida](https://github.com/promatik) - maintainer;
- [All Contributors][link-contributors]

Special thanks go to:
- [Owen Melbourne](https://github.com/OwenMelbz), [Oliver Ziegler](https://github.com/OliverZiegler), [Thomas Swonke](https://github.com/tswonke), [Catalin Tudorache](https://github.com/tumf87), [Abby Janke](https://github.com/AbbyJanke), [David Lloyd](https://github.com/lloy0076) - A LOT of new features, bug fixing, support, feedback and code review;
- [Łukasz Holeczek](https://coreui.io/) - creator of CoreUI (used in Backpack v4);
- [Abdullah Almsaeed](https://adminlte.io/) - creator of AdminLTE (used in Backpack v3);
- [John Skoumbourdis](http://www.grocerycrud.com/) - Grocery CRUD for CodeIgniter was a big inspiration for Backpack v1 & v2;
- [Taylor Otwell](https://github.com/taylorotwell) & Laravel contributors (of course);

## License

Backpack is dual-license: 
- FREE for non-commercial use
- PAID for commercial use

Please see the [License File](LICENSE.md) and [Pricing](https://backpackforlaravel.com/pricing) for more information.

<a name="versioning"></a>
## Versioning

When installing Backpack, require its minor version (currently ```4.1.*```). For us, this is what ```major.minor.patch``` means:

- ```major``` - **PAID upgrade; MAJOR breaking changes;** historically every 2-3 years; upgrading may take even 2-3 hours; includes major new features, major changes in how the whole system works, and complete rewrites; it allows us to _considerably_ improve the product, and add features that were previously impossible;
- ```minor``` - **FREE upgrade; MINOR breaking changes**; historically every 6-12 months; upgrading takes less than 30 minutes; it allows us to add big new features, for free;
- ```patch``` - **FREE upgrade; NO breaking changes**; historically every week; upgrading can be done automatically with composer; includes bug fixes and non-breaking new features;

## Hire us

We've spend more than 10.000 hours creating, polishing and maintaining administration panels on Laravel. We've developed e-Commerce, e-Learning, ERPs, social networks, payment gateways and much more. We've worked on admin panels _so much_, that we've created one of the most popular packages for Laravel - just from making public what was repetitive in our projects.

If you are looking for a developer/team to help you build an admin panel on Laravel, look no further. You'll have a difficult time finding someone with more experience & enthusiasm for admin panels. This is _what we do_. [Contact us](https://backpackforlaravel.com/need-freelancer-or-development-team).



[ico-version]: https://img.shields.io/packagist/v/dick/crud.svg?style=flat-square
[ico-license]: https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square
[ico-downloads]: https://img.shields.io/packagist/dt/tabacitu/crud.svg?style=flat-square

[link-packagist]: https://packagist.org/packages/backpack/crud
[link-downloads]: https://packagist.org/packages/backpack/crud
[link-author]: https://tabacitu.ro
[link-contributors]: ../../contributors
