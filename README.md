# ☀️ Sistema de Check-in - Comunidade Terra do Sol

![Project Status](https://img.shields.io/badge/status-active-success)
![License](https://img.shields.io/badge/license-MIT-blue)

Um sistema completo e moderno para cadastro social e gestão de famílias, desenvolvido com foco em usabilidade, performance e design limpo. O projeto permite o cadastro detalhado de núcleos familiares (pai, mãe, filhos, endereço), upload de fotos e possui uma área administrativa segura para gestão dos dados.

## 🚀 Tecnologias Utilizadas

O projeto foi construído com uma stack moderna e robusta:

* **Frontend:** [Next.js 14+](https://nextjs.org/) (App Router)
* **Linguagem:** [TypeScript](https://www.typescriptlang.org/)
* **Estilização:** [Tailwind CSS](https://tailwindcss.com/)
* **Ícones:** [FontAwesome](https://fontawesome.com/)
* **Banco de Dados & Auth:** [Supabase](https://supabase.com/)
* **Alertas/Modais:** [SweetAlert2](https://sweetalert2.github.io/)

---

## ✨ Funcionalidades

### 🏠 Para o Público (Formulário)
* **Cadastro Completo:** Registro de Pai, Mãe e Endereço.
* **Gestão de Filhos:** Adição dinâmica de filhos com dados escolares.
* **Logica Condicional:** Campos se adaptam conforme as respostas (ex: se trabalha, pede renda; se não mora, pede endereço).
* **Upload de Fotos:** Envio da foto da fachada da casa direto para a nuvem.
* **UX Aprimorada:** Feedback visual de carregamento e sucesso.

### 🔒 Área Administrativa (Restrita)
* **Login Seguro:** Autenticação via e-mail e senha.
* **Dashboard Visual:** Visualização dos cadastros em cards elegantes.
* **Busca Inteligente:** Filtro em tempo real por nome (pai/mãe/filho) ou bairro, ignorando acentos.
* **Edição Completa:** Modal para alterar dados e substituir fotos.
* **Exclusão:** Remoção segura de registros.

## 🛠️ Como Rodar o Projeto

### Pré-requisitos
* Node.js instalado (v18 ou superior).
* Uma conta no [Supabase](https://supabase.com/).

### Passo a Passo

1.  **Clone o repositório:**
    ```bash
    git clone https://github.com/Poliih/sun-land
    cd sun-land
    ```

2.  **Instale as dependências:**
    ```bash
    npm install
    # ou
    yarn install
    ```

3.  **Configure as Variáveis de Ambiente:**
    Crie um arquivo `.env.local` na raiz do projeto e adicione suas chaves do Supabase:
    ```env
    NEXT_PUBLIC_SUPABASE_URL=sua_url_do_supabase
    NEXT_PUBLIC_SUPABASE_PUBLISHABLE_DEFAULT_KEY=sua_chave_anonima
    ```

4.  **Rode o servidor de desenvolvimento:**
    ```bash
    npm run dev
    ```
    Acesse `http://localhost:3000` no seu navegador.

---

## 🤝 Contribuição

Contribuições são bem-vindas! Se você tiver sugestões de melhorias:

---

## 📄 Licença

Distribuído sob a licença MIT. Veja `LICENSE` para mais informações.


<p align="center">
Desenvolvido com 💜 por <strong>Poliana Rodrigues</strong>
</p>

