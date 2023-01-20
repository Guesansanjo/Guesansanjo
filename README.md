<h1 align="left">Hello there 👋,I'm Jose ..</h1>
<h3 align="left">Wanna get to know me ?.</h3>

- 🌱 I’m currently learning **Ruby**
- ⚡ Fun fact **I like coffee**
```ruby
# frozen_string_literal: true

require 'json'
# Print a JSON
class PrintJson
  def generate_json(data)
    puts JSON.pretty_generate(data)
  end
end

data = [
  {
    name: 'Jose Maria',
    surname: 'Guerrero Sanchez',
    technologies: {
      frontend: {
        typescript: true,
        hotwire: true,
        http: %w[Axios Ajax Jquery],
        frameworks: ['Angular', 'Svelte', 'Vue', 'Stimulus.js'],
        css: %w[Bootstrap Tailwind]
      },
      backend: {
        java: 'Sprting',
        ruby: 'Rails',
        python: 'Django'
      },
      database: %w[MySQL PostgreSQL Oracle]
    }
  }
]

printer = PrintJson.new
printer.generate_json(data)
```
