# 🔐 Password Strength Analyzer
<img width="1031" height="347" alt="image" src="https://github.com/user-attachments/assets/f6a9fd9c-9a1e-4b0b-97c0-b4d1f77a0686" />


Analisador de força de senhas que verifica complexidade e checa se a senha foi vazada em violações de dados.

## 🎯 Sobre

Projeto de cybersecurity que avalia a segurança de senhas através de múltiplos critérios e integração com a API Have I Been Pwned.

**Verificações realizadas:**
- Comprimento mínimo (8+ caracteres)
- Letras maiúsculas e minúsculas
- Números e caracteres especiais
- Consulta em banco de senhas vazadas

  <img width="1065" height="682" alt="image" src="https://github.com/user-attachments/assets/f3049177-4317-43af-a7d8-91e5f1de29de" />


## 🚀 Instalação

```bash
git clone https://github.com/theycallmefreire/password-strength-analyzer.git
cd password-strength-analyzer
pip install -r requirements.txt
```

## 💻 Uso

```bash
python main.py
```

Digite sua senha e receba feedback instantâneo com pontuação e sugestões de melhoria.

## 🔒 Segurança

A integração com Have I Been Pwned usa o método **k-anonymity**:
- Sua senha nunca é enviada completa
- Apenas 5 caracteres do hash SHA-1 são transmitidos
- Comparação feita localmente

## 🛠️ Tecnologias

- Python 3.x
- Requests (API calls)
- Hashlib (SHA-1 hashing)
