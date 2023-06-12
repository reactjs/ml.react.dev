---
title: ഇൻസ്റ്റലേഷൻ
---

<Intro>
React രൂപകൽപ്പന ചെയ്തിരിക്കുന്നത് പടിപടിയായി ഉപയോഗിക്കാൻ എളുപ്പമുള്ള തരത്തിലാണ്. നിങ്ങൾക്ക് ഇഷ്ടമുള്ളത്രയും കുറച്ചോ എങ്ങനെ വേണമെങ്കിലും React ഉപയോഗിക്കാം. നിങ്ങൾക്ക് React പരീക്ഷിക്കണ്ണമോ? അല്ലെങ്കിൽ, ഒരു അടിസ്ഥാനമായ HTML പേജിലേക്ക് ചില സംവിധാനങ്ങൾ ചേർക്കണമോ? അതുമല്ലെങ്കിൽ, React ഉപയോഗിച്ച് പ്രവർത്തിക്കുന്ന കൂടുതൽ ന്യൂതനമായ അപ്ലിക്കേഷൻ നിർമിക്കാൻ നിങ്ങൾ തയ്യാറാണോ? എങ്കിൽ ഈ സെക്ഷനുകൾ ഇവകൾ ആരംഭിക്കുന്നതിനായി നിങ്ങളെ സഹായിക്കും.
</Intro>

<YouWillLearn isChapter={true}>

* [എങ്ങനെ ഒരു പുതിയ React പ്രോജക്റ്റ് ആരംഭിക്കാം](/learn/start-a-new-react-project)
* [എങ്ങനെ നിലവിലുള്ള ഒരു പ്രോജക്റ്റിലേക്ക് React ചേർക്കാം](/learn/add-react-to-an-existing-project)
* [എങ്ങനെ നിങ്ങളുടെ എഡിറ്റർ സജ്ജീകരിക്കാം](/learn/editor-setup)
* [എങ്ങനെ റിയാക്റ്റ് ഡെവലപ്പർ ടൂളുകൾ ഇൻസ്റ്റാൾ ചെയ്യാം](/learn/react-developer-tools)

</YouWillLearn>

## React ഉപയോഗിക്കാം {/*try-react*/}

React ഉപയോഗിക്കാൻ നിങ്ങൾ ഒന്നും ഇൻസ്റ്റാൾ ചെയ്യേണ്ടതില്ല. ഈ സാൻഡ്ബോക്സ് എഡിറ്റ് ചെയ്യൂ!

<Sandpack>

```js
function Greeting({ name }) {
  return <h1>Hello, {name}</h1>;
}

export default function App() {
  return <Greeting name="world" />
}
```

</Sandpack>

നിങ്ങൾക്ക് ഇത് നേരിട്ട് എഡിറ്റ് ചെയ്യാം അല്ലെങ്കിൽ മുകളിൽ വലതുവശത്തുള്ള "Fork" ബട്ടൺ അമർത്തി പുതിയ ടാബിൽ തുറക്കാം.

React ഡോക്യുമെന്റേഷനിലെ മിക്ക പേജുകളിലും ഇതുപോലുള്ള സാൻഡ്ബോക്സുകൾ ഉണ്ട്. React ഡോക്യുമെന്റേഷനു പുറമെ, React-നെ  സപ്പോർട്ട് നിരവധി ഓൺലൈൻ സാൻഡ്ബോക്സുകൾ ഉണ്ട്: ഉദാഹരണത്തിന്, [CodeSandbox](https://codesandbox.io/s/new), [StackBlitz](https://stackblitz.com/fork/react), അല്ലെങ്കിൽ [CodePen.](https://codepen.io/pen?&editors=0010&layout=left&prefill_data_id=3f4569d1-1b11-4bce-bd46-89090eed5ddb)

### React ലോക്കലിൽ ഉപയോഗിക്കാം {/*try-react-locally*/}

നിങ്ങളുടെ കമ്പ്യൂട്ടറിൽ React പരീക്ഷിക്കുന്നതിന്, [ഈ HTML പേജ് ഡൗൺലോഡ് ചെയ്യുക.](https://gist.githubusercontent.com/gaearon/0275b1e1518599bbeafcde4722e79ed1/raw/db72dcbf3384ee1708c4a07d3be79860db04bff0/example.html) നിങ്ങളുടെ എഡിറ്ററിലും ബ്രൗസറിലും ഇത് തുറക്കുക!

## ഒരു പുതിയ React പ്രോജക്റ്റ് ആരംഭിക്കാം {/*start-a-new-react-project*/}

നിങ്ങൾക്ക് React ഉപയോഗിച്ച് പൂർണ്ണമായും ഒരു ആപ്പോ വെബ്‌സൈറ്റോ നിർമ്മിക്കണമെങ്കിൽ, [ഒരു പുതിയ റിയാക്റ്റ് പ്രോജക്റ്റ് തുടങ്ങാം.](/learn/start-a-new-react-project)

## നിലവിലുള്ള ഒരു പ്രോജക്റ്റിലേക്ക് React ചേർക്കാം {/*add-react-to-an-existing-project*/}

നിങ്ങളുടെ നിലവിലുള്ള ആപ്പിലോ വെബ്‌സൈറ്റിലോ React ഉപയോഗിക്കണമെങ്കിൽ, [നിലവിലുള്ള ഒരു പ്രോജക്റ്റിലേക്ക് റിയാക്റ്റ് ചേർക്കാം.](/learn/add-react-to-an-existing-project)

## അടുത്ത ഘട്ടങ്ങൾ {/*next-steps*/}

എല്ലാ ദിവസവും നിങ്ങൾ അഭിമുഖീകരിക്കുന്ന ഏറ്റവും പ്രധാനപ്പെട്ട React ആശയങ്ങളെ സംബന്ധിച്ചു അറിയുവാനായി [Quick Start Guide](/learn) കാണുക.

