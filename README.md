## Hi there 👋

<!--
**slwnt31/slwnt31** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
![venom](https://capsule-render.vercel.app/api?type=venom&height=200&text=I%20am%20Venom.&fontSize=70&color=0:8871e5,100:b678c4&stroke=b678c4)

import click
from rich.markdown import Markdown
from rich.console import Console
from rich.progress import track
from rich.table import Table
from rich.syntax import Syntax
import time, pyfiglet

console = Console()

@click.command()
def main():
    for step in track(range(5), description="Wait..."):
        time.sleep(0.3)

    print("\n")

    click.echo(pyfiglet.figlet_format("Welcome To SLWNT31", font="slant"))

if __name__ == "__main__":
    main()


## 자기소개 CLI
- Clone this repository:
```sh
git clone https://github.com/slwnt31/CLIck-Me.git
```
- Install the dependencies:
```sh
python -m venv hellopy-cli

hellopy-cli\Scripts\activate.bat

pip install click colorama pyfiglet rich
```
- Usage:
```
python BaekSujin/cli-proflie.py
```

