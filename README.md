# NXP Template for Documentation using AsciiDoctor

1. To build use the following commands:

```bash
$ apt-get install ruby
$ gem install bundler
$ bundle install
```
2. Fork the `doc-generator` at this [link](https://bitbucket.sw.nxp.com/users/nxf47857/repos/doc-generator/browse).

3. To generate a new template:
```bash
$ git checkout master
$ git branch "your_document_branch_name"
$ ./doc-generator -d "File name" -t "Document Title"
```

3. To re-compile the document:

```bash
$ ./doc-generator
```
