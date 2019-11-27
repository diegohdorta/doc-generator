namespace :build do
task :pdf do
`bundle exec asciidoctor-pdf -apdf-style=themes/custom-theme.yml -a pdf-fontsdir=themes/fonts embedded_os_guide.adoc -o output/embedded_os_guide.pdf`
end
task :html do
`bundle exec asciidoctor embedded_os_guide.adoc -o output/embedded_os_guide.html`
end
end
desc 'Build all default formats'
task :build => [ 'build:html', 'build:pdf' ]
