require 'quarto'
require 'quarto/tasks'

Quarto.configure do |config|
  config.author = 'Yasuhito Takamiya'
  config.title = 'Hello World'

  config.use :bundle
  config.use :git
  config.use :orgmode
  config.use :prince

  config.source_files = ['trema.org']

  config.stylesheets.font = '"IPAexg", sans-serif'
  config.add_font( "IPAexg", file: "fonts/ipaexg.ttf" )
end
