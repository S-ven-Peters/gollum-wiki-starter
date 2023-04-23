# gollum-wiki-starter
this is currently empty, but will hold a starter for a git based wiki with convenience scripts and convenience pages such as:
- a help section inside the wiki
- an index
- a page with a list of invalid links

it will be designed to work on [Windows](https://www.microsoft.com/windows/)
for now it will be designed to work with John Gruber's [Markdown](https://daringfireball.net/projects/markdown/syntax) other syntaxes might come later or they might not

## dependencies (probably)
- [gollum](https://github.com/gollum/gollum)
- [jRuby](https://www.jruby.org/)
- [python](https://www.python.org/downloads/)

## notes for me:
once the basic starter is complete:
- automatically check if syntax might have been updated on your end
- roll out in components, so existing wikis can be updated
- check if it works on Win 11
- these are probably a combination of feature request and collaboration:
  - toolbar for special pages that is visible from anywhere ([gollum](https://github.com/gollum/gollum))
  - allow for spaces in section titles so they can be linked with '#section title' (check where the link click handling actually comes from)
