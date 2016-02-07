# sdmp-example-keys

Pre-generated public and private keys, used for tests in
the SDMP software.

These keys are publically visible, so you shouldn't use
them for anything important.

They also are not the keys of any of the contributors to
the SDMP project.

They are simply a pair of public/private keys, used inside
of tests, so that you don't have to generate your own.

## how were they made?

The following commands were run:

	openssl genrsa -out private.pem 2048
	openssl rsa -in private.pem -pubout -out public.pem

The contents of the `private.pem` and `public.pem` were
then copied to the `keys.json` file.

## license

These keys and this module are published under the
[Very Open License](http://veryopenlicense.com/).

<3
