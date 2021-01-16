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

abstract class MyExperienceAsAFlutterDeveloper {
    bool WasAFlutterDeveloperAtInteractiuImpactedMyCareer();
    void IsAFlutterDeveloperFreelancerAtIDelub();
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
    bool WasAFlutterDeveloperAtInteractiuImpactedMyCareer() {
        _myCareerRepository.addProjectDone(twinapp);
        final bool myFirstAttemptWithFlutterSucceeded = _myCareerRepository.isPublishedAndWorking(twinapp);
        final didILovedIt = true;
        _myCareerRepository.addExperience(oneYearExperience);
        return myFirstAttemptWithFlutterSucceed && didILovedIt;
    }
    
    @override
    void IsAFlutterDeveloperFreelancerAtIDelub(){
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
        Twinapp,
        ElPuntAvui
        Findo,
        Ecohint];
    List<String> get developedPackages => [flutter_fullpdfview];
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

- [Twinapp](https://www.twinapp.net/),
- [ElPuntAvui Android](https://play.google.com/store/apps/details?id=cat.epa.quiosc.epan&gl=ES),
- [ElPuntAvui iOS](https://apps.apple.com/us/app/el-punt-avui-nacional-v2/id1505758634),
- [Findo](https://findoapp.es),
- [flutter_fullpdfview on github](https://github.com/arnaudelub/flutter_fullpdfview),
- [flutter_fullpdfview on pub.dev](https://pub.dev/packages/flutter_fullpdfview) => [![Pub Version](https://img.shields.io/pub/v/flutter_fullpdfview)](https://pub.dev/packages/flutter_fullpdfview)

<!--
**arnaudelub/arnaudelub** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
