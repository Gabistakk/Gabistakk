## [emerenciano.dev](https://emerenciano.dev)

```
export default function me(){
  const personality = () => {
    return [
      'coding',
      'karate/mma',
      'gaming',
      'chess',
      'thinking differently',
    ]
  }
  const musicTaste = (input) => {
    if(input == 'soundcloud'){
      return [
          'https://soundcloud.com/user-835086313/what-we-did-in-the-desert',
          'https://soundcloud.com/brainfuckedbutdeadly/nada-contra-ciume'
          ]
    }
    if(input == 'profile'){
      return 'https://soundcloud.com/gabistakk';
    }
    return 'anything really.'
  }
}
```
