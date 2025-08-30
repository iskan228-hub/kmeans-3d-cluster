# 🤝 Guia de Contribuição

Obrigado por contribuir com este projeto!  
Aqui estão algumas regras e boas práticas para mantermos o repositório organizado e padronizado.

---

## 📌 Fluxo de Trabalho (Workflow)

1. **Sempre crie uma branch** para suas alterações:
   ```bash
   git checkout -b feat/nome-da-feature
   ```
2. Faça commits pequenos e claros.
3. Abra um **Pull Request (PR)** descrevendo suas alterações.
4. Relacione o PR a uma **issue**, quando aplicável (`closes #número-da-issue`).

---

## 📝 Convenções de Commit

Adotamos o padrão **Conventional Commits**:

| Tipo        | Uso                                                                 | Exemplo |
|-------------|---------------------------------------------------------------------|---------|
| **feat**    | Nova funcionalidade                                                 | `feat(kmeans): adicionar visualização 3D` |
| **fix**     | Correção de bug                                                     | `fix(data-cleaning): corrigir tratamento de nulos` |
| **docs**    | Mudança apenas em documentação                                      | `docs: atualizar README com instalação` |
| **style**   | Ajustes de formatação (sem impacto no código)                       | `style: padronizar aspas simples` |
| **refactor**| Refatoração sem alterar comportamento                               | `refactor: extrair função de cálculo de distância` |
| **test**    | Inclusão ou alteração de testes                                     | `test: criar casos para normalização` |
| **chore**   | Tarefas de manutenção, configs, builds                              | `chore: atualizar dependências no requirements.txt` |
| **perf**    | Melhorias de performance                                            | `perf: otimizar loop de clusterização` |
| **build**   | Alterações em build ou dependências externas                        | `build: configurar pipeline de deploy` |
| **ci**      | Alterações em integração contínua                                   | `ci: corrigir workflow do GitHub Actions` |
| **revert**  | Reversão de commit anterior                                         | `revert: desfazer alteração no gráfico` |

---

## 🔖 Issues e Milestones

- Cada nova tarefa deve estar vinculada a uma **issue**.
- Agrupe issues relacionadas em **milestones** (ex.: “Entrega B1”).
- Use **labels** para classificação (bug, enhancement, documentation, etc.).

---

## 📂 Estrutura do Projeto

```
kmeans-3d-cluster/
│── data/           # Dados brutos e processados
│── docs/           # Documentação do projeto
│── models/         # Modelos gerados
│── notebooks/      # Notebooks Jupyter
│── src/            # Código-fonte
│── README.md       # Descrição do projeto
│── CONTRIBUTING.md # Guia de contribuição (este arquivo)
```

---

## ✅ Checklist antes de abrir um PR

- [ ] Código testado e funcionando.  
- [ ] Commits no padrão definido.  
- [ ] Issue relacionada foi referenciada (`closes #n`).  
- [ ] Documentação atualizada, se necessário.  

---

✍️ **Dúvidas ou sugestões?**  
Abra uma [issue](../../issues) ou entre em contato com os mantenedores.
