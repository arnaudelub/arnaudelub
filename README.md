## Hello World 👋!
Uncle bob said "Clean code reads like well-written prose", so why not reading my README.md like you read clean code

```dart
library arnaudelub;

export 'welcome/my_name_is_arnaud_delubac';
export 'fully_remote_worker/as_freelance/at_idelub';
export 'cross_plaform_developer/flutter';
export 'experienced_in_ecommerce';
export 'my_editor/vim_4_ever/nvim';
export 'my_os/linux_4_ever/manjaro';

```

```dart
part 'my_career.dart';
```

```dart

const oneYearExperience = '1 year of experience';
const twinapp = 'Twinapp';
const findo = 'Findo';
const elPuntAvui = 'El Punt Avui';
const reliqium = 'Reliqium';

abstract class MyExperienceAsAFlutterDeveloper {
    bool wasAFlutterDeveloperAtInteractiuImpactedMyCareer();
    void isAFlutterDeveloperFreelancerAtIDelub();
    Future<void> willBeCTOAndCoFounderAtFindo();
}

/*
 * Quick Note, this class is a lazy singleton, but to avoid any missunderstanding,
 * i am neither lazy nor single!
**/
@LazySingleton(as: MyExperienceAsAFlutterDeveloper)
class MyExperienceAsAFlutterDeveloperImplementation implements MyExperienceAsAFlutterDeveloper {
    final MyCareerRepository _myCareerRepository;
    const MyExperienceAsAFlutterDeveloperImplementation(this._myCareerRepository);
    
    @override
    bool wasAFlutterDeveloperAtInteractiuImpactedMyCareer() {
        _myCareerRepository.addProjectDone(twinapp);
        final bool myFirstAttemptWithFlutterSucceeded = _myCareerRepository.isPublishedAndWorking(twinapp);
        final didILovedIt = true;
        _myCareerRepository.addExperience(oneYearExperience);
        return myFirstAttemptWithFlutterSucceed && didILovedIt;
    }
    
    @override
    void isAFlutterDeveloperFreelancerAtIDelub(){
        _myCareerRepository.addProjectDone(elPuntAvui);
        final today = DateTime.now();
        final startDateAsFreelance = DateTime(2020, 04, 01);
        final int numberOfYears = today.difference(startDateAsFreelance).inYears;
        final year = "year${numberOfYears > 1 ? 's' : ''}";
        _myCareerRepository.addExperience("$numberOfYears $year of experience");
    }
    
    @override
    Future<bool> willBeCTOAndCoFounderAtFindo() async {
        _myCareerRepository.addProjectDone(findo);
        final myLastProjectSucceeded = await _myCareerRepository.isPublishedAndWorking(hero);
        _myCareerRepository.canLevelUp(myLastProjectSucceeded);
        return myLastProjectSucceeded;
    }
}

extension MyFlutterAppsAndPackages on Flutter {
    List<String> get developedApp => [
        Reliqium,
        Twinapp,
        ElPuntAvui
        Findo,
        Ecohint];
    List<String> get developedPackages => [flutter_fullpdfview, csv_picker_button, flutter_firebase_aut_facade];
}
```

#### My pubspec.yaml:

```yaml
dependencies:
    - Flutter: 2+
    - Python: 6+
    - Angular: 3+
    - Java: 1+
```

##### Links
- [Reliqium](https://www.reliqium.com/),
- [Twinapp](https://www.twinapp.net/),
- [ElPuntAvui Android](https://play.google.com/store/apps/details?id=cat.epa.quiosc.epan&gl=ES),
- [ElPuntAvui iOS](https://apps.apple.com/us/app/el-punt-avui-nacional-v2/id1505758634),
- [Findo](https://findoapp.es),
- [flutter_fullpdfview on github](https://github.com/arnaudelub/flutter_fullpdfview),
- [flutter_fullpdfview on pub.dev](https://pub.dev/packages/flutter_fullpdfview) => [![Pub Version](https://img.shields.io/pub/v/flutter_fullpdfview)](https://pub.dev/packages/flutter_fullpdfview)
- [flutter packages on Github](https://github.com/arnaudelub/flutter_packages),
- [csv picker button on pub.dev](https://pub.dev/packages/csv_picker_button) => [![Pub Version](https://img.shields.io/pub/v/csv_picker_button)](https://pub.dev/packages/csv_picker_button)
- [flutter_firebase_auth_faacade on pub.dev](https://pub.dev/packages/flutter_firebase_auth_facade) => [![Pub Version](https://img.shields.io/pub/v/flutter_firebase_auth_facade)](https://pub.dev/packages/flutter_firebase_auth_facade)

## My articles

|               |               |
| ------------- | ------------- |
| <a href="https://medium.com/flutter-espa%C3%B1a/dart-isolate-y-flutter-compute-b8b23896e6b8"> <img src="https://miro.medium.com/max/1667/1*ezz3rf8fNGrX4drJBr0VUQ.jpeg" height="200" align="right"/> </a>  |  **Dart isolate and Flutter Compute** </br>Give your main thread som breath! |
| <a href="https://medium.com/flutter-espa%C3%B1a/flutter-y-nfc-unleashed-98238c85a1e2"> <img src="https://miro.medium.com/max/1500/1*Qicsn8Y8n9pOYPhF8KONeA.png" height="200" align="right"/> </a>  |  **Flutter and NFC** </br> Control you NFC chip with flutter |
| <a href="https://medium.com/flutter-espa%C3%B1a/flutter-y-firebase-login-todo-lo-que-necesitas-saber-b1deada16f0f"> <img src="https://miro.medium.com/max/8000/1*NO6fXIYHapLHHPSDMs8SFQ.png" height="200" align="right"/> </a>  |  **Flutter and Firebase Login** </br> All you need to know about Firebase authentication with Flutter (Spanish only) |
| <a href="https://arnaudelub.medium.com/usar-debouncetime-de-rxdart-y-bloc-para-esperar-a-que-un-usuario-termine-de-escribir-147c91243329"> <img src="https://miro.medium.com/max/7000/1*qAo7JxuD9adRUqREtqnFEA.jpeg" height="200" align="right"/> </a>  |  **debounceTime from RxDart and Bloc** </br> Use Rxdart's debounceTime with Bloc (En, Fr, Es) |
| <a href="https://arnaudelub.medium.com/flutter-bloc-y-firestore-stream-la-combinaci%C3%B3n-perfecta-si-se-usa-de-la-manera-correcta-33fc8a64bcca"> <img src="https://miro.medium.com/max/6912/1*z9gsZMQKdzRGXVxSq7TNKw.jpeg" height="200" align="right"/> </a>  |  **Flutter, Bloc and Firestore stream** </br> Controle Firestore's stream with Bloc |



## My open source projects

|               |               |
| ------------- | ------------- |
| <a href="https://github.com/arnaudelub/flutterence">  Flutterence </a>  |  **Open source Project, so it can evolve thanks to the community and for the community!** </br> Anyone who want to contribute is welcome to contact me |
| <a href="https://github.com/arnaudelub/flutter_packages/tree/main/csv_picker_button"> csv_picker_button </a> [![Pub Version](https://img.shields.io/pub/v/csv_picker_button)](https://pub.dev/packages/csv_picker_button) |  **Load and read you CSV!** </br> Parse your CSV data from a simple button |
| <a href="https://github.com/arnaudelub/flutter_packages/tree/main/flutter_firebase_auth_facade"> firebase auth facade </a> [![Pub Version](https://img.shields.io/pub/v/flutter_firebase_auth_facade)](https://pub.dev/packages/flutter_firebase_auth_facade)  |  **Login with Firebase!** </br>All the power from firebase authentication in a simple plugin! |

<!--| <a href="https://github.com/arnaudelub/flutter_issues_app">  Flutter issue app </a>  |  **Check and filter Flutter issue!|-->
