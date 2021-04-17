---
layout: single
title:  "Let's learn Go!"
date:   2021-04-15 00:00:34 +0530
categories: golang
---
Go is a statically typed, compiled language developed by Google. It's also a really fun language to build simple reliable and efficient software.

## Installation
Head over to [golang.org](https://golang.org) and download the installer for your platform.
<br />
After going through the installation, ensure that the `go` command is available at your terminal. 

## The Basics
Let's start by going through the age-old rite of passage for all programmers in a new language, the boring hello world program.
<br />
{% highlight go %}
package main

import "fmt"

func main() {
    fmt.Println("hello world")
}
{% endhighlight %}
<br />
Now, let's look at the code in more detail.