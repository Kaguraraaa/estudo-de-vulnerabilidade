# 🔐 Projeto Educacional: Aplicação Web Vulnerável com Flask

Este projeto tem como objetivo **simular vulnerabilidades comuns** encontradas em aplicações web, com fins **educacionais e demonstrativos**. Ideal para práticas de segurança, testes de penetração (pentest) e estudo de boas práticas de desenvolvimento seguro.

---

## 🚧 Aviso Importante

> ⚠️ Este sistema contém **vulnerabilidades propositalmente implementadas**.
> **Não use em produção.** Este projeto é destinado exclusivamente para fins de estudo e laboratório.

---

## 🎯 Objetivos de Aprendizagem

- ✅ Compreender falhas como **SQL Injection**, **armazenamento inseguro de senhas**, e autenticação fraca
- ✅ Aplicar ferramentas como **Burp Suite**, **OWASP ZAP** para análise dinâmica
- ✅ Refletir sobre mitigações e práticas seguras de desenvolvimento
- ✅ Documentar todo o processo e gerar uma vitrine de conhecimento no GitHub

---

## 🛠️ Tecnologias Usadas

- 🐍 Python 3
- 🌶️ Flask
- 📦 SQLite (banco de dados simples)
- 🎧 playsound / pygame (para interação com áudio, se desejado)

---

## 🚨 Vulnerabilidades Simuladas

| Vulnerabilidade        | Descrição                                                                 |
|------------------------|---------------------------------------------------------------------------|
| 🔓 Autenticação fraca  | Senhas são armazenadas em texto plano, sem validação de força ou criptografia |
| 💉 SQL Injection       | Query no login é concatenada diretamente com os dados do usuário, permitindo comandos maliciosos |
| 🔑 Chave secreta fraca | Utiliza um segredo facilmente adivinhável e exposto no código |
| 🧃 Entrada sem sanitização | Os campos de formulário não validam conteúdo, podendo aceitar scripts ou payloads maliciosos |
| 🕵️ Falta de controle de sessão | Não há verificação de tempo de sessão ou proteção contra hijacking |
