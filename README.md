# S3 Secret URL

A simple tool that lists the contents of a bucket, presemts a list of
it's contents and asks you what item you'd like to generate a secret
link for.


# Installation & requirements

[boto][1] is a requirement and you'll have to [configure it][2] before
s3-secret-url will work

Whack s3-secret-url on your path and away you go.

# Usage

`s3-secret-url my-bucket` you'll be asked which file you'd like to
create a link for.



[1]: https://github.com/boto/boto
[2]: http://code.google.com/p/boto/wiki/BotoConfig
