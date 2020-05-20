# Mouse ~~Gamer~~ Coder

Comprei essa bagaça (aproveitar o frete) e quis fazer algo útil:
![Mouse](https://http2.mlstatic.com/mouse-gamer-dazz-griffon-4000dpi-17-botoes-D_NQ_NP_733683-MLB27843797407_072018-F.webp)

### Pacotes necessários

Depende de qual botão... mas no geral:

- notify-send (libnotify-bin para o Debian)
- zenity
- code (VS Code)
- git

### Configurações necessárias

Em prol da preguiça, eu coloquei meu usuário no sudoers... Digitar a senha gasta muita energia :)

Mimimi, segurança, mimimi... Caguei, preguiça rula! :D


```bash
sudo visudo
```

Colocar:

```bash
seu_usuario ALL=(ALL) NOPASSWD:ALL
```

### E tem o que nessa joça?

- Botão 1: Nada ainda;
- Botão 2: Nada ainda;
- Botão 3: Nada ainda;
- Botão 4: Nada ainda;
- Botão 5: Nada ainda;
- Botão 6: Nada ainda;
- Botão 7: Abre um projeto no VS Code e atualiza o git dele (na branch atual);
- Botão 8: Atualiza projeto da AWS baseado no nome com o domínio;
- Botão 9: Commit e push de projeto (na branch corrente);
- Botão 10: Limpa buffer da memória e swap (pq nem todo dia é perfeito);
- Botão 11: Encerra os containers de desenvolvimento (LXC);
- Botão 12: Inicia os containers de desenvolvimento (LXC).

### Resto...

 * Na pasta aws_keys eu coloquei os .pem pra conectar o ssh dos servers