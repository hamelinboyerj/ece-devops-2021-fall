---
duration: 30 min
---

# Prerequisites

## Terminal

* Most useful developer tool
* Any number of customizations
* On Windows: Linux Bash Shell, Powershell, Git Bash
* On MacOS / Linux: native

[Bash base commands](https://www.educative.io/blog/bash-shell-command-cheat-sheet)

## Vi(m)

* Bash text editor
* Use `:` to enter command mode
  * `w` to write file
  * `q` to quit
  * `q!` to quit without saving
  * 'x' to write & quit
* Use `/` to search for text
* Use `i` to enter edit mode and `esc` to exit it
* `vimtutor` is the best tutorial to learn

## Client VS Server

* Two parts of a distributed computing model:
  * Client requests the info and displays it
  * Server processes the request and services the result
* We will do server work + a bit of client side

## The IP protocol

* Send data from one computer to another over a network (ex: client/server)
* Use of IPV4 addresses (ex: 172.16.254.1), IPV6 also available but not much used
* Data packaged in IP packets with 2 sections
  * Header: IP version, addresses, TTL, ...
  * Data: the packet's content

## The HTTP protocol

* Application protocol for transmitting hypermedia documents (HTML)
* Two types of messages: *requests* & *responses*
* HTTP message split between *headers* & *body*
* HTTP response always contains
  * the *protocol* (HTTP/1.1)
  * a *status code* (200, 404, ...)
  * a *status text* (page not found)

## SSH - Secure SHell

* Cryptographic network protocol to operate network services securely over an unsecured network
* Exchange of public & private keys to secure the exchange
  * Client has the private key
  * Server needs to have the associated public key
  * Client & server exchange messages encrypted with the keys to authenticate

## Editors

As a developer, your editor shall be your best friend.

* Vim
* VsCode editor
* Atom
* Sublime Text
* TextWrangler 
* Notepad++
* WebStorm
* ...

## Programation paradigms

* "A way of programming"
* Common paradigms:
  * Imperative - Control flow is an explicit sequence of commands
  * Functional - Computation proceeds by function calls, no global state
  * Object-oriented - Everything is an object
  * Event-driven - Control flow determined by async actions

## StackOverflow

* Huge data source
* Reactive community
* Any subject
* Lots of answered questions (> 1M !)
* Don’t forget the source code !
