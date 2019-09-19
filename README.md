# NXP Template for Documentation using AsciiDoctor

To build use the following commands:

```bash
$ apt-get install ruby
$ gem install bundler
$ bundle install
```

To generate a new template:
```bash
$ ./doc-generator -d "File name" -t "Document Title"
```

To re-compile the document:

```bash
$ ./doc-generator
```
