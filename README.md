# SLI_OMSTI
## SLI mappings for OMSTI dataset

|File|Size|Description|
|----|-----|-------| 
|SLI_OMSTI_ILI_CoNLL_1.0.7z|41M|The distribution includes a version of the OMSTI (One Million Sense-Tagged Instances) dataset (available at http://lcl.uniroma1.it/wsdeval/training-data), originally tagged with WordNet 3.0 Sense Keys, projected by SLI to WordNet 3.0 Inter-Lingual Index (ILI) and encoded in CoNLL format for machine learning|
|SLI_OMSTI_BLC_CoNLL_1.0.7z|41M|The distribution includes a version of the OMSTI (One Million Sense-Tagged Instances) dataset (available at http://lcl.uniroma1.it/wsdeval/training-data), originally tagged with WordNet 3.0 Sense Keys, projected by SLI to semantic classes (BLC) and encoded in CoNLL format for machine learning|
|SLI_OMSTI_BabelDomains_CoNLL_1.0.7z|40M|The distribution includes a version of the OMSTI (One Million Sense-Tagged Instances) dataset (available at http://lcl.uniroma1.it/wsdeval/training-data), originally tagged with WordNet 3.0 Sense Keys, projected by SLI to semantic classes (BabelDomains) and encoded in CoNLL format for machine learning|
|SLI_OMSTI_Epinonyms_CoNLL_1.0.7z|41M|The distribution includes a version of the OMSTI (One Million Sense-Tagged Instances) dataset (available at http://lcl.uniroma1.it/wsdeval/training-data), originally tagged with WordNet 3.0 Sense Keys, projected by SLI to semantic classes (epinonyms) and encoded in CoNLL format for machine learning|
|SLI_OMSTI_Supersenses_CoNLL_1.0.7z|41M|The distribution includes a version of the OMSTI (One Million Sense-Tagged Instances) dataset (available at http://lcl.uniroma1.it/wsdeval/training-data), originally tagged with WordNet 3.0 Sense Keys, projected by SLI to semantic classes (supersenses) and encoded in CoNLL format for machine learning|


These mappings are made available under the terms of Creative Commons Attribution 4.0 International Public License (CC BY 4.0) (which you can find at https://creativecommons.org/licenses/by/4.0/), and are distributed without any warranty.

Information and contact: Xavier Gómez Guinovart (xgg2021@gmail.com)

***
## Note

Files have been split into 25MB parts with the _split_ command. For instance:

```console
$ split -b 25M -d SLI_OMSTI_ILI_CoNLL_1.0.7z SLI_OMSTI_ILI_CoNLL_1.0.7z.part
```

To rejoin these parts, you can use the _cat_ command. For instance:

```console
$ cat SLI_OMSTI_ILI_CoNLL_1.0.7z.part* > SLI_OMSTI_ILI_CoNLL_1.0.7z
```

