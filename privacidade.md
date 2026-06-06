# Política de Privacidade — VendeAI

**Última atualização:** junho de 2026

---

## 1. Introdução

O **VendeAI** ("nós", "nosso" ou "aplicativo") é um sistema de gestão de vendas desenvolvido por **Adega Digital**. Esta Política de Privacidade descreve quais dados coletamos, como os utilizamos, com quem os compartilhamos e quais são seus direitos, em conformidade com a **Lei Geral de Proteção de Dados (LGPD — Lei nº 13.709/2018)**.

Ao usar o VendeAI, você concorda com os termos desta política.

---

## 2. Dados que coletamos

### 2.1 Dados fornecidos por você

| Dado | Finalidade |
|---|---|
| E-mail e senha | Criação e autenticação de conta (plano Pro) |
| Nome da loja / empresa | Personalização do app |
| Produtos, preços, estoque | Gestão do negócio |
| Vendas realizadas | Histórico e relatórios |
| Nome, telefone e e-mail de clientes | Cadastro de clientes (opcional) |
| Nome e e-mail de fornecedores | Cadastro de fornecedores (opcional) |
| Fotos de produtos | Identificação visual dos produtos |

Todos esses dados são **de sua propriedade**. Nós não os acessamos para fins comerciais.

### 2.2 Dados coletados automaticamente

| Dado | Por quê | Quem coleta |
|---|---|---|
| Relatórios de falha (crash) | Identificar e corrigir bugs | Firebase Crashlytics |
| Identificador de publicidade | Exibição de anúncios relevantes (plano gratuito) | Google AdMob |
| Informações de assinatura | Gerenciar plano Pro | Google Play Billing |

---

## 3. Como usamos os dados

- **Funcionamento do app**: dados de vendas, produtos e clientes são armazenados localmente no seu dispositivo, criptografados com SQLCipher.
- **Sincronização em nuvem** (plano Pro): os dados do negócio são sincronizados via Google Firebase Firestore para possibilitar acesso em múltiplos dispositivos.
- **Imagens de produtos**: fotos de produtos são armazenadas no Room (armazenamento local do seu dispositivo)
- **Melhoria do app**: relatórios de falha anônimos (Crashlytics) são usados exclusivamente para corrigir erros técnicos. Essa coleta é desativada em versões de desenvolvimento.
- **Anúncios** (plano gratuito): o Google AdMob exibe anúncios.

---

## 4. Armazenamento e segurança

- **Local**: banco de dados criptografado com **SQLCipher (AES-256)**; preferências do app protegidas com **EncryptedSharedPreferences**.
- **Nuvem** (Pro): dados transmitidos via HTTPS e armazenados nos servidores do Google Firebase, com conformidade SOC 2 e ISO 27001.
- **Backup**: arquivos de backup gerados pelo app são salvos na pasta que você escolher no seu dispositivo, protegidos por criptografia AES-256.
- Não armazenamos senhas em texto simples.

---

## 5. Compartilhamento de dados

**Não vendemos, alugamos nem comercializamos seus dados.**

Compartilhamos dados apenas com os seguintes provedores de serviço, estritamente no que é necessário para o funcionamento do app:

| Provedor | Finalidade | Política |
|---|---|---|
| Google Firebase | Autenticação, banco de dados em nuvem, armazenamento de imagens, relatórios de falha | [firebase.google.com/support/privacy](https://firebase.google.com/support/privacy) |
| Google AdMob | Exibição de anúncios (plano gratuito) | [policies.google.com/privacy](https://policies.google.com/privacy) |
| Google Play Billing | Processamento de assinatura | [play.google.com/about/privacy-security](https://play.google.com/about/privacy-security) |

---

## 6. Permissões do dispositivo

| Permissão | Finalidade |
|---|---|
| Câmera | Leitura de código de barras e foto de produtos |
| Galeria / armazenamento de mídia | Importar fotos de produtos da galeria |
| Armazenamento externo | Salvar e restaurar backups (Android ≤ 9) |
| Notificações | Alertas de backup automático (Android 13+) |
| Internet | Sincronização em nuvem e anúncios |

As permissões de câmera e galeria são solicitadas apenas quando você acessa as funcionalidades correspondentes e podem ser revogadas a qualquer momento nas configurações do Android.

---

## 7. Retenção de dados

- **Dados locais**: permanecem no dispositivo até você desinstalar o app ou realizar uma restauração de fábrica.
- **Dados em nuvem** (Pro): mantidos enquanto sua conta estiver ativa. Ao excluir a conta, os dados em nuvem são removidos em até **30 dias**.
- **Relatórios de falha**: retidos por até **90 dias** pela Firebase Crashlytics.

---

## 8. Crianças

O VendeAI é destinado a **maiores de 18 anos** (empreendedores e lojistas). Não coletamos intencionalmente dados de menores de 18 anos. Se identificarmos tal situação, os dados serão excluídos imediatamente.

---

## 9. Seus direitos (LGPD)

Você tem direito a:

- **Acessar** os dados que o app armazena sobre você
- **Corrigir** dados incompletos ou desatualizados
- **Excluir** seus dados (apagando o app ou solicitando exclusão da conta)
- **Portabilidade**: exportar seus dados via função de backup do app
- **Revogar consentimento** a qualquer momento

Para exercer qualquer um desses direitos, entre em contato: **udecosta@gmail.com**

---

## 10. Alterações nesta política

Podemos atualizar esta política periodicamente. Alterações significativas serão comunicadas dentro do app. A data da última atualização está sempre no topo desta página.

---

## 11. Contato

**Adega Digital**
E-mail: udecosta@gmail.com
