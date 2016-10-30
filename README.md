# NAME

Map::Metro::Plugin::Map::Helsinki - Map::Metro map for Helsinki

<div>
    <p>
    <img src="https://img.shields.io/badge/perl-5.10+-blue.svg" alt="Requires Perl 5.10+" />
    <a href="https://travis-ci.org/Csson/p5-Map-Metro-Helsinki"><img src="https://api.travis-ci.org/Csson/p5-Map-Metro-Helsinki.svg?branch=master" alt="Travis status" /></a>
    <a href="http://cpants.cpanauthors.org/release/CSSON/Map-Metro-Plugin-Map-Helsinki-0.1987"><img src="http://badgedepot.code301.com/badge/kwalitee/CSSON/Map-Metro-Plugin-Map-Helsinki/0.1987" alt="Distribution kwalitee" /></a>
    <a href="http://matrix.cpantesters.org/?dist=Map-Metro-Plugin-Map-Helsinki%200.1987"><img src="http://badgedepot.code301.com/badge/cpantesters/Map-Metro-Plugin-Map-Helsinki/0.1987" alt="CPAN Testers result" /></a>
    <img src="https://img.shields.io/badge/coverage-88.2%-orange.svg" alt="coverage 88.2%" />
    </p>
</div>

# VERSION

Version 0.1987, released 2016-10-30.

# SYNOPSIS

    use Map::Metro;
    my $graph = Map::Metro->new('Helsinki')->parse;

    my $graph2 = Map::Metro->new('Helsinki', hooks => 'Helsinki::Swedish')->parse;
    # now the station names are in Swedish

# DESCRIPTION

See [Map::Metro](https://metacpan.org/pod/Map::Metro) for usage information.

This distribution also includes the `Map::Metro::Plugin::Hook::Helsinki::Swedish` hook, which if applied
translates all station names into Swedish.

# Status

See [Map::Metro::Plugin::Map::Helsinki::Lines](https://metacpan.org/pod/Map::Metro::Plugin::Map::Helsinki::Lines)

This map includes:

- The two branches of the Helsinki metro \[[wikipedia](https://en.wikipedia.org/wiki/Helsinki_Metro)\]

# SOURCE

[https://github.com/Csson/p5-Map-Metro-Helsinki](https://github.com/Csson/p5-Map-Metro-Helsinki)

# HOMEPAGE

[https://metacpan.org/release/Map-Metro-Plugin-Map-Helsinki](https://metacpan.org/release/Map-Metro-Plugin-Map-Helsinki)

# AUTHOR

Erik Carlsson <info@code301.com>

# COPYRIGHT AND LICENSE

This software is copyright (c) 2016 by Erik Carlsson.

This is free software; you can redistribute it and/or modify it under
the same terms as the Perl 5 programming language system itself.
