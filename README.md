# vuetify-vim

This is an unofficial vim plugin that defines [UltiSnips](https://github.com/SirVer/ultisnips) snippets for vuetify.

The snippets are created from the official one in [vuetify-vscode](https://github.com/vuetifyjs/vuetify-vscode) so you can refer to the documentation [here](https://github.com/vuetifyjs/vuetify-vscode/blob/master/documentation.md).

## Creating the snippets

The main.go programm is copied from [this gist](https://gist.github.com/suyash/76ce40081f99a42c3eb1926e9986f7aa).

    wget https://raw.githubusercontent.com/vuetifyjs/vuetify-vscode/master/snippets/vuetify.json
    go get github.com/suyash/algo
    go run main.go vuetify.json