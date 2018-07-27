# Vim Circuit-ui Snippets

A Vim snippet library for [circuit-ui]([https://github.com/sumup/circuit-ui)

Requires [UltiSnips](https://github.com/SirVer/ultisnips).

## Installation

Using [vim-plug](https://github.com/junegunn/vim-plug):

```vim
" React code snippets
Plug 'cristianoliveira/vim-circuit-ui-snippets'

" Ultisnips
Plug 'SirVer/ultisnips'

" Trigger configuration (Optional)
" let g:UltiSnipsExpandTrigger="<C-l>"
```

## Usage

As any other - you use specific codes for autocompletion. For this library
it is basic the html tag name.

### Common snippets

* `cimp "Circuit-ui import components" w`

#### Theme

* `cts "Circui-ui theme spacings"`
* `ctg "Circui-ui theme grid"`
* `ctc "Circui-ui theme colors"`
* `ctis "Circui-ui theme icon sizes"`
* `ctt "Circui-ui theme typography"`
* `ctth "Circui-ui theme typography for headings"`
* `cttsh "Circui-ui theme typography for subHeadings"`
* `cttt "Circui-ui theme typography for text"`
* `ctmq "Circui-ui theme media query"`

#### Measurement

* `cmb "Circui-ui measurement byte"`
* `cmk "Circui-ui measurement kilo"`
* `cmg "Circui-ui measurement giga"`
* `cmt "circui-ui measurement tera"`

#### Complex component usage

* `cbc "circui-ui button component "`
* `ccc "circui-ui card component"`

## Contributing

* Fork it!
* Create your feature branch: `git checkout -b my-new-feature`
* Commit your changes: `git commit -am 'Add some feature'`
* Push to the branch: `git push origin my-new-feature`
* Submit a pull request, they are welcome!
* Please include unit tests in your pull requests

# License

MIT
