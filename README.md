# Desafio das 3 Pistas — Patrimônio do Brasil

Jogo educativo em HTML, CSS e JavaScript puro. Não precisa de banco de dados nem instalação.

## Publicar na Vercel
1. Extraia o ZIP.
2. Entre em https://vercel.com/ e escolha **Add New → Project**.
3. Importe um repositório Git com estes arquivos ou use a opção de deploy pela CLI.
4. Não é necessário framework nem comando de build: o `index.html` fica na raiz.
5. Depois do deploy, abra o endereço gerado pela Vercel.

## Recursos
- Roleta animada para sortear os desafios.
- 20 rodadas por partida, com 3 pistas por desafio.
- Pontuação: 10 pontos na primeira pista, 7 na segunda e 5 na terceira.
- Ranking local salvo no navegador (localStorage).
- Layout responsivo, com laranja e vermelho predominantes.

## Observação sobre o ranking
O ranking é salvo no navegador/dispositivo em que o jogo é utilizado. Para um ranking compartilhado entre diferentes computadores ou turmas, será necessário conectar um banco de dados, como Supabase ou Firebase.
