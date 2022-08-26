# Introduction

This dataset is derived from 2847 early modern English petitions from
selected local and central institutions, transcribed and published by
**The Power of Petitioning in Seventeenth-Century England** (TPOP)
project. It includes information about archival sources, dates,
petition topics, petitioners and administrative responses.

The full edition of the transcribed petitions is available at British
History Online, where each volume of petitions also has an editorial
introduction with further background and source information. The dataset
may be used independently of the BHO transcribed petitions or as a
supplementary resource and finding aid. Please note that the dataset
does not include the transcriptions.

# The Power of Petitioning project

The Power of Petitioning project research team consisted of:

-   Dr Brodie Waddell (Birkbeck, University of London) - Principal
    Investigator
-   Professor Jason Peacey (University College London) - Co-investigator
-   Sharon Howard (Birkbeck) - Research Associate

Further information:

-   Project website: <https://petitioning.history.ac.uk/>
-   BHO edition:
    <https://www.british-history.ac.uk/search/series/petitions>

Contacts:

-   general questions related to the project: <b.waddell@bbk.ac.uk>
-   specific questions about the dataset:
    <sharon.howard@sheffield.ac.uk>

# Data creation

The bulk of data collection and processing took place during 2019-2020,
with some supplementary data work in 2021.

## Source choices and sampling

Wherever available, the project used existing catalogues and resources
to determine selection of records. The archival collections were
selected to represent three institutions (Parliament, Crown, county) and
four regions (London, south-east, midlands, north-west), with a
particular focus on series that contained surviving late 16th-century
petitions.

A number of the collections were too large for the project to be able to
transcribe every surviving petition and these were sampled; sampling
strategies were pragmatic and depended on the size and distribution of
each archive.

## Transcriptions

Gavin Robinson and Tim Wales transcribed the petitions from photographs
of the archival documents. As the transcriptions are not included in
this dataset, the transcription conventions are not documented in
detail, but key features for subsequent data processing are noted below.

Basic metadata was recorded at the transcription stage for every
petition, including:

-   full archival reference, repository and collection
-   document year (derived from archival context if the petition itself
    was undated)
-   document date if the petition itself contained a date (many do not)

The transcriptions were made in plain text with some XML-style tagging
used to mark up key features that the project wanted to record.

Most original spelling, punctuation, etc was retained, but the
transcriptions were not diplomatic and no attempt was made to represent
the materiality of the documents. For example, abbreviations were
silently expanded, proper names were always capitalised and
capitalisation in general was modernised. Line breaks and paragraph
breaks were retained.

Paratext (anything added in a different hand from the main body of the
petition) was tagged as such. Subscribed names were also tagged.

## Post-transcription processing

The key elements of manual work undertaken to enhance basic archival
metadata consisted of:

-   collation of available catalogue metadata (Brodie Waddell)
-   assignment of topics and subtopics (Brodie Waddell, Jason Peacey,
    Sharon Howard, Anna Cusack)
-   writing abstracts for petitions where these weren’t available from
    catalogues (Brodie Waddell, Sharon Howard)
-   assignment of response categories (QS petitions only) (Sharon
    Howard)

Sharon Howard wrote R scripts to add further information to the data,
including:

-   extracting metadata and tagged content from the transcriptions
-   extraction of data from catalogues (particularly for the House of
    Lords petitions) and other resources
-   identifying petitioner names, assigning gender, and associating them
    with locations and statuses

Sharon Howard was also responsible for the final compilation and
documentation of the public release of the data.

# The collections

The petitions are organised in seven volumes on British History Online
(<https://www.british-history.ac.uk/search/series/petitions>).

## Quarter Sessions (QS)

The five separate county volumes of Quarter Sessions petitions have been
collated into a single QS collection (1728 petitions).

### Cheshire

Dates covered: 1573-1798

Sampling: one year in ten

Number of petitions: 613

Number of petitioners: 644

Number of subscribers: 1352

Notes on data collection:

-   transcribed all surviving 16th-century petitions and
    17th/18th-century petitions from 1 year in 20 (years ending in -8)
    (292 petitions)
-   added extensive metadata for petitions from the intervening years
    ending in -8 (321 petitions)

Further information:
<https://www.british-history.ac.uk/petitions/cheshire/introduction>

### Derbyshire

Dates covered: 1632-1770

Sampling: all surviving petitions that could be dated

Number of petitions: 94

Number of petitioners: 94

Number of subscribers: 151

Notes on data collection:

-   transcribed every surviving petition that could be dated to within a
    decade
-   121 petitions which couldn’t be dated were excluded

Further information:
<https://www.british-history.ac.uk/petitions/derbyshire/introduction>

### Staffordshire

Dates covered: 1589-1799

Sampling: one year in ten

Number of petitions: 239

Number of petitioners: 288

Number of subscribers: 632

Notes on data collection:

-   transcribed all surviving petitions from 1 year per decade (years
    ending in -9)

Further information:
<https://www.british-history.ac.uk/petitions/staffordshire/introduction>

### Westminster

Dates covered: 1620-1799

Sampling: all surviving usable petitions

Number of petitions: 424

Number of petitioners: 435

Number of subscribers: 349

Notes on data collection:

-   transcribed all surviving petitions except a few early
    illegible/damaged ones
-   44 petitions can only be dated to within 20 years (1620-40) and some
    others to a decade
-   there is a large gap in the archive between 1646 and 1688

Further information:
<https://www.british-history.ac.uk/petitions/westminster/introduction>

### Worcestershire

Dates covered: 1592-1797

Sampling: all surviving usable petitions

Number of petitions: 360

Number of petitioners: 346

Number of subscribers: 1047

Notes on data collection:

-   transcribed all surviving petitions except a few early
    illegible/damaged ones
-   there are large gaps in the middle of the 17th century

Further information:
<https://www.british-history.ac.uk/petitions/worcs-quarter-sessions/introduction>

## House of Lords (HOL)

Dates covered: 1597-1696

Sampling: selected years

Number of petitions: 732

Number of petitioners: 844

Number of subscribers: 2367

Notes on data collection:

-   transcribed every surviving petition 1597-1620 and then selected
    years across the 17th century:
-   1597-1620 (13), 1621 (65), 1624 (78), 1640 (80), 1648 (80), 1661
    (104), 1671 (71), 1679 (88), 1689 (80), 1696 (73)
-   the selection aimed to produce as even a survey as possible, given
    that Parliament did not meet every year
-   1640 and 1689 are exceptionally voluminous years and so collection
    was limited to the first 80 petitions (as filed)

Further information:
<https://www.british-history.ac.uk/petitions/house-of-lords/introduction>

## State Papers (SP)

Dates covered: 1600-1699

Sampling: up to 4 petitions per year

Number of petitions: 387

Number of petitioners: 433

Number of subscribers: 602

Notes on data collection:

-   transcribed the first four surviving petitions for each year from
    1600 to 1699 (based on the Calendar of State Papers Domestic)
-   less than four petitions survived in some years, especially towards
    the end of the period

Further information:
<https://www.british-history.ac.uk/petitions/state-papers/introduction>

# The data

## Collection prefixes

-   QS: Quarter Sessions
-   HOL: House of Lords
-   SP: State Papers

## Data tables

For each collection there are two tables:

-   petitions
-   petitioners

## Formats

The dataset is provided in three formats to cater for varying levels of
technical expertise and preferred workflows:

-   Excel spreadsheet, containing all six data tables
-   CSVs (one file per table, as a zip archive)
-   SQLite database, containing six tables

## Petitions

The main petition-level metadata. With the exception of the 321
supplementary Cheshire petitions, the full text of the petitions is
available on British History Online and can be located there using the
collection name (and county for QS), date and archival reference.

| column          | collections | description                                                                                                                                                                              |
|:----------------|:------------|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| petition_id     | HOL QS SP   | a unique identifier for the petition within the dataset (added because not all archival references are unique; *not* part of the BHO edition)                                            |
| year            | HOL QS SP   | year of petition; often assumed from archival context, eg the date of a session file, as many petitions are not dated. A few are approximate, but most to within a decade.               |
| date            | HOL QS SP   | date of petition (a date written on the petition itself; many are undated)                                                                                                               |
| county          | QS          | county, for QS petitions: Cheshire, Derbyshire, Staffordshire, Westminster, Worcestershire                                                                                               |
| topic           | QS SP       | one of a number of broad topics assigned by TPOP; see below for details of the topics                                                                                                    |
| subtopic        | QS          | adds further detail to the topic; looser and less comprehensive than topics                                                                                                              |
| topic_detail    | SP          | a slightly more detailed version of the broad topic                                                                                                                                      |
| themes          | HOL         | up to three topics or themes have been assigned to each HOL petition. Where more than one, a list of items separated by a pipe “\|” symbol.                                              |
| named_petrs     | HOL QS SP   | count of named petitioners                                                                                                                                                               |
| subscribers     | HOL QS SP   | count of named subscribers                                                                                                                                                               |
| petition_type   | HOL QS SP   | based on the number/type of petitioner. Values: single, multiple, collective (not individually named) + “behalf” for petitions made on behalf of someone other than the named petitioner |
| petition_gender | HOL QS SP   | a summary of the gender of the petitioners. Values: f, m, fm (mixed), u (unknown); left blank for collective petitions                                                                   |
| sub_gender      | HOL QS SP   | similar summary of the gender of subscribers                                                                                                                                             |
| response_cat    | QS          | some petitions have responses annotated on the petition; see below for list of possible values                                                                                           |
| petitioner      | HOL QS SP   | the individual petitioner(s) name or collective title                                                                                                                                    |
| addressee       | SP          | person or institution to whom petition was addressed (in SP this can be quite varied)                                                                                                    |
| abstract        | QS          | short summary of the contents of the petition; some have been written by TPOP and others sourced from archives catalogues and they vary in level of detail                               |
| description     | HOL         | description of the petition taken from the Parliamentary Archives catalogue                                                                                                              |
| request         | SP          | a very short summary of the nature of the request                                                                                                                                        |
| repository      | HOL QS SP   | the archival institution that currently holds the records                                                                                                                                |
| collection      | HOL QS SP   | the archival series or collection in which the petitions are located                                                                                                                     |
| reference       | HOL QS SP   | the archival reference of the document. In HOL and Westminster QS these are not all unique identifiers                                                                                   |
| ll_img          | QS          | some Westminster QS petitions are online at London Lives (www.londonlives.org). This identifier can be used in LL’s reference search to find the document.                               |
| bho_transcribed | QS          | was the petition transcribed for the BHO online edition? “y” (yes) or “n” (no). Most are “y”, but some Cheshire QS petitions have abstracts only.                                        |

### Topics/themes

*QS*

Each QS petition was assigned a single topic from the following list,
designed to cover the most common and significant broad categories of
concern to QS petitioners. The project aimed to be as consistent as
possible to enable comparative analysis. Nonetheless, the topics are a
limited tool; some petitions might have fallen into more than one
category, in which case an editorial decision was made as to which was
the primary concern of the petitioner. Many petitions also have
subtopics, but these were assigned rather less systematically and are
not documented here.

| topic              | description                                                                                                                                   |
|:-------------------|:----------------------------------------------------------------------------------------------------------------------------------------------|
| alehouse           | petitions to do with licences for alehouses, inns, taverns, victualling houses                                                                |
| charitable brief   | petitions for certificates to allow the petitioners to collect charity in response to personal calamities such as house fires                 |
| cottage            | petitions concerning licences to build cottages on ‘waste’ lands                                                                              |
| dissenting worship | appllications for licences to establish nonconformist places of worship (following the Toleration Act of 1689)                                |
| employment         | petitions to do with service, apprenticeship, wages and other disputes between employers and employees                                        |
| imprisoned debtors | applications for release from imprisoned debtors (18th century)                                                                               |
| litigation         | broad category for uses of and encounters with the legal/criminal justice system (eg request for prosecution, request for mercy or discharge) |
| military relief    | petitions from wounded soldiers/sailors or their widows/wives for military pensions                                                           |
| officeholding      | petitions concerning local officials, mainly constables, eg trying to get out of serving, or seeking compensation for expenses                |
| other              | miscellaneous petitions that didn’t fit into the other topics                                                                                 |
| paternity          | petitions concerning financial support for children, mainly bastardy cases                                                                    |
| poor relief        | petitions concerning relief or removal under the poor law system                                                                              |
| rates              | petitions (mainly) attempting to impose or avoid payment of various communal rates, levies or taxes                                           |

*SP*

Each SP topic was assigned a single topic from the following list, which
again was designed to reflect the distinct concerns of petitioners to
the Crown.

| topic              | description                                                                                                      |
|:-------------------|:-----------------------------------------------------------------------------------------------------------------|
| charity            | almshouse, hospital, etc.                                                                                        |
| church             | ecclesiastical office or jurisdiction                                                                            |
| crime              | mercy, pardon or, conversely, punishment for alleged illegality, including homicide, libel, treason, theft, etc. |
| diplomacy/travel   | diplomatic aid, passports, ambassadorial office, etc.                                                            |
| infrastructure     | harbours, bridges, sewers, bridges                                                                               |
| land               | property inheritances, natural resources, tenancies, etc.                                                        |
| lawsuit            | ongoing litigation, arbitration, legal offices, etc.                                                             |
| military           | army and navy, including wages, pensions, supplies, quarterage, etc.                                             |
| monetary grant     | financial allowance or pension                                                                                   |
| other              | miscellaneous                                                                                                    |
| other royal office | park-keeper, household service, Cinque Ports, Exchequer, sheriff, Jewel House, etc.                              |
| school/university  | scholarships, educational licences, appointments, etc.                                                           |
| tax                | customs, poll tax, ship money, etc.                                                                              |
| trade              | commercial privileges, privateering, piracy, etc.                                                                |

*HOL*

A much larger and looser set of themes was used for the House of Lords
petitions, up to three per petition. They are listed here for
information, but it is not possible to document them in any detail.

| themes                                                                                                                                                                                                                                                                                              |
|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| advowson; algerian slaves; alimony; arbitration; army; arrears; arrest; assault                                                                                                                                                                                                                     |
| baptists; bishops wars                                                                                                                                                                                                                                                                              |
| charitable uses; charter; church government; church lands; church politics; church repairs; clemency; clerical living; clerical livings; coat and conduct; college of physicians; colonies; compounding; concealed lands; conspiracy; contempt; conventicle; corruption; courts of justice; customs |
| danby; debt; debts; defamation; delay; delay hearing; diplomacy; divorce                                                                                                                                                                                                                            |
| elections; employment                                                                                                                                                                                                                                                                               |
| fees; fen drainage; fishing; forests; forgery; fraud                                                                                                                                                                                                                                                |
| hackney carriages                                                                                                                                                                                                                                                                                   |
| impeachment; imprisonment; indemnity; industry; irish rebellion                                                                                                                                                                                                                                     |
| jacobite; judgment                                                                                                                                                                                                                                                                                  |
| land; leg; legislation; libel; license to stay in london; licenses; litigation; livery companies                                                                                                                                                                                                    |
| matthew parker tomb; monopolies                                                                                                                                                                                                                                                                     |
| naturalisation                                                                                                                                                                                                                                                                                      |
| oates; office; office / official duties; official duties; other; overseas trade                                                                                                                                                                                                                     |
| pardon; patent; patents; pay; peerage; pension; petitioning; plantations; plot; plunder; poor; popery; popish priest; prerogative courts; priests; printing; prisons; priv; privilege; prizes; process; property; protection                                                                        |
| records; recusancy; recusants; regicide; relief; religion; river navigation; romish priest; royalist soldiers; rye house plot                                                                                                                                                                       |
| salary; scotland; seditious words; sequestration; service; ship money; slander                                                                                                                                                                                                                      |
| testamentary; tobacco; toleration; trade; trade regulation; trading companies; treason; trusts                                                                                                                                                                                                      |
| war; words                                                                                                                                                                                                                                                                                          |

### Responses

Responses have been categorised for the QS collection only (so far).

| category    | description                                                                                                       |
|:------------|:------------------------------------------------------------------------------------------------------------------|
| granted     | request granted in full                                                                                           |
| grant_part  | request partially granted                                                                                         |
| grant_cond  | request granted on condition of doing something                                                                   |
| referred    | request referred for further investigation or mediation                                                           |
| nothing     | “nil”, “nothing”, or similar wording, with no further reason given for rejection                                  |
| rejected    | request rejected, usually with some kind of reason                                                                |
| absent      | request rejected because the petitioner was absent                                                                |
| uncertain   | there is an annotation which may be a response, but its meaing is unclear (due to damage, illegible writing, etc) |
| no_response | no response of any kind is recorded on the petition                                                               |

## Petitioners

Supplementary data about petitioners and subscribers named in petitions:
the names of petitioners (including those petitioned “on behalf of”) and
subscribers have been identified and further information about them has
been added.

Some petition-level data has been added to the petitioner tables in the
Excel spreadsheet version of the dataset for users’ convenience;
documentation of those columns is not repeated here.

| column        | collections | description                                                                                                                                                                                                                                                                            |
|:--------------|:------------|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| petitioner_id | HOL QS SP   | a unique identifier for the petitioner within the dataset                                                                                                                                                                                                                              |
| petition_id   | HOL QS SP   | the dataset ID for the petition (see the petitions table documentation); shared key for the CSV/SQL versions of the data                                                                                                                                                               |
| name          | HOL QS SP   | petitioner’s name                                                                                                                                                                                                                                                                      |
| name_type     | HOL QS SP   | type of individual within the context of the petition. Values: “petr”=identified as petitioner at the beginning of the petition; “behalf”=a person on whose behalf the petition is submitted; “sub”=subscriber (names at the foot of the petition or a separate sheet)                 |
| sig_type      | HOL QS SP   | signature “types”. Values: “sig”=autograph signature; “in”=initials; “m”=signed with a mark; “ss”=petitioner’s name but in the same hand as the petition text (so probably written by a scribe); “\[s\]”=there is a signature but type not recorded (untranscribed Cheshire petitions) |
| gender        | HOL QS SP   | gender of petitioner. Values: male/female/unknown.                                                                                                                                                                                                                                     |
| residence     | QS          | petitioner’s residence, where identifiable within the petition                                                                                                                                                                                                                         |
| status        | QS          | petitioner occupation/social status, where identifiable within the petition                                                                                                                                                                                                            |

### Notes and caveats

Signatures were encoded at the time of transcription, making it
relatively easy to extract subscriber names (apart from a few that were
illegible or lost to damage).

All other petitioner data, including names, has been extracted from the
texts, largely relying on semi-automated procedures.

Although the process was accompanied by extensive manual checks,
corrections and additions, especially for petitioner names, none of this
additional data has been *comprehensively* checked for errors or
omissions.

-   Petitioner names were usually identified from the first line of the
    petition.
-   Gender was assigned primarily on the basis of extensive name lists
    drawn from English sources covering the 17th to 19th centuries.
-   Residence and occupation/status have been (so far) extracted for QS
    petitioners only, using a combination of context (eg, keywords such
    as “of” or “near” immediately following a name), place name
    gazetteers and fuzzy matching, followed by manual cleanup and
    removal of obvious errors. The quality/detail of available geo data
    varied between counties and was best for Cheshire.

# Data version

1.0, August 2022.

# Licence

This dataset is shared under a Creative Commons Attribution (CC-BY-SA)
licence (<https://creativecommons.org/licenses/by/4.0/>)

# Citation

Suggested format: Brodie Waddell and Sharon Howard. (2022). *The Power
of Petitioning in Early Modern England, 1573-1799, version 1.0*
\[dataset\].

# Credits and acknowledgments

An Arts and Humanities Research Council Research Grant (AH/S001654/1)
provided the primary funding for the project from January 2019 to
December 2020.

Two Economic History Society Carnevali Small Research Grants:

1.  funding for a pilot project in 2014-15
2.  funding to enable the addition of 18th-century QS petitions
    (2019-20)

IHR Digital undertook the technical work to publish the edition and
provided extensive valuable advice to the project
(<https://www.history.ac.uk/research/digital-history>)

Gavin Robinson (<https://www.drgavinrobinson.uk>) and Tim Wales
transcribed the petitions.

The repositories, without whom a project of this nature would be
impossible:

-   Cheshire Archives and Local Studies
    (<https://www.cheshirearchives.org.uk/>)
-   Derbyshire Record Office
    (<https://calmview.derbyshire.gov.uk/calmview/>)
-   London Metropolitan Archives (<https://search.lma.gov.uk>)
-   Staffordshire Archives
    (<http://www.archives.staffordshire.gov.uk/CalmView/Default.aspx>)
-   Worcestershire Archive and Archaeology Service
    (<http://e-services.worcestershire.gov.uk/CalmView/>)
-   Parliamentary Archives (<https://archives.parliament.uk/>)
-   The National Archives (<https://discovery.nationalarchives.gov.uk/>)

Significant additional online resources:

-   London Lives 1690-1800 (18th c Westminster petitions)
    (<https://www.londonlives.org/>)
-   State Papers Online \[subscription\]
    (<https://www.gale.com/intl/primary-sources/state-papers-online>)
-   FamilySearch (images of Cheshire QS records)
    (<https://www.familysearch.org/en/>)
-   Internet Archive (collection of *Calendar of State Papers Domestic*)
    (<https://archive.org/details/texts>)
-   Record Society of Lancashire and Cheshire (online publications)
    (<http://rslc.org.uk/out-of-print-publications/>)
