# Byte Pair Encoding

Neural Machine Translation improved the  quality of translation models. However, conventional NMT systems cannot correctly translate rare words [2].   It is important to find a method of translating rare words because improper translation in some domains can change the meaning [1,2]. 

Byte Pair Encoding (BPE) to generate a dictionary of subwords was proposed by [2]. The basic ideais that some word classes are translatable in smaller units than words.

BPE is a data compressionalgorithm where frequent byte pairs are usually replaced with a single unique byte. [2] adaptedBPE for segmentation of words, where most frequent characters or character sequences are merged.

The python code used here was obtained from https://leimao.github.io/blog/Byte-Pair-Encoding/.

**References**

[1] Ngoc-Quan  Pham,  Jan  Niehues,  and  Alex  Waibel.   Towards  one-shot  learning  for  rare-wordtranslation with external experts.arXiv preprint arXiv:1809.03182, 2018.

[2]  Rico Sennrich, Barry Haddow, and Alexandra Birch.  Neural machine translation of rare wordswith subword units.arXiv preprint arXiv:1508.07909, 2015.
