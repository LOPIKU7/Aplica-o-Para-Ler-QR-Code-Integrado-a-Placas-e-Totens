# Cidade Conectada

**Cidade Conectada** é uma aplicação Android desenvolvida como parte da Atividade Extensionista do curso de Engenharia de Software (UNINTER).
O objetivo é fornecer informações turísticas e de mobilidade urbana sem depender de conexão à internet.

## Sobre o Projeto

Leitor de QRCode para localização e obtenção de informações sobre o local.

## Funcionalidades

* **Leitura Offline:** Não requer internet ou base de dados externa.
* **Scanner Vertical:** Interface de câmara personalizada para uso fácil com uma mão.
* **Interpretação JSON:** Decodifica automaticamente strings JSON contidas no QR Code.
* **Navegação GPS:** Exibe coordenadas geográficas do local.

## Tecnologias Utilizadas

* **Linguagem:** Kotlin
* **IDE:** Android Studio
* **Bibliotecas:**
    * `ZXing Android Embedded` (Leitura de códigos de barras/QR)
    * `GSON` (Google) (Conversão de JSON para Objetos)

## Exemplo de Dados (JSON)

Para testar a aplicação, utilize um QR Code contendo o seguinte formato:

## JSON de Exemplo
[{
  "nome": "Estatua São José",
  "descricao": "Estatua São José",
  "coordenadas": "27°36'07\"S 48°36'24\"W",
  "tipo": "Turitico"
}]

## QRCode gerado apartir do JSON acima
<img width="690" height="690" alt="image" src="https://github.com/user-attachments/assets/b5d7c51a-9c37-4b4a-bd92-fe3971b3941d" />

## Resultado do Escaneamento Feito Pela Aplicação
![Imagem do WhatsApp de 2025-11-24 à(s) 21 54 37_a27f7470](https://github.com/user-attachments/assets/464f4c48-6f91-42f1-86d2-1c975aa88a97)
