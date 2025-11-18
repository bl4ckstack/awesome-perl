# Awesome Perl [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome Perl frameworks, libraries, software and resources.

Perl is a highly capable, feature-rich programming language with over 30 years of development. Perl runs on over 100 platforms from portables to mainframes and is suitable for both rapid prototyping and large scale development projects.

[![Perl](https://img.shields.io/badge/Perl-5.38-39457E?style=flat&logo=perl&logoColor=white)](https://www.perl.org/)
[![CPAN](https://img.shields.io/badge/CPAN-200K%2B%20Modules-blue)](https://metacpan.org/)
[![License](https://img.shields.io/badge/License-Artistic%202.0-green.svg)](https://opensource.org/licenses/Artistic-2.0)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/username/awesome-perl/graphs/commit-activity)

## Contents

- [Web Frameworks](#web-frameworks)
- [Web Frameworks-Like](#web-frameworks-like)
- [Object Oriented Programming](#object-oriented-programming)
- [Database](#database)
- [Database Drivers](#database-drivers)
- [Date & Time](#date--time)
- [Data Formats](#data-formats)
- [Development Tools](#development-tools)
- [Email](#email)
- [Exception Handling](#exception-handling)
- [File Manipulation](#file-manipulation)
- [Form Frameworks](#form-frameworks)
- [Image Processing](#image-processing)
- [List Manipulation](#list-manipulation)
- [Logging](#logging)
- [Module Development](#module-development)
- [Network](#network)
- [Package Management](#package-management)
- [Processes & Threads](#processes--threads)
- [Profiling](#profiling)
- [Protocol](#protocol)
- [Queueing](#queueing)
- [REST Frameworks](#rest-frameworks)
- [Science/Numerics](#sciencenumerics)
- [Stream Manipulation](#stream-manipulation)
- [Template Engines](#template-engines)
- [Testing](#testing)
- [Text Processing](#text-processing)
- [Tools](#tools)
- [Type Checking](#type-checking)
- [Video](#video)
- [Web Crawling](#web-crawling)
- [Web Frameworks](#web-frameworks)
- [Web Scraping](#web-scraping)
- [Web Services](#web-services)
- [Caching](#caching)
- [Configuration](#configuration)
- [Cryptography](#cryptography)
- [GUI](#gui)
- [Asynchronous](#asynchronous)
- [Command Line](#command-line)
- [Benchmarking](#benchmarking)
- [Security](#security)
- [Performance](#performance)
- [Message Queue](#message-queue)
- [Authentication](#authentication)
- [Authorization](#authorization)
- [API Clients](#api-clients)
- [Serialization](#serialization)
- [Machine Learning](#machine-learning)
- [DevOps Tools](#devops-tools)
- [Deployment](#deployment)
- [Robotics](#robotics)
- [Metadata](#metadata)
- [Resources](#resources)

## Web Frameworks

*Modern web frameworks for building web applications.*

- **[Mojolicious](https://mojolicious.org/)** - Real-time web framework with elegant and powerful syntax, WebSockets support, and non-blocking I/O.
- **[Dancer2](https://metacpan.org/pod/Dancer2)** - Lightweight yet powerful web application framework inspired by Sinatra.
- **[Catalyst](https://metacpan.org/pod/Catalyst)** - MVC web framework with excellent plugin ecosystem and flexibility.
- **[Web::Simple](https://metacpan.org/pod/Web::Simple)** - Minimalist web framework for building simple web applications.
- **[CGI::Application](https://metacpan.org/pod/CGI::Application)** - Framework for building reusable web applications.
- **[Amon2](https://metacpan.org/pod/Amon2)** - Lightweight web application framework with DBI integration.
- **[Kelp](https://metacpan.org/pod/Kelp)** - Light, modular web framework with Plack integration.

## Web Frameworks-Like

*Lightweight frameworks and micro-frameworks.*

- **[Aplaven](https://metacpan.org/pod/Aplaven)** - Micro web framework with Plack support.
- **[Poet](https://metacpan.org/pod/Poet)** - Modern Perl web framework with Mason templates.
- **[Raisin](https://metacpan.org/pod/Raisin)** - REST API micro-framework for Perl.

## Object Oriented Programming

*Modern OOP systems for Perl.*

- **[Moose](https://metacpan.org/pod/Moose)** - Complete modern object system with meta-object protocol, roles, and type constraints.
- **[Moo](https://metacpan.org/pod/Moo)** - Minimalist object orientation with Moose compatibility and better startup performance.
- **[Mouse](https://metacpan.org/pod/Mouse)** - Lightweight Moose alternative with XS acceleration.
- **[Class::Tiny](https://metacpan.org/pod/Class::Tiny)** - Minimalist class builder with automatic accessor generation.
- **[Object::Pad](https://metacpan.org/pod/Object::Pad)** - Experimental new object system for Perl 5 with native syntax.
- **[Class::Accessor](https://metacpan.org/pod/Class::Accessor)** - Automated accessor generation.
- **[Class::Accessor::Lite](https://metacpan.org/pod/Class::Accessor::Lite)** - Minimalist accessor generator.
- **[Class::InsideOut](https://metacpan.org/pod/Class::InsideOut)** - Inside-out object implementation.
- **[Object::Tiny](https://metacpan.org/pod/Object::Tiny)** - Class builder with no dependencies.
- **[Role::Tiny](https://metacpan.org/pod/Role::Tiny)** - Minimal role composition.

## Database

*Libraries for working with databases and ORMs.*

- **[DBI](https://metacpan.org/pod/DBI)** - Database independent interface for Perl.
- **[DBIx::Class](https://metacpan.org/pod/DBIx::Class)** - Extensible and flexible ORM with advanced features.
- **[DBIx::Connector](https://metacpan.org/pod/DBIx::Connector)** - Fast, safe DBI connection and transaction management.
- **[DBIx::Handler](https://metacpan.org/pod/DBIx::Handler)** - Fork-safe and easy database handler.
- **[DBIx::Inspector](https://metacpan.org/pod/DBIx::Inspector)** - Get schema information from database.
- **[DBIx::QueryLog](https://metacpan.org/pod/DBIx::QueryLog)** - Log queries for DBI.
- **[DBIx::Sunny](https://metacpan.org/pod/DBIx::Sunny)** - Useful DBI wrapper.
- **[DBIx::TransactionManager](https://metacpan.org/pod/DBIx::TransactionManager)** - Simple transaction manager.
- **[Teng](https://metacpan.org/pod/Teng)** - Lightweight and simple O/R Mapper.
- **[SQL::Maker](https://metacpan.org/pod/SQL::Maker)** - SQL builder with named placeholders.
- **[SQL::Abstract](https://metacpan.org/pod/SQL::Abstract)** - Generate SQL from Perl data structures.
- **[SQL::Interp](https://metacpan.org/pod/SQL::Interp)** - Interpolate Perl variables into SQL statements.

## Database Drivers

*Database-specific drivers and integrations.*

- **[DBD::mysql](https://metacpan.org/pod/DBD::mysql)** - MySQL driver for DBI.
- **[DBD::Pg](https://metacpan.org/pod/DBD::Pg)** - PostgreSQL driver for DBI.
- **[DBD::SQLite](https://metacpan.org/pod/DBD::SQLite)** - Self-contained SQLite database engine.
- **[DBD::Oracle](https://metacpan.org/pod/DBD::Oracle)** - Oracle database driver.
- **[Mojo::Pg](https://metacpan.org/pod/Mojo::Pg)** - PostgreSQL integration with non-blocking queries.
- **[Mojo::mysql](https://metacpan.org/pod/Mojo::mysql)** - MySQL integration for Mojolicious.
- **[Redis](https://metacpan.org/pod/Redis)** - Perl binding for Redis database.
- **[Redis::Fast](https://metacpan.org/pod/Redis::Fast)** - Fast Redis client.
- **[MongoDB](https://metacpan.org/pod/MongoDB)** - Official MongoDB driver for Perl.
- **[UnQLite](https://metacpan.org/pod/UnQLite)** - Embedded NoSQL database.
- **[Mango](https://metacpan.org/pod/Mango)** - Non-blocking MongoDB driver.
- **[Cache::Memcached::Fast](https://metacpan.org/pod/Cache::Memcached::Fast)** - Fast Memcached client.

## Date & Time

*Libraries for working with dates and times.*

- **[DateTime](https://metacpan.org/pod/DateTime)** - Comprehensive date and time object with timezone support.
- **[Time::Piece](https://metacpan.org/pod/Time::Piece)** - Object-oriented time objects included with Perl.
- **[Time::Moment](https://metacpan.org/pod/Time::Moment)** - High-performance immutable datetime objects.
- **[DateTime::Format::Strptime](https://metacpan.org/pod/DateTime::Format::Strptime)** - Parse and format datetime strings.
- **[DateTime::Format::ISO8601](https://metacpan.org/pod/DateTime::Format::ISO8601)** - Parse ISO8601 formatted dates.
- **[DateTime::Format::Natural](https://metacpan.org/pod/DateTime::Format::Natural)** - Parse natural language date/time strings.
- **[DateTime::TimeZone](https://metacpan.org/pod/DateTime::TimeZone)** - Timezone support for DateTime.
- **[Time::Local](https://metacpan.org/pod/Time::Local)** - Efficiently compute time from local and GMT time.
- **[Date::Calc](https://metacpan.org/pod/Date::Calc)** - Gregorian calendar date calculations.
- **[Date::Simple](https://metacpan.org/pod/Date::Simple)** - Simple date objects.

## Data Formats

*Libraries for parsing and manipulating data formats.*

- **[JSON::MaybeXS](https://metacpan.org/pod/JSON::MaybeXS)** - Use the fastest available JSON implementation.
- **[JSON::XS](https://metacpan.org/pod/JSON::XS)** - Fast JSON encoder/decoder.
- **[Cpanel::JSON::XS](https://metacpan.org/pod/Cpanel::JSON::XS)** - JSON encoder/decoder with cPanel modifications.
- **[JSON::PP](https://metacpan.org/pod/JSON::PP)** - Pure Perl JSON encoder/decoder.
- **[YAML::XS](https://metacpan.org/pod/YAML::XS)** - Fast YAML parser and dumper.
- **[YAML::Tiny](https://metacpan.org/pod/YAML::Tiny)** - Minimal YAML implementation.
- **[YAML](https://metacpan.org/pod/YAML)** - Pure Perl YAML implementation.
- **[XML::LibXML](https://metacpan.org/pod/XML::LibXML)** - Interface to libxml2 library for XML processing.
- **[XML::Simple](https://metacpan.org/pod/XML::Simple)** - Simple API for reading and writing XML.
- **[XML::Twig](https://metacpan.org/pod/XML::Twig)** - Process XML documents in tree mode.
- **[XML::Parser](https://metacpan.org/pod/XML::Parser)** - Perl extension interface to James Clark's XML parser.
- **[Data::MessagePack](https://metacpan.org/pod/Data::MessagePack)** - MessagePack serialization format.
- **[Text::CSV_XS](https://metacpan.org/pod/Text::CSV_XS)** - High-performance CSV parser.
- **[Text::CSV](https://metacpan.org/pod/Text::CSV)** - Comma-separated values manipulator.
- **[TOML](https://metacpan.org/pod/TOML)** - Parser for Tom's Obvious Minimal Language.
- **[Config::Tiny](https://metacpan.org/pod/Config::Tiny)** - Read/write .ini style files.
- **[Data::Printer](https://metacpan.org/pod/Data::Printer)** - Beautiful data structure dumper.
- **[Data::Dumper](https://metacpan.org/pod/Data::Dumper)** - Stringify Perl data structures.

## Development Tools

*Tools for Perl development.*

- **[Perl::Critic](https://metacpan.org/pod/Perl::Critic)** - Critique Perl source code for best practices.
- **[Perl::Tidy](https://metacpan.org/pod/Perl::Tidy)** - Perl source code formatter.
- **[Devel::REPL](https://metacpan.org/pod/Devel::REPL)** - Modern Perl interactive shell.
- **[Reply](https://metacpan.org/pod/Reply)** - Read-eval-print-loop with plugin support.
- **[Carton](https://metacpan.org/pod/Carton)** - Perl module dependency manager.
- **[cpanm](https://metacpan.org/pod/App::cpanminus)** - Get, unpack, build and install modules from CPAN.
- **[Perlbrew](https://perlbrew.pl/)** - Manage multiple Perl installations.
- **[plenv](https://github.com/tokuhirom/plenv)** - Perl version manager.
- **[Smart::Comments](https://metacpan.org/pod/Smart::Comments)** - Comments that do more than just document.
- **[Data::Dump](https://metacpan.org/pod/Data::Dump)** - Pretty printing of data structures.

## Email

*Libraries for sending and parsing email.*

- **[Email::Sender](https://metacpan.org/pod/Email::Sender)** - Library for sending email via multiple transports.
- **[Email::MIME](https://metacpan.org/pod/Email::MIME)** - Easy MIME message handling.
- **[Email::Valid](https://metacpan.org/pod/Email::Valid)** - Check validity of email addresses.
- **[Email::Simple](https://metacpan.org/pod/Email::Simple)** - Simple parsing of RFC2822 message format and headers.
- **[Email::Stuffer](https://metacpan.org/pod/Email::Stuffer)** - Easy email creation and sending.
- **[Email::Address](https://metacpan.org/pod/Email::Address)** - Parse RFC 2822 email addresses.
- **[Mail::IMAPClient](https://metacpan.org/pod/Mail::IMAPClient)** - IMAP client interface.
- **[MIME::Lite](https://metacpan.org/pod/MIME::Lite)** - Simple MIME email creation.
- **[Mail::Sendmail](https://metacpan.org/pod/Mail::Sendmail)** - Simple platform independent mailer.

## Exception Handling

*Libraries for exception and error handling.*

- **[Try::Tiny](https://metacpan.org/pod/Try::Tiny)** - Minimal try/catch with proper preservation of $@.
- **[TryCatch](https://metacpan.org/pod/TryCatch)** - First-class try/catch semantics.
- **[Exception::Class](https://metacpan.org/pod/Exception::Class)** - Module for declaring exception hierarchies.
- **[Throwable](https://metacpan.org/pod/Throwable)** - Role for classes that can be thrown.
- **[autodie](https://metacpan.org/pod/autodie)** - Replace functions with ones that succeed or die.

## File Manipulation

*Libraries for file manipulation and MIME type detection.*

- **[Path::Tiny](https://metacpan.org/pod/Path::Tiny)** - Simple object-oriented file path manipulation.
- **[Path::Class](https://metacpan.org/pod/Path::Class)** - Cross-platform path specification.
- **[File::Slurp](https://metacpan.org/pod/File::Slurp)** - Simple and efficient file reading and writing.
- **[File::Slurper](https://metacpan.org/pod/File::Slurper)** - Simple, sane and efficient module for file slurping and spurting.
- **[File::Find::Rule](https://metacpan.org/pod/File::Find::Rule)** - Alternative interface to File::Find.
- **[File::HomeDir](https://metacpan.org/pod/File::HomeDir)** - Get home directory for any user.
- **[File::Temp](https://metacpan.org/pod/File::Temp)** - Create temporary files and directories.
- **[File::Which](https://metacpan.org/pod/File::Which)** - Portable implementation of 'which'.
- **[File::Copy::Recursive](https://metacpan.org/pod/File::Copy::Recursive)** - Recursive copy of files and directories.
- **[Archive::Extract](https://metacpan.org/pod/Archive::Extract)** - Generic archive extracting mechanism.
- **[Archive::Zip](https://metacpan.org/pod/Archive::Zip)** - Create, manipulate, read, and write Zip archives.
- **[Archive::Tar](https://metacpan.org/pod/Archive::Tar)** - Create and manipulate tar files.
- **[IO::All](https://metacpan.org/pod/IO::All)** - Unified IO operations.

## Form Frameworks

*Libraries for form rendering and validation.*

- **[HTML::FormHandler](https://metacpan.org/pod/HTML::FormHandler)** - Moose-based form handling with validation.
- **[Form::Tiny](https://metacpan.org/pod/Form::Tiny)** - Form validation framework with Moo.
- **[FormValidator::Simple](https://metacpan.org/pod/FormValidator::Simple)** - Simple validation library.
- **[Data::FormValidator](https://metacpan.org/pod/Data::FormValidator)** - Profile-based validation.

## Image Processing

*Libraries for manipulating images.*

- **[Image::Magick](https://metacpan.org/pod/Image::Magick)** - ImageMagick bindings for Perl.
- **[GD](https://metacpan.org/pod/GD)** - Interface to GD graphics library.
- **[Imager](https://metacpan.org/pod/Imager)** - Perl extension for image manipulation.
- **[Image::Info](https://metacpan.org/pod/Image::Info)** - Extract meta information from images.
- **[Image::ExifTool](https://metacpan.org/pod/Image::ExifTool)** - Read and write meta information in image files.

## List Manipulation

*Libraries for manipulating lists and arrays.*

- **[List::Util](https://metacpan.org/pod/List::Util)** - Selection of general utility list subroutines.
- **[List::MoreUtils](https://metacpan.org/pod/List::MoreUtils)** - Provide the stuff missing in List::Util.
- **[List::AllUtils](https://metacpan.org/pod/List::AllUtils)** - Combination of List::Util and List::MoreUtils.
- **[List::UtilsBy](https://metacpan.org/pod/List::UtilsBy)** - Higher-order list utility functions.
- **[Array::Utils](https://metacpan.org/pod/Array::Utils)** - Small utils for array manipulation.

## Logging

*Libraries for generating and working with log files.*

- **[Log::Log4perl](https://metacpan.org/pod/Log::Log4perl)** - Log4j implementation for Perl.
- **[Log::Dispatch](https://metacpan.org/pod/Log::Dispatch)** - Dispatches messages to multiple outputs.
- **[Log::Any](https://metacpan.org/pod/Log::Any)** - Logging abstraction layer for modules.
- **[Log::Minimal](https://metacpan.org/pod/Log::Minimal)** - Minimal and customizable logger.
- **[Mojo::Log](https://metacpan.org/pod/Mojo::Log)** - Simple logger for Mojolicious projects.
- **[Log::Contextual](https://metacpan.org/pod/Log::Contextual)** - Simple logging interface with context.

## Module Development

*Libraries for module development and distribution.*

- **[Dist::Zilla](https://metacpan.org/pod/Dist::Zilla)** - Distribution builder with plugins.
- **[Minilla](https://metacpan.org/pod/Minilla)** - CPAN module authoring tool.
- **[Module::Build](https://metacpan.org/pod/Module::Build)** - Build and install Perl modules.
- **[ExtUtils::MakeMaker](https://metacpan.org/pod/ExtUtils::MakeMaker)** - Create a Makefile for a Perl module.
- **[Module::Install](https://metacpan.org/pod/Module::Install)** - Standalone module installer.
- **[Module::Starter](https://metacpan.org/pod/Module::Starter)** - Bootstrap a new module.

## Network

*Libraries for network programming.*

- **[IO::Socket::IP](https://metacpan.org/pod/IO::Socket::IP)** - IPv4/IPv6 socket interface.
- **[IO::Socket::SSL](https://metacpan.org/pod/IO::Socket::SSL)** - SSL sockets with IO::Socket interface.
- **[Net::SSH::Perl](https://metacpan.org/pod/Net::SSH::Perl)** - Pure Perl SSH client.
- **[Net::SSH2](https://metacpan.org/pod/Net::SSH2)** - SSH2 protocol support via libssh2.
- **[Net::SFTP::Foreign](https://metacpan.org/pod/Net::SFTP::Foreign)** - SFTP client for SSH2.
- **[Net::DNS](https://metacpan.org/pod/Net::DNS)** - Perl interface to the DNS resolver.
- **[Net::Ping](https://metacpan.org/pod/Net::Ping)** - Check remote host availability.
- **[NetAddr::IP](https://metacpan.org/pod/NetAddr::IP)** - Manage IPv4 and IPv6 addresses.

## Package Management

*Libraries for package management.*

- **[cpanm](https://metacpan.org/pod/App::cpanminus)** - Get, unpack, build and install CPAN modules.
- **[CPAN](https://metacpan.org/pod/CPAN)** - Query, download and build perl modules from CPAN.
- **[Carton](https://metacpan.org/pod/Carton)** - Perl module dependency manager using cpanfile.
- **[Pinto](https://metacpan.org/pod/Pinto)** - Curate your own CPAN repository.

## Processes & Threads

*Libraries for managing processes and threads.*

- **[Parallel::ForkManager](https://metacpan.org/pod/Parallel::ForkManager)** - Simple parallel processing fork manager.
- **[Parallel::Prefork](https://metacpan.org/pod/Parallel::Prefork)** - Simple prefork server framework.
- **[Proclet](https://metacpan.org/pod/Proclet)** - Minimalistic process manager.
- **[Proc::ProcessTable](https://metacpan.org/pod/Proc::ProcessTable)** - Access process table information.
- **[threads](https://metacpan.org/pod/threads)** - Perl interpreter-based threads.

## Profiling

*Libraries for code profiling and performance analysis.*

- **[Devel::NYTProf](https://metacpan.org/pod/Devel::NYTProf)** - Powerful feature-rich Perl profiler.
- **[Devel::Cover](https://metacpan.org/pod/Devel::Cover)** - Code coverage metrics for Perl.
- **[Benchmark](https://metacpan.org/pod/Benchmark)** - Benchmark running times of Perl code.
- **[Dumbbench](https://metacpan.org/pod/Dumbbench)** - More reliable benchmarking with statistics.

## Protocol

*Protocol clients and libraries.*

- **[HTTP::Tiny](https://metacpan.org/pod/HTTP::Tiny)** - Minimal HTTP client.
- **[LWP::UserAgent](https://metacpan.org/pod/LWP::UserAgent)** - Full-featured HTTP client.
- **[LWP::Protocol::https](https://metacpan.org/pod/LWP::Protocol::https)** - HTTPS support for LWP.
- **[Furl](https://metacpan.org/pod/Furl)** - Fast HTTP client.
- **[HTTP::Cookies](https://metacpan.org/pod/HTTP::Cookies)** - HTTP cookie jars.
- **[Net::HTTP](https://metacpan.org/pod/Net::HTTP)** - Low-level HTTP connection.
- **[Protocol::WebSocket](https://metacpan.org/pod/Protocol::WebSocket)** - WebSocket protocol implementation.

## Queueing

*Message queue and job queue systems.*

- **[TheSchwartz](https://metacpan.org/pod/TheSchwartz)** - Reliable job queue.
- **[Qudo](https://metacpan.org/pod/Qudo)** - Simple job queue manager.
- **[Minion](https://metacpan.org/pod/Minion)** - Job queue for Mojolicious.
- **[Gearman](https://metacpan.org/pod/Gearman::Worker)** - Distributed job system.

## REST Frameworks

*Libraries for developing REST APIs.*

- **[Dancer2::Plugin::REST](https://metacpan.org/pod/Dancer2::Plugin::REST)** - REST plugin for Dancer2.
- **[Catalyst::Action::REST](https://metacpan.org/pod/Catalyst::Action::REST)** - REST support for Catalyst.
- **[Raisin](https://metacpan.org/pod/Raisin)** - REST API micro-framework.
- **[WebService::Async](https://metacpan.org/pod/WebService::Async)** - Async REST client framework.

## Science/Numerics

*Libraries for scientific computing and numerical analysis.*

- **[PDL](https://metacpan.org/pod/PDL)** - Perl Data Language for scientific computing.
- **[Math::BigInt](https://metacpan.org/pod/Math::BigInt)** - Arbitrary size integer math.
- **[Math::BigFloat](https://metacpan.org/pod/Math::BigFloat)** - Arbitrary size floating point math.
- **[Math::Prime::Util](https://metacpan.org/pod/Math::Prime::Util)** - Prime number utilities.
- **[Statistics::Descriptive](https://metacpan.org/pod/Statistics::Descriptive)** - Basic statistical functions.
- **[Math::Random](https://metacpan.org/pod/Math::Random)** - Random number generators.
- **[Chart::Clicker](https://metacpan.org/pod/Chart::Clicker)** - Chart creation library.

## Stream Manipulation

*Libraries for working with event streams.*

- **[Stream::Buffered](https://metacpan.org/pod/Stream::Buffered)** - Temporary buffer for reading stream.
- **[Data::Stream::Bulk](https://metacpan.org/pod/Data::Stream::Bulk)** - N-at-a-time iteration API.

## Template Engines

*Libraries for templating and lexing.*

- **[Template Toolkit](https://metacpan.org/pod/Template)** - Powerful and extensible template processing system.
- **[Text::Xslate](https://metacpan.org/pod/Text::Xslate)** - Fast template engine with multiple syntaxes.
- **[HTML::Template](https://metacpan.org/pod/HTML::Template)** - Simple HTML templating system.
- **[Mason](https://metacpan.org/pod/Mason)** - Powerful template system with component-based architecture.
- **[Mojo::Template](https://metacpan.org/pod/Mojo::Template)** - Lightweight embedded Perl templates.
- **[Text::Template](https://metacpan.org/pod/Text::Template)** - Expand template text with embedded Perl.
- **[Template::Tiny](https://metacpan.org/pod/Template::Tiny)** - Template Toolkit reimplemented in minimal code.

## Testing

*Libraries for testing codebases and generating test data.*

- **[Test::More](https://metacpan.org/pod/Test::More)** - Basic testing framework included with Perl.
- **[Test2::Suite](https://metacpan.org/pod/Test2::Suite)** - Modern testing framework with rich feature set.
- **[Test::Simple](https://metacpan.org/pod/Test::Simple)** - Basic utilities for writing tests.
- **[Test::Exception](https://metacpan.org/pod/Test::Exception)** - Test exception-based code.
- **[Test::Fatal](https://metacpan.org/pod/Test::Fatal)** - Test for exceptions with better diagnostics.
- **[Test::Differences](https://metacpan.org/pod/Test::Differences)** - Test strings and data structures for equality.
- **[Test::Deep](https://metacpan.org/pod/Test::Deep)** - Extremely flexible deep comparison.
- **[Test::MockModule](https://metacpan.org/pod/Test::MockModule)** - Override subroutines in modules for testing.
- **[Test::MockObject](https://metacpan.org/pod/Test::MockObject)** - Emulate troublesome interfaces.
- **[Test::Mock::Guard](https://metacpan.org/pod/Test::Mock::Guard)** - Simple mock test library.
- **[Test::Time](https://metacpan.org/pod/Test::Time)** - Override time for testing.
- **[Test::TCP](https://metacpan.org/pod/Test::TCP)** - Testing TCP programs.
- **[Test::WWW::Mechanize](https://metacpan.org/pod/Test::WWW::Mechanize)** - Test web applications.
- **[Test::Mojo](https://metacpan.org/pod/Test::Mojo)** - Testing toolkit for Mojolicious applications.
- **[Test::File](https://metacpan.org/pod/Test::File)** - Test file attributes.
- **[Test::Class](https://metacpan.org/pod/Test::Class)** - Class-based testing.
- **[Test::Harness](https://metacpan.org/pod/Test::Harness)** - Run Perl test scripts.
- **[Devel::Cover](https://metacpan.org/pod/Devel::Cover)** - Code coverage metrics for Perl.

## Text Processing

*Libraries for parsing and manipulating text.*

- **[Regexp::Common](https://metacpan.org/pod/Regexp::Common)** - Collection of common regular expressions.
- **[Regexp::Assemble](https://metacpan.org/pod/Regexp::Assemble)** - Assemble multiple regexps into a single one.
- **[String::Util](https://metacpan.org/pod/String::Util)** - String processing utilities.
- **[Text::Trim](https://metacpan.org/pod/Text::Trim)** - Remove leading/trailing whitespace.
- **[Lingua::EN::Inflect](https://metacpan.org/pod/Lingua::EN::Inflect)** - Convert singular to plural English words.
- **[Text::Diff](https://metacpan.org/pod/Text::Diff)** - Perform diffs on files and strings.
- **[String::CamelCase](https://metacpan.org/pod/String::CamelCase)** - Convert to/from camel case.
- **[Text::Table](https://metacpan.org/pod/Text::Table)** - Organize data in tables.
- **[Text::Markdown](https://metacpan.org/pod/Text::Markdown)** - Convert Markdown to HTML.
- **[Text::Unidecode](https://metacpan.org/pod/Text::Unidecode)** - Transliterate Unicode to ASCII.
- **[Unicode::UTF8](https://metacpan.org/pod/Unicode::UTF8)** - Fast UTF-8 encoding/decoding.

## Tools

*Useful command-line tools.*

- **[App::Ack](https://metacpan.org/pod/App::Ack)** - grep-like text finder optimized for programmers.
- **[App::perlbrew](https://metacpan.org/pod/App::perlbrew)** - Manage perl installations.
- **[App::cpanminus](https://metacpan.org/pod/App::cpanminus)** - Get, unpack, build and install modules.
- **[Perl::Tidy](https://metacpan.org/pod/Perl::Tidy)** - Indent and reformat Perl scripts.
- **[Reply](https://metacpan.org/pod/Reply)** - Read-eval-print-loop shell.

## Type Checking

*Libraries for type checking and validation.*

- **[Type::Tiny](https://metacpan.org/pod/Type::Tiny)** - Tiny yet comprehensive type library.
- **[Types::Standard](https://metacpan.org/pod/Types::Standard)** - Type constraints based on Moose type system.
- **[MooseX::Types](https://metacpan.org/pod/MooseX::Types)** - Type library for Moose.
- **[Params::Validate](https://metacpan.org/pod/Params::Validate)** - Validate method/function parameters.
- **[Params::ValidationCompiler](https://metacpan.org/pod/Params::ValidationCompiler)** - Build fast validators for parameters.
- **[Smart::Args](https://metacpan.org/pod/Smart::Args)** - Smart argument validation.

## Video

*Libraries for manipulating video.*

- **[FFmpeg](https://metacpan.org/pod/FFmpeg)** - Interface to FFmpeg video converter.
- **[Video::Info](https://metacpan.org/pod/Video::Info)** - Extract metadata from video files.

## Web Crawling

*Libraries for crawling and spidering websites.*

- **[WWW::Mechanize](https://metacpan.org/pod/WWW::Mechanize)** - Handy web browsing in a Perl object.
- **[WWW::Mechanize::Cached](https://metacpan.org/pod/WWW::Mechanize::Cached)** - Cache response of WWW::Mechanize.
- **[WWW::Selenium](https://metacpan.org/pod/WWW::Selenium)** - Perl client for Selenium Remote Control.

## Web Scraping

*Libraries for extracting data from websites.*

- **[Web::Scraper](https://metacpan.org/pod/Web::Scraper)** - Web scraping toolkit using HTML and CSS selectors.
- **[Mojo::UserAgent](https://metacpan.org/pod/Mojo::UserAgent)** - Non-blocking HTTP and WebSocket user agent.
- **[LWP::UserAgent](https://metacpan.org/pod/LWP::UserAgent)** - Web user agent class.
- **[HTML::TreeBuilder](https://metacpan.org/pod/HTML::TreeBuilder)** - Parser that builds HTML tree structures.
- **[HTML::TreeBuilder::XPath](https://metacpan.org/pod/HTML::TreeBuilder::XPath)** - Add XPath support to HTML::TreeBuilder.
- **[HTML::Query](https://metacpan.org/pod/HTML::Query)** - jQuery-like DOM manipulation.

## Web Services

*Libraries for working with web services.*

- **[SOAP::Lite](https://metacpan.org/pod/SOAP::Lite)** - SOAP client and server.
- **[XML::Compile::SOAP](https://metacpan.org/pod/XML::Compile::SOAP)** - SOAP 1.1 client and server.
- **[XML::RPC](https://metacpan.org/pod/XML::RPC)** - Pure Perl XML-RPC implementation.
- **[Net::Amazon::S3](https://metacpan.org/pod/Net::Amazon::S3)** - Framework for accessing Amazon S3.
- **[WebService::Slack::WebApi](https://metacpan.org/pod/WebService::Slack::WebApi)** - Slack Web API client.

## Caching

*Libraries for caching data.*

- **[CHI](https://metacpan.org/pod/CHI)** - Unified cache interface.
- **[Cache::Cache](https://metacpan.org/pod/Cache::Cache)** - Cache interface.
- **[Cache::FastMmap](https://metacpan.org/pod/Cache::FastMmap)** - Shared memory cache.
- **[Cache::Memcached](https://metacpan.org/pod/Cache::Memcached)** - Memcached client.
- **[Cache::Memcached::Fast](https://metacpan.org/pod/Cache::Memcached::Fast)** - Fast Perl client for memcached.

## Configuration

*Libraries for configuration files.*

- **[Config::Tiny](https://metacpan.org/pod/Config::Tiny)** - Read/write .ini style files.
- **[Config::Any](https://metacpan.org/pod/Config::Any)** - Load configuration from many formats.
- **[Config::General](https://metacpan.org/pod/Config::General)** - Apache-style config files.
- **[Config::GitLike](https://metacpan.org/pod/Config::GitLike)** - Git-style config files.
- **[Config::YAML](https://metacpan.org/pod/Config::YAML)** - YAML-based configuration loader.

## Cryptography

*Libraries for encryption and cryptographic functions.*

- **[Crypt::OpenSSL::RSA](https://metacpan.org/pod/Crypt::OpenSSL::RSA)** - RSA encoding and decoding.
- **[Crypt::OpenSSL::X509](https://metacpan.org/pod/Crypt::OpenSSL::X509)** - Parse X509 certificates.
- **[Crypt::JWT](https://metacpan.org/pod/Crypt::JWT)** - JSON Web Token implementation.
- **[Digest::SHA](https://metacpan.org/pod/Digest::SHA)** - SHA cryptographic hash functions.
- **[Digest::MD5](https://metacpan.org/pod/Digest::MD5)** - MD5 message digest algorithm.
- **[Crypt::Bcrypt](https://metacpan.org/pod/Crypt::Bcrypt)** - Modern password hashing for Perl.
- **[Crypt::Rijndael](https://metacpan.org/pod/Crypt::Rijndael)** - AES encryption implementation.
- **[Crypt::CBC](https://metacpan.org/pod/Crypt::CBC)** - Encrypt with cipher block chaining.
- **[Crypt::Random](https://metacpan.org/pod/Crypt::Random)** - Cryptographically strong random numbers.

## GUI

*Libraries for creating graphical user interfaces.*

- **[Tk](https://metacpan.org/pod/Tk)** - Perl/Tk interface to Tk GUI toolkit.
- **[Wx](https://metacpan.org/pod/Wx)** - Perl interface to wxWidgets.
- **[Prima](https://metacpan.org/pod/Prima)** - Perl graphic toolkit.
- **[GTK2](https://metacpan.org/pod/Gtk2)** - Perl bindings for GTK+ 2.x.

## Asynchronous

*Libraries for asynchronous programming.*

- **[IO::Async](https://metacpan.org/pod/IO::Async)** - Event-driven programming framework.
- **[AnyEvent](https://metacpan.org/pod/AnyEvent)** - Event loop programming interface.
- **[POE](https://metacpan.org/pod/POE)** - Portable multitasking and networking framework.
- **[Coro](https://metacpan.org/pod/Coro)** - Cooperative threads in Perl.
- **[Future](https://metacpan.org/pod/Future)** - Represent operations awaiting completion.
- **[Promises](https://metacpan.org/pod/Promises)** - Promise/A+ implementation for Perl.
- **[Reflex](https://metacpan.org/pod/Reflex)** - Reactive programming framework.

## Command Line

*Libraries for building CLI applications.*

- **[Getopt::Long](https://metacpan.org/pod/Getopt::Long)** - Extended processing of command line options.
- **[Getopt::Long::Descriptive](https://metacpan.org/pod/Getopt::Long::Descriptive)** - Getopt::Long with usage text.
- **[App::Cmd](https://metacpan.org/pod/App::Cmd)** - Framework for building command-line applications.
- **[Term::ANSIColor](https://metacpan.org/pod/Term::ANSIColor)** - Color screen output using ANSI escape sequences.
- **[Term::UI](https://metacpan.org/pod/Term::UI)** - Term::ReadLine user interface.
- **[IO::Prompter](https://metacpan.org/pod/IO::Prompter)** - Prompt users for input with validation.
- **[Term::ProgressBar](https://metacpan.org/pod/Term::ProgressBar)** - Provide progress bars for long-running operations.
- **[Term::ReadKey](https://metacpan.org/pod/Term::ReadKey)** - Simple terminal control.
- **[Term::ReadLine](https://metacpan.org/pod/Term::ReadLine)** - Interface to readline libraries.

## Benchmarking

*Libraries for benchmarking code.*

- **[Benchmark](https://metacpan.org/pod/Benchmark)** - Benchmark running times of Perl code.
- **[Dumbbench](https://metacpan.org/pod/Dumbbench)** - More reliable benchmarking with statistics.
- **[Benchmark::Dumb](https://metacpan.org/pod/Benchmark::Dumb)** - Benchmark without the magic.

## Security

*Libraries for security and cryptography.*

- **[Net::SSLeay](https://metacpan.org/pod/Net::SSLeay)** - Perl extension for using OpenSSL.
- **[Authen::SASL](https://metacpan.org/pod/Authen::SASL)** - SASL authentication framework.
- **[Authen::Passphrase](https://metacpan.org/pod/Authen::Passphrase)** - Hashed passwords/passphrases.
- **[Crypt::SaltedHash](https://metacpan.org/pod/Crypt::SaltedHash)** - Salted hash generation.
- **[Crypt::PBKDF2](https://metacpan.org/pod/Crypt::PBKDF2)** - Password-based key derivation.

## Performance

*Libraries for improving performance.*

- **[Devel::NYTProf](https://metacpan.org/pod/Devel::NYTProf)** - Powerful feature-rich Perl profiler.
- **[Sereal](https://metacpan.org/pod/Sereal)** - Fast, compact, powerful binary serialization.
- **[Inline::C](https://metacpan.org/pod/Inline::C)** - Write Perl subroutines in C.
- **[Memoize](https://metacpan.org/pod/Memoize)** - Transparently speed up functions.
- **[Class::XSAccessor](https://metacpan.org/pod/Class::XSAccessor)** - Generate fast XS accessors.

## Message Queue

*Message queue and broker systems.*

- **[Net::RabbitMQ](https://metacpan.org/pod/Net::RabbitMQ)** - RabbitMQ client library.
- **[Net::AMQP::RabbitMQ](https://metacpan.org/pod/Net::AMQP::RabbitMQ)** - RabbitMQ AMQP client.
- **[Net::Stomp](https://metacpan.org/pod/Net::Stomp)** - Streaming Text Orientated Messaging Protocol client.
- **[Net::Kafka](https://metacpan.org/pod/Kafka)** - Apache Kafka client.

## Authentication

*Libraries for implementing authentication.*

- **[Authen::Simple](https://metacpan.org/pod/Authen::Simple)** - Simple authentication framework.
- **[Net::LDAP](https://metacpan.org/pod/Net::LDAP)** - LDAP client library.
- **[Authen::PAM](https://metacpan.org/pod/Authen::PAM)** - PAM authentication.
- **[Net::OAuth](https://metacpan.org/pod/Net::OAuth)** - OAuth protocol support.
- **[LWP::Authen::OAuth](https://metacpan.org/pod/LWP::Authen::OAuth)** - OAuth support for LWP.

## Authorization

*Libraries for implementing authorization.*

- **[DBIx::Class::EncodedColumn](https://metacpan.org/pod/DBIx::Class::EncodedColumn)** - Automatically encode column values.
- **[Authorization::AccessControl](https://metacpan.org/pod/Authorization::AccessControl)** - Access control lists.

## API Clients

*Libraries for accessing third-party APIs.*

- **[Net::Twitter](https://metacpan.org/pod/Net::Twitter)** - Twitter API client.
- **[Net::GitHub](https://metacpan.org/pod/Net::GitHub)** - GitHub API client.
- **[WebService::DigitalOcean](https://metacpan.org/pod/WebService::DigitalOcean)** - DigitalOcean API.
- **[Paws](https://metacpan.org/pod/Paws)** - Perl AWS SDK.
- **[Net::Google::Drive::Simple](https://metacpan.org/pod/Net::Google::Drive::Simple)** - Google Drive API client.
- **[WWW::Twilio::API](https://metacpan.org/pod/WWW::Twilio::API)** - Twilio API client.

## Serialization

*Libraries for serializing data.*

- **[Storable](https://metacpan.org/pod/Storable)** - Persistence for Perl data structures.
- **[Sereal](https://metacpan.org/pod/Sereal)** - Fast binary serialization.
- **[Data::MessagePack](https://metacpan.org/pod/Data::MessagePack)** - MessagePack implementation.
- **[FreezeThaw](https://metacpan.org/pod/FreezeThaw)** - Convert Perl structures to strings.
- **[CBOR::XS](https://metacpan.org/pod/CBOR::XS)** - Concise Binary Object Representation.

## Machine Learning

*Libraries for machine learning and AI.*

- **[AI::MXNet](https://metacpan.org/pod/AI::MXNet)** - Perl interface to Apache MXNet.
- **[Algorithm::NaiveBayes](https://metacpan.org/pod/Algorithm::NaiveBayes)** - Naive Bayes classifier.
- **[AI::DecisionTree](https://metacpan.org/pod/AI::DecisionTree)** - Decision tree learning.
- **[AI::NeuralNet::BackProp](https://metacpan.org/pod/AI::NeuralNet::BackProp)** - Backpropagation neural network.
- **[Algorithm::SVM](https://metacpan.org/pod/Algorithm::SVM)** - Support Vector Machines.

## DevOps Tools

*Tools for deployment and system administration.*

- **[Rex](https://metacpan.org/pod/Rex)** - Remote execution framework.
- **[App::Sqitch](https://metacpan.org/pod/App::Sqitch)** - Database change management.
- **[IPC::Run](https://metacpan.org/pod/IPC::Run)** - Run commands with piping and redirection.
- **[Sys::Info](https://metacpan.org/pod/Sys::Info)** - Get system information.
- **[Sys::Hostname](https://metacpan.org/pod/Sys::Hostname)** - Get hostname.

## Deployment

*Tools for deploying applications.*

- **[Plack](https://metacpan.org/pod/Plack)** - PSGI toolkit and server adapters.
- **[Starman](https://metacpan.org/pod/Starman)** - High-performance preforking PSGI server.
- **[Starlet](https://metacpan.org/pod/Starlet)** - Simple, high-performance PSGI server.
- **[Gazelle](https://metacpan.org/pod/Gazelle)** - Preforked Plack handler for performance.
- **[Server::Starter](https://metacpan.org/pod/Server::Starter)** - Superdaemon for hot-deploying servers.

## Robotics

*Libraries for robotics.*

- **[Device::SerialPort](https://metacpan.org/pod/Device::SerialPort)** - Serial port communication.
- **[UAV::Pilot](https://metacpan.org/pod/UAV::Pilot)** - Control drones and UAVs.

## Metadata

*Libraries for handling metadata.*

- **[Software::License](https://metacpan.org/pod/Software::License)** - Software license objects.
- **[CPAN::Meta](https://metacpan.org/pod/CPAN::Meta)** - Distribution metadata.
- **[Module::Metadata](https://metacpan.org/pod/Module::Metadata)** - Gather package and POD information from modules.

## Resources

*Where to discover new Perl libraries and resources.*

### Websites

- **[MetaCPAN](https://metacpan.org/)** - Search and browse CPAN modules with documentation.
- **[Perl.org](https://www.perl.org/)** - Official Perl website with downloads and documentation.
- **[PerlMonks](https://www.perlmonks.org/)** - Community discussion forum for Perl programmers.
- **[Perl Weekly](https://perlweekly.com/)** - Weekly newsletter about Perl.
- **[blogs.perl.org](https://blogs.perl.org/)** - Perl blogging community.
- **[Perl Maven](https://perlmaven.com/)** - Tutorials, articles, and screencasts.
- **[Perl.com](https://www.perl.com/)** - Articles and news about Perl.

### Books

- **[Modern Perl](http://modernperlbooks.com/)** - Free book covering modern Perl practices.
- **[Learning Perl](https://www.oreilly.com/library/view/learning-perl-7th/)** - Classic introduction to Perl (The Llama Book).
- **[Programming Perl](https://www.oreilly.com/library/view/programming-perl-4th/)** - The definitive Perl reference (The Camel Book).
- **[Intermediate Perl](https://www.oreilly.com/library/view/intermediate-perl-2nd/)** - Beyond the basics of Perl.
- **[Mastering Perl](https://www.oreilly.com/library/view/mastering-perl-2nd/)** - Advanced Perl programming techniques.
- **[Higher-Order Perl](https://hop.perl.plover.com/)** - Advanced functional programming techniques (free online).
- **[Perl Best Practices](https://www.oreilly.com/library/view/perl-best-practices/)** - Best practices for Perl programming.
- **[Object Oriented Perl](https://www.manning.com/books/object-oriented-perl)** - Object-oriented programming in Perl.

### Tutorials & Learning

- **[Perl Tutorial](https://perldoc.perl.org/perlintro)** - Official Perl introduction.
- **[Learn Perl](https://learn.perl.org/)** - Comprehensive learning resources.
- **[Perl Maven](https://perlmaven.com/)** - Tutorials and articles for all levels.
- **[PerlDoc](https://perldoc.perl.org/)** - Official Perl documentation.
- **[Exercism Perl Track](https://exercism.org/tracks/perl5)** - Practice Perl with exercises.

### Community

- **[Reddit /r/perl](https://reddit.com/r/perl)** - Perl subreddit with discussions and news.
- **[Perl Monks](https://perlmonks.org/)** - Perl community Q&A and discussion site.
- **[IRC #perl](https://www.perl.org/community.html)** - Perl IRC channels on various networks.
- **[Perl on Stack Overflow](https://stackoverflow.com/questions/tagged/perl)** - Q&A for Perl.
- **[The Perl Foundation](https://www.perlfoundation.org/)** - Dedicated to advancing Perl.

### Conferences & Events

- **[The Perl Conference](https://perlconference.us/)** - Annual Perl conference in North America.
- **[YAPC (Yet Another Perl Conference)](https://www.yapc.org/)** - Regional Perl conferences worldwide.
- **[London Perl Workshop](https://act.yapc.eu/lpw/)** - Annual London event.
- **[German Perl Workshop](https://www.perl-workshop.de/)** - German Perl community event.

### Videos & Podcasts

- **[YAPC NA Videos](https://www.youtube.com/user/yapcna)** - Conference talks on YouTube.
- **[Perl YouTube Channels](https://www.youtube.com/results?search_query=perl+programming)** - Various Perl tutorials.

### Other Awesome Lists

- **[Awesome Mojolicious](https://github.com/kraih/mojo/wiki/Projects-using-Mojolicious)** - Projects using Mojolicious.
- **[Awesome CPAN](https://github.com/hachiojipm/awesome-perl)** - Another curated list of Perl resources.
- **[Task::Kensho](https://metacpan.org/pod/Task::Kensho)** - Glimpse of enlightenment - recommended modules.

## Contributing

Your contributions are always welcome! Please read the contribution guidelines first.

### Guidelines

- Search previous suggestions before making a new one.
- Make an individual pull request for each suggestion.
- Use the following format: `**[Name](link)** - Description.`
- New categories or improvements to existing categorization are welcome.
- Keep descriptions short and simple, but descriptive.
- Check your spelling and grammar.
- Make sure your text editor is set to remove trailing whitespace.

Thank you for your suggestions!

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related rights to this work.
