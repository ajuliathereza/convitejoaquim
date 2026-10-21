# Convite do Joaquim — Minha primeira volta ao sol

Versão temática baseada na referência enviada: azul-céu, branco, amarelo-sol e detalhes laranja.

## O que foi preservado
- Envelope animado e abertura do convite por toque/clique;
- Música que começa depois de abrir o envelope, com controle de pausar/continuar;
- Vídeo no topo, com arte de reserva quando o vídeo não está disponível;
- Contagem regressiva;
- Confirmação de presença via WhatsApp;
- Botão de mapa;
- Modal com sugestões de presentes;
- Botão do álbum (por enquanto mostra “em breve” enquanto o link estiver vazio);
- Colagem solar animada ao redor da ilustração do Joaquim; as figurinhas clicáveis viram corações amarelos; contador/progresso do mini-jogo; mensagem reposicionada abaixo da imagem para não cobrir os pés;
- Efeitos de celebração e layouts responsivos.

## Colagem interativa
Na área final do convite, o Joaquim aparece como um recorte sobre um fundo de colagens em movimento. Toque nas oito figurinhas ao redor dele para transformá-las em corações amarelos. A barra e o contador mostram o progresso; ao encontrar todas, aparece uma celebração. A frase principal foi reposicionada abaixo da imagem para não cobrir os pés. O recorte transparente usado na página está em `assets/images/joaquim-sol.png`; a imagem original foi mantida como `joaquim-sol.jpg`.

## Música
A música enviada foi incluída em `assets/audio/minha-volta-ao-sol.mp3`.

## Vídeo
Quando terminar seu vídeo, salve-o em `assets/videos/joaquim-volta-ao-sol.mp4`. O caminho já está configurado no `index.html`.

## Para abrir
Abra a pasta no VS Code e use a extensão Live Server, ou publique a pasta inteira em seu serviço de hospedagem. Mantenha `index.html`, `style.css`, `script.js` e a pasta `assets` juntos.

## Dados da festa
Nome, data, horário, endereço, WhatsApp, texto da confirmação e links ficam no bloco `const convite` no início de `script.js`. Os dados de data/local/telefone foram mantidos do código original fornecido.



