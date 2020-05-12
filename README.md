# kudo

> Manage your todos using kubernetes

![image](https://i.imgur.com/jgh0fZw.png)

## Why?

Because you can.

## Should I use it?

I don't know, it is up to you. It works. 🤷

## Usage

We create a namespace called todo for all the stuff that kudo does

```
Usage: kudo <command>
Commands:
list   : list all incomplete todos
new    : add a new todo
done   : mark a todo as done
undone : mark a todo as undone
delete : delete a todo
```

## Uninstall

- k delete ns todos
- k delete crd todos.meain.io
