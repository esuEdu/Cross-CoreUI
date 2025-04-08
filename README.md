# Cross-CoreUI

**Cross-CoreUI** é um Swift Package modular criado para oferecer **componentes de UI reutilizáveis** e **telas padrão** em SwiftUI, ideal para uso em fábricas de software ou múltiplos projetos iOS.

## ✨ Features

- Componentes customizáveis (botões, textfields, loaders, etc.)
- Telas padrão (Login, Onboarding, etc.)
- Tema centralizado (cores, tipografia, espaçamento)
- ViewModifiers e extensões úteis para SwiftUI

## 🛠 Instalação

Use o Swift Package Manager:

```swift
.package(url: "https://github.com/esuEdu/Cross-CoreUI.git", from: "1.0.0")
```
E adicione DefaultKit como dependência no seu target.

## 🧱 Estrutura

plaintext
Copy
Edit

```
Sources/
└── Cross-CoreUI/
    ├── Components/
    ├── Screens/
    ├── Theme/
    ├── Extensions/
    └── Modifiers/
```
## 🚀 Exemplo de Uso

swift
Copy
Edit

```
import Cross-CoreUI

var body: some View {
    PrimaryButton(title: "Entrar") {
        print("Botão pressionado")
    }
}
```
## 📦 Roadmap
 Suporte a dark mode completo

 Adição de loading spinners

 Mais telas padrão (cadastro, perfil, etc.)

 Suporte multiplataforma (iPadOS/macOS)

## 🔒 Licença
MIT License.



