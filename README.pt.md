# digitallife（数字人生）

[English](README.md) · [简体中文](README.zh.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Français](README.fr.md) · [Deutsch](README.de.md) · [Español](README.es.md) · **Português**

> Um monitor de atividade nativo para macOS —— **todos os seus dados permanecem no seu próprio Mac.**

O digitallife regista discretamente o que acontece no seu Mac no dia a dia: que aplicações usa e durante quanto tempo, o consumo de rede e de bateria/energia, as alterações de ficheiros, as aplicações instaladas e removidas… e apresenta tudo através de uma elegante aplicação nativa da barra de menus, em relatórios diários / semanais / mensais claros. Sem nuvem, sem conta, nada é enviado.

---

## 📸 Capturas de tela

<p align="center">
  <img src="images/en/01-overview.png" width="49%" alt="Overview">
  <img src="images/en/02-report.png" width="49%" alt="Report">
</p>
<p align="center">
  <img src="images/en/03-files.png" width="49%" alt="Files">
  <img src="images/en/04-apps.png" width="49%" alt="Apps">
</p>
<p align="center">
  <img src="images/en/05-clean.png" width="49%" alt="Clean">
  <img src="images/en/06-data.png" width="49%" alt="Data">
</p>

---

## ✨ O que pode ver

- **Tempo de utilização das aplicações** e classificações diárias (com ícones)
- **Tendências de bateria e energia**, classificação de consumo energético por aplicação (opcional)
- **Tráfego de rede** por aplicação
- **Atividade de ficheiros**: criados / eliminados / modificados —— pasta, tipo e aplicação de origem
- Tabela dos maiores consumos de **CPU / memória**
- **Títulos de janelas e tempo inativo**, aplicações da barra de menus / residentes em segundo plano
- Histórico de **instalação / desinstalação** de aplicações
- **Análise do espaço em disco** (localização de pastas / ficheiros grandes) e **limpeza de ficheiros desnecessários**
- **Relatórios diários / semanais / mensais**, tempo de ecrã comparado com o período anterior
- Os dados podem ser apagados por dia / categoria, com **exportação JSON / CSV**

---

## 💻 Requisitos do sistema

- **macOS 13 (Ventura) ou posterior**
- **Apple Silicon** (chip da série M)

---

## ⬇️ Transferência e instalação

1. Transfira a `DigitalLife-<versão>.dmg` mais recente a partir de **[Releases](https://github.com/Link-X/digitallife-releases/releases/latest)**
2. Abra o DMG e **arraste «数字人生» para «Aplicações»**
3. **Faça duplo clique para abrir** —— a aplicação está **autenticada (notarized) pela Apple**, pelo que não surge qualquer bloqueio de «danificada» / «programador não verificado», nem é necessário «clique com o botão direito → Abrir»
4. Após o primeiro arranque, abra «权限设置…» (Permissões) a partir da barra de menus e conceda as permissões do sistema conforme indicado

### Permissões (conceda conforme necessário; se faltar uma, apenas a função correspondente fica limitada, mais nada)

| Permissão | Utilização |
|------|------|
| Acesso Total ao Disco | Histórico do navegador, etc. |
| Acessibilidade | Identificar a aplicação em primeiro plano |
| Gravação de Ecrã | Ler títulos de janelas (**não são feitas capturas de ecrã**) |
| Automatização (Eventos do Sistema) | Aplicação / janela em primeiro plano |

---

## 🔒 Privacidade

É aquilo com que o digitallife mais se preocupa:

- **100 % dos seus dados permanecem localmente**, gravados numa base de dados no seu próprio Mac, **sem qualquer transmissão pela rede**
- **O único pedido de rede** ocorre quando **clica manualmente em «Procurar atualizações»** —— apenas obtém um número de versão e não envia nenhum dos seus dados; de resto, a aplicação está totalmente offline
- Para maior proteção, pode **ativar a encriptação da base de dados** nas definições (a chave é guardada no porta-chaves do sistema)

---

## 🔄 Procurar atualizações

Menu da aplicação **«关于数字人生» (Acerca de) → «检查更新» (Procurar atualizações)**: clique manualmente uma vez; se existir uma versão mais recente, será notificado com uma ligação de transferência. Sem sondagem em segundo plano nem transferências automáticas.

---

## 📄 Licença

**Software proprietário · Todos os direitos reservados (All Rights Reserved)** — Copyright © 2026 许道斌 (Daobin Xu).

- **O código-fonte é fechado**: exceto o autor, não é permitida qualquer utilização, cópia, modificação, engenharia inversa ou distribuição do código-fonte sem autorização prévia por escrito. **«Visível» não significa «utilizável».**
- **Aplicação oficial gratuita para uso não comercial**: os particulares (estudo / investigação / lazer), as organizações sem fins lucrativos, as instituições de ensino e investigação e os organismos governamentais podem **utilizar gratuitamente** a aplicação assinada e autenticada, não modificada, publicada oficialmente neste repositório.
- **Canal oficial, apenas uso próprio**: transfira a partir dos [Releases](https://github.com/Link-X/digitallife-releases/releases/latest) deste repositório para seu próprio uso; **a redistribuição, o reencaminhamento, a cópia, a modificação e a engenharia inversa são proibidos.**
- **O uso comercial requer autorização**: qualquer uso comercial —— **incluindo a utilização por uma organização com fins lucrativos (empresa / companhia) no âmbito da sua atividade, mesmo que seja de uso estritamente interno pelos seus colaboradores** —— requer autorização prévia por escrito.

> «Não comercial» significa uma utilização que não se destina principalmente a vantagem comercial ou compensação monetária: uso pessoal, organizações sem fins lucrativos, instituições de ensino e investigação, e organismos governamentais no âmbito das suas funções não lucrativas / públicas.

Para questões de licenciamento, contacte **许道斌 (Daobin Xu)** (<15555537368xu@gmail.com>). Os termos bilingues completos encontram-se em [LICENSE](LICENSE).
