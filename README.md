![Baidu Logo](resource/baidu-research-logo-small.png)

# Open Information eXpression 

introduction to open information extraction 

## Open Information Annotation

Open Information Annotation (OIA) is an implementation of Open Information eXpression (OIX). It is a language annotation on sentences. 

The OIA standard has evolved in two versions: 

* v 1.0: described in our EMNLP 2020 paper [\[1\]](#reference), with [annotation guideline](doc/annotation_guideline.pdf).
* v 1.1: described in our ACL 2022 paper [\[2\]](#reference), which extend the set of node types.  



## Data 

We construct our OIA data set (in standard v 1.1) as described in our ACL 2022 paper [2]. It can be found in the [data](data) folder. 

### Format 

See [OIA Data Format](doc/data_format.md) for details. 

### License/Copyright

The annotations and database rights of the OIA Dataset are licensed under a Creative Commons Attribution-ShareAlike 4.0 International License.

You should have received a copy of the license along with this work. If not, see http://creativecommons.org/licenses/by-sa/4.0/.

The underlying texts come from where the sentences are from [English-EWT (version 2.4)](https://lindat.mff.cuni.cz/repository/xmlui/handle/11234/1-2988) of the Uinversal Dependency Dataset

## Citation

If you want to use this data set, please kindly cite the following paper. The bibtex are listed below:
<pre>
@inproceedings{sun2020predicate,
  title={A Predicate-Function-Argument Annotation of Natural Language for Open-Domain Information eXpression},
  author={Sun, Mingming and Hua, Wenyue and Liu, Zoey and Wang, Xin and Zheng, Kangjie and Li, Ping},
  booktitle={Proceedings of the 2020 Conference on Empirical Methods in Natural Language Processing (EMNLP)},
  pages={2140--2150},
  year={2020},
  doi = "10.18653/v1/2020.emnlp-main.167",
}

@inproceedings{wangxin2022oie@oia,
  title={OIE@OIA: an Adaptable and Efficient Open Information Extraction Framework},
  author={Wang, Xin and Peng, Minlong and Sun, Mingming and Li, Ping},
  booktitle={Proceedings of the 2022 Conference on Association for Computational Linguistics (ACL)},
  year={2022},
}
</pre>

## Reference 

\[1\] Mingming Sun, Wenyue Hua, Zoey Liu, Xin Wang, Kangjie Zheng, and Ping Li. 2020. [A Predicate-Function-Argument Annotation of Natural Language for Open-Domain Information eXpression](https://aclanthology.org/2020.emnlp-main.167/). In Proceedings of the 2020 Conference on Empirical Methods in Natural Language Processing (EMNLP), pages 2140–2150, Online. Association for Computational Linguistics.

\[2\] Xin Wang, Minlong Peng, Mingming Sun, Ping Li. 2022. OIE@OIA: an Adaptable and Efficient Open Information Extraction Framework. In Proceedings of the 2022 Conference on Association for Computational Linguistics (ACL).
