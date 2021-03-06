# save_skype
Messages will persist in the Skype app's database even after they're deleted, and this utility will recover them as text files.

## Installation
`pip3 install save_skype`

Or

- Pull the repo
- Install dependencies w/ pip
`pip3 install -r requirements.txt && python3 setup.py install`



## Usage
- Get the path of your main.db
`~/.Skype/USERNAME/main.db`

```
alex@mba:/media/alex/Downloads/save_skype$ save_skype --help
Usage: save_skype [OPTIONS] FILE

Options:
  -s, --save TEXT  Path to save chats
  --help           Show this message and exit.

alex@mba:/media/alex/Downloads/save_skype$ save_skype ~/.Skype/MY_USERNAME/main.db
chat_896_other1_me.txt
chat_1536_me_other2.txt
chat_901_me_other3.txt
chat_2057_me_other4.txt
...

Files saved to .
```

## License
See `LICENSE`. Message me if you'd like to use this project with a different license.
