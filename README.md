<h3 align="left"><em><strong>Hi there! <img alt="hi" src="https://raw.githubusercontent.com/Nikhil-1920/Nikhil-1920/master/images/HandWave.gif" width="40" /> I'm Nikhil</strong></em></h3>

<hr height="1px" align="center" />

<h3 align="left"> <img height="40" width="40" alt="github" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/github.svg" /><em><strong> About Me </strong></em></h3>

```python

from dataclasses import dataclass
from typing import Tuple


class Meta(type):
    def __new__(cls, name, bases, attrs):
        new_cls = super().__new__(cls, name, bases, attrs)
        return dataclass(unsafe_hash=True, frozen=True)(new_cls)


class Bio(metaclass=Meta):
    name        : str = "Nikhil Singh"
    designation : str = "Software Engineer"
    company     : str = "IBM Research"
    base        : str = "Noida, India"
    blog        : str = "https://medium.com/@nikhilsingh3"


class Stack(metaclass=Meta):
    languages   : Tuple[str, ...] = ("Python", "Go", "Shell")
    databases   : Tuple[str, ...] = ("MySQL", "PostgreSQL", "Mongo", "Redis")
    misc        : Tuple[str, ...] = ("Docker", "Celery")
    ongoing     : Tuple[str, ...] = ("Django", "GraphQL")


class Social(metaclass=Meta):
    twitter     : str = "SinghNikhil1920"
    linkedin    : str = "nikhil-singh-b2a78014a"
```

<hr height="1px" align="left" />

<p>
    <img height="180em" src="https://github-readme-stats.vercel.app/api?username=Nikhil-1920&hide=prs&show_icons=true&theme=tokyonight">
    &emsp; &emsp;
    <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Nikhil-1920&theme=tokyonight">
</p>

<hr height="1px" align="center" />

<a href="https://github.com/Nikhil-1920/Nikhil-1920 /">
    <img src="https://github.com/Nikhil-1920/Nikhil-1920/blob/main/images/SnakeGrid.svg" alt="snake" />
</a>





