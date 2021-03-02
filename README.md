# ASCII UML

There has been a trend in software development to present non-code artifact via plain text, often called ASCII.
Because ASCII has been the most used encoding, and it became part of Unicode, 
and UTF-8 has the exactly the same codes.

ASCII usage has been extended for general graphics, often called AsciiArt (see <http://asciiflow.com>, <http://www.jave.de/>) 
and UML, e.g. 
[PlantUML](http://plantuml.com),
[TextUML](http://abstratt.github.io/textuml/readme.html) ([mp](https://marketplace.eclipse.org/content/textuml-toolkit))
.

PlantUML is the most rich. TextUML is for class diagrams only. 
For web tool for sequence diagram
see <https://github.com/bramp/js-sequence-diagrams>
and <http://sequencediagram.org> (PlantUML syntax) with additional drag-n-drop of image elements on the right side.



## Tooling for PlantUML

**Prerequisite**. For local preview you need to [download/install Graphviz](https://www.graphviz.org/download/).  
And possibly `GRAPHVIS_DOT` environment variable having full path and name to `dot` executable.

### IDEA

IDEA (Ultimate and CE) has Markdown plugin that can have PlantUML support enabled.
In the **Settings/Preferences** dialog <kbd>⌘,</kbd>, 
select **Languages & Frameworks** | Markdown.
(https://www.jetbrains.com/help/idea/markdown.html#diagrams)
However that will do only sequence diagram, and all types of diagram install ["PLantUML integration" plugin](https://plugins.jetbrains.com/plugin/7017-plantuml-integration).

### Eclipse

![](images/ASCII-UML-logo.png)

This mini-site provides Eclipse update site under  
`https://ascii-uml.github.io/eclipse/`  
and [marketplace entry](https://marketplace.eclipse.org/content/ascii-uml-asciidoc-editor-plantuml-plugin)
[![Drag onto running Eclipse main toolbar. *Requires Eclipse Marketplace Client](https://marketplace.eclipse.org/sites/all/themes/solstice/public/images/marketplace/btn-install.png)](http://marketplace.eclipse.org/marketplace-client-intro?mpc_install=4120961 "Drag onto running Eclipse main toolbar. *Requires Eclipse Marketplace Client"),
that includes 2 plugins:

- Asciidoctor Editor ( <https://github.com/de-jcup/eclipse-asciidoctor-editor> )
- <http://plantuml.com/eclipse> ( <https://github.com/hallvard/plantuml> )

![](https://user-images.githubusercontent.com/11644753/40945905-039f7ddc-685b-11e8-854d-eed6b89ea3a4.png)


### VSCode
 
Several, e.g. <https://marketplace.visualstudio.com/items?itemName=jebbs.plantuml> ( <https://github.com/qjebbs/vscode-plantuml> )

![](https://raw.githubusercontent.com/qjebbs/vscode-plantuml/master/images/auto_update_demo.gif)


### Atom & VSCode

- <https://github.com/shd101wyy/markdown-preview-enhanced>
- <https://github.com/shd101wyy/vscode-markdown-preview-enhanced>
  can render within markdown, see 
[`diagrams.md`](https://github.com/shd101wyy/markdown-preview-enhanced/blob/master/docs/diagrams.md).

![](https://user-images.githubusercontent.com/1908863/33236972-4f190f98-d22a-11e7-842f-d9c4a74d2118.png)

### Web/Online

- <http://www.plantuml.com/plantuml>
- <https://www.planttext.com/>
- <http://sequencediagram.org>
- <https://www.websequencediagrams.com/>


## Links

- <https://modeling-languages.com/text-uml-tools-complete-list/#yUML>

[Edit this page](https://github.com/ascii-uml/ascii-uml.github.io/edit/master/README.md)

This mini-site is created by  
Paul Verest.  
2018-2021
