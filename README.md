# fabler_icons
### !!! this repository forked of https://github.com/bigbadbob2003/flutter_tabler_icons 😉

The official [Tabler Icon Pack](https://github.com/tabler/tabler-icons).

official Tabler icons version: 1.111.0

## pubspec.yaml
```yml
dependencies:
  flutter:
    sdk: flutter
  fabler_icons: ^1.2.13
```

## Usage
```Dart
import 'package:fabler_icons/fabler_icons.dart';

class MyWidget extends StatelessWidget {
  Widget build(BuildContext context) {
    return new IconButton(
      icon: new Icon(FablerIcons.iconAddressBook),
      onPressed: () { print('iconAddressBook pressed'); }
     );
  }
}
```
![alt text](https://github.com/bigbadbob2003/fabler_icons/raw/master/.github/screenshot.png)
