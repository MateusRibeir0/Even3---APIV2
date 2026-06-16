<div align="center">
  <img src="https://static.even3.com/content/img/logos/logo-even3-light.svg" height="48" alt="Even3" />

  <h1>Insomnia Collection</h1>

  <p>Collection pronta para importar no Insomnia e testar todos os endpoints da API pública da Even3</p>

  <br/>

  ![Insomnia](https://img.shields.io/badge/Insomnia-Compatible-4000BF?style=for-the-badge&logo=insomnia&logoColor=white)
  ![REST](https://img.shields.io/badge/REST-API-6BA539?style=for-the-badge)
  ![JSON](https://img.shields.io/badge/Response-JSON-F7B731?style=for-the-badge)
  ![Auth](https://img.shields.io/badge/Auth-Bearer_Token-E74C3C?style=for-the-badge)
</div>

---

## 📌 Sobre

Este repositório contém a **collection oficial da API pública da Even3 V2** no formato compatível com o [Insomnia](https://insomnia.rest/). Com ela, você pode testar todos os endpoints disponíveis sem precisar configurar as requisições do zero.

> 📖 Documentação completa: [thjkz9i8jw.apidog.io](https://thjkz9i8jw.apidog.io)

---

## 🔑 Autenticação

Antes de importar e usar a collection, você precisa gerar sua **chave de API** dentro da plataforma Even3.

> ⚠️ Cada evento possui sua própria chave. Certifique-se de usar a credencial correta para o evento que deseja integrar.

**Como gerar sua chave:**

**1.** Acesse o evento desejado na plataforma Even3 e abra o menu lateral → **Ferramentas**

**2.** Dentro de Ferramentas, acesse **Integrações** e selecione a opção da API Even3

**3.** Informe um nome para a integração e gere a chave de acesso

**Como usar nas requisições:**

Todas as chamadas autenticadas devem enviar a chave no header de autorização no seguinte formato:

```
Authorization: Bearer SUA_CHAVE_AQUI
```

> 🔒 Mantenha sua chave em ambiente seguro. Evite expô-la em repositórios públicos, scripts abertos ou aplicações client-side.

---

## 📥 Como importar no Insomnia

**1. Clone ou baixe este repositório**

```bash
git clone https://github.com/SEU_USUARIO/NOME_DO_REPO.git
```

Ou baixe o arquivo `.json` da collection diretamente pela interface do GitHub clicando em **Code → Download ZIP**.

**2. Abra o Insomnia**

Certifique-se de ter o [Insomnia](https://insomnia.rest/download) instalado na sua máquina.

**3. Importe a collection**

- No Insomnia, clique em **`Create`** → **`Import`**
- Selecione **`From File`**
- Navegue até o arquivo `.json` baixado neste repositório e confirme a importação

**4. Configure a autenticação**

- Acesse as configurações da collection importada
- Adicione sua chave no campo de **Bearer Token** ou configure via variável de ambiente

**5. Pronto!** Todas as requisições já estarão disponíveis para uso 🎉

---

## 📂 Endpoints disponíveis

A collection cobre os 8 grupos de recursos da API pública da Even3:

| Grupo | Descrição |
|---|---|
| 👤 **Pessoas** | Participantes e informações de inscrição |
| 🎉 **Eventos** | Dados gerais dos eventos e suas entradas |
| 💳 **Pagamentos** | Acompanhamento e detalhamento financeiro |
| 📅 **Programação** | Atividades, palestrantes e agenda |
| 📄 **Submissões** | Modalidades, áreas temáticas e apresentações |
| 🖼️ **Página do evento** | Informações estruturadas da página pública |
| ✅ **Credenciamento** | Presença e credenciamento de participantes |
| 🏅 **Certificados** | Certificados emitidos e participantes vinculados |

> Para detalhes de cada endpoint, parâmetros e exemplos de resposta, consulte a [documentação completa](https://thjkz9i8jw.apidog.io/inicio-api-2180158m0).

---
