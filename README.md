# TodoListDockerAula

Aula de monolito com docker, docker-compos e nginx.

## Instruções

1. Faça um fork deste repositório.
2. Clone o repositório para a sua máquina.
3. Siga as instruções do arquivo [Tutorial.md](Tutorial.md) para realizar a atividade.
4. Após finalizar a atividade, faça um commit e um push para o seu repositório.
5. Envie o link do seu repositório para o professor.

## Como rodar

### Hosts
Estamos usando o domínio `desweb.local` para testar a aplicação. Adicione o seguinte ao arquivo `hosts`:
```sh
127.0.0.1 desweb.local
```
> Se estiver usando WSL, o arquivo `hosts` está em `C:\Windows\System32\drivers\etc\hosts`. Você precisará editar como administrador. No Linux, o arquivo está em `/etc/hosts`.

### rodar
Alguns aquivos que deveriam estar no `.gitignore` não estão, então fica mais facil de rodar. O build esta automatico.

```sh
docker compose up
```
