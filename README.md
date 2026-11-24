# hr-psql.vim

> open psql formatted table definitions from vim
> [Postgres](https://www.postgresql.org/)

## Usage

Move the cursor over a table name word (Thing, thing, things) and type `<leader>d` to view a
the table definition as seen in `psql` in a scratch window.

To override the default mapping, use the following command:

``` vimscript
nmap <Leader>db  <Plug>hr_psql_pg_table_window
```

## Installation

To install `hr-psql.vim`, use your favorite Vim plugin manager (e.g.
[Plug](https://github.com/junegunn/vim-plug)):

```vimscript
Plug '-/vim-hr-psql'
```

### License

hr-psql.vim is released under the [MIT License](http://www.opensource.org/licenses/MIT).

---


