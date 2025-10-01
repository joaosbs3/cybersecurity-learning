# 🔐 EFS — Encrypting File System (Windows)

## 📌 O que é
Recurso do Windows para criptografar arquivos/pastas/volumes ligados a uma conta de usuário.

## ✅ Características
- Criptografia ligada à conta do usuário: somente quem encriptou (ou chaves de recuperação) consegue acessar.
- Ideal para proteger dados em notebooks/estação de trabalho.

## ℹ️ Como usar (resumo)
- Clique com o botão direito no arquivo/pasta → Propriedades → Avançado → "Criptografar conteúdo para proteger dados".
- Gerencie certificados/chaves com `certmgr.msc` e exporte a chave de recuperação.

## 📝 Cuidados
- Faça backup das chaves (exportar certificado) — perda da chave = perda dos dados.
