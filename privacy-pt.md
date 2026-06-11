---
layout: default
title: Política de Privacidade
---

# Política de Privacidade

**Data de vigência:** [DATA DE LANÇAMENTO]
**Última atualização:** [DATA DE LANÇAMENTO]

Esta Política de Privacidade descreve como o Ventaglio ("nós", "aplicativo") trata suas informações. Ao usar o Ventaglio, você concorda com os termos descritos aqui.

[← Voltar ao início](./)

## Quem somos

Ventaglio é um aplicativo independente para iOS e watchOS desenvolvido para jogadores de beach tennis acompanharem métricas de desempenho durante partidas. O aplicativo é desenvolvido por Nikolas Mesquita do Nascimento como desenvolvedor independente.

## Quais informações coletamos

### Informações que você fornece diretamente

Quando você faz login no Ventaglio usando o Login com Google, recebemos:

- Seu **nome** (nome de exibição da sua conta Google)
- Seu **endereço de email**
- Um **identificador único de usuário** (Firebase user ID, usado internamente para associar seus dados à sua conta)

Ao completar a tela de onboarding, você também fornece:

- Seu **nível de jogador** (iniciante, intermediário ou avançado)
- Sua **mão dominante** (destro ou canhoto)

Essas informações de perfil são armazenadas **apenas no seu dispositivo** e não são transmitidas para nenhum servidor.

### Informações coletadas automaticamente durante o uso

Durante uma sessão ativa de beach tennis no seu Apple Watch, o aplicativo coleta:

- **Frequência cardíaca** (via HealthKit)
- **Calorias ativas** (via HealthKit)
- **Contagem de passos** (via HealthKit)
- **Distância percorrida** (via HealthKit e Core Location / GPS)
- **Localização precisa** (apenas enquanto você está usando o aplicativo ativamente, para medir distância percorrida em quadras outdoor)

Esses dados são coletados apenas durante uma sessão de treino ativa.

## Como usamos suas informações

Suas informações são usadas exclusivamente para fornecer a funcionalidade principal do aplicativo:

- Exibir suas métricas de partida em tempo real no Apple Watch
- Salvar seu histórico de partidas no iPhone para consulta posterior
- Salvar partidas no app Saúde do iOS como treinos (se você conceder permissão)
- Autenticar você entre sessões e dispositivos

**Não** usamos suas informações para:

- Publicidade
- Rastreamento entre outros aplicativos ou sites
- Perfilamento ou análise comportamental
- Comunicação de marketing

## Onde suas informações são armazenadas

| Dado | Local |
|---|---|
| Perfil (nome, nível, mão dominante) | No seu dispositivo (SwiftData, local) |
| Métricas de partida (FC, calorias, passos, distância) | No seu dispositivo (SwiftData, local) |
| Credenciais de autenticação (conta Google, user ID) | Servidores do Firebase Authentication (Google Cloud) |
| Dados de saúde (se você salvar partidas como treinos) | App Saúde do iOS, no seu dispositivo |

**Dados de partida nunca são transmitidos para nossos servidores ou terceiros.** Eles existem apenas no seu iPhone e Apple Watch, e são sincronizados entre eles via WatchConnectivity da Apple.

A única informação que sai do seu dispositivo é sua autenticação Google, que vai diretamente para o Firebase Authentication (operado pelo Google) com o único propósito de verificar sua identidade.

## Serviços de terceiros

O Ventaglio utiliza os seguintes serviços de terceiros:

### Login com Google e Firebase Authentication

Usamos o Login com Google para autenticar usuários. Quando você faz login:

- O Google realiza a autenticação
- O Firebase Authentication (Google Cloud) armazena suas credenciais de autenticação
- Recebemos seu nome, email e um user ID desse processo

Política de privacidade do Google: [https://policies.google.com/privacy](https://policies.google.com/privacy)
Privacidade do Firebase: [https://firebase.google.com/support/privacy](https://firebase.google.com/support/privacy)

### Apple HealthKit e Core Location

São serviços do sistema da Apple. Dados acessados via HealthKit e Core Location são regidos pelas políticas de privacidade da Apple e permanecem sob seu controle através das Configurações do iOS.

Política de privacidade da Apple: [https://www.apple.com/legal/privacy/](https://www.apple.com/legal/privacy/)

## Seus direitos

### Sob a LGPD (Brasil)

- Direito de confirmar o tratamento de dados
- Direito de acessar seus dados
- Direito de corrigir dados incompletos ou inexatos
- Direito de anonimizar, bloquear ou eliminar dados desnecessários
- Direito à portabilidade dos dados
- Direito de eliminar dados tratados com seu consentimento
- Direito à informação sobre compartilhamento de dados
- Direito de revogar o consentimento

### Sob o GDPR (União Europeia)

- Direito de acesso aos seus dados
- Direito de corrigir dados inexatos
- Direito de eliminar dados ("direito ao esquecimento")
- Direito à portabilidade de dados
- Direito de se opor ao tratamento
- Direito de apresentar reclamação à autoridade supervisora

### Como exercer seus direitos

Para exercer qualquer um desses direitos, entre em contato em [support@ventaglio.app](mailto:support@ventaglio.app).

### Excluindo seus dados

- **Dados de partida e perfil:** desinstale o aplicativo do seu iPhone e Apple Watch. Todos os dados locais são permanentemente apagados.
- **Conta de autenticação:** envie email para [support@ventaglio.app](mailto:support@ventaglio.app) solicitando exclusão da conta. Excluiremos seu registro do Firebase Authentication em até 30 dias.

## Retenção de dados

- **Dados locais (perfil, partidas):** mantidos no seu dispositivo até você desinstalar o aplicativo ou excluir manualmente.
- **Dados de autenticação:** mantidos no Firebase até você solicitar a exclusão da conta.

## Privacidade de crianças

O Ventaglio não é direcionado a crianças menores de 13 anos. Não coletamos conscientemente dados de crianças menores de 13 anos. Se você souber que uma criança forneceu informações pessoais, entre em contato em [support@ventaglio.app](mailto:support@ventaglio.app).

## Segurança

Usamos práticas de segurança padrão da indústria:

- Toda comunicação com o Firebase Authentication é criptografada via HTTPS/TLS
- Dados locais são protegidos pela proteção de dados do iOS e pelo código do seu dispositivo
- Não armazenamos senhas (a autenticação é feita pelo Google)

## Alterações nesta política

Podemos atualizar esta Política de Privacidade. A data de "Última atualização" no topo reflete a revisão mais recente. Mudanças materiais serão comunicadas através do aplicativo.

## Contato

Dúvidas ou solicitações sobre esta Política de Privacidade:

**Email:** [support@ventaglio.app](mailto:support@ventaglio.app)

---

[← Voltar ao início](./) · [Privacy Policy (English)](./privacy)
