# Laravel-5-Blade-Snippets
Updated package for use in Laravel 5 Blade templating.

Laravel5BladeSnippets 
# Laravel 5 Blade Snippets for Sublime Text 3

`Blade` is a simple, yet powerful templating engine provided with [Laravel 5] (http://laravel.com) PHP framework.

These snippets works with blade files (`.blade.php`) either with php syntax or with blade syntax using: **PHP - Laravel Blade** available from [Laravel Blade Highlighter] (https://github.com/Medalink/laravel-blade) package.

##Usage
When you're on a blade file, type the snippet shortcut then press `tab` key.

##Installation
Via `Package Manager` search for `Laravel 5 Blade Snippets` then click/tap…wait a sec and tada!

![Blade Snippets](http://f.dev.mk.ua/files/dadbee44b4461b709d444951ba26f70f/file_51d27202c2a8b.png)

Or clone this repository into your Packages folder:

    git clone https://github.com/phillipmadsen/Laravel-5-Blade-Snippets.git


Or download the snippets zip file and unzip it into your Packages folder.

##Avalable snippets

| Shortcut                     | Result |
|----------------------------- |--------|
| ext		                   | @extends('`name`') |
| lay		                   | @layout('`name`')  |
| sec		                   | @section('`name`') <br /> **{!!-- expr --!!}** <br /> @endsection    |
| secy		                   | @section('`name`') <br /> **{!!-- expr --!!}** <br /> @yield_section |
| yl		                   | @yield('`section`', '`default`') |
| lsec		                   | @section('`name`') <br /> **{!!-- expr --!!}** <br /> @show |
| par		                   | @parent	|
| !!		                   | {!! $`var` !!}	|
| !!}		                   | {!! `escaped output` !!}	|
| inc		                   | @include('`view.name`', `array('some' => 'data')`)  |
| if		                   | @if (`condition`) <br /> **{!!-- expr --!!}** <br /> @endif   |
| ife		                   | @if (`condition`) <br /> **{!!-- expr --!!}** <br /> @else <br /> **{!!-- expr --!!}** <br /> @endif  |
| foreach	                   | @foreach(`$array` as `$element`) <br /> **{!!-- expr --!!}** <br /> @endforeach  |
| fore		                   | @forelse (`$array` as `$element`) <br /> **{!!-- expr --!!}** <br /> @endforelse  |
| for		                   | @for (`$i` = `0`; `$i` `<` `…`; `$i++`) <br /> **{!!-- expr --!!}** <br /> @endfor  |
| each		                   | @each ('`item.view`', $`items`, '`item`', '`empty.view`')
| trans		                   | {!! trans('`language.line`') !!}	|
| route		                   | {!! route('`name`') !!}	|
| asset		                   | {!! asset('`path`') !!}	|
| while		                   | @while (`condition`) <br /> **{!!-- expr --!!}** <br /> @endwhile  |
| unless	                   | @unless (`condition`) <br /> **{!!-- expr --!!}** <br /> @endunless  |
| choise	                   | @choice('`language.line`', $`number`)  |
| comment	                   | {!!-- `comment` --!!}	|
| lang		                   | @lang('`language.line`', array('`variable` => '`replacement`'))  | 
| l5 form: 	textarea           | see inside snippet	|
| l5 form: 	textfield          | see inside snippet	| 
 



---
Original snippets by:
[@AAlakkad](https://github.com/AAlakkad)
[@dev4dev](https://github.com/dev4dev)

Cool Readme formatting and latest updates belong to:
* Github: .[@phillipmadsen](https://github.com/phillipmadsen)
* Email: [contact@affordableprogrammer.com](mailto:contact@affordableprogrammer.com).

