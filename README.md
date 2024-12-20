# Code Snippets Repository / Kod Snippetleri Deposu

This repository contains snippets designed to speed up and simplify coding in various programming languages. Currently, it includes Flutter snippets, but we aim to expand to other languages in the future.

Bu repository, çeşitli programlama dillerinde kullanılmak üzere hazırlanmış, kod yazımını hızlandıran ve kolaylaştıran snippet'ler içerir. Şu an için Flutter snippet'leri yer almakla birlikte, ilerleyen dönemlerde diğer diller için de genişletilebilir bir altyapı sunmayı hedefliyoruz.

---

## Table of Contents / İçindekiler
- [Installation / Kurulum](#installation--kurulum)
- [Usage / Kullanım](#usage--kullanım)
- [Available Snippets / Mevcut Snippetler](#available-snippets--mevcut-snippetler)
- [Customizing Snippets / Snippetleri Kişiselleştirme](#customizing-snippets--snippetleri-kişiselleştirme)
- [Future Plans / Gelecek Planları](#future-plans--gelecek-planları)
- [Contributing / Katkı](#contributing--katkı)

---

## Installation / Kurulum

### 1. For VS Code / VS Code için Kurulum
1. Open your **Snippets** folder / **Snippets** klasörünüzü açın:
   - Windows: `%APPDATA%/Code/User/snippets`
   - macOS: `~/Library/Application Support/Code/User/snippets`
   - Linux: `~/.config/Code/User/snippets`

2. Create a file named `flutter.code-snippets` or any name you prefer and paste the snippet codes into it. / `flutter.code-snippets` veya dilediğiniz bir isimde dosya oluşturun ve ilgili snippet kodlarını buraya yapıştırın.

3. Restart VS Code. / VS Code'u yeniden başlatın.

### 2. Other Editors / Diğer Editörler
- The snippet format may vary depending on the editor. This repository currently includes snippets in VS Code format only. / Snippet formatı editörden editöre değişiklik gösterebilir. Bu repository şu an için sadece VS Code formatında snippet'ler içerir.

---

## Usage / Kullanım

### 1. Running a Snippet in the Code Editor / Kod Editöründe Snippet'i Çalıştırma
- To call a snippet, simply type the **prefix** value and press `Tab`. / Bir snippet çağırmak için öncelikle ilgili snippet'in **prefix** değerini yazıp `Tab` tuşuna basmanız yeterlidir.

Example / Örnek:
```dart
aaLazySingleton
```
This will automatically insert the Lazy Singleton structure. / Bu, otomatik olarak Lazy Singleton yapısını ekler.

---

## Available Snippets / Mevcut Snippetler

### Flutter Snippets / Flutter Snippetleri

#### 1. Singleton Structures / Singleton Yapıları
- **Lazy Singleton**: Defines a structure that creates a single instance. / Tek bir instance oluşturan yapıyı tanımlar.
- **Eager Singleton**: Creates a single instance upon first call. / İlk çağrıda tek instance oluşturur.

#### 2. Flutter UI Components / Flutter UI Bileşenleri
- **Column**: Quickly creates a `Column` widget. / Hızlıca bir `Column` widget'ı oluşturur.
- **Row**: Quickly creates a `Row` widget. / Hızlıca bir `Row` widget'ı oluşturur.
- **Expanded**: Provides a template for the `Expanded` widget. / `Expanded` widget'ı için bir şablon sunar.
- **RichText**: Creates a `RichText` structure with customizable styles. / Stiller eklenebilir `RichText` yapısı oluşturur.
- **LayoutBuilder**: Includes LayoutBuilder for responsive design. / Responsive tasarım için LayoutBuilder içerir.

#### 3. MVVM Structures / MVVM Yapıları
- **DartFrame**: Creates a Frame suitable for the MVVM structure. / MVVM yapısına uygun bir Frame oluşturur.
- **DartScreen**: Provides a Screen template for MVVM. / MVVM için bir Screen şablonu sağlar.
- **DartViewModel**: A ViewModel template compatible with MobX. / MobX ile uyumlu bir ViewModel şablonu.

#### 4. Others / Diğer
- **DartNewFile**: A basic template for creating new files. / Yeni dosya oluştururken temel bir şablon.
- **initStateMethod**: An initState method for Flutter lifecycle. / Flutter lifecycle için bir initState metodu.

---

## Customizing Snippets / Snippetleri Kişiselleştirme

### 1. Using Placeholders / Placeholder Kullanımı
Placeholders like `${1:ClassName}` in snippets can be adjusted to fit your project. These placeholders allow for customizable fields when the snippet is invoked. / Snippet'lerde yer alan `${1:ClassName}` gibi placeholder'ları, kendi projenize uygun şekilde düzenleyebilirsiniz. Bu placeholder'lar, snippet'i çağırdığınızda otomatik olarak değiştirilebilir alanlar sunar.

Example / Örnek:
```dart
class ${1:ClassName} {
  static ${1:ClassName}? _instance;
}
```
Replace `${1:ClassName}` with your desired class name. / `${1:ClassName}` yerine kendi sınıf isminizi yazabilirsiniz.

### 2. Default Values / Varsayılan Değerler
You can add default values to snippets for frequently used fields. For instance: / Daha sık kullanılan değerleri snippet'lerin içine varsayılan olarak ekleyebilirsiniz. Örneğin:
```json
"Date: ${CURRENT_YEAR}-${CURRENT_MONTH}-${CURRENT_DATE}"
```
This will automatically add the current date. / Bu değer, otomatik olarak günün tarihini ekler.

### 3. Adding New Snippets / Yeni Snippet Ekleme
You can create new snippets by referring to the existing structure. / Yeni snippet'ler oluşturmak için mevcut yapıyı referans alabilirsiniz.
Example / Örnek:
```json
"New Snippet": {
  "prefix": "prefixName",
  "body": [
    "Snippet content here..."
  ],
  "description": "Snippet description"
}
```

---

## Future Plans / Gelecek Planları
- Snippet sets for different languages (JavaScript, Python, Swift, etc.). / Farklı diller için snippet setleri (JavaScript, Python, Swift, vb.).
- More Flutter components. / Daha fazla Flutter bileşeni.
- Automatic `LocaleKeys` snippets for localization support. / Yerelleştirme desteği için otomatik `LocaleKeys` snippet'leri.
- Ready structures for error management across projects. / Proje genelinde hata yönetimi için hazır yapılar.

---

## Contributing / Katkı

If you'd like to contribute: / Katkıda bulunmak istiyorsanız:
1. Fork the repository. / Repository'yi fork'layın.
2. Add your new snippets. / Yeni snippet'lerinizi ekleyin.
3. Submit a pull request. / Pull request gönderin.

We appreciate all suggestions and feedback! / Her türlü öneri ve geri bildirim için teşekkür ederiz!

---

**Prepared by / Hazırlayan:** [Aslınur Topcu](https://github.com/Asli-nur-t)

