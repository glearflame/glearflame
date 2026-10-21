# Glear flame

**Só um dev.** Linux, automação e ferramentas de terminal.

Gosto de resolver o problema que o one-liner não resolve: medir disco sem
mentir, fazer recon sem perder resultado, automatizar o que dá para
automatizar. A maior parte do que está aqui é Bash e Python, feita para rodar
em Debian/Kali.

---

### O que vale a pena olhar

**[topdirs](https://github.com/glearflame/topdirs)** · `Bash`
As maiores pastas do sistema, com caminho completo — e `--df-check`, que prova
a medição comparando com o `df`. Feito porque `du -h | sort -h | head` erra
com newline no nome, locale pt_BR, hardlink e diretório sem permissão.

**[My-system-auto-analise-](https://github.com/glearflame/My-system-auto-analise-)** · `Bash`
Framework de reconhecimento ofensivo automatizado: enumeração de subdomínios,
detecção de WAF com ajuste automático de estratégia, endpoint scoring e passive
intel. Tem CI, testes e ShellCheck limpo. *Uso apenas com autorização.*

**[pentest-kit](https://github.com/glearflame/pentest-kit)** · `Python`
GUI para orquestrar ferramentas de pentest sem decorar flag.

**[rinear-systems-painel](https://github.com/glearflame/rinear-systems-painel)** · `JavaScript`
Painel web de gestão.

**[PriceRadarBR](https://github.com/glearflame/PriceRadarBR)** · `Python`
Monitor de preços.

---

### Stack

![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Debian](https://img.shields.io/badge/Debian-A81D33?style=flat-square&logo=debian&logoColor=white)

---

<sub>Ferramentas de segurança aqui são para uso em sistemas com autorização
explícita. Não me responsabilizo por uso indevido.</sub>
