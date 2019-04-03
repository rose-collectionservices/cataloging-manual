# D. MARC Fields

1.	Currently Rose Library catalogers use MARC encoding format for bibliographic records. When copy cataloging from records in OCLC Connexion, exercise caution that the record is for the same item you have in hand.
2.	Any records from Connexion for items after 1801 should be edited to comply with RDA Guidelines. This includes changing Fixed Fields, updating 260 to appropriate 264, adding appropriate RDA relator terms, checking that all contributors appear in 7xx fields.
3.	Name and Subject Authorities should be checked for accuracy, and any uncontrolled names and subjects should be updated to controlled vocabulary if possible.
4.	Any added name authorities, non-LCSH vocabulary (for example, RBMS thesaurus), binding notes or identifying marks notes that pertain specifically to the Rose copy should have $5 GEU as the final subfield. This protects these fields from being edited/deleted during batch updates and other catalog-wide processes.

* [A. 245/246 fields](#a-245246-fields)
* [B. 510 Fields](#b-510-fields)
* [C. 562 Fields](#c-562-fields)
* [D. 563 Fields](#d-563-fields)
* [E. 500/590 fields](#e-500590-fields)
* [F. 6xx Fields](#f-6xx-fields)
* [G. 7xx Fields](#g-7xx-fields)
* [H. Collection notes](#h-collection-notes)

### A. 245/246 Fields

Add as many 246 fields as necessary to record parallel titles and variations between the title page title and the cover, spine, running and/or caption titles. Use discretion regarding the first indicator as to whether users need to *see* all the variants or only need to be able to use them in *searching*.

### B. 510 Fields

This field is used for citations from published bibliographies. They are only given if they clarify which edition or printing Rose has, or to authenticate to users which rare early item Rose holds (particularly from Short Title Catalogs, see Resources at the end of this document). The 510 field is visible in DiscoverE.

Many bibliographies are available in print in Rose Library (for example: Chester Topp’s *Victorian yellowbacks & paperbacks, 1849-1905*, or Brandes and Durkan’s *Seamus Heaney : a bibliography, 1959-2003*).

For further information on the formation and use of 510 citations consult Standard Citation Forms for Rare Book Cataloging, which is accessible through Cataloger’s Desktop.

### C. 562 Fields

This field is used primarily to note identifying marks in the Rose copy, such as signature, marginalia, bookplates, or other permanent copy-specific markings. The final subfield in 562 must be $5 GEU. This field is visible in DiscoverE.

### D. 563 Fields

This field is used for notes about the item binding, primarily for works that have copy-specific bindings, publisher’s decorated bindings (19th century, generally), fine bindings, artists’ books, etc. Additionally, many Danowski items come in paper wrappers, which should be noted, as well as if the item is in a slipcase or box other than those made by Preservation.

For binding terms help, use either the print or online version of Roberts and Etherington *Bookbinding and the conservation of books: a dictionary of descriptive terminology*.

For rare books that are not artists’ books or modern editions (Danowksi), 563 notes are usually echoed in 655_7 terms from the RBMS vocabulary. The final subfield in 562 must be $5 GEU unless the binding information can apply to any copy of the item. This field is visible in DiscoverE.

### E. 500/590 Fields

In Rose Library records there are often extensive use of 5xx fields in order to record all the edition-specific and Rose item-specific characteristics of an item.

1. The 500 field is meant to reflect only notes that are true of all copies of an item, such as information in a colophon, untraced information from a series, or additional information about the edition.
2.	Use the 563 field for binding notes. This field is free text, but should end the $5 GEU
3.	The 590 is used to record information that only pertains to the locally held copy. If there are multiple copies of a resource in Rose Library, each item gets its own 590 in the bibliographic record.
4.	Delete from Connexion record any 500 or 590 (or other local notes) that do not apply to the Rose Library copy.
5.	Each 590 should begin with:

    “Stuart A. Rose Manuscript, Archives, & Rare Book Library copy…”

    For Danowski items the note should read:

    “Stuart A. Rose Manuscript, Archives, & Rare Book Library Danowski copy…”

    However, if there are other forms of this library’s name in existing 590s (Woodruff Special Collections, etc.) do not change those forms.
6.	590 fields should note some specific attributes of the Rose copy.

  a. __Limited editions__: A note containing the edition note, usually from the colophon or title page verso should appear in the 500 field, followed by a 590 note with the Rose copy number:

500 __ $a "A special edition was made of 40 fold-out copies, hardbound in cloth, each with an original hand-sprayed image. They are signed and numbered by the artist. 500 plain-clothed copies were bound in Speckeltone cover (recycled)"--Title page verso.

590 __ $a Stuart A. Rose Manuscript, Archives, & Rare Book Library copy is number 20.

  b.	__Autograph, presentation, and inscribed copies__: Add 590 note when a work is autographed or inscribed by an individual. If the autograph consists of more than just the person’s name quote the whole autograph in the note. If the work is inscribed to an individual, quote the entire inscription in the note unless it is unusually long; then some parts may be omitted for brevity.

590   Manuscript, Archives, and Rare Book Library copy signed by the author.

590   Manuscript, Archives, and Rare Book Library copy has autograph: Ralph McGill, 3-17-58.

590   Manuscript, Archives, and Rare Book Library copy has presentation inscription: “For Alice Walker, with the warmest regards of Elizabeth Smith, 10-27-88.”

  * Also add a 700 added entry with the appropriate RDA relator term for collector, inscriber or signer.

  c.	__Bookplates__: Note the presence of bookplates in either a 562 or a 590 note. Add a 700 note with the appropriate RDA relator term for former owner.

  d.	__Additional distinguishing characteristics to note__:

  *	Presence of dust jacket
  *	Paperback (if necessary to distinguish it from other copies)
  *	Any imperfections, such as missing pages.

  e.	__Laid- in items__: Occasionally volumes will have additional items such as letters or newspaper clippings. If there is a manuscript collection that corresponds to the volume’s provenance, complete a “separated from” form for the item and give it to a member of Arrangement and Description so it can be added to the manuscript collection. If there is no corresponding manuscript collection the item should be transferred to Preservation so the laid-in item can be housed in acid-free paper and kept with the volume. In either case, add to, or add a 590 note detailing either that the item has moved to the manuscript collection (use the proper name of the collection), or that the volume has a letter/prospectus/program etc. laid in.

### F. 6xx Fields

1.	Follow standard practice for assigning subject and genre fields. All Rose Library materials should have a minimum of one subject heading or genre/form term. However, the more access points catalogers can reasonably assign up to approximately six (6), the better. For more information on subject headings in general, please see the Subject Heading Manual  (SHM) section H180: [https://www.loc.gov/aba/publications/FreeSHM/H0180.pdf](https://www.loc.gov/aba/publications/FreeSHM/H0180.pdf)
2. Any 655 fields that are specific to the Rose copy, such as RBMS vocabulary must have $5 GEU as the final subfield.
3. One of the major collecting areas for Rose is African American print culture. In order to call out early items, a small number of local genre terms are used in MARBL cataloging and are used when cataloging African American materials or works printed in the __South pre-1871__:

655  7 African American author. |2 local |5 GEU

655  7 African American illustrator. |2 local |5 GEU

655  7 African American pamphlet. |2 local |5 GEU

655  7 African American publisher. |2 local |5 GEU

655  7 Southern imprint |z [state of publication/printing] |y [year of publication/printing] |2 local |5 GEU

4.	Any thesaurus terms that are not LCSH generally appear in 655 _ 7 with the addition of $2 for the source of the term (see LC Genre/Form Code and Term Source Codes).

### G. 7xx Fields

In Rose Library records, there are often quite a few 7xx fields to capture names of both manifestation level contributors, and names related at the item level.

1.	Create added entry headings for all contributors to an expression, including authors, editors, writers of added content, publishers, and printers; or contributors to an item including bookbinders, inscribers, former owners, signers, etc.
2.	All added entries should include $e with the appropriate RDA relator term. Use RDA vocabulary terms is standard local practice for Rose Library. For item level names, such as former owners, collectors, signers, inscribers, etc, add $5 GEU as the final subfield to protect those entries from overlay.
3.	Use authorized forms if they are available, otherwise create a name using RDA Guidelines. If the contributor is considered significant enough to merit a new authority, complete cataloging and forward the item to the NACO cataloger (generally Rare Book Cataloger) for authority creation.

### H. Collection notes

A number of Rose Library collections records have additional added fields to identify the collection to which they belong.

1. All named collections should have a 590 note that reads:

    Stuart A. Rose Manuscript, Archives, & Rare Book Library copy from the library of…

2.	All volumes from named collections that are received with the original collection should have 700_1 added entries, for example:

    Danowski, Raymond, $e collector $5 GEU
    Billops, Camille, $e former owner.$5 GEU
    Hatch, James V. $q (James Vernon),$d 1928-$ former owner.$5 GEU

    This note should not be added to items that were added to a collection after the original collection items. This is particulary true of the Danowski items, many of which were not collected by Raymond Danowski but have been purchased subsequently by Rose Library.

3.	Volumes donated by Stuart Rose also receive both a 590 and a 700:

    Rose, Stuart, $e collector.

4.	All items of the Danowski Literary and Poetry Library should have a 590 and also have a 710_2

    590 _ _ Stuart A. Rose Manuscript, Archives, & Rare Book Library Danowski copy forms part of the Raymond Danowski Poetry Library.
    710 2_Raymond Danowski Poetry Library (Emory University. General Libraries) $5 GEU
