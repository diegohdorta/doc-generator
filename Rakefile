namespace :build do
task :pdf do
`bundle exec asciidoctor-pdf -apdf-style=themes/custom-theme.yml -a pdf-fontsdir=themes/fonts GettingStartedtools.adoc -o output/GettingStartedtools.pdf`
end
task :html do
`bundle exec asciidoctor GettingStartedtools.adoc -o output/GettingStartedtools.html`
end
end
desc 'Build all default formats'
task :build => [ 'build:html', 'build:pdf' ]
