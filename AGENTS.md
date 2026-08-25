# Soc Ops: instrucoes para agentes

## Checklist obrigatorio

- Lint: nao ha plugin de lint configurado; verifique warnings e estilo nas alteracoes.
- Build: `cd socops && ./mvnw clean package`
- Testes: `cd socops && ./mvnw test`
- UI: para mudancas web, execute `cd socops && ./mvnw spring-boot:run` e verifique `http://localhost:8080/`.

## Projeto

- Jogo Social Bingo em Spring Boot 3.4.2, Java 21, Maven Wrapper e JUnit 5.
- Thymeleaf: `socops/src/main/resources/templates/game.html`.
- CSS utilitario local: `socops/src/main/resources/static/css/app.css`; nao adicione Tailwind sem necessidade.
- `BingoRestController` serve `/` e `GET /api/bingo/fresh-board`.
- `BoardAssembler` concentra a logica pura do tabuleiro, alternancia de celulas e deteccao de vitorias.
- Modelos, prompts e testes ficam em `socops/src/main/java/com/socops/model/`, `socops/src/main/java/com/socops/data/` e `socops/src/test/java/`.

## Convencoes

- Siga os padroes existentes e evite dependencias ou abstracoes desnecessarias.
- Cubra novas regras com testes unitarios proximos de `BoardAssemblerTests`.
- Preserve o fluxo lobby -> jogo e a grade responsiva 5x5.
- Consulte [CSS utilities](.github/instructions/css-utilities.instructions.md), [frontend design](.github/instructions/frontend-design.instructions.md), [README.md](README.md) e [workshop/GUIDE.md](workshop/GUIDE.md) antes de duplicar orientacoes.
- Nao altere deploy ou documentacao multilingue sem necessidade.
