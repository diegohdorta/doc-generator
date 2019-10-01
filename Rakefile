namespace :build do
task :pdf do
`bundle exec asciidoctor-pdf -a icons=font -apdf-style=themes/custom-theme.yml -a pdf-fontsdir=themes/fonts eIQ-Hands-on.adoc -o output/eIQ-Hands-on.pdf`
end
task :html do
`bundle exec asciidoctor eIQ-Hands-on.adoc -o output/eIQ-Hands-on.html`
end
end
desc 'Build all default formats'
task :build => [ 'build:html', 'build:pdf' ]
