# OSIRRC 2019 Image Library

This repo catalogs the images that have been submitted to the [SIGIR 2019 Open-Source IR Replicability Challenge (OSIRRC 2019)](https://osirrc.github.io/osirrc2019/).
The actual raw runs are held in a [separate repository](https://github.com/osirrc/osirrc2019-runs).

+ [Anserini](#Anserini)
+ [Anserini-bm25prf](#Anserini-bm25prf)
+ [ATIRE](#ATIRE)
+ [Birch](#Birch)
+ [Elastirini](#Elastirini)
+ [EntityRetrieval](#EntityRetrieval)
+ [Galago](#Galago)
+ [ielab](#ielab)
+ [Indri](#Indri)
+ [IRC-CENTRE2019](#IRC-CENTRE2019)
+ [JASS](#JASS)
+ [JASSv2](#JASSv2)
+ [NVSM](#NVSM)
+ [OldDog](#OldDog)
+ [PISA](#PISA)
+ [Solrini](#Solrini)
+ [Terrier](#Terrier)

<a name="Anserini"></a>
## Anserini
[![Generic badge](https://img.shields.io/badge/GitHub-go%21-green.svg)](https://github.com/osirrc/anserini-docker)
[![Generic badge](https://img.shields.io/badge/DockerHub-go%21-yellow.svg)](https://hub.docker.com/r/osirrc2019/anserini)
[![DOI](https://zenodo.org/badge/176356474.svg)](https://zenodo.org/badge/latestdoi/176356474)

Execution log:

Output | Date | Collection | Host | Jig | Image |
:------|:-----|:-----------|:-----|:----|:------|
[[link](https://github.com/osirrc/osirrc2019-runs/tree/master/anserini/core18/2019-06-28)] | 2019/06/28 | core18 | `Standard_D64s_v3` | `v0.1.1` | `v0.1.1`
[[link](https://github.com/osirrc/osirrc2019-runs/tree/master/anserini/core17/2019-06-28)] | 2019/06/28 | core17 | `Standard_D64s_v3` | `v0.1.1` | `v0.1.1`
[[link](https://github.com/osirrc/osirrc2019-runs/tree/master/anserini/robust04/2019-06-28)] | 2019/06/28 | robust04 | `Standard_D64s_v3` | `v0.1.1` | `v0.1.1`
[[link](https://github.com/osirrc/osirrc2019-runs/tree/master/anserini/core18/2019-06-18)] | 2019/06/18 | core18 | `Standard_D64s_v3` | `v0.1.0` | `v0.1.1`
[[link](https://github.com/osirrc/osirrc2019-runs/tree/master/anserini/core17/2019-06-18)] | 2019/06/18 | core17 | `Standard_D64s_v3` | `v0.1.0` | `v0.1.1`
[[link](https://github.com/osirrc/osirrc2019-runs/tree/master/anserini/robust04/2019-06-17)] | 2019/06/17 | robust04 | `Standard_D64s_v3` | `v0.1.0` | `v0.1.1`
[[link](https://github.com/osirrc/osirrc2019-runs/tree/master/anserini/robust04/2019-05-27)] | 2019/05/27 | robust04 | `Standard_D64s_v3` | [`2307f2c`](https://github.com/osirrc/jig/commit/2307f2c0171ee4808940a634e471955f55def1a3) | [`dd4fbde`](https://github.com/osirrc/anserini-docker/commit/dd4fbde7ff06db3ed0b1fdb76b7fab063aeddabd)

<a name="Anserini-bm25prf"></a>
## Anserini-bm25prf
[![Generic badge](https://img.shields.io/badge/GitHub-go%21-green.svg)](https://github.com/osirrc/anserini-bm25prf-docker)
[![Generic badge](https://img.shields.io/badge/DockerHub-go%21-yellow.svg)](https://hub.docker.com/r/osirrc2019/anserini-bm25prf)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3251482.svg)](https://doi.org/10.5281/zenodo.3251482)

Execution log:

Output | Date | Collection | Host | Jig | Image |
:------|:-----|:-----------|:-----|:----|:------|
[[link](https://github.com/osirrc/osirrc2019-runs/tree/master/anserini-bm25prf/robust04/2019-06-28)] | 2019/06/28 | robust04 | `Standard_D64s_v3` | `v0.1.1` | `v0.2.2`
[[link](https://github.com/osirrc/osirrc2019-runs/tree/master/anserini-bm25prf/robust04/2019-06-21)] | 2019/06/21 | robust04 | `Standard_D64s_v3` | `v0.1.0` | `v0.2.2`

<a name="ATIRE"></a>
## ATIRE
[![Generic badge](https://img.shields.io/badge/GitHub-go%21-green.svg)](https://github.com/osirrc/atire-docker)
[![Generic badge](https://img.shields.io/badge/DockerHub-go%21-yellow.svg)](https://hub.docker.com/r/osirrc2019/atire)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3247156.svg)](https://doi.org/10.5281/zenodo.3247156)

Execution log:

Output | Date | Collection | Host | Jig | Image |
:------|:-----|:-----------|:-----|:----|:------|
[[link](https://github.com/osirrc/osirrc2019-runs/tree/master/atire/core17/2019-06-28)] | 2019/06/28 | core17 | `Standard_D64s_v3` | `v0.1.1` | `v0.1.1`
[[link](https://github.com/osirrc/osirrc2019-runs/tree/master/atire/robust04/2019-06-28)] | 2019/06/28 | robust04 | `Standard_D64s_v3` | `v0.1.1` | `v0.1.1`
[[link](https://github.com/osirrc/osirrc2019-runs/tree/master/atire/core17/2019-06-18)] | 2019/06/18 | core17 | `Standard_D64s_v3` | `v0.1.0` | `0.1.0`
[[link](https://github.com/osirrc/osirrc2019-runs/tree/master/atire/robust04/2019-06-17)] | 2019/06/17 | robust04 | `Standard_D64s_v3` | `v0.1.0` | `0.1.0`
[[link](https://github.com/osirrc/osirrc2019-runs/tree/master/atire/robust04/2019-05-27)] | 2019/05/27 | robust04 | `Standard_D64s_v3` | [`2307f2c`](https://github.com/osirrc/jig/commit/2307f2c0171ee4808940a634e471955f55def1a3) | [`ebdc076`](https://github.com/osirrc/atire-docker/commit/ebdc0762b07d4395b85d766b0e5df08b6855fae5)


<a name="Birch"></a>
## Birch
[![Generic badge](https://img.shields.io/badge/GitHub-go%21-green.svg)](https://github.com/osirrc/birch-docker)
[![Generic badge](https://img.shields.io/badge/DockerHub-go%21-yellow.svg)](https://hub.docker.com/r/osirrc2019/birch)
[![DOI](https://zenodo.org/badge/190048534.svg)](https://zenodo.org/badge/latestdoi/190048534)

Execution log:

Output | Date | Collection | Host | Jig | Image |
:------|:-----|:-----------|:-----|:----|:------|
[[link](https://github.com/osirrc/osirrc2019-runs/tree/master/birch/robust04/2019-06-28)] | 2019/06/28 | robust04 | `Standard_D64s_v3` | `v0.1.1` | `v0.1.0`
[[link](https://github.com/osirrc/osirrc2019-runs/tree/master/birch/robust04/2019-06-17)] | 2019/06/17 | robust04 | `Standard_D64s_v3` | `v0.1.0` | `v0.1.0`

<a name="#Elastirini"></a>
## Elastirini
[![Generic badge](https://img.shields.io/badge/GitHub-go%21-green.svg)](https://github.com/osirrc/elastirini-docker)
[![Generic badge](https://img.shields.io/badge/DockerHub-go%21-yellow.svg)](https://hub.docker.com/r/osirrc2019/elastirini)
[![DOI](https://zenodo.org/badge/191802305.svg)](https://zenodo.org/badge/latestdoi/191802305)

Elastirini is configured to produce the same exact batch runs as [Anserini](#Anserini), but provides an additional `interact` hook starts up Elasticsearch to support interactive querying.

<a name="EntityRetrieval"></a>
## EntityRetrieval
[![Generic badge](https://img.shields.io/badge/GitHub-go%21-green.svg)](https://github.com/osirrc/entityretrieval-docker)
[![Generic badge](https://img.shields.io/badge/DockerHub-go%21-yellow.svg)](https://hub.docker.com/r/osirrc2019/entityretrieval)
[![DOI](https://zenodo.org/badge/189270514.svg)](https://zenodo.org/badge/latestdoi/189270514)

Execution log:

Output | Date | Collection | Host | Jig | Image |
:------|:-----|:-----------|:-----|:----|:------|
[[link](https://github.com/osirrc/osirrc2019-runs/tree/master/birch/robust04/2019-06-28)] | 2019/06/28 | robust04 | `Standard_D64s_v3` | `v0.1.1` | `v0.1.0`
[[link](https://github.com/osirrc/osirrc2019-runs/tree/master/birch/robust04/2019-06-17)] | 2019/06/17 | robust04 | `Standard_D64s_v3` | `v0.1.0` | `v0.1.0`

<a name="Galago"></a>
## Galago
[![Generic badge](https://img.shields.io/badge/GitHub-go%21-green.svg)](https://github.com/osirrc/galago-docker)
[![Generic badge](https://img.shields.io/badge/DockerHub-go%21-yellow.svg)](https://hub.docker.com/r/osirrc2019/galago)
[![DOI](https://zenodo.org/badge/193567421.svg)](https://zenodo.org/badge/latestdoi/193567421)

Execution log:

Output | Date | Collection | Host | Jig | Image |
:------|:-----|:-----------|:-----|:----|:------|
[[link](https://github.com/osirrc/osirrc2019-runs/tree/master/galago/robust04/2019-06-28)] | 2019/06/28 | robust04 | `Standard_D64s_v3` | `v0.1.1` | `v0.0.2`

<a name="ielab"></a>
## ielab
[![Generic badge](https://img.shields.io/badge/GitHub-go%21-green.svg)](https://github.com/osirrc/ielab-docker)
[![Generic badge](https://img.shields.io/badge/DockerHub-go%21-yellow.svg)](https://hub.docker.com/r/osirrc2019/ielab)
[![DOI](https://zenodo.org/badge/180635817.svg)](https://zenodo.org/badge/latestdoi/180635817)

Execution log:

Output | Date | Collection | Host | Jig | Image |
:------|:-----|:-----------|:-----|:----|:------|
[[link](https://github.com/osirrc/osirrc2019-runs/tree/master/ielab/robust04/2019-06-28)] | 2019/06/28 | robust04 | `Standard_D64s_v3` | `v0.1.1` | `v0.0.1`

<a name="Indri"></a>
## Indri
[![Generic badge](https://img.shields.io/badge/GitHub-go%21-green.svg)](https://github.com/osirrc/indri-docker)
[![Generic badge](https://img.shields.io/badge/DockerHub-go%21-yellow.svg)](https://hub.docker.com/r/osirrc2019/indri)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3247067.svg)](https://doi.org/10.5281/zenodo.3247067)

Execution log:

Output | Date | Collection | Host | Jig | Image |
:------|:-----|:-----------|:-----|:----|:------|
[[link](https://github.com/osirrc/osirrc2019-runs/tree/master/indri/robust04/2019-06-28)] | 2019/06/28 | robust04 | `Standard_D64s_v3` | `v0.1.1` | `v0.2.1`
[[link](https://github.com/osirrc/osirrc2019-runs/tree/master/indri/robust04/2019-06-17)] | 2019/06/17 | robust04 | `Standard_D64s_v3` | `v0.1.0` | `v0.1.0`


<a name="IRC-CENTRE2019"></a>
## IRC-CENTRE2019 
[![Generic badge](https://img.shields.io/badge/GitHub-go%21-green.svg)](https://github.com/osirrc/irc-centre2019-docker)
[![Generic badge](https://img.shields.io/badge/DockerHub-go%21-yellow.svg)](https://hub.docker.com/r/osirrc2019/irc-centre2019)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3245439.svg)](https://doi.org/10.5281/zenodo.3245439)

Execution log:

Output | Date | Collection | Host | Jig | Image |
:------|:-----|:-----------|:-----|:----|:------|
[[link](https://github.com/osirrc/osirrc2019-runs/tree/master/irc-centre2019/core17/2019-06-28)] | 2019/06/28 | core17 | `Standard_D64s_v3` | `v0.1.1` | `v0.1.3`
[[link](https://github.com/osirrc/osirrc2019-runs/tree/master/irc-centre2019/core17/2019-06-24)] | 2019/06/24 | core17 | `Standard_D64s_v3` | `v0.1.0` | `v0.1.3`

<a name="JASS"></a>
## JASS
[![Generic badge](https://img.shields.io/badge/GitHub-go%21-green.svg)](https://github.com/osirrc/jass-docker)
[![Generic badge](https://img.shields.io/badge/DockerHub-go%21-yellow.svg)](https://hub.docker.com/r/osirrc2019/jass)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3247163.svg)](https://doi.org/10.5281/zenodo.3247163)

Execution log:

Output | Date | Collection | Host | Jig | Image |
:------|:-----|:-----------|:-----|:----|:------|
[[link](https://github.com/osirrc/osirrc2019-runs/tree/master/jass/core17/2019-06-28)] | 2019/06/28 | core17 | `Standard_D64s_v3` | `v0.1.1` | `v0.1.1`
[[link](https://github.com/osirrc/osirrc2019-runs/tree/master/jass/robust04/2019-06-28)] | 2019/06/28 | robust04 | `Standard_D64s_v3` | `v0.1.1` | `v0.1.1`
[[link](https://github.com/osirrc/osirrc2019-runs/tree/master/jass/core17/2019-06-18)] | 2019/06/18 | core17 | `Standard_D64s_v3` | `v0.1.0` | `0.1.0`
[[link](https://github.com/osirrc/osirrc2019-runs/tree/master/jass/robust04/2019-06-17)] | 2019/06/17 | robust04 | `Standard_D64s_v3` | `v0.1.0` | `0.1.0`
[[link](https://github.com/osirrc/osirrc2019-runs/tree/master/jass/robust04/2019-05-27)] | 2019/05/27 | robust04 | `Standard_D64s_v3` | [`2307f2c`](https://github.com/osirrc/jig/commit/2307f2c0171ee4808940a634e471955f55def1a3) | [`16480cf`](https://github.com/osirrc/jass-docker/commit/16480cfa196f0a3463744eafbf579a86942efa91)


<a name="JASSv2"></a>
## JASSv2
[![Generic badge](https://img.shields.io/badge/GitHub-go%21-green.svg)](https://github.com/osirrc/jassv2-docker)
[![Generic badge](https://img.shields.io/badge/DockerHub-go%21-yellow.svg)](https://hub.docker.com/r/osirrc2019/jassv2)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3247175.svg)](https://doi.org/10.5281/zenodo.3247175)

Execution log:

Output | Date | Collection | Host | Jig | Image |
:------|:-----|:-----------|:-----|:----|:------|
[[link](https://github.com/osirrc/osirrc2019-runs/tree/master/jassv2/core17/2019-06-28)] | 2019/06/28 | core17 | `Standard_D64s_v3` | `v0.1.1` | `v0.1.1`
[[link](https://github.com/osirrc/osirrc2019-runs/tree/master/jassv2/robust04/2019-06-28)] | 2019/06/28 | robust04 | `Standard_D64s_v3` | `v0.1.1` | `v0.1.1`
[[link](https://github.com/osirrc/osirrc2019-runs/tree/master/jassv2/core17/2019-06-18)] | 2019/06/18 | core17 | `Standard_D64s_v3` | `v0.1.0` | `0.1.0`
[[link](https://github.com/osirrc/osirrc2019-runs/tree/master/jassv2/robust04/2019-06-17)] | 2019/06/17 | robust04 | `Standard_D64s_v3` | `v0.1.0` | `0.1.0`
[[link](https://github.com/osirrc/osirrc2019-runs/tree/master/jassv2/robust04/2019-05-27)] | 2019/05/27 | robust04 |  `Standard_D64s_v3` | [`2307f2c`](https://github.com/osirrc/jig/commit/2307f2c0171ee4808940a634e471955f55def1a3) | [`018981e`](https://github.com/osirrc/jassv2-docker/commit/018981e564bb3adc9401a3d2d24166dbf6092b38)


<a name="NVSM"></a>
## NVSM
[![Generic badge](https://img.shields.io/badge/GitHub-go%21-green.svg)](https://github.com/osirrc/nvsm-docker)
[![Generic badge](https://img.shields.io/badge/DockerHub-go%21-yellow.svg)](https://hub.docker.com/r/osirrc2019/nvsm)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3246362.svg)](https://doi.org/10.5281/zenodo.3246362)

Execution log:

Output | Date | Collection | Host | Jig | Image |
:------|:-----|:-----------|:-----|:----|:------|
[[link](https://github.com/osirrc/osirrc2019-runs/tree/master/nvsm/robust04/2019-06-24)] | 2019/06/24 | robust04 | `Standard_D64s_v3` | `v0.1.0` | `v0.1.0`

<a name="OldDog"></a>
## OldDog
[![Generic badge](https://img.shields.io/badge/GitHub-go%21-green.svg)](https://github.com/osirrc/olddog-docker)
[![Generic badge](https://img.shields.io/badge/DockerHub-go%21-yellow.svg)](https://hub.docker.com/r/osirrc2019/olddog)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3246441.svg)](https://doi.org/10.5281/zenodo.3246441)

Execution log:

Output | Date | Collection | Host | Jig | Image |
:------|:-----|:-----------|:-----|:----|:------|
[[link](https://github.com/osirrc/osirrc2019-runs/tree/master/olddog/core18/2019-06-28)] | 2019/06/28 | core18 | `Standard_D64s_v3` | `v0.1.1` | `v1.0.0`
[[link](https://github.com/osirrc/osirrc2019-runs/tree/master/olddog/robust04/2019-06-28)] | 2019/06/28 | robust04 | `Standard_D64s_v3` | `v0.1.1` | `v1.0.0`
[[link](https://github.com/osirrc/osirrc2019-runs/tree/master/olddog/robust04/2019-06-17)] | 2019/06/17 | robust04 | `Standard_D64s_v3` | `v0.1.0` | `v0.2.0`
[[link](https://github.com/osirrc/osirrc2019-runs/tree/master/olddog/robust04/2019-05-27)] | 2019/05/27 | robust04 |  `Standard_D64s_v3` | [`2307f2c`](https://github.com/osirrc/jig/commit/2307f2c0171ee4808940a634e471955f55def1a3) | [`dd8b230`](https://github.com/osirrc/olddog-docker/commit/dd8b23036b76cd0f2d004b6823b0c17065013eb7)


<a name="PISA"></a>
## PISA
[![Generic badge](https://img.shields.io/badge/GitHub-go%21-green.svg)](https://github.com/osirrc/pisa-docker)
[![Generic badge](https://img.shields.io/badge/DockerHub-go%21-yellow.svg)](https://hub.docker.com/r/osirrc2019/pisa)
[![DOI](https://zenodo.org/badge/179735565.svg)](https://zenodo.org/badge/latestdoi/179735565)

Execution log:

Output | Date | Collection | Host | Jig | Image |
:------|:-----|:-----------|:-----|:----|:------|
[[link](https://github.com/osirrc/osirrc2019-runs/tree/master/pisa/core18/2019-06-28)] | 2019/06/28 | core18 | `Standard_D64s_v3` | `v0.1.1` | `v0.1.3`
[[link](https://github.com/osirrc/osirrc2019-runs/tree/master/pisa/core17/2019-06-28)] | 2019/06/28 | core17 | `Standard_D64s_v3` | `v0.1.1` | `v0.1.3`
[[link](https://github.com/osirrc/osirrc2019-runs/tree/master/pisa/robust04/2019-06-28)] | 2019/06/28 | robust04 | `Standard_D64s_v3` | `v0.1.1` | `v0.1.3`
[[link](https://github.com/osirrc/osirrc2019-runs/tree/master/pisa/core18/2019-06-18)] | 2019/06/18 | core18 | `Standard_D64s_v3` | `v0.1.0` | `v0.1.2`
[[link](https://github.com/osirrc/osirrc2019-runs/tree/master/pisa/core17/2019-06-18)] | 2019/06/18 | core17 | `Standard_D64s_v3` | `v0.1.0` | `v0.1.2`
[[link](https://github.com/osirrc/osirrc2019-runs/tree/master/pisa/robust04/2019-06-17)] | 2019/06/17 | robust04 | `Standard_D64s_v3` | `v0.1.0` | `v0.1.2`
[[link](https://github.com/osirrc/osirrc2019-runs/tree/master/pisa/robust04/2019-05-27)] | 2019/05/27 | robust04 | `Standard_D64s_v3` | [`2307f2c`](https://github.com/osirrc/jig/commit/2307f2c0171ee4808940a634e471955f55def1a3) | [`095e9ce`](https://github.com/osirrc/pisa-docker/commit/095e9ce8b3e07ce1066b527dfd1ea8ae72f92a16)

<a name="Solrini"></a>
## Solrini
[![Generic badge](https://img.shields.io/badge/GitHub-go%21-green.svg)](https://github.com/osirrc/solrini-docker)
[![Generic badge](https://img.shields.io/badge/DockerHub-go%21-yellow.svg)](https://hub.docker.com/r/osirrc2019/solrini)
[![DOI](https://zenodo.org/badge/182200684.svg)](https://zenodo.org/badge/latestdoi/182200684)

Solrini is configured to produce the same exact batch runs as [Anserini](#Anserini), but provides an additional `interact` hook starts up Solr to support interactive querying.

<a name="Terrier"></a>
## Terrier
[![Generic badge](https://img.shields.io/badge/GitHub-go%21-green.svg)](https://github.com/osirrc/terrier-docker)
[![Generic badge](https://img.shields.io/badge/DockerHub-go%21-yellow.svg)](https://hub.docker.com/r/osirrc2019/terrier)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3246373.svg)](https://doi.org/10.5281/zenodo.3246373)

Execution log:

Output | Date | Collection | Host | Jig | Image |
:------|:-----|:-----------|:-----|:----|:------|
[[link](https://github.com/osirrc/osirrc2019-runs/tree/master/terrier/core18/2019-06-28)] | 2019/06/28 | core18 | `Standard_D64s_v3` | `v0.1.1` | `v0.1.1`
[[link](https://github.com/osirrc/osirrc2019-runs/tree/master/terrier/robust04/2019-06-28)] | 2019/06/28 | robust04 | `Standard_D64s_v3` | `v0.1.1` | `v0.1.1`
[[link](https://github.com/osirrc/osirrc2019-runs/tree/master/terrier/core18/2019-06-20)] | 2019/06/20 | core18 | `Standard_D64s_v3` | `v0.1.0` | `v0.1.7`
[[link](https://github.com/osirrc/osirrc2019-runs/tree/master/terrier/robust04/2019-06-20)] | 2019/06/20 | robust04 | `Standard_D64s_v3` | `v0.1.0` | `v0.1.7`
