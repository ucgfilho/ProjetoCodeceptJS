# Projeto CodeceptJS – SWAPI

Testes automatizados de API utilizando **CodeceptJS** na **Star Wars API (SWAPI)**.

## Tecnologias

- **Node.js 18+**
- **CodeceptJS**
- **REST & JSONResponse Helpers**
- **Allure Reports**
- **Mochawesome**

## Instalação

```bash
npm install
```

## Como executar

### Rodar testes com passos no console
```bash
npx codeceptjs run --steps
```

### Relatórios

#### Allure
```bash
npx codeceptjs run --plugins allure
```

```bash
npx allure serve allure-results
```

#### Mochawesome
Gera `mochawesome-report/mochawesome.html`:
```bash
npx codeceptjs run --reporter mochawesome
```

## Estrutura

- **codecept.conf.js** — configurações gerais
- **people_test.js** — cenários da SWAPI
- **output/** — logs
- **allure-results/** — artefatos Allure
- **mochawesome-report/** — relatório HTML