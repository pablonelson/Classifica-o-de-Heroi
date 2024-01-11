# Classificador de Heróis

Este projeto consiste em um código JavaScript para classificar heróis com base em seus níveis de experiência (XP). O código atribui diferentes categorias de níveis, como Ferro, Bronze, Prata, Ouro, Platina, Diamante, Ascendente, Imortal e Radiante, com base em valores específicos de XP.

## Estrutura do Projeto

O projeto é composto por um arquivo JavaScript (`classificador_heroi.js`) que contém as funções necessárias para realizar a classificação de heróis.

### Arquivos no Projeto

- `classificador_heroi.js`: Contém a implementação do classificador de heróis.
- `exemplo_uso.html`: Página HTML para demonstrar o uso do classificador com diferentes valores de XP.

## Como Usar

Para utilizar o classificador de heróis em seu próprio projeto, siga as instruções abaixo:

1. **Inclusão do Script:**
   - Adicione o script `classificador_heroi.js` ao seu projeto.

   ```html
   <script src="caminho/para/classificador_heroi.js"></script>
   ```

2. **Chamada da Função:**
   - Utilize a função `classificarNivelHeroi(xp)` para classificar heróis com base em seus XP.

   ```javascript
   const xpDoHeroi = 5000;
   const resultadoClassificacao = classificarNivelHeroi(xpDoHeroi);
   console.log(`XP: ${xpDoHeroi} - Classificação: ${resultadoClassificacao}`);
   ```

## Configuração dos Níveis

Os limites de XP para cada nível são definidos no objeto `limitesXP` no arquivo `classificador_heroi.js`. Modifique esses valores conforme necessário para ajustar os critérios de classificação de acordo com os requisitos do seu projeto.

```javascript
const limitesXP = {
  ferro: 1000,
  bronze: 2000,
  prata: 3000,
  ouro: 4000,
  platina: 5000,
  diamante: 6000,
  ascendente: 7000,
  imortal: 8000,
  radiante: 9000
};
```

## Exemplo de Uso

O arquivo `exemplo_uso.html` demonstra como utilizar o classificador de heróis com diferentes valores de XP.

## Contribuições

Contribuições são bem-vindas! Se você encontrar problemas, melhorias ou novos recursos que podem ser adicionados ao projeto, sinta-se à vontade para criar uma _issue_ ou enviar um _pull request_.

## Licença

Este projeto é distribuído sob a licença MIT. Consulte o arquivo [LICENSE](LICENSE) para obter detalhes.

---

Esperamos que este classificador de heróis seja útil para as suas necessidades de classificação com base nos níveis de experiência. Caso tenha alguma dúvida ou sugestão, não hesite em entrar em contato.

**Equipe de Desenvolvimento**
