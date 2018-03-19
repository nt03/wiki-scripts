# census

Generate data of edits per user for every wiki in wikia.

Written in Perl5.

## Dependencies
* Bundle::LWP. In debian and derivatives it's included in the `libwww-perl` package. Alternatively, It can be installed using CPAN: `perl -MCPAN -e 'install Bundle::LWP'`
* Perl JSON lib. In debian and derivatives it's included in the `libjson-perl` package, other distros can find it in `perl-JSON`. Alternatively, It can be installed using CPAN: `perl -MCPAN -e 'install JSON'`
* Perl HTML::Strip lib. In debian and derivatives it's included in the `libhtml-strip-perl` package. Alternatively, install it using CPAN: `perl -cpan HTML::Strip`