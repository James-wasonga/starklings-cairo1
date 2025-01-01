<a href="https://app.onlydust.com/p/starklings-cairo1">
<img src="https://img.shields.io/badge/OnlyDust-Starklings-grey?labelColor=000&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABQAAAATCAYAAACQjC21AAAAAXNSR0IArs4c6QAABNNJREFUOE9tlGtQ1FUchp/z/+8usLCArOAuICyggwpI4mVEQzNJVMQZb6WpqTikXSxDDC2bMUv9YAw2loWUOo06lo02XsoUL2NqogmmgmCgcleQ24Jclt09zeLo2OV8O7/3Pc+cOXPeV/A/S57B96Zm/Gu7m1MLsqYvOv+sZVNeXvwrg/rGhgcF7hEioP3fx8WzA7keDRGk1hst2cOiDl+rDR061qWf8S/y8lOMMvaB6ZFrv25SbWHGHhHm4+++Anz3CiGcTzhPgTJluJ6Yqzk9g3ULdmw+S3P38Bkflbv9JFv29nFszjyIqkg185fZwieqKZKSlcuSPLLfO2YEteNLaF0lxMBuF7QXKJGKLe7Vb3RT9y+5rsaT+vE+3BEJUTkN+VWJynf1FbY5slFHDH77FxeFLg7OPrvYy6Ms1//sBNTIfkB9NoSvEkLIXmABDfMiLNn7vBdtpuC3XBpPzyPY/c5XQ7pi3nTpppyu5G67Q2l+y/NI7wU+VU+idSQ6x29EjMxAKJXguJ8iNAlHxRykOg9b9XjjLpPfrDU0HNuEX+xO1OjCDtJGmMXAfOs/3lleNvHwSCXSqXV2GVCCl4NoAsftMtRLkWIy1hlz0B+covsZU8o6RNx18AfiIiAmy4Fu2twDB9RDHICJi1ihH0KW1mxXhEbB3gw6/xbACvZb0JyXLOKo+3Yp/VInKwUExXyO27pDMCwJwtfj7Img9bQHTefbnT11IOu9FH00SDt4J4BikPhOuA90QtdlKNuYI/y4dW06lthkVAa53WHQiZ1oEtKQzhAaT9nZOt+J46FGvkQX/d1rxSO/MKS7B442CFjaTkjGdugogQcXofKvQqFyuXYIZnMiZp5DYei0FgZse8SWWUY6CnUESBU/sI+iCV+KNXrtbdQBNZR3LCNidhq+0XmgOKG1B+ocdSKAgmob2qARBBGHgXDgLhIvNBgRBABeUDqAkr7eosjoYb6BR0Q+R5piMUUWMzr6KLi+dZtA1vSvEXOpunic+ngVHRb0rCKUOrrpRkcgGgyPgdvDKA/2Ua5N97TkU9vnASsLs/CWbqwJPoFJew8P0UhPc9gl8SOOrCo6069hxRcNw/DlJlaq6CKZIDwBPcwcQFmYQSnKMljOs7D6dbAF0wctI9FgwYkndhRElsi1yBf07ZwxNEm6nU7qsFGMlbt0MJUg/NEhwS+GunCj8ucfdabbpNfOJwQDRrQYhBONVNACboiE3qS8uLbn6pLdmrj6+61c0FVgUjWypsNLGHAjmX72eQitK57V4rT9Q62XKLeFk2TqlC9HHBbnSsZxpXEwlXTk/4rP6F7gpPSeMbMOq+dC73SrCW8PRDepoXVmSnGph9SNSiG4cyFC7/JViIvdY6WnLlg1n9+3tu9QNcjmveV9JxVtDkcnzufz8Ln0tG1yQ+Q7/SvZ6rDkiylZY2joDMzMXHA5PQqz+2qE7+PM322Pp6X+xvfRuzyrlQ2fbWuh4J6QNmzpv2Pa+rRtnmT1OPLdNpxbvMblapNWv1G1IcU64j5c+BrDQJcnjYqqXBqirVfiij/5oCbw2EnZY4PMMkKy/9OHTwY/ICPbsJ0KmfKFOTFtbeySmaVluwnrcukW7rqXtPsnZCwvPb5jj1Ltjm6ilaiyZ8vjb2wS2X7S7itMAAAAAElFTkSuQmCC" />
</a>

<a href="https://twitter.com/intent/follow?screen_name=onlydust_com">
<img src="https://img.shields.io/twitter/follow/onlydust_com?label=Follow OnlyDust&style=social" />
</a>

<a href="https://twitter.com/intent/follow?screen_name=shrameetweets">
<img src="https://img.shields.io/twitter/follow/shrameetweets?label=Follow ShrameeTweets&style=social" />
</a>

<a href="https://t.me/+wu8frxmrbeliZWI1">
<img src="https://img.shields.io/static/v1?label=Telegram&message=Starklings Dev&color=eee&logo=telegram&style=social" />
</a>

# STARKLINGS

### An interactive tutorial to get you up and running with Cairo and Starknet

---

## Setup and run

### 1. Install Rust

Make sure you have Rust and Cargo installed with the `default` toolchain.  

```sh
curl https://sh.rustup.rs -sSf | sh -s
```

### 2. Clone the Repository

```sh
git clone https://github.com/shramee/starklings-cairo1.git
```

### 3. Navigate to the Directory

```sh
cd starklings-cairo1
```

### 4. Run Starklings

Run the following command to start Starklings. The first run might take a while:

```sh
cargo run -r --bin starklings
```

### 5. Start Watch Mode

Once you're ready, start Starklings in watch mode:

```sh
cargo run -r --bin starklings *watch*
```

---

## Start at a Specific Exercise

To begin with a specific exercise, pass its name to the `watch` command. For example, to start at `starknet1`:

```sh
cargo run -r --bin starklings watch starknet1
```

---

## Instructions and Welcome Message

```
starklings - An interactive tutorial to get started with Cairo and Starknet

       _             _    _ _
      | |           | |  | (_)
   ___| |_ __ _ _ __| | _| |_ _ __   __ _ ___
  / __| __/ _` | '__| |/ / | | '_ \ / _` / __|
  \__ \ || (_| | |  |   <| | | | | | (_| \__ \
  |___/\__\__,_|_|  |_|\_\_|_|_| |_|\__, |___/
                                     __/ |
                                    |___/

Thanks for installing starklings!

Is this your first time? Don't worry, starklings is made for beginners! We are
going to teach you a bunch of stuff about StarkNet and Cairo.

Here's how starklings works,

1. To start starklings run `cargo run -r --bin starklings watch`
2. It'll automatically start with the first exercise. Don't get confused by
error message popping up as soon as you run starklings! This is part of the
exercise that you're supposed to solve, so open the exercise file in an editor
and start your detective work!
3. If you're stuck on an exercise, there is a helpful hint you can view by
typing `hint` (in watch mode), or running `cargo run -r --bin starklings hint
exercise_name`.
4. When you have solved the exercise successfully, Remove `// I AM NOT DONE`
comment to move on to the next exercise.
5. If an exercise doesn't make sense to you, please open an issue on GitHub!
(https://github.com/shramee/starklings-cairo1/issues/new).

Got all that? Great! To get started, run `starklings watch` in order to get the
first exercise. Make sure to have your editor open!
```

---

## VSCode Extension & Language Server

For syntax highlighting and language server features, install the Cairo Language Server. Instructions are available in the [Cairo repository](https://github.com/starkware-libs/cairo/tree/main/vscode-cairo).

---

## Testing

### For Cairo-related Tests

```sh
cargo test cairo
```

### For All Tests

```sh
cargo test
```

---

## Contributing

### Adding New Exercises

1. Add the exercise file in the `./exercises` directory.
2. Insert information about the exercise in `./info.toml` file. For example
    ```toml
    [[exercises]]
    name = "new_exercise"
    path = "exercises/new_module/new_exercise.cairo"
    mode = "test"
    hint = """
    Try the Harlem shake
    """
    ```
3. Run your exercise with `starklings run` as you write
```
cargo run -r --bin starklings run new_exercise
```
4. Check that the [tests](#testing) pass.
5. Send your PR!

### Updating Rust logic/Cairo version

1. [Test](#testing) your changes.
2. Make sure you have solutions to all the exercises in `./solutions` directory.