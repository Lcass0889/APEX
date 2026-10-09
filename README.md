<div align="center">

<img src="assets/apex-icone.png" width="128" alt="Ícone do APEX">

# APEX

### Para quem gosta de dirigir.

Velocímetro por GPS, alertas de radar pela via e pelo sentido, rotas gravadas, garagem e comunidade com amigos.<br>
No iPhone, no CarPlay e no Android.

![iOS 18+](https://img.shields.io/badge/iOS-18%2B-161A12?style=for-the-badge&logo=apple&logoColor=D2F85A)
![CarPlay](https://img.shields.io/badge/CarPlay-nativo-161A12?style=for-the-badge&logo=apple&logoColor=D2F85A)
![Android 8+](https://img.shields.io/badge/Android-8%2B-161A12?style=for-the-badge&logo=android&logoColor=D2F85A)
![Supabase](https://img.shields.io/badge/backend-Supabase-161A12?style=for-the-badge&logo=supabase&logoColor=D2F85A)
![Teste fechado](https://img.shields.io/badge/status-teste_fechado-D2F85A?style=for-the-badge&labelColor=161A12)

</div>

<p align="center">
  <img src="assets/dirigir.jpg" width="180" alt="Dirigir: velocímetro pronto para iniciar">
  <img src="assets/explorar.jpg" width="180" alt="Explorar: radares agrupados no mapa do Brasil">
  <img src="assets/rota.jpg" width="180" alt="Rota até a Avenida Paulista com opções e radares no caminho">
  <img src="assets/radares.jpg" width="180" alt="Radar no mapa com limite de 60 km/h">
</p>

## Recursos

- **Dirigir** — velocidade por GPS e alerta só dos radares da via e do sentido em que você está, com aviso por voz e bipe acima do limite. Continua funcionando em segundo plano.
- **Radares** — base de todo o Brasil, usada offline, atualizada diariamente com dados abertos e conferida com cadastros oficiais (CET, DER-SP, ANTT e prefeituras).
- **Explorar e rotas** — busca de destino com rotas alternativas e os radares de cada caminho, gravação e histórico de percursos, importação de GPX.
- **Garagem** — seus veículos e modificações, guardados no aparelho.
- **Comunidade** — amigos no mapa, grupos, encontros e Largada: contagem 3, 2, 1, VAI para pista fechada.
- **CarPlay** — app nativo no carro e painel de velocidade e radar no Dashboard.

<p align="center">
  <img src="assets/carplay.jpg" width="480" alt="APEX na tela inicial do CarPlay">
</p>

## Privacidade

- A localização só é compartilhada com os amigos que você escolher, pelo prazo que escolher (15 minutos, 1 hora ou 2 horas) e com o app aberto.
- Rotas, garagem e perfil ficam no aparelho. O backup é local e cifrado.
- A base de radares só é baixada: o app nunca envia a sua posição para atualizá-la.

## Plataformas

| | Tecnologia | Requisito |
|---|---|---|
| iPhone | SwiftUI e SwiftData | iOS 18 ou posterior |
| CarPlay | Driving Task e Atividade ao Vivo | iPhone compatível |
| Android | Kotlin e Jetpack Compose | Android 8.0 ou posterior |
| Backend | Supabase (Postgres, Auth, Storage, Realtime) | — |

## Status

Em teste fechado: iPhone pelo TestFlight e Android por APK. Ainda não está na App Store nem no Google Play. O código é privado.

---

### Outros projetos

- **GymFocus** — app de treino em React Native com Expo. [Política de privacidade e termos](https://github.com/Lcass0889/gymfocus-legal).
- **L.E.O.** — assistente de voz que roda localmente: Whisper, Ollama e Piper, com clientes desktop e web.
- **Prospector** — encontra negócios locais sem site cruzando dados públicos (CNPJ, DNS, Google Maps e registro.br).

**Tecnologias:** Swift · Kotlin · TypeScript · React Native · Python · FastAPI · PostgreSQL · Supabase · GitHub Actions
