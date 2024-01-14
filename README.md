# Canarim-Bert-Nheengatu

<p align="center">
  <img width="350" alt="Camarim Logo" src="https://raw.githubusercontent.com/DominguesM/canarim-bert-nheengatu/main/assets/canarim-yrl-nbg.png">
</p>

</br>

## Introduction

Canarim-Bert-Nheengatu is a BERT model pre-trained for the Nheengatu language, an indigenous language spoken in Brazil. The model was trained with the aim of being used in NLP (Natural Language Processing) tasks for the Nheengatu language, thereby aiding in the development of resources for the language.

## Nheengatu

Nheengatu, also known as modern Tupi and Amazonian General Language, among other names, is one of the dozens of still living Brazilian indigenous languages. The term Nheengatu emerged around the mid-19th century, originally meaning "good language," a result of the composition of the noun nheenga 'language' and the adjective katú 'good'. In the ISO 639-3 standard, it is represented by the code `yrl`, derived from yeral (general in Portuguese), one of the terms by which it is designated in Spanish.

The study of Nheengatu is of great historical importance, as it was, for two and a half centuries, in the words of José Ribamar Bessa Freire, “the main language of the Amazon”, a position it would lose to Portuguese only in the second half of the 19th century. It is perhaps the only Brazilian indigenous language whose development over more than four centuries can be traced through texts that document its various stages of evolution. (Source: [Leonel Figueiredo de Alencar - CompLin](https://github.com/CompLin/nheengatu/blob/main/nheengatu.md))

## Training Data

To train the model, an extensive collection of Nheengatu text data was gathered, extracted from various sources such as books, articles, websites, etc. The data were cleaned and prepared for model training. Below is a table with all the sources used for training the model.

<details>
  <summary>References (ABNT)</summary>
  
  ```
    AMORIM, DE. Lendas em nheengatu e em português. [s.l.] Fundo Editorial-ACA, 1987.

    ARGOLO, W. Colonização e língua geral: o caso do sul da bahia. Papia, v. 23, p. 75–96, 2013.

    ÁVILA, M. T.; TREVISAN, R. G. Jaguanhenhém: um estudo sobre a linguagem do iauaretê. Magma, v. 22, p. 297–335, 2015.

    AYROSA, P. Diccionario portuguez-brasiliano e brasiliano-portuguez. [s.l.] Imprensa official do estado, 1934.

    AYROSA, P. Orações e diálogos da doutrina cristã na língua brasílica: Mss. do séc. XVIII. [s.l.] Universidade de São Paulo, Faculdade de Filosofia, Ciências e Letras, 1950.

    AYROSA, P. Apontamentos para a bibliografia da língua tupi-guarani. [s.l.] Universidade de São Paulo, 1954.

    BARROS, C.; LESSA, A. L. Dicionário da língua geral do brasil. [s.l.] MPEG, 2015.

    BASTOS, A. A pantofagia, ou, As estranhas práticas alimentares na selva: estudo na região amazônica. [s.l.] Companhia Editora Nacional, 1987.

    BORGES, L. C. A lingua geral amazonica : aspectos de sua fonemica. Disponível em: <https://repositorio.unicamp.br/acervo/detalhe/30265>. Acesso em: 29 dez. 2023.

    BRASIL. [CONSTITUIÇÃO (1988)]. “MUNDU SA TURUSU” WAÁ ŨBÊUWA MAYÉ MÍRA ITÁ UIKÚ ARÃMA PURÃGA IKÉ BRAZIU UPÉ. Brasília, DF: Presidente Da República, 19 jul. 2023. Disponível em: <https://www.cnj.jus.br/wp-content/uploads/2023/07/constituicao-nheengatu-web.pdf>. Acesso em: 29 dez. 2023.

    CÂNDIDA, M. A relação entre manuscritos e impressos em tupi como forma de estudo da política linguística jesuítica no século XVIII na Amazônia. Revista Letras, v. 61, 2003.

    CÂNDIDA, M.; MARQUES, M. Passagens do livro “Itinerário para Párocos de Índios”, de Peña Montenegro (1668), em um confessionário jesuítico setecentista da Amazônia. Boletim do Museu Paraense Emílio Goeldi. Ciências Humanas, v. 5, n. 3, p. 669–679, 1 dez. 2010.

    COSTA, A. Doutrina christã destinada aos naturaes do Amazonas em nhihingatu: com tradução portugueza em face. [s.l.] Pacheco Silva, 1898.

    DA CRUZ, A. O Estatuto das Fricativas na Língua Geral Amazônica: IX Encontro dos Alunos de Pós-Graduação em Lingüística da Universidade de São Paulo. Afinal, o que, nós, fazemos? Seleção de textos proferidos durante o IX Encontro dos Alunos de Pós-Graduação em Lingüística da Universidade de São Paulo., 2007.

    DA CRUZ, A. Fonologia e gramática do nheengatú. [s.l.] LOT, 2011.

    DE FARIA, F. R. C. Compendio da lingua brazilica para uzo dos que a ella se quizerem dedicar. [s.l.] Typ. de Santos & Filhos, 1858.

    DE MAGALHÃES, C. O selvagem: I. Curso da lingua geral segundo Ollendorf, comprehendendo o texto original de lendas tupìs. II. Origens, costumes, região selvagem, methodo a empregar para amansalos por intermedio das colonias militares e do interprete militar. [s.l.] Livrària Popular, 1876.

    ECKART, A.; PLATZMANN, J. Anselmi eckarti specimen linguae brasilicae vulgaris. [s.l.] B.G. Teubner, 1890.

    EDELWEISS, F. G. Estudos tupis e tupi-guaranis: confrontos e revisões. [s.l.] Livraria Brasiliana Editôra, 1969.

    ERMANNO, S. Leggenda dell’Jurupary. Bolletino Della Societá Geografica Italiana, v. 3, p. 659–689, 1890.

    FERNANDES, A. Grammatica tupy. [s.l.] Livraria Araripe, 1924.

    FREIRE, J. R. B.; ROSA, M. C. Línguas Gerais: política linguística e Catequese na América do Sul no período colonial. [s.l.] Editora da Universidade do Estado do Rio de Janeiro, 2003.

    HARTT, C. F. Notes on the Lingoa geral or modern Tupí of the Amazonas. Boston: [s.n.].

    HARTT, C. F. Contribuicões para a ethnologia do valle do Amazonas. [s.l.] Typ. e lith. economica, de Machado & c., 1885.

    HARTT, C. F.; BIBLIOTECA NACIONAL (BRAZIL). Notas sobre a língua geral, ou tupí moderno do Amazonas. [s.l.] Serviço gráfico do Ministério da educação e saude, 1938.

    ISHIKAWA, N. K.; MORGANS, S. Brilhos na floresta. [s.l.] Selene Morgans, 2019.

    KITTIYA, L. M. Conversing in colony: the Brasílica and the Vulgar in Portuguese America, 1500–1759. [s.l.] The Johns Hopkins University, 2006.

    MASUCCI, O. Dicionário tupi portugués e vice-versa: com um dicionário de topográficos. [s.l.] Brasilivros, 1979.

    MELLO, O. Dicionário tupi (nheengatu) português e vice-versa: comum dicionário de rimas tupi. [s.l.] F. Masucci, 1967.

    MICHAELE, F. A. S. Manual de conversação de lingua tupi: 1a. série, 20 lições. [s.l.] Centro Cultural “Euclides da Cunha”, 1951.

    MOORE, D.; FACUNDES, S.; PIRES, N. Nheengatu (Língua Geral Amazônica), its History, and the Effects of Language Contact. escholarship.org, 1994.

    MULLER, J. C. et al. Dicionário de língua geral amazônica: 1a parte: Português–Língua geral - 2a parte: Língua Geral–Português. [s.l.] Universitat Potsdam, 2019.

    NIMUENDAJÚ, C.; ATHIAS, R. Reconhecimento dos rios içána, ayarí e uaupés: apontamentos linguísticos e ensaio fotográfico. [s.l.] Museo do Indio FUNAI, 2015.

    OLIVEIRA, R. L. G. DE. Natureza e direções das mudanças lexicais ocorridas na língua geral Amazônica do século XVII. icts.unb.br, 11 out. 2010.

    ORICO, O. Mitos ameríndios e crendices amazônicas. [s.l.] Civilização Brasileira, 1975.

    PLATZMANN, J. O diccionario anonymo da lingua geral do Brasil publicado de novo com o seu reverso por Julio Platzmann. [s.l.] B.G. Teubner, 1896.

    QUEIXALÓS, F.; GOMES, D. M. O sintagma nominal em línguas amazônicas. [s.l.] Pontes, 2016.

    RODRIGUES, A. D.; SUELLY, A. A contribution to the linguistic history of the língua geral amazônica. Alfa: Revista de Linguística (São José do Rio Preto), v. 55, p. 613–639, 2011.

    RODRIGUES, J. B. Vocabulario indigena com a orthographia correcta: (complemento da Poranduba amazonense). [s.l.] Bibliotheca Nacional, 1893.

    RODRIGUES, J. B. Mbaé kaá tapyiyetá enoyndaua ou A botanica ea nomenclatura indigena. [s.l.] Imprensa Nacional, 1905.

    SILVA, DA; DE, C. Discoteca etno-linguístico-musical das tribos dos rios uaupés, içana e cauaburi. [s.l.] Centro de Pesquisas de Iauareté, 1961.

    VERÍSSIMO, J. As populações Indigenas e Mestiças da Amazonia: linguagem, crenças e costumes. Rio de Janeiro: [s.n.].

    VERÍSSIMO, J. Estudos amazônicos. [s.l.] Universidade Federal do Pará, 1970. v. 1.
  ```
</details>


## Available Models

| Model | Arch. | #Layers | #Params | #Task |
| ------ | ----------- | ------- | ------- | ------- |
| [Canarim-Bert-Nheengatu](https://huggingface.co/dominguesm/canarim-bert-nheengatu) | Bert | 12 | 110M | MLM |
| [Canarim-Bert-PosTag-Nheengatu](https://huggingface.co/dominguesm/canarim-bert-postag-nheengatu) | Bert | 12 | 110M | Token Classification |


## How to Use

```python
from transformers import pipeline

pipe = pipeline('fill-mask', "dominguesm/canarim-bert-nheengatu")

# ptbr: Ele tinha febre, por isso não foi pescar.
# yrl: Aé urikú takuwa yawé resewara ti usú upinaitika.
pipe('Aé urikú takuwa yawé [MASK] ti usú upinaitika.')
# [{'score': 0.41232067346572876,
#   'token': 460,
#   'token_str': 'tẽ',
#   'sequence': 'Aé urikú takuwa yawé tẽ ti usú upinaitika.'},
#  {'score': 0.1178387925028801,
#   'token': 665,
#   'token_str': 'resewara',
#   'sequence': 'Aé urikú takuwa yawé resewara ti usú upinaitika.'},
#  {'score': 0.029453271999955177,
#   'token': 2168,
#   'token_str': 'artigu',
#   'sequence': 'Aé urikú takuwa yawé artigu ti usú upinaitika.'},
#  {'score': 0.027277836576104164,
#   'token': 669,
#   'token_str': 'sikuyaára',
#   'sequence': 'Aé urikú takuwa yawé sikuyaára ti usú upinaitika.'},
#  {'score': 0.020948367193341255,
#   'token': 642,
#   'token_str': 'akayu',
#   'sequence': 'Aé urikú takuwa yawé akayu ti usú upinaitika.'}]

```

### License (canarim-bert-nheengatu)

This model is licensed under the [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) license. 

<br/>
<br/>


# Canarim-Bert-PosTag-Nheengatu

## About

The `canarim-bert-posTag-nheengatu` model is a part-of-speech tagging model for the Nheengatu language, trained using the `UD_Nheengatu-CompLin` dataset available on [github](https://github.com/UniversalDependencies/UD_Nheengatu-CompLin/). It is based on the tokenizer and the [`Canarim-Bert-Nheengatu`](https://huggingface.co/dominguesm/canarim-bert-nheengatu) model.


## Supported Tags

The model can identify the following grammatical classes:

|**tag**|**abbreviation in glossary**|**expansion of abbreviation**|
|-------|-----------------------------|-----------------------------|
|ADJ|adj.|1st class adjective|
|ADP|posp.|postposition|
|ADV|adv.|adverb|
|AUX|aux.|auxiliary|
|CCONJ|cconj.|coordinating conjunction|
|DET|det.|determiner|
|INTJ|interj.|interjection|
|NOUN|n.|1st class noun|
|NUM|num.|numeral|
|PART|part.|particle|
|PRON|pron.|1st class pronoun|
|PROPN|prop.|proper noun|
|PUNCT|punct.|punctuation|
|SCONJ|sconj.|subordinating conjunction|
|VERB|v.|1st class verb|

## Training

### Dataset

The dataset used for training was the [`UD_Nheengatu-CompLin`](https://github.com/UniversalDependencies/UD_Nheengatu-CompLin/), divided into 80/10/10 proportions for training, evaluation, and testing, respectively.


```
DatasetDict({
    train: Dataset({
        features: ['id', 'tokens', 'pos_tags', 'text'],
        num_rows: 1068
    })
    test: Dataset({
        features: ['id', 'tokens', 'pos_tags', 'text'],
        num_rows: 134
    })
    eval: Dataset({
        features: ['id', 'tokens', 'pos_tags', 'text'],
        num_rows: 134
    })
})
```

### Hyperparameters

The hyperparameters used for training were:

* `learning_rate`: 3e-4
* `train_batch_size`: 16
* `eval_batch_size`: 32
* `gradient_accumulation_steps`: 1
* `weight_decay`: 0.01
* `num_train_epochs`: 10

### Results

The training and validation loss over the steps can be seen below:

<p align="center">
  <img width="600" alt="Train Loss" src="https://raw.githubusercontent.com/DominguesM/canarim-bert-nheengatu/main/assets/postag-train-loss.png">
</p>

<p align="center">
  <img width="600" alt="Eval Loss" src="https://raw.githubusercontent.com/DominguesM/canarim-bert-nheengatu/main/assets/postag-eval-loss.png">
</p>

The model's results on the evaluation set can be viewed below:

```
{
  'eval_loss': 0.5337784886360168,
  'eval_precision': 0.913735899137359,
  'eval_recall': 0.913735899137359,
  'eval_f1': 0.913735899137359,
  'eval_accuracy': 0.913735899137359,
  'eval_runtime': 0.1957,
  'eval_samples_per_second': 684.883,
  'eval_steps_per_second': 25.555,
  'epoch': 10.0
}
```

### Metrics

The model's evaluation metrics on the test set can be viewed below:

```
                precision    recall  f1-score   support
         ADJ     0.7895    0.6522    0.7143        23
         ADP     0.9355    0.9158    0.9255        95
         ADV     0.8261    0.8172    0.8216        93
         AUX     0.9444    0.9189    0.9315        37
       CCONJ     0.7778    0.8750    0.8235         8
         DET     0.8776    0.9149    0.8958        47
        INTJ     0.5000    0.5000    0.5000         4
        NOUN     0.9257    0.9222    0.9239       270
         NUM     1.0000    0.6667    0.8000         6
        PART     0.9775    0.9062    0.9405        96
        PRON     0.9568    1.0000    0.9779       155
       PROPN     0.6429    0.4286    0.5143        21
       PUNCT     0.9963    1.0000    0.9981       267
       SCONJ     0.8000    0.7500    0.7742        32
        VERB     0.8651    0.9347    0.8986       199
   micro avg     0.9202    0.9202    0.9202      1353
   macro avg     0.8543    0.8135    0.8293      1353
weighted avg     0.9191    0.9202    0.9187      1353
```

<br/>

<p align="center">
  <img width="600" alt="Canarim BERT Nheengatu - POSTAG - Confusion Matrix" src="https://raw.githubusercontent.com/DominguesM/canarim-bert-nheengatu/main/assets/postag-confusion-matrix.png">
</p>

## Usage

The use of this model follows the common standards of the [transformers](https://github.com/huggingface/transformers) library. To use it, simply install the library and load the model:


```python
from transformers import pipeline
model_name = "dominguesm/canarim-bert-postag-nheengatu"
pipe = pipeline("ner", model=model_name)
pipe("Yamunhã timbiú, yapinaitika, yamunhã kaxirí.", aggregation_strategy="average")
```

The result will be:

```json
[
  {"entity_group": "VERB", "score": 0.999668, "word": "Yamunhã", "start": 0, "end": 7},
  {"entity_group": "NOUN", "score": 0.99986947, "word": "timbiú", "start": 8, "end": 14},
  {"entity_group": "PUNCT", "score": 0.99993193, "word": ",", "start": 14, "end": 15},
  {"entity_group": "VERB", "score": 0.9995308, "word": "yapinaitika", "start": 16, "end": 27},
  {"entity_group": "PUNCT", "score": 0.9999416, "word": ",", "start": 27, "end": 28},
  {"entity_group": "VERB", "score": 0.99955815, "word": "yamunhã", "start": 29, "end": 36},
  {"entity_group": "NOUN", "score": 0.9998684, "word": "kaxirí", "start": 37, "end": 43},
  {"entity_group": "PUNCT", "score": 0.99997807, "word": ".", "start": 43, "end": 44}
]
```

## References

```bibtex
@inproceedings{stil,
  author = {Leonel de Alencar},
  title = {Yauti: A Tool for Morphosyntactic Analysis of Nheengatu within the Universal Dependencies Framework},
  booktitle = {Anais do XIV Simpósio Brasileiro de Tecnologia da Informação e da Linguagem Humana},
  location = {Belo Horizonte/MG},
  year = {2023},
  keywords = {},
  issn = {0000-0000},
  pages = {135--145},
  publisher = {SBC},
  address = {Porto Alegre, RS, Brasil},
  doi = {10.5753/stil.2023.234131},
  url = {https://sol.sbc.org.br/index.php/stil/article/view/25445}
}
```

### License (`canarim-bert-postag-nheengatu`)

The license of this model follows that of the dataset used for training, which is [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode). For more information, please visit the [dataset repository](https://github.com/UniversalDependencies/UD_Nheengatu-CompLin/tree/master).
