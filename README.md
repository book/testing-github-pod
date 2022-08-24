# Testing POD rendering on GitHub

None of the files gives a 500 anymore.

The remaining `FAIL` files do not render correctly.

    $ file *.pod
    FAIL-aring-emoji-utf8.pod:          Perl POD document, UTF-8 Unicode text
    FAIL-eacute-latin1-no-encoding.pod: Perl POD document, ISO-8859 text
    FAIL-emoji-aring-utf8.pod:          Perl POD document, UTF-8 Unicode text
    PASS-aring-escape.pod:              Perl POD document, ASCII text
    PASS-aring-utf8.pod:                Perl POD document, UTF-8 Unicode text
    PASS-eacute-escape.pod:             Perl POD document, ASCII text
    PASS-eacute-latin1.pod:             Perl POD document, ISO-8859 text
    PASS-eacute-utf8.pod:               Perl POD document, UTF-8 Unicode text
    PASS-emoji-utf8.pod:                Perl POD document, UTF-8 Unicode text
