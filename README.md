# Flutter Video Player

Aplicativo simples em Flutter para reprodução de vídeo local, utilizando o pacote `video_player`.

## 📱 Funcionalidades

- Reprodução de vídeo armazenado localmente (assets)
- Botão para pausar/reproduzir o vídeo
- Player exibido com a proporção (aspect ratio) correta
- Indicador de carregamento enquanto o vídeo é inicializado

## 🛠️ Tecnologias

- [Flutter](https://flutter.dev/)
- [video_player](https://pub.dev/packages/video_player)

## 📂 Estrutura do projeto

```
lib/
  main.dart          # Tela principal com o player de vídeo
assets/
  videos/
    video_exemplo.mp4 # Vídeo local reproduzido no app
```

## ▶️ Como rodar o projeto

1. Clone o repositório:
   ```bash
   git clone https://github.com/LuizPauloSoares/flutter-video-player.git
   cd flutter-video-player
   ```

2. Instale as dependências:
   ```bash
   flutter pub get
   ```

3. Certifique-se de que o vídeo está na pasta `assets/videos/` e que o `pubspec.yaml` está configurado para incluir os assets:
   ```yaml
   flutter:
     assets:
       - assets/videos/
   ```

4. Execute o app:
   ```bash
   flutter run
   ```

## 📌 Observações

- O vídeo utilizado é local (asset), não é carregado via URL/rede.
- Para trocar o vídeo, basta substituir o arquivo em `assets/videos/` e ajustar o nome no `VideoPlayerController.asset()`.

## 👤 Autor

Luiz Paulo Soares
- [LinkedIn](https://linkedin.com/in/luiz-paulo-soares/)
- [Instagram](https://instagram.com/lu1z_st)
