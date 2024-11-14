# The Dev Machine - A Máquina do Dev

Esta é uma coleção de scripts que auxiliam o desenvolvedor a configurar sua máquina.

Para configurar sua máquina execute o comando abaixo:
```
curl -s https://raw.githubusercontent.com/Hibex-Solutions/TheDevMachine/refs/heads/main/the-dev-machine-init.sh | sudo bash -s
```

> ⚠️ CUIDADO! Você estará executando o comando como super usuário!

## Premissas do projeto

- O desenvolvedor deve ser administrador da sua própria máquina
- Pretendemos apenas "perder menos tempo" com a tarefa de configurar a própria máquina
- Não abstraímos ou consolidamos erros, apenas o exibimos como o script faz

## Não objetivos do projeto

- Não pretendemos ser um gerenciador de pacotes ou meta-pacotes
- Não esperamos que a configuração ocorra sem iteração do próprio desenvolvedor
- Não pretendemos comprovar que os scripts são seguros.
  - Só o fato de disponibilizar o código fonte já dá a cada a capacidade de validar
 
## Créditos e agradecimentos

- Nosso script inicial é fortemente baseado no script `rustup-init.sh` do [projeto Rustup][RUSTUP_SCRIPT]
  - Obrigado [projeto Rustup][RUSTUP_SCRIPT]!
- Também nos baseamos muito nas ideias de execução de scripts do [projeto Oh My Posh][OHMYPOSH]
  - Obrigado [Jan De Dobbeleer](https://github.com/JanDeDobbeleer)!

<!-- links -->
[RUSTUP_SCRIPT]: https://github.com/rust-lang/rustup/blob/master/rustup-init.sh
[OHMYPOSH]: https://github.com/jandedobbeleer/oh-my-posh
