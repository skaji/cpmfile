[![Actions Status](https://github.com/skaji/cpmfile/workflows/linux/badge.svg)](https://github.com/skaji/cpmfile/actions)

# NAME

Module::cpmfile - Parse cpmfile

# SYNOPSIS

    use Module::cpmfile;

    my $cpmfile = Module::cpmfile->load("cpm.yml");
    my $reqs = $cpmfile->effective_requirements(undef, ["runtime"], ["requires"]);

# DESCRIPTION

THIS IS EXPERIMENTAL.

cpmfile (usually saved as `cpm.yml`) is yet another file format for describing module dependencies,
and Module::cpmfile helps you parse it.

cpmfile will be used mainly by [App::cpm](https://metacpan.org/pod/App%3A%3Acpm).

# SEE ALSO

[cpanfile](https://metacpan.org/pod/cpanfile)

[Module::CPANfile](https://metacpan.org/pod/Module%3A%3ACPANfile)

[App::cpm](https://metacpan.org/pod/App%3A%3Acpm)

# AUTHOR

Shoichi Kaji <skaji@cpan.org>

# COPYRIGHT AND LICENSE

Copyright 2021 Shoichi Kaji <skaji@cpan.org>

This library is free software; you can redistribute it and/or modify
it under the same terms as Perl itself.
