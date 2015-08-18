# Instruções
Isto é um quick tutorial para usar o git no terminal.

Corrijam-me se houver alguma coisa em falta ;)

## Para criar repositório local:

```git clone https://github.com/lribeirogomes/geo```

## Para copiar repositório remoto (sobrescrevendo repositório local):

```git fetch --all```

```git reset --hard origin/master```

## Para publicar ficheiros no repositório remoto:

```git status``` , para verificar os ficheiros que foram alterados

```git add``` (meter a localização dos ficheiros que mudaste)

ou ```git remove``` (meter a localização ficheiros que eliminaste)

```git status``` , para verificar se ainda há ficheiros por aderir/remover

```git commit -m``` "(mensagem do commit, que explica e justifica as alterações efectuadas)"

```git push```

## Se ```git push``` for aceite:

 - Notificar restantes membros

## Se ```git push``` for rejeitado:

```git fetch```

```git rebase```

## Se rebase detectar inconsistências:

```git status``` , para verificar os ficheiros que estão em conflito

ver ficheiro e corrigir inconsistências (entre as linhas <<<<<<< e >>>>>>>)

```git add``` (meter a localização dos ficheiros que corrigiste)

```git rebase --continue``` , para verificar se ainda existem inconsistências

## Por fim, se ```git push``` for aceite:

 - Notificar restantes membros

# Atenção !!!

Não fazer ```git fork```, para simplificar a sincronização e leitura dos repositórios.

