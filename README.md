# PRONOM Archive and Skeleton Test Suite

## Epilogue

The PRONOM archive and (archive) of the skeleton test suite is no longer
maintained. The experiment was to create a record of the of Raw data that went
into PRONOM (the file format registry) for future research purposes.

Rather than just storing the data and leaving it, handles were minted in
Zenodo to provide an anchor for researchers to point back to. This made the
workflow a bit more difficult to do by hand and it has been hard to keep up with
the pace of publication with PRONOM.

Also, the reality is, I don't think digital preservation researchers actually
care about this data and I don't anticipate PRONOM creating a historical
interface allowing it to be viewed, filling in a gap in a historical audit
trail for the system.

Most research projects looking at the change in file format signatures over the
years have focused on the DROID signature file. This makes sense because the
DROID signature file actually triggers file format identification and so it
can be measured against something, i.e. something being identified vs. not
being identified.

Anecdotally, I believe the DROID export has historically encoded PRONOM data
with slight variations to the recorded signature. Richard Lehane can shed more
light on these minor divergances through his work on Siegfried.

### Generating a PRONOM archive in the future

Fortunately, the weight of maintaining a PRONOM record was not entirely on this
repository's shoulders. Richard has also been maintaining somewhat of a PRONOM
record through his [builder][builder] utility.

[builder]: https://github.com/richardlehane/builder

Builder's record goes back to PRONOM v92 and the raw PRONOM data can be
accessed via the tool's release pages: [here][builder-releases].

[builder-releases]: https://github.com/richardlehane/builder/releases?page=1

To that end, between this repository going back to v70 and Builder starting at
v92, should any researcher want to come back to the historical record of
PRONOM, they can build a pretty decent picture going back to 2013.

### Skeleton test suite generation

Generating a skeleton test suite will still be possible and that code will
continue to be maintained as its benefit to signature and tool development. You
can read more about the skeleton suite generator work below.

## Introduction

Herein lies a tool for the automated generation of digital objects based on the
digital signatures documented in the PRONOM database maintained by The National
Archives, UK: PRONOM Data is licensed under the
[Open Government Licence (OGL)][ogl-license].

[ogl-license]: http://www.nationalarchives.gov.uk/doc/open-government-licence/

The skeleton-test-suite-generator serves to fill the gap that exists whereby
the community requires a corpus of digital objects for the validation and
evaluation of format identification tools and techniques. The tool should be
used to complement a methodology whereby skeleton files are also generated
manually by signature developers.

The research paper this work led to can be found on the
[IJDC website][ijdc].

[ijdc]: http://www.ijdc.net/index.php/ijdc/article/view/8.1.120

## DOIs

Each PRONOM release now has a DOI provided by the Skeleton Suite. This will
help academics referencing versions of PRONOM but more importantly will help
preservation of this record.

* [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.4297109.svg)][sk97]
Skeleton Test Suite and PRONOM Archive v97
* [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3740666.svg)][sk96]
Skeleton Test Suite and PRONOM Archive v96
* [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3269467.svg)][sk95]
Skeleton Test Suite and PRONOM Archive v95
* [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1451193.svg)][sk94]
Skeleton Test Suite and PRONOM Archive v94
* [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1098334.svg)][sk93]
Skeleton Test Suite and PRONOM Archive v93
* [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1004423.svg)][sk92]
Skeleton Test Suite and PRONOM Archive v92
* [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1004419.svg)][sk91]
Skeleton Test Suite and PRONOM Archive v91
* [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1004415.svg)][sk90]
Skeleton Test Suite and PRONOM Archive v90
* [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1004409.svg)][sk89]
Skeleton Test Suite and PRONOM Archive v89
* [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1004405.svg)][sk88]
Skeleton Test Suite and PRONOM Archive v88
* [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1004403.svg)][sk86]
Skeleton Test Suite and PRONOM Archive v86
* [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1004399.svg)][sk85]
Skeleton Test Suite and PRONOM Archive v85
* [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1004395.svg)][sk84]
Skeleton Test Suite and PRONOM Archive v84
* [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1004391.svg)][sk83]
Skeleton Test Suite and PRONOM Archive v83
* [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1004389.svg)][sk82]
Skeleton Test Suite and PRONOM Archive v82
* [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1004387.svg)][sk81]
Skeleton Test Suite and PRONOM Archive v81
* [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1004385.svg)][sk79]
Skeleton Test Suite and PRONOM Archive v79
* [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1004381.svg)][sk78]
Skeleton Test Suite and PRONOM Archive v78
* [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1004378.svg)][sk77]
Skeleton Test Suite and PRONOM Archive v77
* [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1004374.svg)][sk75]
Skeleton Test Suite and PRONOM Archive v75
* [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1004372.svg)][sk74]
Skeleton Test Suite and PRONOM Archive v74
* [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1004370.svg)][sk73]
Skeleton Test Suite and PRONOM Archive v73
* [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1004368.svg)][sk72]
Skeleton Test Suite and PRONOM Archive v72
* [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1004366.svg)][sk70]
Skeleton Test Suite and PRONOM Archive v70

[sk97]: https://doi.org/10.5281/zenodo.4297109
[sk96]: https://doi.org/10.5281/zenodo.3740666
[sk95]: https://doi.org/10.5281/zenodo.3269467
[sk94]: https://doi.org/10.5281/zenodo.1451193
[sk93]: https://doi.org/10.5281/zenodo.1098334
[sk92]: https://doi.org/10.5281/zenodo.1004423
[sk91]: https://doi.org/10.5281/zenodo.1004419
[sk90]: https://doi.org/10.5281/zenodo.1004415
[sk89]: https://doi.org/10.5281/zenodo.1004409
[sk88]: https://doi.org/10.5281/zenodo.1004405
[sk86]: https://doi.org/10.5281/zenodo.1004403
[sk85]: https://doi.org/10.5281/zenodo.1004399
[sk84]: https://doi.org/10.5281/zenodo.1004395
[sk83]: https://doi.org/10.5281/zenodo.1004391
[sk82]: https://doi.org/10.5281/zenodo.1004389
[sk81]: https://doi.org/10.5281/zenodo.1004387
[sk79]: https://doi.org/10.5281/zenodo.1004385
[sk78]: https://doi.org/10.5281/zenodo.1004381
[sk77]: https://doi.org/10.5281/zenodo.1004378
[sk75]: https://doi.org/10.5281/zenodo.1004374
[sk74]: https://doi.org/10.5281/zenodo.1004372
[sk73]: https://doi.org/10.5281/zenodo.1004370
[sk72]: https://doi.org/10.5281/zenodo.1004368
[sk70]: https://doi.org/10.5281/zenodo.1004366

### Source Code

Code to generate the container, and standard skeleton suites can be found:

* [github.com/exponential-decay/skeleton-test-suite-generator][gh-1]
* [github.com/exponential-decay/skeleton-container-test-suite-generator][gh-2]

[gh-1]: https://github.com/exponential-decay/skeleton-test-suite-generator
[gh-2]: https://github.com/exponential-decay/skeleton-container-test-suite-generator

### Testing reports

I completed two reports on the Skeleton Test Suite back in 2012/2013. They
document testing of the files on DROID and explore reasons why some files do or
do not work. The reports and links to the test-suites used for testing can be
found on the repository wiki, here: [Skeleton-reports][reports-1].

[reports-1]: https://github.com/exponential-decay/skeleton-test-suite-generator/wiki

### Blogs

More information can be found on my blog: [More information][skeleton-blog].

[skeleton-blog]: http://exponentialdecay.co.uk/blog/the-problem-with-comprehensive-test-suites/

#### Other blogs and uses of the skeleton suite

* [Siegfried 1.0 released][opf-1].
* [Introduction to Siegfried][opf-2].
* [Automation in Digital Preservation][dpc-1].
* [Skeleton suite's contribution to PRONOM v92][pronom-1].
* [PRONOM in practice][pronom-2].
* [addtext (adding missing file extensions using PRONOM data)][walsh-1].

[opf-1]: https://openpreservation.org/blogs/siegfried-v-1-0-released-a-file-format-identification-tool/?order=relevance%3ADESC&search=skeleton&q=9152
[opf-2]: https://openpreservation.org/blogs/siegfried-pronom-based-file-format-identification-tool/
[dpc-1]: https://www.dpconline.org/blog/wdpd/automation-in-digital-preservation
[pronom-1]: https://groups.google.com/g/pronom/c/Eh4d8baHIhc/m/rqzUomXkBQAJ
[pronom-2]: https://osf.io/2jbpe/
[walsh-1]: https://github.com/tw4l/addext

### License

Copyright (c) 2015 Ross Spencer

This software is provided 'as-is', without any express or implied warranty. In
no event will the authors be held liable for any damages arising from the use
of this software.

Permission is granted to anyone to use this software for any purpose, including
commercial applications, and to alter it and redistribute it freely, subject to
the following restrictions:

The origin of this software must not be misrepresented; you must not claim that
you wrote the original software. If you use this software in a product, an
acknowledgment in the product documentation would be appreciated but is not
required.

Altered source versions must be plainly marked as such, and must not be
misrepresented as being the original software.

This notice may not be removed or altered from any source distribution.
