# Multi-CAST Tulil

## How to cite

If you use these data please cite
- the original source
  > Meng, Chenxi. 2019. Multi-CAST Tulil. In Haig, Geoffrey & Schnell, Stefan (eds.), Multi-CAST: Multilingual corpus of annotated spoken texts. Version 1907. Bamberg: University of Bamberg. (multicast.aspra.uni-bamberg.de/#tulil) (date accessed)
- the derived dataset using the DOI of the [particular released version](../../releases/) you were using

![](cldf/media/image.jpg)

## Description


**Tulil** ([taul1251](https://glottolog.org/resource/languoid/id/taul1251)), also known as Taulil, is a Papuan language spoken in the East New Britain Province of Papua New Guinea. As of 2000, Tulil is spoken by approximately 2 000 people spread out over four villages (Tulil 1, Tulil 2, Kadaulung, and Toma).

The six texts in this corpus comprise a subset of a larger collection of material that was recorded and transcribed during two field trips undertaken by Chenxi Meng in 2012 and 2015 for her PhD project, which has resulted in a comprehensive [grammar of Tulil](MediaTable#cldf:Meng2018_a-grammar-of-Tulil.pdf) ([Meng 2018](Source#cldf:meng2018)). The entirety of the data has been deposited in [PARADISEC](http://catalog.paradisec.org.au/collections/CM2).

The texts selected for Multi-CAST include both traditional and personal narratives. Annotations with RefIND were added by Maria Vollmer.

This dataset is licensed under a CC-BY-4.0 license

Available online at https://multicast.aspra.uni-bamberg.de/#tulil


```geojson
{
    "type": "FeatureCollection",
    "features": [
        {
            "type": "Feature",
            "geometry": {
                "type": "Point",
                "coordinates": [
                    152.095,
                    -4.44425
                ]
            }
        },
        {
            "type": "Feature",
            "geometry": {
                "type": "Polygon",
                "coordinates": [
                    [
                        [
                            147.095,
                            0.5557499999999997
                        ],
                        [
                            157.095,
                            0.5557499999999997
                        ],
                        [
                            157.095,
                            -9.44425
                        ],
                        [
                            147.095,
                            -9.44425
                        ],
                        [
                            147.095,
                            0.5557499999999997
                        ]
                    ]
                ]
            }
        }
    ]
}
```



## Corpus counts

Only a small number of basic GRAID symbols are counted:

*Function symbols*
- ⟨0⟩ zero
- ⟨pro⟩ definite pronoun
- ⟨np⟩ full noun phrase
- ⟨other⟩ form not further specified

*Person/Animacy symbols*
- ⟨.1⟩ first person
- ⟨.2⟩ second person
- ⟨.h⟩ third person, human
- ⟨.d⟩ third person, anthropomorphic
- ø third person, non-human

*Function symbols*
- ⟨:s⟩ subject of an intransitive clause
- ⟨:a⟩ subject of a transitive clause
- ⟨:ncs⟩ non-canonical subject
- ⟨:p⟩ direct object
- ⟨:obl⟩ oblique argument
- ⟨:g⟩ goal argument
- ⟨:l⟩ locational argument
- ⟨:pred⟩ predicate
- ⟨:poss⟩ possessive
- ⟨:other⟩ function not further specified

Only basic categories are listed; categories represented by complex symbols with additional
specifiers (e.g. ⟨dem_pro⟩ ‘demonstrative pronoun’) have been subsumed under the more basic
category (e.g. ⟨pro⟩ ‘definite pronoun’). Please refer to the annotation notes for this corpus for
information on all annotated categories, including those not listed here.

| GRAID | ⟨:s⟩ | ⟨:a⟩ | ⟨:ncs⟩ | ⟨:p⟩ | ⟨:obl⟩ | ⟨:g⟩ | ⟨:l⟩ | ⟨:pred⟩ | ⟨:poss⟩ | ⟨:other⟩ | totals |
|:--------------|-------:|-------:|---------:|-------:|---------:|-------:|-------:|----------:|----------:|-----------:|---------:|
| **⟨0.1⟩** | 132 | 119 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 251 |
| **⟨0.2⟩** | 14 | 29 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 43 |
| **⟨0.h⟩** | 132 | 122 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 254 |
| **⟨0.d⟩** | 62 | 34 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 96 |
| **⟨0⟩** | 69 | 15 | 0 | 22 | 1 | 0 | 0 | 0 | 0 | 0 | 107 |
| **⟨pro.1⟩** | 57 | 17 | 0 | 33 | 8 | 0 | 0 | 1 | 74 | 0 | 190 |
| **⟨pro.2⟩** | 6 | 2 | 0 | 5 | 1 | 0 | 0 | 0 | 7 | 0 | 21 |
| **⟨pro.h⟩** | 28 | 13 | 0 | 52 | 14 | 7 | 6 | 1 | 62 | 0 | 183 |
| **⟨pro.d⟩** | 13 | 1 | 0 | 13 | 15 | 1 | 0 | 1 | 33 | 0 | 77 |
| **⟨pro⟩** | 49 | 11 | 0 | 98 | 9 | 0 | 5 | 5 | 18 | 4 | 199 |
| **⟨np.1⟩** | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| **⟨np.2⟩** | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| **⟨np.h⟩** | 20 | 10 | 0 | 7 | 10 | 1 | 1 | 11 | 8 | 1 | 69 |
| **⟨np.d⟩** | 27 | 9 | 0 | 4 | 5 | 0 | 0 | 6 | 6 | 0 | 57 |
| **⟨np⟩** | 119 | 24 | 0 | 170 | 49 | 66 | 91 | 74 | 12 | 39 | 644 |
| **⟨other.1⟩** | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| **⟨other.2⟩** | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| **⟨other.h⟩** | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| **⟨other.d⟩** | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| **⟨other⟩** | 6 | 0 | 0 | 8 | 0 | 49 | 51 | 169 | 0 | 0 | 283 |
| | 734 | 406 | 0 | 412 | 112 | 124 | 154 | 268 | 220 | 44 | 2474 |


**Clause boundaries**

| GRAID | count |
|:-----------|--------:|
| **⟨##⟩** | 765 |
| **⟨#⟩** | 499 |
| **totals** | 1264 |



## Corpus metadata

- [Annotation notes](cldf/media/annotation-notes.pdf)
- [Translated texts](cldf/media/translated-texts.pdf)
- [Meng2018_a grammar of tulil](cldf/media/Meng2018_a-grammar-of-Tulil.pdf)


## CLDF Datasets

The following CLDF datasets are available in [cldf](cldf):

- CLDF [TextCorpus](https://github.com/cldf/cldf/tree/master/modules/TextCorpus) at [cldf/TextCorpus-metadata.json](cldf/TextCorpus-metadata.json)