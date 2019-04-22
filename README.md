# perlver - The Perl Minimum Version Analyzer

## SYNOPSIS

    adam@red:~$ perlver Perl-MinimumVersion
    Found directory '.'
    Searching for Perl files... found 3 file(s)
    Scanning lib/Perl/MinimumVersion.pm... done
    Scanning t/01_compile.t... done
    Scanning t/02_main.t... done

        ---------------------------------------------------------
      | file                       | explicit | syntax | external |
      | --------------------------------------------------------- |
      | lib/Perl/MinimumVersion.pm | 5.005    | ~      | n/a      |
      | t/01_compile.t             | ~        | ~      | n/a      |
      | t/02_main.t                | ~        | ~      | n/a      |
        ---------------------------------------------------------

    Minimum version of Perl required: ...

    adam@red:~$

## DESCRIPTION

`perlver` is a console script created to provide convenient access to the
functionality provided by [Perl::MinimumVersion](https://metacpan.org/pod/Perl::MinimumVersion).

\--blame option shows code which requires this version of perl

The synopsis above pretty much covers all you need to know at this point.

# AUTHORS

- Adam Kennedy <adamk@cpan.org>
- Neil Bowers <neil@bowers.com>

# SEE ALSO

[PPI](https://metacpan.org/pod/PPI), [Perl::MinimumVersion](https://metacpan.org/pod/Perl::MinimumVersion)

# COPYRIGHT

Copyright 2005 - 2012 Adam Kennedy.
Copyright 2015 - 2019 Neil Bowers and contributors.

This program is free software; you can redistribute
it and/or modify it under the same terms as Perl itself.

The full text of the license can be found in the
LICENSE file included with this module.
