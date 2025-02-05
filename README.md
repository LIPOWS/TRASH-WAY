# TRASH WAY

Projeto desenvolvido no curso **Academia Mastertech** da **Estação Hack from Facebook**, ministrado pela **Mastertech**.

## 📌 Sobre o Projeto
O **TRASH WAY** é um sistema desenvolvido em **Django** com o objetivo de facilitar o descarte correto de materiais recicláveis e promover a doação de móveis e eletrodomésticos.

### 🔹 Funcionalidades
- **Mapa de Ecopontos:** Exibe todos os ecopontos cadastrados no Brasil.
- **Localização Inteligente:** O usuário pode inserir um endereço, e o sistema encontra o ecoponto mais próximo e traça a rota até ele.
- **Doação de Móveis e Eletrodomésticos:** Uma lista de itens disponíveis para doação, permitindo que interessados entrem em contato diretamente com os doadores.
- **Integração com Google Maps API:** O mapeamento e a rota são gerados utilizando a API do Google Maps.

## 🛠 Tecnologias Utilizadas
- **Front-end:** HTML, CSS, JavaScript
- **Back-end:** Python, Django
- **Mapa:** API do Google Maps (implementado em JavaScript)

## 🚀 Como Executar o Projeto
### 📌 Requisitos
- Python 3.x
- Django
- Conta e chave de API do Google Maps

### 📌 Passos para Rodar o Projeto
1. Clone o repositório:
   ```sh
   git clone https://github.com/seu-usuario/trash-way.git
   cd trash-way
   ```
2. Crie e ative um ambiente virtual:
   ```sh
   python -m venv venv
   source venv/bin/activate  # Linux/macOS
   venv\Scripts\activate  # Windows
   ```
3. Instale as dependências:
   ```sh
   pip install -r requirements.txt
   ```
4. Configure as variáveis de ambiente e sua chave da API do Google Maps
5. Aplique as migrações e execute o servidor:
   ```sh
   python manage.py migrate
   python manage.py runserver
   ```
6. Acesse no navegador:
   ```
   http://127.0.0.1:8000/
   ```

## 📄 Licença
Este projeto está sob a licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 💡 Sobre o Curso
O **Estação Hack from Facebook** é um programa de formação promovido pelo Facebook em parceria com a **Mastertech**, oferecendo capacitação em tecnologia e inovação. Durante o curso, aprendemos:
- Desenvolvimento Full Stack
- HTML, CSS, JavaScript
- Python e Django
- Design Thinking
- Metodologias Ágeis

## ✨ Créditos
Projeto desenvolvido por:
- Felipe Daniel de Souza
- Daniel Pereira da Silva
- Mayara Assef Cotrim
- Lucas Felipe Campos Miranda
- Alexandre Jácobo Goebbels

Mastertech - Estação Hack from Facebook.

