# Git Create :hammer:

Setting up and creating a Git repository is too much of a hassle, if you do it a lot

Hence I came up with this simple script where you can create a GitHub repository with a single line of command `create-git` in your Linux machine

![](header.png)

## Setup :wrench:

1. Setup SSH [here](https://help.github.com/en/github/authenticating-to-github/adding-a-new-ssh-key-to-your-github-account)

1. Create a personal access token for GitHub [here](https://help.github.com/en/github/authenticating-to-github/creating-a-personal-access-token-for-the-command-line)

1. Move/Copy/Create/Save the `.create-github-repo.sh` to your home directory (`cd`)

1. Source the bash script and add your personal access token into your `~/.bashrc`. Example:

```bash
# Insert this line inside your ~/.bashrc
export GITHUB_API_TOKEN=fac086307dab129b81ca11a842bb94acd0d98f99
source ~/.create-github-repo.sh
```

## Usage example :page_with_curl:

```bash
start-git-project
```

## Contributing :construction_worker:

1. Fork this
2. Create your feature branch (`git checkout -b feature/fooBar`)
3. Commit your changes (`git commit -am 'Add some fooBar'`)
4. Push to the branch (`git push origin feature/fooBar`)
5. Create a new Pull Request

## License :copyright:

Copyright 2019 Jerry Ng

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.