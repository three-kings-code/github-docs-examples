## Writing Good Documentation

### Step 1 - Using Codeblocks

Codeblocks in markdown make it *very* easy for tech people to **copy, paste and share** code. A good Cloud Engineer uses Codeblocks whenever possible

Because it allows other so copy and paste their code to replicate or research issues.

```
provider "aws" {
  region = "us-east-1"
}

resource "aws_instance" "web_server" {
  ami = "ami-01234567890123456"
  instance_type = "t2.micro"
  tags = {
    Name = "Web Server"
  }
}
```

- When you should attempt to apply syntax highlighting to your codeblocks



```Terraform
provider "aws" {
  region = "us-east-1"
}

resource "aws_instance" "web_server" {
  ami = "ami-01234567890123456"
  instance_type = "t2.micro"
  tags = {
    Name = "Web Server"
  }
}
```

Two differnet ways to show pictures the bottom one you can change the size the top one you can't
![20220913_110252](https://github.com/three-kings-code/github-docs-examples/assets/64013976/e4ca2b9d-94c4-402d-8cf6-807a6cde79ea)
<img width="250px" src="https://github.com/three-kings-code/github-docs-examples/assets/64013976/e4ca2b9d-94c4-402d-8cf6-807a6cde79ea" />


Good cloud engineers use codeblocks for both code and errors that appear in the console.

```bash
$ ./myscript.sh
./myscript.sh: line 10: syntax error: unexpected end of file
```
> Here is an example of using a codeblock for an error that appears in bash.


- [x] Finish Step 1
- [ ] Finish Step 2
- [ ] Finish Step 3
- [ ] Finish Step 4

### Step 4 - Use Emojis (Optional)

GitHub Flavored Markdown (GFM) supports emoji shortcodes.

Here are some examples:
 | Name | Shortcode |emoji|
 |---|---|---|
 |Cloud|`:cloud`:|☁️|
 |Cloud with lighting|`:cloud_with_lightning`:|:cloud_with_lightning:|
 |Sunny|`:sunny`:|☀️|

 ### Step 5 - How to Create a Table

You can use the following markdown format to create tables 

 ```md
 | Name | Shortcode |emoji|
 |---|---|---|
 |Cloud|`:cloud`:|☁️|
 |Cloud with lighting|`:cloud_with_lightning`:|🌩️|
 |Sunny|`:sunny`:|☀️|
```
Github extends the functionality of Markdown tables to provide more alignment and table cell formatting options


## References
- [Basic Markdown Writing](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) <sub>[1]<sub>
- [GFM - Tasks Lists](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists)
- [GFM - Formatting](https://docs.github.com/en/gfm) <sup>[2]<sup>
- [GFM - Emoji Cheat Sheet](https://github.com/ikatyang/emoji-cheat-sheet)
- [GFM - Tables using extentions](https://docs.github.com/gfm/#tables-extention-)
