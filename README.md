# TODO

We'll use Java (`springboot`) to build this api.

Some tasks:

## Main tasks

- [] Handle CRUD operations on the notes (notes are written in markdown), namely:
  - [] research the best practices if we want to notes (do we create a new file on the server? or do we store it in a database and create a "virtual file" representation)
  - [] `POST` requests to create notes
  - [] `GET` requests to get/read notes
  - [] `UPDATE` to update notes
  - [] `DELETE` to delete notes
- [] Handle user authentication

## Side tasks

- [] turn the markdown into pdf or a webpage or slides or something (can use `pandoc`)
- [] maybe do some `latex` or `typst`
- [] learn to safely run terminal command on the server (`pandoc`, `pdflatex`, `typst`) in order to prevent SQL injection kinda stuff
