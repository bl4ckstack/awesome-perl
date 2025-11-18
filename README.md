# Awesome Perl [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome Perl frameworks, libraries, software and resources.

Perl is a highly capable, feature-rich programming language with over 30 years of development. Perl runs on over 100 platforms from portables to mainframes and is suitable for both rapid prototyping and large scale development projects.

[![Perl](https://img.shields.io/badge/Perl-5.38-39457E?style=flat&logo=perl&logoColor=white)](https://www.perl.org/)
[![CPAN](https://img.shields.io/badge/CPAN-Modules-blue)](https://metacpan.org/)
[![License](https://img.shields.io/badge/License-Artistic%202.0-green.svg)](https://opensource.org/licenses/Artistic-2.0)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

## Contents

- [Web Frameworks](#web-frameworks)
- [Object Oriented Programming](#object-oriented-programming)
- [Database](#database)
- [Template Engines](#template-engines)
- [Testing](#testing)
- [Command Line](#command-line)
- [Data Formats](#data-formats)
- [Date & Time](#date--time)
- [Email](#email)
- [File Manipulation](#file-manipulation)
- [Logging](#logging)
- [Web Scraping](#web-scraping)
- [Asynchronous](#asynchronous)
- [Text Processing](#text-processing)
- [Security](#security)
- [Performance](#performance)
- [Development Tools](#development-tools)
- [Resources](#resources)

## Web Frameworks

*Modern web frameworks for building web applications.*

- **[Mojolicious](https://mojolicious.org/)** - Real-time web framework with elegant and powerful syntax.
- **[Dancer2](https://metacpan.org/pod/Dancer2)** - Lightweight yet powerful web application framework inspired by Sinatra.
- **[Catalyst](https://metacpan.org/pod/Catalyst)** - MVC web framework with excellent plugin ecosystem.
- **[Web::Simple](https://metacpan.org/pod/Web::Simple)** - Minimalist web framework for building simple web applications.
- **[CGI::Application](https://metacpan.org/pod/CGI::Application)** - Framework for building reusable web applications.

## Object Oriented Programming

*Modern OOP systems for Perl.*

- **[Moose](https://metacpan.org/pod/Moose)** - Complete modern object system with meta-object protocol.
- **[Moo](https://metacpan.org/pod/Moo)** - Minimalist object orientation with Moose compatibility.
- **[Mouse](https://metacpan.org/pod/Mouse)** - Lightweight Moose alternative with better performance.
- **[Class::Tiny](https://metacpan.org/pod/Class::Tiny)** - Minimalist class builder with automatic accessor generation.
- **[Object::Pad](https://metacpan.org/pod/Object::Pad)** - Experimental new object system for Perl 5.

## Database

*Libraries for working with databases.*

- **[DBI](https://metacpan.org/pod/DBI)** - Database independent interface for Perl.
- **[DBIx::Class](https://metacpan.org/pod/DBIx::Class)** - Extensible and flexible ORM.
- **[Mojo::Pg](https://metacpan.org/pod/Mojo::Pg)** - PostgreSQL integration with non-blocking queries.
- **[Redis](https://metacpan.org/pod/Redis)** - Perl binding for Redis database.
- **[MongoDB](https://metacpan.org/pod/MongoDB)** - Official MongoDB driver for Perl.
- **[DBD::SQLite](https://metacpan.org/pod/DBD::SQLite)** - Self-contained SQLite database engine.

## Template Engines

*Libraries for templating and lexing.*

- **[Template Toolkit](https://metacpan.org/pod/Template)** - Powerful and extensible template processing system.
- **[Text::Xslate](https://metacpan.org/pod/Text::Xslate)** - Fast template engine with multiple syntaxes.
- **[HTML::Template](https://metacpan.org/pod/HTML::Template)** - Simple HTML templating system.
- **[Mason](https://metacpan.org/pod/Mason)** - Powerful template system with component-based architecture.
- **[Mojo::Template](https://metacpan.org/pod/Mojo::Template)** - Lightweight embedded Perl templates.

## Testing

*Libraries for testing codebases and generating test data.*

- **[Test::More](https://metacpan.org/pod/Test::More)** - Basic testing framework included with Perl.
- **[Test2::Suite](https://metacpan.org/pod/Test2::Suite)** - Modern testing framework with rich feature set.
- **[Test::Exception](https://metacpan.org/pod/Test::Exception)** - Test exception-based code.
- **[Test::MockModule](https://metacpan.org/pod/Test::MockModule)** - Override subroutines in modules for testing.
- **[Devel::Cover](https://metacpan.org/pod/Devel::Cover)** - Code coverage metrics for Perl.
- **[Test::Mojo](https://metacpan.org/pod/Test::Mojo)** - Testing toolkit for Mojolicious applications.

## Command Line

*Libraries for building CLI applications.*

- **[Getopt::Long](https://metacpan.org/pod/Getopt::Long)** - Extended processing of command line options.
- **[App::Cmd](https://metacpan.org/pod/App::Cmd)** - Framework for building command-line applications.
- **[Term::ANSIColor](https://metacpan.org/pod/Term::ANSIColor)** - Color screen output using ANSI escape sequences.
- **[IO::Prompter](https://metacpan.org/pod/IO::Prompter)** - Prompt users for input with validation.
- **[Term::ProgressBar](https://metacpan.org/pod/Term::ProgressBar)** - Provide progress bars for long-running operations.

## Data Formats

*Libraries for parsing and manipulating data formats.*

- **[JSON::MaybeXS](https://metacpan.org/pod/JSON::MaybeXS)** - Use the fastest available JSON implementation.
- **[YAML::XS](https://metacpan.org/pod/YAML::XS)** - Fast YAML parser and dumper.
- **[XML::LibXML](https://metacpan.org/pod/XML::LibXML)** - Interface to libxml2 library for XML processing.
- **[Data::MessagePack](https://metacpan.org/pod/Data::MessagePack)** - MessagePack serialization format.
- **[CSV](https://metacpan.org/pod/Text::CSV_XS)** - Fast CSV parser written in C.
- **[TOML](https://metacpan.org/pod/TOML)** - Parser for Tom's Obvious Minimal Language.

## Date & Time

*Libraries for working with dates and times.*

- **[DateTime](https://metacpan.org/pod/DateTime)** - Comprehensive date and time object.
- **[Time::Piece](https://metacpan.org/pod/Time::Piece)** - Object-oriented time objects included with Perl.
- **[DateTime::Format::Strptime](https://metacpan.org/pod/DateTime::Format::Strptime)** - Parse and format datetime strings.
- **[Time::Moment](https://metacpan.org/pod/Time::Moment)** - High-performance immutable datetime objects.

## Email

*Libraries for sending and parsing email.*

- **[Email::Sender](https://metacpan.org/pod/Email::Sender)** - Library for sending email.
- **[Email::MIME](https://metacpan.org/pod/Email::MIME)** - Easy MIME message handling.
- **[Email::Valid](https://metacpan.org/pod/Email::Valid)** - Check validity of email addresses.
- **[Mail::IMAPClient](https://metacpan.org/pod/Mail::IMAPClient)** - IMAP client interface.

## File Manipulation

*Libraries for file manipulation and MIME type detection.*

- **[Path::Tiny](https://metacpan.org/pod/Path::Tiny)** - Simple object-oriented file path manipulation.
- **[File::Slurp](https://metacpan.org/pod/File::Slurp)** - Simple and efficient file reading and writing.
- **[File::Find::Rule](https://metacpan.org/pod/File::Find::Rule)** - Alternative interface to File::Find.
- **[Archive::Extract](https://metacpan.org/pod/Archive::Extract)** - Generic archive extracting mechanism.
- **[Archive::Zip](https://metacpan.org/pod/Archive::Zip)** - Create, manipulate, read, and write Zip archives.

## Logging

*Libraries for generating and working with log files.*

- **[Log::Log4perl](https://metacpan.org/pod/Log::Log4perl)** - Log4j implementation for Perl.
- **[Log::Dispatch](https://metacpan.org/pod/Log::Dispatch)** - Dispatches messages to multiple outputs.
- **[Log::Any](https://metacpan.org/pod/Log::Any)** - Logging abstraction layer for modules.
- **[Mojo::Log](https://metacpan.org/pod/Mojo::Log)** - Simple logger for Mojolicious projects.

## Web Scraping

*Libraries for extracting data from websites.*

- **[Web::Scraper](https://metacpan.org/pod/Web::Scraper)** - Web scraping toolkit using HTML and CSS selectors.
- **[Mojo::UserAgent](https://metacpan.org/pod/Mojo::UserAgent)** - Non-blocking HTTP and WebSocket user agent.
- **[WWW::Mechanize](https://metacpan.org/pod/WWW::Mechanize)** - Handy web browsing in a Perl object.
- **[LWP::UserAgent](https://metacpan.org/pod/LWP::UserAgent)** - Web user agent class.
- **[HTML::TreeBuilder](https://metacpan.org/pod/HTML::TreeBuilder)** - Parser that builds HTML tree structures.

## Asynchronous

*Libraries for asynchronous programming.*

- **[IO::Async](https://metacpan.org/pod/IO::Async)** - Event-driven programming framework.
- **[AnyEvent](https://metacpan.org/pod/AnyEvent)** - Event loop programming interface.
- **[Future](https://metacpan.org/pod/Future)** - Represent operations awaiting completion.
- **[Promises](https://metacpan.org/pod/Promises)** - Promise/A+ implementation for Perl.

## Text Processing

*Libraries for parsing and manipulating text.*

- **[Regexp::Common](https://metacpan.org/pod/Regexp::Common)** - Collection of common regular expressions.
- **[Text::CSV_XS](https://metacpan.org/pod/Text::CSV_XS)** - High-performance CSV parser.
- **[String::Util](https://metacpan.org/pod/String::Util)** - String processing utilities.
- **[Lingua::EN::Inflect](https://metacpan.org/pod/Lingua::EN::Inflect)** - Convert singular to plural English words.
- **[Text::Diff](https://metacpan.org/pod/Text::Diff)** - Perform diffs on files and strings.

## Security

*Libraries for security and cryptography.*

- **[Digest::SHA](https://metacpan.org/pod/Digest::SHA)** - SHA cryptographic hash functions.
- **[Crypt::Bcrypt](https://metacpan.org/pod/Crypt::Bcrypt)** - Modern password hashing for Perl.
- **[Crypt::Rijndael](https://metacpan.org/pod/Crypt::Rijndael)** - AES encryption implementation.
- **[Net::SSLeay](https://metacpan.org/pod/Net::SSLeay)** - Perl extension for using OpenSSL.
- **[Authen::SASL](https://metacpan.org/pod/Authen::SASL)** - SASL authentication framework.

## Performance

*Libraries for improving performance.*

- **[Devel::NYTProf](https://metacpan.org/pod/Devel::NYTProf)** - Powerful feature-rich Perl profiler.
- **[Sereal](https://metacpan.org/pod/Sereal)** - Fast, compact, powerful binary serialization.
- **[Inline::C](https://metacpan.org/pod/Inline::C)** - Write Perl subroutines in C.
- **[Memoize](https://metacpan.org/pod/Memoize)** - Transparently speed up functions.

## Development Tools

*Tools for Perl development.*

- **[Perl::Critic](https://metacpan.org/pod/Perl::Critic)** - Critique Perl source code for best practices.
- **[Perl::Tidy](https://metacpan.org/pod/Perl::Tidy)** - Perl source code formatter.
- **[Devel::REPL](https://metacpan.org/pod/Devel::REPL)** - Modern Perl interactive shell.
- **[Carton](https://metacpan.org/pod/Carton)** - Perl module dependency manager.
- **[cpanm](https://metacpan.org/pod/App::cpanminus)** - Get, unpack, build and install modules from CPAN.
- **[Perlbrew](https://perlbrew.pl/)** - Manage multiple Perl installations.

## Resources

*Where to discover new Perl libraries and resources.*

### Websites

- [MetaCPAN](https://metacpan.org/) - Search and browse CPAN modules.
- [Perl.org](https://www.perl.org/) - Official Perl website.
- [PerlMonks](https://www.perlmonks.org/) - Community discussion forum.
- [Perl Weekly](https://perlweekly.com/) - Weekly Perl newsletter.
- [blogs.perl.org](https://blogs.perl.org/) - Perl blogging community.

### Books

- [Modern Perl](http://modernperlbooks.com/) - Free book covering modern Perl practices.
- [Learning Perl](https://www.oreilly.com/library/view/learning-perl-7th/9781491954317/) - Classic introduction to Perl.
- [Programming Perl](https://www.oreilly.com/library/view/programming-perl-4th/9781449321451/) - The definitive Perl reference.
- [Higher-Order Perl](https://hop.perl.plover.com/) - Advanced functional programming techniques.

### Tutorials

- [Perl Tutorial](https://perldoc.perl.org/perlintro) - Official Perl introduction.
- [Learn Perl](https://learn.perl.org/) - Comprehensive learning resources.
- [Perl Maven](https://perlmaven.com/) - Tutorials and articles for all levels.

### Community

- [Reddit /r/perl](https://reddit.com/r/perl) - Perl subreddit.
- [Perl Monks](https://perlmonks.org/) - Perl community discussion site.
- [IRC #perl](https://www.perl.org/community.html) - Perl IRC channels.

## Contributing

Your contributions are always welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related rights to this work.
