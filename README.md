# Khmer Line Breaker

The lightweight Khmer line breaker with no dependencies.

```
npm install khmer-line-breaker
```

```js
import parse from "khmer-line-breaker";

const tokens = parse("មិនដឹងទេលោកព្រះ")
console.log(tokens);

// => [ 'មិន', 'ដឹង', 'ទេ', 'លោក', 'ព្រះ' ]
```

## License

`MIT`

## Reference

- [google/budoux](https://github.com/google/budoux)
- [Asian Language Treebank (ALT) Project](https://www2.nict.go.jp/astrec-att/member/mutiyama/ALT/)
- [ye-kyaw-thu/khPOS/](https://github.com/ye-kyaw-thu/khPOS/)


## Evaluation

```
train accuracy: 0.95734
train prec.:    0.91397
train recall:   0.91331
train fscore:   0.91364
```