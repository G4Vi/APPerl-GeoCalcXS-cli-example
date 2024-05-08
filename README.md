# APPerl-GeoCalcXS-cli-example

Tested with Perl-Dist-APPerl-v0.5.0

To build, install Perl::Dist::APPerl and install build deps if you haven't already:
```
cpanm Perl::Dist::APPerl
apperlm install-build-deps
```

Then, download this version of Geo::Calc::XS:
```
wget https://cpan.metacpan.org/authors/id/A/AS/ASP/Geo-Calc-XS-0.33.tar.gz
```

Finally configure and build:
```
apperlm checkout geocalcxs
apperlm configure
apperlm build
```

Try it out:
```
./geocalcxs.com 40.417875 -3.710205 get_lat
```
