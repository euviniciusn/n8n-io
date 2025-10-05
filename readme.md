# n8n Docker Deployment 🚀

Instalação automatizada do n8n com PostgreSQL via Docker Compose.

## ⚡ Quick Start

### Requisitos
- Docker instalado
- Portainer instalado
- Portas 5678 disponível

### Como usar este repositório

1. **No Portainer:**
   - Vá em Stacks → Add Stack → Repository
   - Cole a URL deste repositório
   - Configure as variáveis de ambiente
   - Deploy!

2. **Variáveis obrigatórias:**
   - `N8N_ENCRYPTION_KEY`: Chave de 32+ caracteres
   - `JWT_SECRET`: Secret para JWT
   - `POSTGRES_PASSWORD`: Senha do banco

### Primeiro acesso
- URL: http://seu-ip:5678
- Crie o usuário administrador

### Suporte
- [Documentação n8n](https://docs.n8n.io)
- [Community Forum](https://community.n8n.io)

## 📝 Licença

Este deployment é open source. O n8n possui sua própria licença.
