Este repositório contém o projeto base fornecido pelo professor, desenvolvido em **TypeScript** para prática de versionamento com **Git** e **GitHub**.

---

## Requisitos do Projeto

De acordo com o arquivo `requisitos.MD`, o sistema deve implementar as seguintes funcionalidades:

- [x] Criar um objeto a partir da classe **Veículo**
- [x] Criar veículo
- [ ] Imprimir o veículo
- [ ] Acelerar
- [ ] Frear
- [ ] Subir marcha
- [ ] Reduzir marcha

---

## Como executar o projeto

1. Instale as dependências:
   ```bash
   npm install
   ```

2. Compile o projeto TypeScript ou execute diretamente com `ts-node`:
   ```bash
   npx ts-node index.ts
   ```

3. Siga as instruções no terminal para interagir com o programa.

---

## Fluxo de Trabalho (Git)

- Branch principal: `main`
- Branch de desenvolvimento: `dev`
- Funcionalidades criadas em branches do tipo:
  ```
  feature/nome-da-funcionalidade
  ```

Exemplo de comandos usados:
```bash
git checkout -b feature/nova-funcionalidade
git add .
git commit -m "Implementação da nova funcionalidade"
git push origin feature/nova-funcionalidade
```

Depois é aberto um **Pull Request** para `dev`.

---

## Equipe

- **Membro 1** – Murilo Viana
- **Membro 2** – Erick Silva

---

## 📷 Evidências de Entrega

- https://github.com/murilorviana/RepositorioES2
