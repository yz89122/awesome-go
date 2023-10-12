# Awesome Tiny JS [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

<div align="center">
  <a href="https://github.com/thoughtspile/awesome-tiny-js#readme">
    <img src="https://github.com/thoughtspile/awesome-tiny-js/raw/main/awesome-logo.png" width="300" height="207">
  </a>
</div>

Tiny front-end libraries to put your bundle on a diet. Rules:

- Size is under 2 kB-ish, min + gzip, with all dependencies, except where noted.
- For multi-purpose libraries, the size of a useful subset must be under 2 kB-ish.
- Useful client-side. I haven't figured out participation rules for node-only libraries, and I'm not too worried about them.
- Second-level libraries only allowed for React, Vue, Angular, svelte. 
- 100+ GitHub stars. Libraries with less are awesome, too, but stars indicate some community review.
- No zero-JS (CSS- or type-only) libraries. It's not awesome-css or something.

## Contents

- [UI Frameworks](#ui-frameworks)
- [Event Emitters](#event-emitters)
- [Reactive Programming](#reactive-programming)
- [State Managers](#state-managers)
- [Routers and URL Utils](#routers-and-url-utils)
- [API Layer](#api-layer)
- [I18N](#i18n)
- [Dates and Time](#dates-and-time)
- [Generic Utilities](#generic-utilities)
- [Unique ID Generation](#unique-id-generation)
- [Colors](#colors)
- [Touch Gestures](#touch-gestures)
- [Text Search](#text-search)

## UI Frameworks

UI frameworks (libraries?) provide declarative templates, event bindings, and observable state to update the view. I've been generous and expanded the size limit for this category to 4.5 kB (if you're boring, count them as 2 libraries), but also increased the star limit to 2K. 

- [preact ![GitHub Repo Stars](https://img.shields.io/github/stars/preactjs/preact) ![GitHub last commit](https://img.shields.io/github/last-commit/preactjs/preact)](https://github.com/preactjs/preact) - React-like API (pre-hooks). Cool ecosystem of similarly tiny tools and components. Highly recommended. <img align="top" height="24" src="https://img.shields.io/bundlephobia/minzip/preact.svg?label=&color=grey">

The following libraries are small and cool, but note they're about [500x less popular than preact.](https://npmtrends.com/preact-vs-fre-vs-hyperapp-vs-million-vs-redom) Kudos for deconstrucing the very essence of a "framework":

- [million ![GitHub Repo Stars](https://img.shields.io/github/stars/aidenybai/million) ![GitHub last commit](https://img.shields.io/github/last-commit/aidenybai/million)](https://github.com/aidenybai/million) - Alternate runtime for React components, <img align="top" height="24" src="https://img.shields.io/bundlephobia/minzip/million.svg?label=&color=grey">
- [fre ![GitHub Repo Stars](https://img.shields.io/github/stars/frejs/fre) ![GitHub last commit](https://img.shields.io/github/last-commit/frejs/fre)](https://github.com/frejs/fre) - React-like library with hooks and concurrency, <img align="top" height="24" src="https://img.shields.io/bundlephobia/minzip/fre.svg?label=&color=grey"> or ~2 kB with tree-shaking.
- [hyperapp ![GitHub Repo Stars](https://img.shields.io/github/stars/jorgebucaran/hyperapp) ![GitHub last commit](https://img.shields.io/github/last-commit/jorgebucaran/hyperapp)](https://github.com/jorgebucaran/hyperapp) - Declarative UI with pure JS syntax and immutable state, <img align="top" height="24" src="https://img.shields.io/bundlephobia/minzip/hyperapp.svg?label=&color=grey">
- [redom ![GitHub Repo Stars](https://img.shields.io/github/stars/redom/redom) ![GitHub last commit](https://img.shields.io/github/last-commit/redom/redom)](https://github.com/redom/redom) - Hyperapp-style templates with _imperative_ event listeners and updates, <img align="top" height="24" src="https://img.shields.io/bundlephobia/minzip/redom.svg?label=&color=grey">

And if being declarative is not your thing:

- [umbrella ![GitHub Repo Stars](https://img.shields.io/github/stars/franciscop/umbrella) ![GitHub last commit](https://img.shields.io/github/last-commit/franciscop/umbrella)](https://github.com/franciscop/umbrella) - jQuery-style DOM manipulation library, <img align="top" height="24" src="https://img.shields.io/bundlephobia/minzip/umbrellajs.svg?label=&color=grey">

## Event Emitters

Event emitter pattern is fairly easy to implement yourself, but why bother when you have these cool tools? With an arms race to build the smallest one, the limit is 0.5 kB.

- [mitt ![GitHub Repo Stars](https://img.shields.io/github/stars/developit/mitt) ![GitHub last commit](https://img.shields.io/github/last-commit/developit/mitt)](https://github.com/developit/mitt) - Plain event emitter that I use on most projects, <img align="top" height="24" src="https://img.shields.io/bundlephobia/minzip/mitt.svg?label=&color=grey">
- [nanoevents ![GitHub Repo Stars](https://img.shields.io/github/stars/ai/nanoevents) ![GitHub last commit](https://img.shields.io/github/last-commit/ai/nanoevents)](https://github.com/ai/nanoevents) - Nicer unsubscribe API, but no `*` event, <img align="top" height="24" src="https://img.shields.io/bundlephobia/minzip/nanoevents.svg?label=&color=grey">
- [eev ![GitHub Repo Stars](https://img.shields.io/github/stars/chrisdavies/eev) ![GitHub last commit](https://img.shields.io/github/last-commit/chrisdavies/eev)](https://github.com/chrisdavies/eev) - More of the same, <img align="top" height="24" src="https://img.shields.io/bundlephobia/minzip/eev.svg?label=&color=grey">
- [onfire.js ![GitHub Repo Stars](https://img.shields.io/github/stars/hustcc/onfire.js) ![GitHub last commit](https://img.shields.io/github/last-commit/hustcc/onfire.js)](https://github.com/hustcc/onfire.js) - Also has `.once` method, <img align="top" height="24" src="https://img.shields.io/bundlephobia/minzip/onfire.js.svg?label=&color=grey">

## Reactive Programming

A step up from a raw event emitter, reactive libraries can build chains of event transforms, filters, and side-effects. You can already use these to build UIs by manually updating DOM on state change:

- [flyd ![GitHub Repo Stars](https://img.shields.io/github/stars/paldepind/flyd) ![GitHub last commit](https://img.shields.io/github/last-commit/paldepind/flyd)](https://github.com/paldepind/flyd) - Rx-styled event streams, <img align="top" height="24" src="https://img.shields.io/bundlephobia/minzip/flyd.svg?label=&color=grey">
- [callbag-basics ![GitHub Repo Stars](https://img.shields.io/github/stars/staltz/callbag-basics) ![GitHub last commit](https://img.shields.io/github/last-commit/staltz/callbag-basics)](https://github.com/staltz/callbag-basics) - Rx-style event streams, <img align="top" height="24" src="https://img.shields.io/bundlephobia/minzip/callbag-basics.svg?label=&color=grey">
- [hyperactiv ![GitHub Repo Stars](https://img.shields.io/github/stars/elbywan/hyperactiv) ![GitHub last commit](https://img.shields.io/github/last-commit/elbywan/hyperactiv)](https://github.com/elbywan/hyperactiv) - 4 functions to make objects observable and listen to changes (mobx-style), <img align="top" height="24" src="https://img.shields.io/bundlephobia/minzip/hyperactiv.svg?label=&color=grey">
- [flimsy ![GitHub Repo Stars](https://img.shields.io/github/stars/fabiospampinato/flimsy) ![GitHub last commit](https://img.shields.io/github/last-commit/fabiospampinato/flimsy)](https://github.com/fabiospampinato/flimsy) - Signals from Solid (it _almost_ fit into UI frameworks category itself). Author warning: _it's probably buggy._ <img align="top" height="24" src="https://img.shields.io/bundlephobia/minzip/flimsy.svg?label=&color=grey">

Honorable mention: [oby ![GitHub Repo Stars](https://img.shields.io/github/stars/vobyjs/oby) ![GitHub last commit](https://img.shields.io/github/last-commit/vobyjs/oby)](https://github.com/vobyjs/oby) _could_ make it _if_ it had tree-shaking, but otherwise is around 7 kB.

## State Managers

State managers combine observable state with actions and framework bindings, intended for app-wide state.

- [zustand ![GitHub Repo Stars](https://img.shields.io/github/stars/pmndrs/zustand) ![GitHub last commit](https://img.shields.io/github/last-commit/pmndrs/zustand)](https://github.com/pmndrs/zustand) - Simple stores with pleasant actions and selectors. React <img align="top" height="24" src="https://img.shields.io/bundlephobia/minzip/zustand.svg?label=&color=grey"> or vanilla <img align="top" height="24" src="https://deno.bundlejs.com/?q=zustand/vanilla&badge=">
- [nanostores ![GitHub Repo Stars](https://img.shields.io/github/stars/nanostores/nanostores) ![GitHub last commit](https://img.shields.io/github/last-commit/nanostores/nanostores)](https://github.com/nanostores/nanostores) - Modular store with good tree-shaking support, <img align="top" height="24" src="https://img.shields.io/bundlephobia/minzip/zustand.svg?label=&color=grey">. Lots of framework connectors (e.g. React <img align="top" height="24" src="https://img.shields.io/bundlephobia/minzip/@nanostores/react.svg?label=&color=grey">).
- [exome ![GitHub Repo Stars](https://img.shields.io/github/stars/marcisbee/exome) ![GitHub last commit](https://img.shields.io/github/last-commit/marcisbee/exome)](https://github.com/marcisbee/exome) - Atomic stores with lots of framework connectors, <img align="top" height="24" src="https://img.shields.io/bundlephobia/minzip/exome.svg?label=&color=grey">
- [reatom ![GitHub Repo Stars](https://img.shields.io/github/stars/artalar/reatom) ![GitHub last commit](https://img.shields.io/github/last-commit/artalar/reatom)](https://github.com/artalar/reatom) - Atomic stores for React / svelte / vanilla, <img align="top" height="24" src="https://img.shields.io/bundlephobia/minzip/@reatom/core.svg?label=&color=grey">
- [storeon ![GitHub Repo Stars](https://img.shields.io/github/stars/storeon/storeon) ![GitHub last commit](https://img.shields.io/github/last-commit/storeon/storeon)](https://github.com/storeon/storeon) - Minimal redux-styled store with lots of framework connectors, <img align="top" height="24" src="https://img.shields.io/bundlephobia/minzip/storeon.svg?label=&color=grey">
- [unistore ![GitHub Repo Stars](https://img.shields.io/github/stars/developit/unistore) ![GitHub last commit](https://img.shields.io/github/last-commit/developit/unistore)](https://github.com/developit/unistore) - Centralized store with actions for React / preact, <img align="top" height="24" src="https://img.shields.io/bundlephobia/minzip/unistore.svg?label=&color=grey">
- [teaful ![GitHub Repo Stars](https://img.shields.io/github/stars/teafuljs/teaful) ![GitHub last commit](https://img.shields.io/github/last-commit/teafuljs/teaful)](https://github.com/teafuljs/teaful) - Store with useState-like API for React / preact, <img align="top" height="24" src="https://img.shields.io/bundlephobia/minzip/teaful.svg?label=&color=grey">

## Routers and URL Utils

Do stuff on URL / history changes, with path matching and parsing:

- [wouter ![GitHub Repo Stars](https://img.shields.io/github/stars/molefrog/wouter) ![GitHub last commit](https://img.shields.io/github/last-commit/molefrog/wouter)](https://github.com/molefrog/wouter) - Declarative router for React / preact, <img align="top" height="24" src="https://img.shields.io/bundlephobia/minzip/wouter.svg?label=&color=grey">, also available as a 400-byte hook.
- [@nanostores/router ![GitHub Repo Stars](https://img.shields.io/github/stars/nanostores/router) ![GitHub last commit](https://img.shields.io/github/last-commit/nanostores/router)](https://github.com/nanostores/router) - Routes as a nanostores store (framework-agnostic), <img align="top" height="24" src="https://img.shields.io/bundlephobia/minzip/@nanostores/router.svg?label=&color=grey">
- [navaid ![GitHub Repo Stars](https://img.shields.io/github/stars/lukeed/navaid) ![GitHub last commit](https://img.shields.io/github/last-commit/lukeed/navaid)](https://github.com/lukeed/navaid) - History-based observable router, <img align="top" height="24" src="https://img.shields.io/bundlephobia/minzip/navaid.svg?label=&color=grey">
- [routie ![GitHub Repo Stars](https://img.shields.io/github/stars/jgallen23/routie) ![GitHub last commit](https://img.shields.io/github/last-commit/jgallen23/routie)](https://github.com/jgallen23/routie) - Hash-based observable router, <img align="top" height="24" src="https://img.shields.io/bundlephobia/minzip/routie.svg?label=&color=grey">

Just want to parse or match URL paths without observing them? Here you go:

- [matchit ![GitHub Repo Stars](https://img.shields.io/github/stars/lukeed/matchit) ![GitHub last commit](https://img.shields.io/github/last-commit/lukeed/matchit)](https://github.com/lukeed/matchit) - Route parser and matcher in <img align="top" height="24" src="https://img.shields.io/bundlephobia/minzip/matchit.svg?label=&color=grey">
- [regexparam ![GitHub Repo Stars](https://img.shields.io/github/stars/lukeed/regexparam) ![GitHub last commit](https://img.shields.io/github/last-commit/lukeed/regexparam)](https://github.com/lukeed/regexparam) - Convert path to regexp in <img align="top" height="24" src="https://img.shields.io/bundlephobia/minzip/regexparam.svg?label=&color=grey">
- [qss ![GitHub Repo Stars](https://img.shields.io/github/stars/lukeed/qss) ![GitHub last commit](https://img.shields.io/github/last-commit/lukeed/qss)](https://github.com/lukeed/qss) - Parse querystrings in <img align="top" height="24" src="https://img.shields.io/bundlephobia/minzip/qss.svg?label=&color=grey">. Not sure you need it, [URL API](https://developer.mozilla.org/en-US/docs/Web/API/URL) support is good. 

## API Layer

`fetch` API has some boilerplate associated with it: serialize & parse data, reject on non-200 response, etc. These tiny packages handle it for you:

- [redaxios ![GitHub Repo Stars](https://img.shields.io/github/stars/developit/redaxios) ![GitHub last commit](https://img.shields.io/github/last-commit/developit/redaxios)](https://github.com/developit/redaxios) - Drop-in axios replacement for modern browsers, <img align="top" height="24" src="https://img.shields.io/bundlephobia/minzip/redaxios.svg?label=&color=grey">
- [wretch ![GitHub Repo Stars](https://img.shields.io/github/stars/elbywan/wretch) ![GitHub last commit](https://img.shields.io/github/last-commit/elbywan/wretch)](https://github.com/elbywan/wretch) - Chainable API with error processing and lots of extra plugins, <img align="top" height="24" src="https://img.shields.io/bundlephobia/minzip/wretch.svg?label=&color=grey">
- [gretchen ![GitHub Repo Stars](https://img.shields.io/github/stars/truework/gretchen) ![GitHub last commit](https://img.shields.io/github/last-commit/truework/gretchen)](https://github.com/truework/gretchen) - Chainable API with type-safe errors, <img align="top" height="24" src="https://img.shields.io/bundlephobia/minzip/gretchen.svg?label=&color=grey">

If for some reason you still need a fetch polyfill, try this one:

- [unfetch ![GitHub Repo Stars](https://img.shields.io/github/stars/developit/unfetch) ![GitHub last commit](https://img.shields.io/github/last-commit/developit/unfetch)](https://github.com/developit/unfetch) - Loose fetch polyfill, <img align="top" height="24" src="https://img.shields.io/bundlephobia/minzip/unfetch.svg?label=&color=grey">

## I18N

A map of strings might seem enough to translate an app, but these tools also handle interpolation and some extra goodies:

- [@nanostores/i18n ![GitHub Repo Stars](https://img.shields.io/github/stars/nanostores/i18n) ![GitHub last commit](https://img.shields.io/github/last-commit/nanostores/i18n)](https://github.com/nanostores/i18n) - Detect locale, load dictionaries, format dates / numbers, <img align="top" height="24" src="https://img.shields.io/bundlephobia/minzip/@nanostores/i18n.svg?label=&color=grey">
- [eo-locale ![GitHub Repo Stars](https://img.shields.io/github/stars/ibitcy/eo-locale) ![GitHub last commit](https://img.shields.io/github/last-commit/ibitcy/eo-locale)](https://github.com/ibitcy/eo-locale) - Interpolation and dates / numbers, <img align="top" height="24" src="https://img.shields.io/bundlephobia/minzip/eo-locale.svg?label=&color=grey"> including react bindings.
- [rosetta ![GitHub Repo Stars](https://img.shields.io/github/stars/lukeed/rosetta) ![GitHub last commit](https://img.shields.io/github/last-commit/lukeed/rosetta)](https://github.com/lukeed/rosetta) - Bare-bones template strings (`{{hello}}, {{username}}`) and custom functions for everyting else, <img align="top" height="24" src="https://img.shields.io/bundlephobia/minzip/rosetta.svg?label=&color=grey">
- [lingui ![GitHub Repo Stars](https://img.shields.io/github/stars/lingui/js-lingui) ![GitHub last commit](https://img.shields.io/github/last-commit/lingui/js-lingui)](https://github.com/lingui/js-lingui) - Small core with template strings, <img align="top" height="24" src="https://img.shields.io/bundlephobia/minzip/@lingui/core.svg?label=&color=grey"> (uses build step). Optional react connector: <img align="top" height="24" src="https://img.shields.io/bundlephobia/minzip/@lingui/react.svg?label=&color=grey">

## Dates and Time

Date and time manipulation in pure JS is verbose. Luckily, two of the top date libraries have sensible size:

- [date-fns ![GitHub Repo Stars](https://img.shields.io/github/stars/date-fns/date-fns) ![GitHub last commit](https://img.shields.io/github/last-commit/date-fns/date-fns)](https://github.com/date-fns/date-fns/) - Not tiny as a whole, but [most functions](https://bundlephobia.com/package/date-fns) are under 1 kB each (format and parse are quite heavy).
- [dayjs ![GitHub Repo Stars](https://img.shields.io/github/stars/iamkun/dayjs) ![GitHub last commit](https://img.shields.io/github/last-commit/iamkun/dayjs)](https://github.com/iamkun/dayjs) - _Almost_ moment.js-compatible API, covers most use cases, <img align="top" height="24" src="https://img.shields.io/bundlephobia/minzip/dayjs.svg?label=&color=grey">

And some more packages that only do formatting:

- [tinytime ![GitHub Repo Stars](https://img.shields.io/github/stars/aweary/tinytime) ![GitHub last commit](https://img.shields.io/github/last-commit/aweary/tinytime)](https://github.com/aweary/tinytime) - Simple date / time formatter: `{h}:{mm} -> 9:33`, <img align="top" height="24" src="https://img.shields.io/bundlephobia/minzip/tinytime.svg?label=&color=grey">
- [tinydate ![GitHub Repo Stars](https://img.shields.io/github/stars/lukeed/tinydate) ![GitHub last commit](https://img.shields.io/github/last-commit/lukeed/tinydate)](https://github.com/lukeed/tinydate) - Date / time formatter, only supports padded numeric output (`September -> 09`), <img align="top" height="24" src="https://img.shields.io/bundlephobia/minzip/tinydate.svg?label=&color=grey">
- [time-stamp ![GitHub Repo Stars](https://img.shields.io/github/stars/jonschlinkert/time-stamp) ![GitHub last commit](https://img.shields.io/github/last-commit/jonschlinkert/time-stamp)](https://github.com/jonschlinkert/time-stamp) - More of the same, <img align="top" height="24" src="https://img.shields.io/bundlephobia/minzip/time-stamp.svg?label=&color=grey">
- [ms ![GitHub Repo Stars](https://img.shields.io/github/stars/vercel/ms) ![GitHub last commit](https://img.shields.io/github/last-commit/vercel/ms)](https://github.com/vercel/ms) - Parse & format ms durations, e.g. `"1m" <-> 60000`, <img align="top" height="24" src="https://img.shields.io/bundlephobia/minzip/ms.svg?label=&color=grey">
- [timeago.js ![GitHub Repo Stars](https://img.shields.io/github/stars/hustcc/timeago.js) ![GitHub last commit](https://img.shields.io/github/last-commit/hustcc/timeago.js)](https://github.com/hustcc/timeago.js) - Format dates into stuff like _X minutes ago_ or _in X hours,_ <img align="top" height="24" src="https://img.shields.io/bundlephobia/minzip/timeago.js.svg?label=&color=grey">
- [fromnow ![GitHub Repo Stars](https://img.shields.io/github/stars/lukeed/fromnow) ![GitHub last commit](https://img.shields.io/github/last-commit/lukeed/fromnow)](https://github.com/lukeed/fromnow) - More of the same, <img align="top" height="24" src="https://img.shields.io/bundlephobia/minzip/fromnow.svg?label=&color=grey">

Note that the built-in [`Intl.DateTimeFormat`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Intl/DateTimeFormat) has decent support.

## Generic Utilities

Something you'd find in lodash or ramda, but smaller. Most are pretty similar and very small, with minor differences in package structure (single / package-per-helper) and tree shaking vs direct helper import.

- [remeda ![GitHub Repo Stars](https://img.shields.io/github/stars/remeda/remeda) ![GitHub last commit](https://img.shields.io/github/last-commit/remeda/remeda)](https://github.com/remeda/remeda) - 90 tree-shakable helpers [(list).](https://bundlephobia.com/package/remeda)
- [rambda ![GitHub Repo Stars](https://img.shields.io/github/stars/selfrefactor/rambda) ![GitHub last commit](https://img.shields.io/github/last-commit/selfrefactor/rambda)](https://github.com/selfrefactor/rambda) - 187 tree-shakable helpers [(list).](https://bundlephobia.com/package/rambda)
- [just ![GitHub Repo Stars](https://img.shields.io/github/stars/angus-c/just) ![GitHub last commit](https://img.shields.io/github/last-commit/angus-c/just)](https://github.com/angus-c/just) - 82 helpers in separate packages [(list).](https://anguscroll.com/just/)
- [@tinkoff/utils ![GitHub Repo Stars](https://img.shields.io/github/stars/Tinkoff/utils.js) ![GitHub last commit](https://img.shields.io/github/last-commit/Tinkoff/utils.js)](https://github.com/Tinkoff/utils.js) - 173 helpers, 1 import per helper. Conservative browser target.
- [@fxts/core ![GitHub Repo Stars](https://img.shields.io/github/stars/marpple/FxTS) ![GitHub last commit](https://img.shields.io/github/last-commit/marpple/FxTS)](https://github.com/marpple/FxTS) - 96 tree-shakable helpers. Lazy evaluation support.

Honorable mention: [underscore, ![GitHub Repo Stars](https://img.shields.io/github/stars/jashkenas/underscore) ![GitHub last commit](https://img.shields.io/github/last-commit/jashkenas/underscore)](https://github.com/jashkenas/underscore) contains many sub-1 kB helpers. It does not tree-shake as well as the libraries above due to codebase structure.

Note: lodash itself is not tree-shakable, but has made many attempts at modulaity with `lodash.method` packages, imports from `lodash/method`, and `lodash-es`, none of which work well in practice.

Also note that much of the original lodash functionality comes built-in with modern ES. Prefer native versions over libraries as your browser target allows.

## Unique ID Generation

Unique ID generation does not take a lot of code, but it's not someting I'd want to write myself. Limit is 500 bytes. Also note that the [native `crypto.randomUUID`](https://developer.mozilla.org/en-US/docs/Web/API/Crypto/randomUUID) has [OK support.](https://caniuse.com/mdn-api_crypto_randomuuid)

- [@lukeed/uuid ![GitHub Repo Stars](https://img.shields.io/github/stars/lukeed/uuid) ![GitHub last commit](https://img.shields.io/github/last-commit/lukeed/uuid)](https://github.com/lukeed/uuid) - Real UUIDs, <img align="top" height="24" src="https://img.shields.io/bundlephobia/minzip/@lukeed/uuid.svg?label=&color=grey">
- [nanoid ![GitHub Repo Stars](https://img.shields.io/github/stars/ai/nanoid) ![GitHub last commit](https://img.shields.io/github/last-commit/ai/nanoid)](https://github.com/ai/nanoid) - Random IDs with larger alphabet, <img align="top" height="24" src="https://deno.bundlejs.com/?q=nanoid&badge=">
- [uid ![GitHub Repo Stars](https://img.shields.io/github/stars/lukeed/uid) ![GitHub last commit](https://img.shields.io/github/last-commit/lukeed/uid)](https://github.com/lukeed/uid) - More of the same, <img align="top" height="24" src="https://img.shields.io/bundlephobia/minzip/uid.svg?label=&color=grey">
- [hexoid ![GitHub Repo Stars](https://img.shields.io/github/stars/lukeed/hexoid) ![GitHub last commit](https://img.shields.io/github/last-commit/lukeed/hexoid)](https://github.com/lukeed/hexoid) - Hexadecimal IDs, <img align="top" height="24" src="https://img.shields.io/bundlephobia/minzip/hexoid.svg?label=&color=grey">

## Colors

Color manipulation is rare in pure UI development, but very helpful for data visualization, and uses [freaky math.](https://en.wikipedia.org/wiki/HSL_and_HSV#Color_conversion_formulae) Don't fry your brain, take these:

- [colord ![GitHub Repo Stars](https://img.shields.io/github/stars/omgovich/colord) ![GitHub last commit](https://img.shields.io/github/last-commit/omgovich/colord)](https://github.com/omgovich/colord) - Manipulate colors and convert between spaces, <img align="top" height="24" src="https://img.shields.io/bundlephobia/minzip/colord.svg?label=&color=grey">. Extra features come as plugins, 150b to 1.5 kB each.
- [colr ![GitHub Repo Stars](https://img.shields.io/github/stars/stayradiated/colr) ![GitHub last commit](https://img.shields.io/github/last-commit/stayradiated/colr)](https://github.com/stayradiated/colr) - More of the same, <img align="top" height="24" src="https://img.shields.io/bundlephobia/minzip/colr.svg?label=&color=grey" >
- [polychrome ![GitHub Repo Stars](https://img.shields.io/github/stars/cdonohue/polychrome) ![GitHub last commit](https://img.shields.io/github/last-commit/cdonohue/polychrome)](https://github.com/cdonohue/polychrome) - More of the same, <img align="top" height="24" src="https://img.shields.io/bundlephobia/minzip/polychrome.svg?label=&color=grey">
- [randomcolor ![GitHub Repo Stars](https://img.shields.io/github/stars/davidmerfield/randomColor) ![GitHub last commit](https://img.shields.io/github/last-commit/davidmerfield/randomColor)](https://github.com/davidmerfield/randomColor) - Attractive random colors with configuration. <img align="top" height="24" src="https://img.shields.io/bundlephobia/minzip/randomcolor.svg?label=&color=grey">

## Touch Gestures

Touch gestures like swipe, drag, pinch or doubletap are a staple of mobile UX, but recognizing a series of touchmove / pointer events as a gesture is tricky, and testing is painful. Here are two libraries that do the heavy lifting for you:

- [alloyfinger ![GitHub Repo Stars](https://img.shields.io/github/stars/AlloyTeam/AlloyFinger) ![GitHub last commit](https://img.shields.io/github/last-commit/AlloyTeam/AlloyFinger)](https://github.com/AlloyTeam/AlloyFinger) - Pan, swipe, tap, doubletap, longpress, _and_ pinch / rotate. My personal favorite. <img align="top" height="24" src="https://deno.bundlejs.com/?q=alloyfinger&badge=">.
- [tinygesture ![GitHub Repo Stars](https://img.shields.io/github/stars/sciactive/tinygesture) ![GitHub last commit](https://img.shields.io/github/last-commit/sciactive/tinygesture)](https://github.com/sciactive/tinygesture) - Configurable pan, swipe, tap, doubletap, longpress. <img align="top" height="24" src="https://deno.bundlejs.com/?q=tinygesture&badge=">.

Even if you want to detect gestures yourself, juggling mouse, touch and pointer events is hard enough, and browser inconsistencies don't help. Here are two more libraries to assist with that:

- [pointer-tracker ![GitHub Repo Stars](https://img.shields.io/github/stars/GoogleChromeLabs/pointer-tracker) ![GitHub last commit](https://img.shields.io/github/last-commit/GoogleChromeLabs/pointer-tracker)](https://github.com/GoogleChromeLabs/pointer-tracker) - Unified interface for mouse, touch and pointer events, <img align="top" height="24" src="https://deno.bundlejs.com/?q=pointer-tracker&badge=">
- [detect-it ![GitHub Repo Stars](https://img.shields.io/github/stars/rafgraph/detect-it) ![GitHub last commit](https://img.shields.io/github/last-commit/rafgraph/detect-it)](https://github.com/rafgraph/detect-it) - Detect present and primary input method (touch / mouse) and supported events, <img align="top" height="24" src="https://deno.bundlejs.com/?q=detect-it&badge=">

Honorable mentions: [any-touch ![GitHub Repo Stars](https://img.shields.io/github/stars/any86/any-touch) ![GitHub last commit](https://img.shields.io/github/last-commit/any86/any-touch)](https://github.com/any86/any-touch) attempts a modular approach to gesture detection, but the core is around 2 kB without any gesture recognizers. [rc-gesture, ![GitHub Repo Stars](https://img.shields.io/github/stars/react-component/gesture) ![GitHub last commit](https://img.shields.io/github/last-commit/react-component/gesture)](https://github.com/react-component/gesture) used in ant design system, could be the only react component on the list, but babel-runtime / corejs polyfills hard-wired into the build push the ~2.5 kB size to over 10 kB.

## Text Search

Text search is important for client-side filtering and autosuggests. Naive `option.includes(search)` has no sensible order on the results, and ignoring word boundaries gives unexpected matches like _spa -> newSPAper._ First, here are some libraries that prioritize word matches:

- [js-search ![GitHub Repo Stars](https://img.shields.io/github/stars/bvaughn/js-search) ![GitHub last commit](https://img.shields.io/github/last-commit/bvaughn/js-search)](https://github.com/bvaughn/js-search) - Feature-rich and customizable: multi-field indices, stop words, custom stemmers and tokenizers. <img align="top" height="24" src="https://deno.bundlejs.com/?q=js-search&treeshake=[{+Search+}]&badge=">
- [ndx ![GitHub Repo Stars](https://img.shields.io/github/stars/localvoid/ndx) ![GitHub last commit](https://img.shields.io/github/last-commit/localvoid/ndx)](https://github.com/localvoid/ndx) - Similar to js-search, differs in [ranking](https://kmwllc.com/index.php/2020/03/20/understanding-tf-idf-and-bm-25/) and is less strict for multi-word queries [(compare)](https://leeoniya.github.io/uFuzzy/demos/compare.html?libs=js-search,ndx,Wade&search=twilight%20sag). Supports field weights. <img align="top" height="24" src="https://deno.bundlejs.com/?q=ndx,ndx/query&badge=">
- [wade ![GitHub Repo Stars](https://img.shields.io/github/stars/kbrsh/wade) ![GitHub last commit](https://img.shields.io/github/last-commit/kbrsh/wade)](https://github.com/kbrsh/wade) - Also similar, [(compare)](https://leeoniya.github.io/uFuzzy/demos/compare.html?libs=js-search,Wade,ndx&search=twilight%20sag) <img align="top" height="24" src="https://deno.bundlejs.com/?q=wade&badge=">
- [libsearch ![GitHub Repo Stars](https://img.shields.io/github/stars/thesephist/libsearch) ![GitHub last commit](https://img.shields.io/github/last-commit/thesephist/libsearch)](https://github.com/thesephist/libsearch) - Index-free search (slower, but easier to use) with sane ordering <img align="top" height="24" src="https://deno.bundlejs.com/?q=libsearch&badge=">

One way to find sensible inexact matches is _stemming_ — converting words to a root form. _Walked_ will match _walking,_ etc. Here are a few [Porter stemmers](https://vijinimallawaarachchi.com/2017/05/09/porter-stemming-algorithm/) for English language:

- [stemmer ![GitHub Repo Stars](https://img.shields.io/github/stars/words/stemmer) ![GitHub last commit](https://img.shields.io/github/last-commit/words/stemmer)](https://github.com/words/stemmer) - <img align="top" height="24" src="https://deno.bundlejs.com/?q=stemmer&badge=">
- [porter-stemmer ![GitHub Repo Stars](https://img.shields.io/github/stars/jedp/porter-stemmer) ![GitHub last commit](https://img.shields.io/github/last-commit/jedp/porter-stemmer)](https://github.com/jedp/porter-stemmer) - <img align="top" height="24" src="https://deno.bundlejs.com/?q=porter-stemmer&badge=">

For non-English words, I only have honorable mentions: [snowball-js ![GitHub Repo Stars](https://img.shields.io/github/stars/fortnightlabs/snowball-js) ![GitHub last commit](https://img.shields.io/github/last-commit/fortnightlabs/snowball-js)](https://github.com/fortnightlabs/snowball-js) is 17 kB with 15 languages, [lunr-languages ![GitHub Repo Stars](https://img.shields.io/github/stars/MihaiValentin/lunr-languages) ![GitHub last commit](https://img.shields.io/github/last-commit/MihaiValentin/lunr-languages)](https://github.com/MihaiValentin/lunr-languages) supports 30 languages but only works with [lunr, ![GitHub Repo Stars](https://img.shields.io/github/stars/olivernn/lunr.js) ![GitHub last commit](https://img.shields.io/github/last-commit/olivernn/lunr.js)](https://github.com/olivernn/lunr.js) the most promising one is [natural ![GitHub Repo Stars](https://img.shields.io/github/stars/NaturalNode/natural) ![GitHub last commit](https://img.shields.io/github/last-commit/NaturalNode/natural)](https://github.com/NaturalNode/natural/tree/master/lib/natural/stemmers) but it depends on Node.js.

### Fuzzy search

__Fuzzy search__ is another take on inexact matching — the words can be modified. First, we have libraries that only allow insertion: spacecat -> SPACECrAfT. Not perfect for general-purpose text search, but great for filename, command, or URL lookups.

- [fuzzy ![GitHub Repo Stars](https://img.shields.io/github/stars/mattyork/fuzzy) ![GitHub last commit](https://img.shields.io/github/last-commit/mattyork/fuzzy)](https://github.com/mattyork/fuzzy) - Index-free, can highlight matches. <img align="top" height="24" src="https://deno.bundlejs.com/?q=fuzzy&badge=">
- [fuzzy-search ![GitHub Repo Stars](https://img.shields.io/github/stars/wouterrutgers/fuzzy-search) ![GitHub last commit](https://img.shields.io/github/last-commit/wouterrutgers/fuzzy-search)](https://github.com/wouterrutgers/fuzzy-search) - With stateful index. <img align="top" height="24" src="https://deno.bundlejs.com/?q=fuzzy-search&treeshake=[{+default+}]&badge=">
- [fzy.js ![GitHub Repo Stars](https://img.shields.io/github/stars/jhawthorn/fzy.js) ![GitHub last commit](https://img.shields.io/github/last-commit/jhawthorn/fzy.js)](https://github.com/jhawthorn/fzy.js) - Matches one string at a time, tree-shakeable scores and match highlighting. <img align="top" height="24" src="https://deno.bundlejs.com/?q=fzy.js&badge="> total, or ~150 bytes for `hasMatch` only.
- [fuzzysearch ![GitHub Repo Stars](https://img.shields.io/github/stars/bevacqua/fuzzysearch) ![GitHub last commit](https://img.shields.io/github/last-commit/bevacqua/fuzzysearch)](https://github.com/bevacqua/fuzzysearch) -  One string at a time, does not compute score / rank. <img align="top" height="24" src="https://deno.bundlejs.com/?q=fuzzysearch&badge=">
- [liquidmetal ![GitHub Repo Stars](https://img.shields.io/github/stars/rmm5t/liquidmetal) ![GitHub last commit](https://img.shields.io/github/last-commit/rmm5t/liquidmetal)](https://github.com/rmm5t/liquidmetal) - Quicksilver algorithm, prioritizes matches at start of word for command abbreviations (e.g. `gp` -> `git push`). One string at a time. <img align="top" height="24" src="https://deno.bundlejs.com/?q=liquidmetal&badge=">
- [quick-score ![GitHub Repo Stars](https://img.shields.io/github/stars/fwextensions/quick-score) ![GitHub last commit](https://img.shields.io/github/last-commit/fwextensions/quick-score)](https://github.com/fwextensions/quick-score) - Another quicksilver-based lib, tweaked for long strings. Built-in list filtering and sorting, <img align="top" height="24" src="https://deno.bundlejs.com/?q=quick-score&badge="> or 1.2 kB for single-string scoring.

Finally, one library is specifically built for spellchecking:

- [fuzzyset ![GitHub Repo Stars](https://img.shields.io/github/stars/Glench/fuzzyset.js) ![GitHub last commit](https://img.shields.io/github/last-commit/Glench/fuzzyset.js)](https://github.com/Glench/fuzzyset.js) - Find misspellings, e.g. missipissi -> Missisipi, <img align="top" height="24" src="https://deno.bundlejs.com/?q=fuzzyset&badge="> Commercial usage costs $42.


## Contributing

Suggestions welcome! See [contributing.md](contributing.md), or drop an [issue ![GitHub Repo Stars](https://img.shields.io/github/stars/thoughtspile/awesome-tiny-js) ![GitHub last commit](https://img.shields.io/github/last-commit/thoughtspile/awesome-tiny-js)](https://github.com/thoughtspile/awesome-tiny-js/issues).

## Footnotes

See [WIP](wip.md) for possibly awesome libraries I have found, but not yet analyzed deeply, and [incubate](incubate.md) for awesome libraries that don't meet popularity criteria yet.

Collected and reviewed by [Vladimir Klepov](https://blog.thoughtspile.tech) in 2023.
