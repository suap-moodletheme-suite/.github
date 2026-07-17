# SUAP Moodle Theme Suite 🎓

Bem-vindo à **SUAP Moodle Theme Suite**! 

Esta organização reúne tema e plugins Moodle desenvolvidos para integrar a experiência visual e funcional do Moodle com o ecossistema do **SUAP (Sistema Unificado de Administração Pública)** do **IFRN (Instituto Federal do Rio Grande do Norte)**.

Para integrador, Painel AVA ou aplicativo mobile veja a [Suap AVA Suite](https://suap-ava-suite.github.io/).

🌐 **Documentação Oficial e Portal da Suíte:** [https://suap-moodletheme-suite.github.io/](https://suap-moodletheme-suite.github.io/)

---

## 📦 Componentes da Suíte

A suíte é composta de forma modular por repositórios independentes, seguindo o padrão do Moodle:

| Repositório                                                                                                 | Descrição                                                                                     | Status      |
| :---------------------------------------------------------------------------------------------------------- | :-------------------------------------------------------------------------------------------- | :---------: |
| 🎨 [**moodle-theme_suap**](https://github.com/suap-moodletheme-suite/moodle-theme_suap)                     | Tema principal com a identidade visual do SUAP/IFRN, customizando layout, tipografia e cores. |  Ativo      |
| 🖼️ [**moodle-block_course_gallery**](https://github.com/suap-moodletheme-suite/moodle-block_course_gallery) | Bloco Moodle para exibição de uma galeria visual de cursos e navegação facilitada.            |  Ativo      |
| ⭐ [**moodle-block_course_rating**](https://github.com/suap-moodletheme-suite/moodle-block_course_rating)   | Bloco para avaliação e classificação de cursos pelos estudantes.                              |  Ativo      |
| ℹ️ [**moodle-block_site_info**](https://github.com/suap-moodletheme-suite/moodle-block_site_info)           | Bloco para exibição de informações institucionais, avisos, horários e contatos.               |  Ativo      |
| 💡 [**moodle-block_recommendation**](https://github.com/suap-moodletheme-suite/moodle-block_recommendation) | Bloco para recomendação personalizada de cursos e conteúdos com base no perfil.               | 🚧 Em breve |

---

## 🚀 Instalação Rápida

Os componentes da suíte seguem o padrão nativo de plugins do Moodle e podem ser instalados de duas formas:

### 📦 Opção 1: Via Interface de Administração (ZIP Release)
1. Acesse a aba **Releases** no repositório do tema ou bloco desejado e baixe o arquivo `.zip` da versão mais recente.
2. No Moodle, navegue até **Administração do site → Plugins → Instalar plugins**.
3. Faça o upload do arquivo `.zip` e siga as instruções na tela para concluir a instalação.

### 💻 Opção 2: Instalação Manual no Servidor (ZIP Release)
1. Acesse a aba **Releases** do repositório desejado e faça o download do arquivo `.zip`.
2. Extraia o conteúdo diretamente no diretório correspondente da sua instalação Moodle:
   - **Tema SUAP:** Extraia na pasta `theme/suap`
   - **Blocos Complementares:** Extraia na pasta `blocks/<nome_do_bloco>` (exemplo: `blocks/course_gallery`)
3. Acesse **Administração do site → Notificações** para executar a atualização do banco de dados e em seguida ative o tema em **Aparência → Temas → Seletor de temas**.

---

## 📜 Licença e Comunidade

- **Licença:** Open Source sob a licença **GPL-3.0**.
- **Instituição:** Instituto Federal do Rio Grande do Norte (IFRN).
- **Documentação:** Visite [https://suap-moodletheme-suite.github.io/](https://suap-moodletheme-suite.github.io/) para obter mais informações e guias.
