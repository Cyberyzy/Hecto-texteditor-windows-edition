# hecto-texteditor-windows-edition
A Windows edition for the hecto text editor, based on [Philipp's tutorial edition](https://www.flenker.blog/hecto/). 

Following the tutorial, I adapted the project for Windows using the crossterm crate (the original edition used termion for terminal interaction, now replaced by crossterm). 

Many thanks to Philipp for his excellent tutorial! This small project serves as a personal exercise to deepen my understanding of Rust.

Some tiny changes:

- **Line Number Display:** The text editor now prominently displays line numbers on the left-hand side.
- **Hard-wrap line and soft-wrap line:** Full support for the "Enter" key has been implemented.
- **Mouse Click Support:**: Now you can use mouse click to move cursor.

I decide to translate the tutorial into Chinese. Check the progress at [here](https://cyberyzy.github.io/)!
