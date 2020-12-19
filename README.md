# GPT-3 as a Text Summarizer (EENG 439 Final Paper)

Initialize the file `config.py` to export your OpenAI API key as `config.key`.

## Summary Statistics

### Comparison with SOTA: ROUGE f-measure

| Model                                       | ROUGE-1 | ROUGE-2 | ROUGE-L |
| ------------------------------------------- | ------- | ------- | ------- |
| GPT-3 Davinci 10 shot                       | 26.63   | 8.08    | 24.22   |
| ControlCopying (Song et al., 2020)          | 39.08   | 20.47   | 36.69   |
| ProphetNet(Yan, Qi, Gong, Liu et al., 2020) | 39.51   | 20.42   | 36.69   |
| UniLM (Dong et al., 2019)                   | 38.90   | 20.05   | 36.00   |

### ROUGE-1 f-measure by engine

|         | Ada   | Babbage | Curie | Davinci |
| ------- | ----- | ------- | ----- | ------- |
| 0-shot  | 06.02 | 05.78   | 08.08 | 07.92   |
| 1-shot  | 07.14 | 08.59   | 14.28 | 20.07   |
| 10-shot | 13.23 | 14.47   | 18.34 | 26.63   |
