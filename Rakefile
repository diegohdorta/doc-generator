namespace :build do
task :pdf do
`bundle exec asciidoctor-pdf -apdf-style=themes/custom-theme.yml -a pdf-fontsdir=themes/fonts robinbird.adoc -o output/robinbird.pdf`
end
task :html do
`bundle exec asciidoctor robinbird.adoc -o output/robinbird.html`
end
end
desc 'Build all default formats'
task :build => [ 'build:html', 'build:pdf' ]
