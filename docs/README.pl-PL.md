[![Build Status](https://travis-ci.org/beautifulinteractions/beautiful-react-hooks.svg?branch=master)](https://travis-ci.org/beautifulinteractions/beautiful-react-hooks)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
![npm](https://img.shields.io/npm/v/beautiful-react-hooks)
![GitHub stars](https://img.shields.io/github/stars/beautifulinteractions/beautiful-react-hooks?style=social)


<div align="center">
  <p align="center">
    <img src="../logo.png" alt="Beautiful React Hooks" width="750px" />
  </p>
</div>
<br />
<div>
  <p align="center">
   Zbiór pięknych (i mamy nadzieję, że użytecznych) hooków React, mających na celu przyspieszenie
tworzenia spersonalizowanych hooków oraz komponentów.
  </p>
</div>

<div>
  <p align="center">
    <a href="https://beautifulinteractions.github.io/beautiful-react-hooks/" target="_blank">
    🌟 Wypróbuj je tutaj 🌟
    </a>
  </p>
</div>

![Usage example](../usage_example.png)

<a href="https://github.com/beautifulinteractions/beautiful-react-hooks/">🇬🇧 English</a> | <a href="https://github.com/beautifulinteractions/beautiful-react-hooks/blob/master/docs/README.zh-CN.md">🇨🇳 简体中文</a> | <a href="https://github.com/beautifulinteractions/beautiful-react-hooks/blob/master/docs/README.it-IT.md">🇮🇹 Italiano</a> |<a href="https://github.com/beautifulinteractions/beautiful-react-hooks/blob/master/docs/README.es-ES.md"> 🇪🇸 Español | <a href="https://github.com/beautifulinteractions/beautiful-react-hooks/blob/master/docs/README.uk-UA.md">🇺🇦 Ukrainian</a> | <a href="https://github.com/beautifulinteractions/beautiful-react-hooks/blob/master/docs/README.pt-BR.md">🇧🇷 Brazilian Portuguese</a> | 🇵🇱 Polski | <a href="https://github.com/beautifulinteractions/beautiful-react-hooks/blob/master/docs/README.jp-JP.md">&#x1f1ef;&#x1f1f5; 日本語 </a>

## 💡 Dlaczego? 

W aplikacji React hooki pozwalają na wyodrębnienie logiki biznesowej komponentów do pojedyńczych funkcji wielokrotnego użytku.<br />
Odkryliśmy, że większość hooków, które stworzyliśmy i dzieliliśmy między naszymi wewnętrznymi projektami, miały zazwyczaj podobną istotę, obejmującą callbacki, eventy oraz cykle zycia komponentów. <br />
Z tego powodu podjęliśmy próbę zebrania tej istoty pod postacią `beautiful-react-hooks` będących zbiorem (* mamy nadzieję *) przydatnych hooków
React, mającym na celu pomoc innym firmom i specjalistom w przyspieszeniu procesu tworzenia aplikacji.<br /><br />
Ponadto, stworzyliśmy zwięzłe i konkretne API, mając na uwadze czytelność kodu oraz pragnąc utrzymać krzywą uczenia się na jak najniższym poziomie, tak, aby można je było wykorzystywać i dzielić się nim w większych zespołach.


**-- Przeczytaj dokumentację kadego z hooków przed jego użyciem! --**

## ☕️ Cechy

* Zwarte API
* Małe i lekkie
* Łatwe do nauki
* Podejście funkcjonalne
* Napisane w całości w JS (chociaż typy TS są również obsługiwane)

<div>
  <p align="center">
    <a href="https://beautifulinteractions.github.io/beautiful-react-hooks/" target="_blank">
    🌟 Wypróbuj je tutaj 🌟
    </a>
  </p>
</div>

## 🕺 Instalacja

używając `npm`:
```bash
$ npm install beautiful-react-hooks
```

używając `yarn`:

```bash
$ yarn add beautiful-react-hooks
```

## 🎨 Hooki

* [useGlobalEvent](docs/useGlobalEvent.md)
* [usePreviousValue](docs/usePreviousValue.md)
* [useValueHistory](docs/useValueHistory.md)
* [useValidatedState](docs/useValidatedState.md)
* [useMediaQuery](docs/useMediaQuery.md)
* [useOnlineState](docs/useOnlineState.md)
* [useViewportSpy](docs/useViewportSpy.md)
* [useGeolocation](docs/useGeolocation.md), [useGeolocationState](docs/useGeolocationState.md) and [useGeolocationEvents](docs/useGeolocationEvents.md)
* [useDrag](docs/useDrag.md), [useDropZone](docs/useDropZone.md) and [useDragEvents](docs/useDragEvents.md)
* [useMouse](docs/useMouse.md), [useMouseState](docs/useMouseState.md) and [useMouseEvents](docs/useMouseEvents.md)
* [useLifecycle](docs/useLifecycle.md), [useDidMount](docs/useDidMount.md) and [useWillUnmount](docs/useWillUnmount.md)
* [useWindowResize](docs/useWindowResize.md)
* [useWindowScroll](docs/useWindowScroll.md)
* [useRequestAnimationFrame](docs/useRequestAnimationFrame.md)
* [useResizeObserver](docs/useResizeObserver.md)
* [useTimeout](docs/useTimeout.md)
* [useConditionalTimeout](docs/useConditionalTimeout.md)
* [useInterval](docs/useInterval.md)
* [useDebouncedFn](docs/useDebouncedFn.md)
* [useThrottledFn](docs/useThrottledFn.md)
* [useLocalStorage](docs/useLocalStorage.md)
* [useSessionStorage](docs/useSessionStorage.md)
* [useStorage](docs/useStorage.md)

<div>
  <p align="center">
    <a href="https://beautifulinteractions.github.io/beautiful-react-hooks/" target="_blank">
    🌟 Wypróbuj je tutaj 🌟
    </a>
  </p>
</div>

## Współpraca

Współpraca jest bardzo mile widziana. 

Przed dodaniem nowego hooka zapoznaj się koniecznie z zasadami projektowymi tutaj [CONTRIBUTING](../CONTRIBUTING.md)

**Przed stworzeniem** nowego pull request, upewnij się, że:

1. uaktualniłeś wersję pliku package.json oraz dodałeś zmiany w pliku [CHANGELOG](../CHANGELOG.md)
2. użyłeś komend `npm test` oraz `npm build`.
3. dodałeś dokumentację do twojego nowego hooka (*możesz użyć szablon [HOOK_DOCUMENTATION_TEMPLATE](../HOOK_DOCUMENTATION_TEMPLATE.md)*).
4. uaktualniłeś plik `index.d.ts` dodając typy Typescript twojego hooka.

### Użyte narzędzia

* [React](https://reactjs.org/)
* [Mocha](https://mochajs.org/)
* [Chai](https://www.chaijs.com/)
* [@testing-library/react](https://testing-library.com/docs/react-testing-library/intro)
* [@testing-library/react-hooks](https://react-hooks-testing-library.com/) 


### Uznanie

Ta biblioteka jest prowadzona i sponsorowana przez: 

<div>
  <p>
    <a href="https://beautifulinteractions.com/">
      <img src="https://beautifulinteractions.com/img/logo-colorful.svg" alt="Beautiful interactions" width="140px" />
    </a>
  </p>
</div>

w ramach naszego zobowiązania do wspierania i kontrybucji do społeczności Open Source.

---

Ikona wykonana przez [Freepik](https://www.flaticon.com/authors/freepik) na [www.flaticon.com](https://www.flaticon.com/free-icon/hook_1081812)
