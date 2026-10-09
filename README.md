<div align="center">

<img src="assets/apex-icone.png" width="112" alt="APEX" />

# APEX

**Para quem gosta de dirigir.**

Velocímetro por GPS com alertas de radar pela via e pelo sentido, rotas gravadas, garagem e
comunidade com amigos no mapa. Nativo no iPhone, no CarPlay e no Android.

[![Baixar no TestFlight](https://img.shields.io/badge/Baixar%20no%20iPhone-TestFlight-0D96F6?style=for-the-badge&logo=apple&logoColor=white)](https://testflight.apple.com/join/jvhhJSjR)
[![Baixar APK para Android](https://img.shields.io/badge/Baixar%20no%20Android-APK-3DDC84?style=for-the-badge&logo=android&logoColor=white)](https://github.com/Lcass0889/APEX/releases/latest)

![iOS 18+](https://img.shields.io/badge/iOS-18%2B-000000?logo=apple&logoColor=white)
![SwiftUI](https://img.shields.io/badge/Swift-SwiftUI-F05138?logo=swift&logoColor=white)
![CarPlay](https://img.shields.io/badge/CarPlay-Driving%20Task-000000?logo=apple&logoColor=white)
![Android 8+](https://img.shields.io/badge/Android-8%2B-3DDC84?logo=android&logoColor=white)
![Jetpack Compose](https://img.shields.io/badge/Kotlin-Jetpack%20Compose-7F52FF?logo=kotlin&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-Postgres%20%2B%20Auth-3FCF8E?logo=supabase&logoColor=white)
![Status](https://img.shields.io/badge/status-beta%20no%20TestFlight-D2F85A)

</div>

---

## 📲 Baixe e teste

| | iPhone | Android |
|---|---|---|
| **Onde** | [TestFlight](https://testflight.apple.com/join/jvhhJSjR) | [Última versão (APK)](https://github.com/Lcass0889/APEX/releases/latest) |
| **Como** | Instale o app TestFlight, abra o link no iPhone e toque em **Aceitar** e **Instalar** | Baixe o `.apk` em **Assets**, abra no celular e, se o Android pedir, permita instalar apps desta origem |
| **Atualizações** | Chegam pelo TestFlight | Instale o APK novo por cima: mesmo certificado, os dados continuam no aparelho |
| **Requisito** | iOS 18 ou posterior | Android 8.0 ou posterior |

Todas as versões Android ficam em [Releases](../../releases), com o SHA-256 de cada arquivo. É uma versão de teste: o APEX não substitui a sinalização da via nem a atenção ao volante.

## 📸 Capturas de tela

| Dirigir | Explorar | Rota | Radares no mapa |
|:---:|:---:|:---:|:---:|
| <img src="assets/dirigir.jpg" width="190" alt="Dirigir"> | <img src="assets/explorar.jpg" width="190" alt="Explorar"> | <img src="assets/rota.jpg" width="190" alt="Rota"> | <img src="assets/radares.jpg" width="190" alt="Radares no mapa"> |

<p align="center"><img src="assets/carplay.jpg" width="420" alt="APEX no CarPlay"></p>

## ✨ Funcionalidades

### 🚗 Dirigir
- **Velocidade por GPS** com aviso por voz e bipe acima do limite.
- **Alerta só dos radares da sua via e do seu sentido**, também em segundo plano.

### 📡 Radares
- Base de todo o Brasil **offline** e **atualizada todo dia** a partir de dados abertos.
- Conferida com **cadastros oficiais**: CET, DER-SP, ANTT e prefeituras.

### 🗺️ Explorar e rotas
- Busca de destino com **rotas alternativas** e os radares de cada caminho.
- **Gravação e histórico** de percursos e importação de **GPX**.

### 🤝 Comunidade
- **Amigos no mapa**, grupos, encontros, chat e **Largada**: contagem 3, 2, 1, VAI para pista fechada.

### 🚘 CarPlay
- App nativo no carro e **painel de velocidade e radar no Dashboard**.

## 🔐 Privacidade

- A localização só é compartilhada com os amigos que você escolher, pelo prazo que escolher (15 minutos, 1 hora ou 2 horas) e com o app aberto.
- Rotas, garagem e perfil ficam no aparelho. O backup é local e cifrado.
- A base de radares só é baixada: o app nunca envia a sua posição para atualizá-la.

## 🧰 Stack

| Plataforma | Tecnologia |
|---|---|
| iPhone | **Swift** · SwiftUI · SwiftData · MapKit |
| CarPlay e Dashboard | CarPlay (Driving Task) · ActivityKit |
| Android | **Kotlin** · Jetpack Compose · MapLibre |
| Backend | **Supabase**: Postgres, Auth, Storage, Realtime e Edge Functions |
| Dados de radar | Python · GitHub Actions · OpenStreetMap e cadastros oficiais |

## 🗺️ Status

Em teste: iPhone pelo [TestFlight](https://testflight.apple.com/join/jvhhJSjR) e Android pelo [APK](https://github.com/Lcass0889/APEX/releases/latest).
Ainda não está na App Store nem no Google Play. O código do app é privado; este repositório guarda a página do APEX e os APKs.

<div align="center"><sub>APEX · SwiftUI + Jetpack Compose + Supabase</sub></div>
