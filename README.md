# move-keep-to-memos
Move Google Keep data to [Memos](https://github.com/usememos/memos)

This script use [memos native API](https://memos.apidocumentation.com/reference)


## How to use
- Go to [Google Takeout](https://takeout.google.com/) and export Keep data
- Extract the ZIP
- Download the python script from [this repo](https://raw.githubusercontent.com/MatthieuTinnes/move-keep-to-memos/refs/heads/main/keep2memos.py)
- Put this script in the extracted archive, alongside Takeout folder
- Get a token for your memos instance, in parameters menu / my account
- Use this command with instance url and token : `python3 main.py --instance https://memos.myserver.com --token XXXX`
You can change the default folder with the --folder parameter


## What does this script import ? 

This script import text and original creation date.

Image are not supported for now. 