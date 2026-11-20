# FuelTrack

Aplicativo Flutter para controle de gastos com combustivel.

## Estado atual

Esta primeira versao contem a identidade visual inicial e a navegacao entre quatro areas:
- Inicio (dashboard demonstrativo)
- Meu veiculo (tela provisoria)
- Abastecer (tela provisoria)
- Historico (tela provisoria)

As funcionalidades de API, persistencia local, cadastro e graficos serao implementadas nas proximas etapas.

## Requisitos

- Flutter SDK instalado
- Android SDK configurado
- Dispositivo Android ou emulador

## Preparar o projeto Android

Este ZIP contem o codigo-fonte Flutter e os arquivos de configuracao, mas nao inclui os arquivos nativos gerados pelo Flutter SDK.

1. Extraia a pasta `FuelTrack`.
2. Abra um terminal dentro dela.
3. Execute:

```bash
flutter create --platforms=android --org br.com.controle .
flutter pub get
flutter run
```

Se o comando `flutter create` perguntar sobre sobrescrever arquivos, preserve `lib/main.dart` e `pubspec.yaml`.

## Tecnologias previstas

- Flutter / Dart
- BrasilAPI
- SQLite (sqflite)
- fl_chart
- http
- intl
