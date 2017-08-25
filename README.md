# CoreProc Code Style Guide for Web Applications

As our number of projects grow, we find that it makes our lives easier if we all stick to a single coding style across 
all projects. This helps a great deal when reading and maintaining code.

This repository quickly outlines the coding style standards that we use as a web application development company. This
repository does not include our Android and iOS style guides.

Our web applications consist mainly of four technologies:

- PHP
- HTML
- CSS
- Javascript

## Code Style Sources

We rank the importance of code clarity and community conventions higher than personal style. We will use open and
transparent community standards whenever available and will not allow personal preferences to dictate the style of our 
code. If a preference is not defined in any of our sources, then we, as a company, will put the preference to a vote.

### PHP

Our PHP web applications follow the following coding style and standards as proposed by the PHP Framework 
Interoperability Group (PHP-FIG):

- [PSR-1 Basic Coding Standard](http://www.php-fig.org/psr/psr-1/)
- [PSR-2 Coding Style Guide](http://www.php-fig.org/psr/psr-2/)

### Javascript

Javascript powers most of our UI in our web applications and is now evolving pretty quickly. We want to follow the
latest standards that the community deems practical and sensible. Because of this, we find that 
[StandardJS](https://standardjs.com) closely follows our code style goals.

### HTML and CSS

Our HTML and CSS code follows [Google's HTML/CSS Style Guide](https://google.github.io/styleguide/htmlcssguide.html). We
find that Google has the most comprehensive guide for our purposes.

## IntelliJ IDEA Code Style Settings

This repository contains the code style settings for IntelliJ IDEs (compatible with WebStorm and PHPStorm).

When developing web applications, you can use IntelliJ's "reformat code" feature to automatically fix your code style.

The default reformat shortcut is `Ctrl+Alt+L` for Windows or `Cmd+Alt+L` for OSX. You can change this to any shortcut 
you deem convenient to you. The default workflow is to reformat your code before hitting save.

### Installation

Clone or [download](https://github.com/CoreProc/code-style-guide-web/archive/master.zip) this repository.

Open up your PHPStorm, go to "File" -> "Import Settings". Navigate to the `code-style.jar` file and choose that. Check 
all the boxes found in the next screen and hit "OK".

After importing, make sure you are using this profile by going to "Preferences" -> "Editor" -> and click on "Code Style".
Choose the "CoreProc" profile from the "Scheme" dropdown and hit OK.
