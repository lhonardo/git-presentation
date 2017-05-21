## GIT

>Gerência de Projetos de Software
>Leonardo

---

### Wikipedia:
>É um VCS (Sistema de controle de versão), monitora mudanças em arquivos e coordena o trabalho neles para um individuo ou um grupo de pessoas, é normalmente usado em desenvolvimento de software, mas também pode ser usado em qualquer tipo de arquivo.

---

### Linus:
![Linus](assets/LinusTorvalds.jpeg)
>Foi criado por Linus Torvalds em 2005 para uso no desenvolvimento do Kernel do Linux.

---

### Antes dos VCS:
#### Compartilhar código?
![Linus](assets/beforevcsflin.png)

---

### Antes dos VCS:
#### Histórico?
![Linus](assets/beforevcstimeline.png)

---

### G.I.T.:

#### Global Information Tracker
_<span style="color:gray">"Se você estiver de bom humor"</span>_


#### Goddamn idiotic truckload of sh*t":
_<span style="color:gray">"Quando não funciona"</span>_

---

### Motivo do nascimento:

>Um dos principais motivos foi o descontentamento do Linus com as ferramentas diponíveis na época

>_"I decided I could write something better than everything out there in two weeks. And I was right." -Linus Torvalds﻿_

---

### O que existia em 2005?
- Perforce
- Monolitico
- CVS
- BitKeeper

---

### O que tinham em comum:
> Além de não serem opensource... (código aberto)

---

### Centralized Repository
<img src="assets/centralized-vs-distributed.png" style="max-height: 500px;"/>

+++

### As três árvores

<img src="assets/workflow.png" style="max-height: 500px;"/>
>Modified, Staged, Committed

+++

### Git add & Git commit

<img src="assets/commandstrees.png" style="max-height: 500px;"/>
>Modified, Staged, Committed

+++

### Linha do Tempo

<img src="assets/timelinecommit.jpg" style="max-height: 500px;"/>

+++

### git log

<img src="assets/gitlog.png" style="max-height: 500px;"/>

---

### Um pouco sobre branch
>Um branch no Git é simplesmente ponteiro móvel para um commit.

<img src="assets/branch1.png" style="max-height: 500px;"/>

+++

### Criando um branch
```
git branch testing
```
<img src="assets/branch2.png" style="max-height: 500px;"/>

+++

### Onde estou?
>Como o git sabe em qual branch eu estou? por outro ponteiro, o HEAD

<img src="assets/branch3.png" style="max-height: 500px;"/>

+++

### Mudando de branch
```
git checkout testing
```
<img src="assets/branch4.png" style="max-height: 500px;"/>

+++

### Commit
```
git add .
git commit -m 'commit em testing'
```
<img src="assets/branch5.png" style="max-height: 500px;"/>

+++

### Voltando a master
```
git checkout master
```
<img src="assets/branch6.png" style="max-height: 500px;"/>

+++

### Commit
```
git add .
git commit -m 'commit na master'
```
<img src="assets/branch7.png" style="max-height: 500px;"/>

---

### O objetivo é compartilhar!

```
git push origin master
```

---

### git push

<img src="assets/gitpush.gif" style="max-height: 500px;"/>

---

### Mas e em grupo...

<img src="assets/collaborativetimeline.jpg" style="max-height: 500px;"/>

---

### Conflitos
<img src="assets/merge-conflict.png" style="max-height: 500px;"/>

---

### Resolvendo conflitos
<img src="assets/conflict.png" style="max-height: 500px;"/>

---

### Junte as branchs
```
git checkout master
git pull
git merge feature
```
<img src="assets/gitmerge.gif" style="max-height: 500px;"/>

---

### Git branches
<img src="assets/gitbranchesbig.jpg" style="max-height: 500px;"/>

---

### Mantém organizado e tenta evitar...
<img src="assets/gitmergefight.gif" style="max-height: 500px;"/>

---

### Repo restrito
<img src="assets/github.png" style="max-height: 500px;"/>

---

### Fork e Pull request
<img src="assets/pullrequest.png" style="max-height: 500px;"/>

---

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

---

### Concluindo
#### git rebase
<img src="assets/gitrebase.png" style="max-height: 500px;"/>

---

### Mais informações
* try.github.io/
* Digging deep into git - Youtube
* Linus Torvalds on git at Google talk 2007 - Youtube

---

### git commit -a -m "Fim"

####Obrigado!
