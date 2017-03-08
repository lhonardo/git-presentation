#HSLIDE

## GIT

>Gerência de Projetos de Software
>Leonardo Santos

#HSLIDE
### Wikipedia:
>É um VCS (Sistema de controle de versão), monitora mudanças em arquivos e coordena o trabalho neles para um individuo ou um grupo de pessoas, é normalmente usado em desenvolvimento de software, mas também pode ser usado em qualquer tipo de arquivo.

#HSLIDE
### Linus:
![Linus](assets/LinusTorvalds.jpeg)
>Foi criado por Linus Torvalds em 2005 para uso no desenvolvimento do Kernel do Linux.

#HSLIDE
### Antes dos VCS:
#### Compartilhar código?
![Linus](assets/beforevcsflin.png)

#HSLIDE
### Antes dos VCS:
#### Histórico?
![Linus](assets/beforevcstimeline.png)

#HSLIDE
### G.I.T.:

#### Global Information Tracker
_<span style="color:gray">"Se você estiver de bom humor"</span>_


#### Goddamn idiotic truckload of sh*t":
_<span style="color:gray">"Quando não funciona"</span>_


#HSLIDE

### Motivo do nascimento:

>Um dos principais motivos foi o descontentamento do Linus com as ferramentas diponíveis na época

>_"I decided I could write something better than everything out there in two weeks. And I was right." -Linus Torvalds﻿_

#HSLIDE
### O que existia 2005?
- Perforce
- Monolitico
- CVS
- BitKeeper

#HSLIDE

### O que tinham em comum:
> Além de não serem opensource... (código aberto)

#HSLIDE

### Centralized Repository
<img src="assets/centralized-vs-distributed.png" style="max-height: 500px;"/>

#VSLIDE

### As três árvores

<img src="assets/workflow.png" style="max-height: 500px;"/>
>Modified, Staged, Committed

#VSLIDE

### Git add & Git commit

<img src="assets/commandstrees.png" style="max-height: 500px;"/>
>Modified, Staged, Committed

#VSLIDE

### Linha do Tempo

<img src="assets/timelinecommit.jpg" style="max-height: 500px;"/>

#VSLIDE

### git log

<img src="assets/gitlog.png" style="max-height: 500px;"/>

#HSLIDE
### Um pouco sobre branch
>Um branch no Git é simplesmente ponteiro móvel para um commit.

<img src="assets/branch1.png" style="max-height: 500px;"/>

#VSLIDE
### Criando um branch
```
git branch testing
```
<img src="assets/branch2.png" style="max-height: 500px;"/>

#VSLIDE
### Onde estou?
>Como o git sabe em qual branch eu estou? por outro ponteiro, o HEAD

<img src="assets/branch3.png" style="max-height: 500px;"/>

#VSLIDE
### Mudando de branch
```
git checkout testing
```
<img src="assets/branch4.png" style="max-height: 500px;"/>

#VSLIDE
### Commit
```
git add .
git commit -m 'commit em testing'
```
<img src="assets/branch5.png" style="max-height: 500px;"/>

#VSLIDE
### Voltando a master
```
git checkout master
```
<img src="assets/branch6.png" style="max-height: 500px;"/>

#VSLIDE
### Commit
```
git add .
git commit -m 'commit na master'
```
<img src="assets/branch7.png" style="max-height: 500px;"/>

#HSLIDE

### O objetivo é compartilhar!

```
git push origin master
```

#HSLIDE

### git push

<img src="assets/gitpush.gif" style="max-height: 500px;"/>

#HSLIDE

### Mas e em grupo...

<img src="assets/collaborativetimeline.jpg" style="max-height: 500px;"/>

#HSLIDE

### Conflitos
<img src="assets/merge-conflict.png" style="max-height: 500px;"/>

#HSLIDE

### Resolvendo conflitos
<img src="assets/conflict.png" style="max-height: 500px;"/>

#HSLIDE

### Junte as branchs
```
git checkout master
git pull
git merge feature
```
<img src="assets/gitmerge.gif" style="max-height: 500px;"/>

#HSLIDE

### Git branches
<img src="assets/gitbranchesbig.jpg" style="max-height: 500px;"/>

#HSLIDE

### Mantém organizado e tenta evitar...
<img src="assets/gitmergefight.gif" style="max-height: 500px;"/>

#HSLIDE
### Repo restrito
<img src="assets/github.png" style="max-height: 500px;"/>

#HSLIDE
### Fork e Pull request
<img src="assets/pullrequest.png" style="max-height: 500px;"/>

#HSLIDE
### Concluindo
#### .gitignore
```
*.class
*.log

.cache
.history
.lib/
dist/*
target/

PITCHME2.md
```

#HSLIDE
### Concluindo
#### git rebase
<img src="assets/gitrebase.png" style="max-height: 500px;"/>

#HSLIDE
### Mais informações
*try.github.io/
*Digging deep into git - Youtube
*Linus Torvalds on git at Google talk 2007 - Youtube

#HSLIDE
### git commit -a -m "Fim"

####Obrigado!
