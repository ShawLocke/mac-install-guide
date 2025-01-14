## How to Open Terminal on Mac

Developers need to know how to open the Terminal application on macOS.

### Terminal application

The Terminal application or _console_ gives us access to the Unix command line, or _shell_. Look in the `Applications/Utilities/` folder for the Terminal application or click the Spotlight icon in the menu bar and type “terminal.” If you see “terminal,” double-click the search result to launch the terminal.

![](/assets/images/ruby/find-macos-terminal.png)

Try out the terminal application by entering a shell command:

```bash
$ whoami
```

Don't type the `$` character. The `$` character is a cue that you should enter a shell command. This is a longtime convention that indicates you should enter a command in the terminal application. The Unix shell command `whoami` returns your username.

Just a reminder to absolute beginners: Press "Enter" after you type the command.

#### Other Terminal applications

The built-in Apple Terminal application is adequate but many developers install [iTerm 2](http://www.iterm2.com/#/section/home). It has more options for customization.

If you use the Visual Studio Code or Nova text editors, an integrated terminal application is included.

### Text editor

Some programmers will suggest you try [Vim](https://en.wikipedia.org/wiki/Vim_(text_editor)) or [Emacs](https://en.wikipedia.org/wiki/Emacs). Either can make you an efficient coder, but they are command-line applications so the learning curve is steep. It's best to start with a graphical text editor if you're new to programming.

The most popular free text editor for developers is:

- [Visual Studio Code](https://code.visualstudio.com/) (free from Microsoft)

Here are older text editors that are less popular that you can still use:

- [Atom](https://atom.io/)
- [Sublime Text](https://www.sublimetext.com/)
- [TextMate](https://macromates.com/)

If your budget allows it, there is a very nice new text editor for macOS:

- [Nova](https://nova.app/) ($99 from Panic)

You don’t need to install a text editor right now, but you will need one as soon as you start developing a Ruby application.

### Resources

Most developers know how to use a terminal application and basic Unix file commands to move around the computer. If Unix is new to you, you can use your file browser to create files and move around, picking up Unix as you go. To learn a little Unix, I recommend either [Learn Enough Command Line to Be Dangerous](http://www.learnenough.com/command-line-tutorial) or Zed Shaw’s free [Command Line Crash Course](https://learnpythonthehardway.org/book/appendixa.html) to gain confidence with Unix shell commands.

Text editors have a lot of features, especially shortcuts for developer efficiency. You won’t need to learn everything to get started, but to level up, take a look at [Learn Enough Text Editor to Be Dangerous ](https://www.learnenough.com/text-editor-tutorial/vim).

