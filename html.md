# Introduction to HTML

###### \(Excerpt from Wikipedia\)

## What is HTML?

**Hypertext Markup Language**\(**HTML**\) is the standard [markup language](https://en.wikipedia.org/wiki/Markup_language) for creating [web pages](https://en.wikipedia.org/wiki/Web_page) and [web applications](https://en.wikipedia.org/wiki/Web_application). With [Cascading Style Sheets](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)\(CSS\) and [JavaScript](https://en.wikipedia.org/wiki/JavaScript) it forms a triad of cornerstone technologies for the [World Wide Web](https://en.wikipedia.org/wiki/World_Wide_Web).[\[3\]](https://en.wikipedia.org/wiki/HTML#cite_note-3)[Web browsers](https://en.wikipedia.org/wiki/Web_browser) receive HTML documents from a [web server](https://en.wikipedia.org/wiki/Web_server) or from local storage and render them into multimedia web pages. HTML describes the structure of a web page [semantically](https://en.wikipedia.org/wiki/Semantic_Web) and originally included cues for the appearance of the document.

[HTML elements](https://en.wikipedia.org/wiki/HTML_element) are the building blocks of HTML pages. With HTML constructs,[images](https://en.wikipedia.org/wiki/HTML_element#Images_and_objects) and other objects, such as [interactive forms,](https://en.wikipedia.org/wiki/Fieldset)may be embedded into the rendered page. It provides a means to create [structured documents](https://en.wikipedia.org/wiki/Structured_document) by denoting structural [semantics](https://en.wikipedia.org/wiki/Semantics) for text such as headings, paragraphs, lists,[links](https://en.wikipedia.org/wiki/Hyperlink), quotes and other items. HTML elements are delineated by tags, written using [angle brackets](https://en.wikipedia.org/wiki/Bracket#Angle_brackets). Tags such as`<img />`and`<input />`introduce content into the page directly. Others such  as`<p>...</p>`surround and provide information about document text and may include other tags as sub-elements. Browsers do not display the HTML tags, but use them to interpret the content of the page.

HTML can embed programs written in a [scripting language](https://en.wikipedia.org/wiki/Scripting_language) such as [JavaScript](https://en.wikipedia.org/wiki/JavaScript) which affect the behavior and content of web pages. Inclusion of CSS defines the look and layout of content. The [World Wide Web Consortium](https://en.wikipedia.org/wiki/World_Wide_Web_Consortium)\(W3C\), maintainer of both the HTML and the CSS standards, has encouraged the use of CSS over explicit presentational HTML since 1997.[\[4\]](https://en.wikipedia.org/wiki/HTML#cite_note-deprecated-4)

## History of HTML

### Development

In 1980, physicist [Tim Berners-Lee](https://en.wikipedia.org/wiki/Tim_Berners-Lee), a contractor at [CERN](https://en.wikipedia.org/wiki/CERN), proposed and prototyped [ENQUIRE](https://en.wikipedia.org/wiki/ENQUIRE), a system for CERN researchers to use and share documents. In 1989, Berners-Lee wrote a memo proposing an [Internet](https://en.wikipedia.org/wiki/Internet)-based [hypertext](https://en.wikipedia.org/wiki/Hypertext) system.[\[5\]](https://en.wikipedia.org/wiki/HTML#cite_note-5) Berners-Lee specified HTML and wrote the browser and server software in late 1990. That year, Berners-Lee and CERN data systems engineer [Robert Cailliau](https://en.wikipedia.org/wiki/Robert_Cailliau) collaborated on a joint request for funding, but the project was not formally adopted by CERN. In his personal notes[\[6\]](https://en.wikipedia.org/wiki/HTML#cite_note-6)from 1990 he listed[\[7\]](https://en.wikipedia.org/wiki/HTML#cite_note-7)"some of the many areas in which hypertext is used" and put an encyclopedia first.

The first publicly available description of HTML was a document called "HTML Tags", first mentioned on the Internet by Tim Berners-Lee in late 1991.[\[8\]](https://en.wikipedia.org/wiki/HTML#cite_note-tagshtml-8)[\[9\]](https://en.wikipedia.org/wiki/HTML#cite_note-9)It describes 18 elements comprising the initial, relatively simple design of HTML. Except for the hyperlink tag, these were strongly influenced by [SGMLguid](https://en.wikipedia.org/wiki/SGMLguid), an in-house [Standard Generalized Markup Language](https://en.wikipedia.org/wiki/Standard_Generalized_Markup_Language)\(SGML\)-based documentation format at CERN. Eleven of these elements still exist in HTML 4.[\[10\]](https://en.wikipedia.org/wiki/HTML#cite_note-10)

HTML is a [markup language](https://en.wikipedia.org/wiki/Markup_language) that [web browsers](https://en.wikipedia.org/wiki/Web_browser) use to interpret and [compose](https://en.wikipedia.org/wiki/Typesetting) text, images, and other material into visual or audible web pages. Default characteristics for every item of HTML markup are defined in the browser, and these characteristics can be altered or enhanced by the web page designer's additional use of [CSS](https://en.wikipedia.org/wiki/Cascading_Style_Sheets). Many of the text elements are found in the 1988 ISO technical report TR 9537 Techniques for using SGML, which in turn covers the features of early text formatting languages such as that used by the [RUNOFF command](https://en.wikipedia.org/wiki/TYPSET_and_RUNOFF) developed in the early 1960s for the [CTSS](https://en.wikipedia.org/wiki/Compatible_Time-Sharing_System)\(Compatible Time-Sharing System\) operating system: these formatting commands were derived from the commands used by typesetters to manually format documents. However, the SGML concept of generalized markup is based on elements \(nested annotated ranges with attributes\) rather than merely print effects, with also the separation of structure and markup; HTML has been progressively moved in this direction with CSS.

Berners-Lee considered HTML to be an application of SGML. It was formally defined as such by the [Internet Engineering Task Force](https://en.wikipedia.org/wiki/Internet_Engineering_Task_Force)\(IETF\) with the mid-1993 publication of the first proposal for an HTML specification, the "Hypertext Markup Language \(HTML\)" Internet Draft by Berners-Lee and [Dan Connolly](https://en.wikipedia.org/wiki/Dan_Connolly_%28computer_scientist%29), which included an SGML [Document type definition](https://en.wikipedia.org/wiki/Document_type_definition)to define the grammar.[\[11\]](https://en.wikipedia.org/wiki/HTML#cite_note-11)[\[12\]](https://en.wikipedia.org/wiki/HTML#cite_note-12)The draft expired after six months, but was notable for its acknowledgment of the [NCSA Mosaic](https://en.wikipedia.org/wiki/Mosaic_%28web_browser%29) browser's custom tag for embedding in-line images, reflecting the IETF's philosophy of basing standards on successful prototypes.[\[13\]](https://en.wikipedia.org/wiki/HTML#cite_note-raymond-13)Similarly,[Dave Raggett](https://en.wikipedia.org/wiki/Dave_Raggett)'s competing Internet-Draft, "HTML+ \(Hypertext Markup Format\)", from late 1993, suggested standardizing already-implemented features like tables and fill-out forms.[\[14\]](https://en.wikipedia.org/wiki/HTML#cite_note-html+-14)

After the HTML and HTML+ drafts expired in early 1994, the IETF created an HTML Working Group, which in 1995 completed "HTML 2.0", the first HTML specification intended to be treated as a standard against which future implementations should be based.[\[15\]](https://en.wikipedia.org/wiki/HTML#cite_note-15)

Further development under the auspices of the IETF was stalled by competing interests. Since 1996, the HTML specifications have been maintained, with input from commercial software vendors, by the [World Wide Web Consortium](https://en.wikipedia.org/wiki/World_Wide_Web_Consortium)\(W3C\).[\[16\]](https://en.wikipedia.org/wiki/HTML#cite_note-raggett-16)However, in 2000, HTML also became an international standard \([ISO](https://en.wikipedia.org/wiki/International_Organization_for_Standardization)/[IEC](https://en.wikipedia.org/wiki/International_Electrotechnical_Commission)15445:2000\). HTML 4.01 was published in late 1999, with further errata published through 2001. In 2004, development began on HTML5 in the [Web Hypertext Application Technology Working Group](https://en.wikipedia.org/wiki/Web_Hypertext_Application_Technology_Working_Group)\(WHATWG\), which became a joint deliverable with the W3C in 2008, and completed and standardized on 28 October 2014.[\[17\]](https://en.wikipedia.org/wiki/HTML#cite_note-17)

### HTML versions timeline

**November 24, 1995**

HTML 2.0 was published as IETF [RFC 1866](https://tools.ietf.org/html/rfc1866). Supplemental [RFCs](https://en.wikipedia.org/wiki/Request_for_Comments) added capabilities:

* November 25, 1995:[RFC 1867](https://tools.ietf.org/html/rfc1867)\(form-based file upload\)
* May 1996:[RFC 1942](https://tools.ietf.org/html/rfc1942)\(tables\)
* August 1996:[RFC 1980](https://tools.ietf.org/html/rfc1980)\(client-side image maps\)
* January 1997:[RFC 2070](https://tools.ietf.org/html/rfc2070)\([internationalization](https://en.wikipedia.org/wiki/Internationalization_and_localization)\)

**January 14, 1997**

HTML 3.2[\[18\]](https://en.wikipedia.org/wiki/HTML#cite_note-18)was published as a [W3C Recommendation](https://en.wikipedia.org/wiki/W3C_Recommendation). It was the first version developed and standardized exclusively by the W3C, as the IETF had closed its HTML Working Group on September 12, 1996.[\[19\]](https://en.wikipedia.org/wiki/HTML#cite_note-19)Initially code-named "Wilbur",[\[20\]](https://en.wikipedia.org/wiki/HTML#cite_note-engelfriet-20)HTML 3.2 dropped math formulas entirely, reconciled overlap among various proprietary extensions and adopted most of [Netscape](https://en.wikipedia.org/wiki/Netscape)'s visual markup tags. Netscape's [blink element](https://en.wikipedia.org/wiki/Blink_element) and [Microsoft](https://en.wikipedia.org/wiki/Microsoft)'s [marquee element](https://en.wikipedia.org/wiki/Marquee_element) were omitted due to a mutual agreement between the two companies.[\[16\]](https://en.wikipedia.org/wiki/HTML#cite_note-raggett-16) A markup for mathematical formulas similar to that in HTML was not standardized until 14 months later in [MathML](https://en.wikipedia.org/wiki/MathML).

**December 18, 1997**

HTML 4.0[\[21\]](https://en.wikipedia.org/wiki/HTML#cite_note-21) was published as a W3C Recommendation. It offers three variations:

* Strict, in which deprecated elements are forbidden
* Transitional, in which deprecated elements are allowed
* Frameset, in which mostly only [frame](https://en.wikipedia.org/wiki/Framing_%28World_Wide_Web%29) related elements are allowed.

Initially code-named "Cougar",[\[20\]](https://en.wikipedia.org/wiki/HTML#cite_note-engelfriet-20) HTML 4.0 adopted many browser-specific element types and attributes, but at the same time sought to phase out Netscape's visual markup features by marking them as [deprecated](https://en.wikipedia.org/wiki/Deprecation) in favor of style sheets. HTML 4 is an SGML application conforming to ISO 8879 – SGML.[\[22\]](https://en.wikipedia.org/wiki/HTML#cite_note-22) 

**April 24, 1998 **

HTML 4.0 [\[23\]](https://en.wikipedia.org/wiki/HTML#cite_note-23) was reissued with minor edits without incrementing the version number. 

**December 24, 1999** 

HTML 4.01[\[24\]](https://en.wikipedia.org/wiki/HTML#cite_note-24) was published as a W3C Recommendation. It offers the same three variations as HTML 4.0 and its last [errata](http://www.w3.org/MarkUp/html4-updates/errata) were published on May 12, 2001.

**May 2000**

ISO/IEC 15445:2000[\[25\]](https://en.wikipedia.org/wiki/HTML#cite_note-iso-html-25)[\[26\]](https://en.wikipedia.org/wiki/HTML#cite_note-26)\("[ISO](https://en.wikipedia.org/wiki/International_Organization_for_Standardization) HTML", based on HTML 4.01 Strict\) was published as an ISO/IEC international standard. In the ISO this standard falls in the domain of the [ISO/IEC JTC1/SC34](https://en.wikipedia.org/wiki/ISO/IEC_JTC1/SC34)\(ISO/IEC Joint Technical Committee 1, Subcommittee 34 – Document description and processing languages\).[\[25\]](https://en.wikipedia.org/wiki/HTML#cite_note-iso-html-25)

After HTML 4.01, there was no new version of HTML for many years as development of the parallel, XML-based language XHTML occupied the W3C's HTML Working Group through the early and mid-2000s.

**October 28, 2014**

HTML5[\[27\]](https://en.wikipedia.org/wiki/HTML#cite_note-27) was published as a W3C Recommendation.[\[28\]](https://en.wikipedia.org/wiki/HTML#cite_note-28)

**November 1, 2016**

HTML 5.1[\[29\]](https://en.wikipedia.org/wiki/HTML#cite_note-29) was published as a W3C Recommendation.[\[30\]](https://en.wikipedia.org/wiki/HTML#cite_note-30)[\[31\]](https://en.wikipedia.org/wiki/HTML#cite_note-31)

**December 14, 2017**

HTML 5.2[\[32\]](https://en.wikipedia.org/wiki/HTML#cite_note-32) was published as a W3C Recommendation.[\[33\]](https://en.wikipedia.org/wiki/HTML#cite_note-33)[\[34\]](https://en.wikipedia.org/wiki/HTML#cite_note-34)

#### HTML draft version timeline

**October 1991**

HTML Tags,[\[8\]](https://en.wikipedia.org/wiki/HTML#cite_note-tagshtml-8) an informal CERN document listing 18 HTML tags, was first mentioned in public.

**June 1992**

First informal draft of the HTML DTD, [\[35\]](https://en.wikipedia.org/wiki/HTML#cite_note-35)with seven[\[36\]](https://en.wikipedia.org/wiki/HTML#cite_note-36)[\[37\]](https://en.wikipedia.org/wiki/HTML#cite_note-37)[\[38\]](https://en.wikipedia.org/wiki/HTML#cite_note-html11-38)subsequent revisions \(July 15, August 6, August 18, November 17, November 19, November 20, November 22\)

**November 1992**

HTML DTD 1.1 \(the first with a version number, based on RCS revisions, which start with 1.1 rather than 1.0\), an informal draft [\[38\]](https://en.wikipedia.org/wiki/HTML#cite_note-html11-38)

**June 1993**

Hypertext Markup Language[\[39\]](https://en.wikipedia.org/wiki/HTML#cite_note-39) was published by the [IETF](https://en.wikipedia.org/wiki/Internet_Engineering_Task_Force) IIIR Working Group as an Internet Draft \(a rough proposal for a standard\). It was replaced by a second version[\[40\]](https://en.wikipedia.org/wiki/HTML#cite_note-ietfiiir-40) one month later, followed by six further drafts published by IETF itself [\[41\]](https://en.wikipedia.org/wiki/HTML#cite_note-41) that finally led to HTML 2.0 in [RFC 1866](https://tools.ietf.org/html/rfc1866).

**November 1993**

HTML+ was published by the IETF as an Internet Draft and was a competing proposal to the Hypertext Markup Language draft. It expired in May 1994.

**April 1995 \(authored March 1995\)**

HTML 3.0[\[42\]](https://en.wikipedia.org/wiki/HTML#cite_note-42) was proposed as a standard to the IETF, but the proposal expired five months later \(28 September 1995\) [\[43\]](https://en.wikipedia.org/wiki/HTML#cite_note-html30cover-43) without further action. It included many of the capabilities that were in Raggett's HTML+ proposal, such as support for tables, text flow around figures and the display of complex mathematical formulas.[\[43\]](https://en.wikipedia.org/wiki/HTML#cite_note-html30cover-43) W3C began development of its own [Arena browser](https://en.wikipedia.org/wiki/Arena_%28web_browser%29) as a [test bed](https://en.wikipedia.org/wiki/Test_bed) for HTML 3 and Cascading Style Sheets,[\[44\]](https://en.wikipedia.org/wiki/HTML#cite_note-44)[\[45\]](https://en.wikipedia.org/wiki/HTML#cite_note-45)[\[46\]](https://en.wikipedia.org/wiki/HTML#cite_note-46) but HTML 3.0 did not succeed for several reasons. The draft was considered very large at 150 pages and the pace of browser development, as well as the number of interested parties, had outstripped the resources of the IETF.[\[16\]](https://en.wikipedia.org/wiki/HTML#cite_note-raggett-16) Browser vendors, including Microsoft and Netscape at the time, chose to implement different subsets of HTML 3's draft features as well as to introduce their own extensions to it.[\[16\]](https://en.wikipedia.org/wiki/HTML#cite_note-raggett-16)\(see [Browser wars](https://en.wikipedia.org/wiki/Browser_wars)\). These included extensions to control stylistic aspects of documents, contrary to the "belief \[of the academic engineering community\] that such things as text color, background texture, font size and font face were definitely outside the scope of a language when their only intent was to specify how a document would be organized."[\[16\]](https://en.wikipedia.org/wiki/HTML#cite_note-raggett-16)Dave Raggett, who has been a W3C Fellow for many years, has commented for example: "To a certain extent, Microsoft built its business on the Web by extending HTML features."[\[16\]](https://en.wikipedia.org/wiki/HTML#cite_note-raggett-16)

**January 2008**

[HTML5](https://en.wikipedia.org/wiki/HTML5) was published as a [Working Draft](https://en.wikipedia.org/wiki/World_Wide_Web_Consortium#Recommendations_and_Certifications) by the W3C.[\[47\]](https://en.wikipedia.org/wiki/HTML#cite_note-47) Although its syntax closely resembles that of [SGML](https://en.wikipedia.org/wiki/SGML), [HTML5](https://en.wikipedia.org/wiki/HTML5) has abandoned any attempt to be an SGML application and has explicitly defined its own "html" serialization, in addition to an alternative XML-based XHTML5 serialization.[\[48\]](https://en.wikipedia.org/wiki/HTML#cite_note-48)

**2011 HTML5 – Last Call**

On 14 February 2011, the W3C extended the charter of its HTML Working Group with clear milestones for HTML5. In May 2011, the working group advanced HTML5 to "Last Call", an invitation to communities inside and outside W3C to confirm the technical soundness of the specification. The W3C developed a comprehensive test suite to achieve broad interoperability for the full specification by 2014, which was the target date for recommendation.[\[49\]](https://en.wikipedia.org/wiki/HTML#cite_note-w3c2014-49)

In January 2011, the WHATWG renamed its "HTML5" living standard to "HTML". The W3C nevertheless continues its project to release HTML5.[\[50\]](https://en.wikipedia.org/wiki/HTML#cite_note-50)

**2012 HTML5 – Candidate Recommendation**

In July 2012, WHATWG and [W3C](https://en.wikipedia.org/wiki/W3C) decided on a degree of separation. W3C will continue the HTML5 specification work, focusing on a single definitive standard, which is considered as a "snapshot" by WHATWG. The WHATWG organization will continue its work with HTML5 as a "Living Standard". The concept of a living standard is that it is never complete and is always being updated and improved. New features can be added but functionality will not be removed.[\[51\]](https://en.wikipedia.org/wiki/HTML#cite_note-51)

In December 2012, W3C designated HTML5 as a Candidate Recommendation.[\[52\]](https://en.wikipedia.org/wiki/HTML#cite_note-52) The criterion for advancement to[W3C Recommendation](https://en.wikipedia.org/wiki/W3C_recommendation#W3C_Recommendation_%28REC%29) is "two 100% complete and fully interoperable implementations".[\[53\]](https://en.wikipedia.org/wiki/HTML#cite_note-W3Crec-53)

**2014 HTML5 – Proposed Recommendation and Recommendation**

In September 2014, W3C moved HTML5 to Proposed Recommendation.[\[54\]](https://en.wikipedia.org/wiki/HTML#cite_note-54)

On 28 October 2014, HTML5 was released as a stable W3C Recommendation,[\[55\]](https://en.wikipedia.org/wiki/HTML#cite_note-55) meaning the specification process is complete.

[\[56\]](https://en.wikipedia.org/wiki/HTML#cite_note-finalars-56)

#### XHTML versions

Main article:

[XHTML](https://en.wikipedia.org/wiki/XHTML)

XHTML is a separate language that began as a reformulation of HTML 4.01 using[XML](https://en.wikipedia.org/wiki/XML)1.0. It is no longer being developed as a separate standard.

* XHTML 1.0 was published as a W3C Recommendation on January 26, 2000[\[57\]](https://en.wikipedia.org/wiki/HTML#cite_note-57) and was later revised and republished on August 1, 2002. It offers the same three variations as HTML 4.0 and 4.01, reformulated in XML, with minor restrictions.
* XHTML 1.1[\[58\]](https://en.wikipedia.org/wiki/HTML#cite_note-58) was published as a W3C Recommendation on May 31, 2001. It is based on XHTML 1.0 Strict, but includes minor changes, can be customized, and is reformulated using modules in the W3C recommendation "Modularization of XHTML", which was published on April 10, 2001.[\[59\]](https://en.wikipedia.org/wiki/HTML#cite_note-59)
* XHTML 2.0 was a working draft, work on it was abandoned in 2009 in favor of work on [HTML5](https://en.wikipedia.org/wiki/HTML5) and [XHTML5](https://en.wikipedia.org/wiki/XHTML#XHTML5).[\[60\]](https://en.wikipedia.org/wiki/HTML#cite_note-60)[\[61\]](https://en.wikipedia.org/wiki/HTML#cite_note-61)[\[62\]](https://en.wikipedia.org/wiki/HTML#cite_note-62)
  XHTML 2.0 was incompatible with XHTML 1.x and, therefore, would be more accurately characterized as an XHTML-inspired new language than an update to XHTML 1.x.
* An XHTML syntax, known as "XHTML5.1", is being defined alongside [HTML5](https://en.wikipedia.org/wiki/HTML5) in the HTML5 draft.[\[63\]](https://en.wikipedia.org/wiki/HTML#cite_note-63)

## Semantic HTML

Semantic HTML is a way of writing HTML that emphasizes the meaning of the encoded information over its presentation \(look\). HTML has included semantic markup from its inception,[\[76\]](https://en.wikipedia.org/wiki/HTML#cite_note-76)but has also included presentational markup, such as`<font>`,`<i>`and`<center>`tags. There are also the semantically neutral [span and div](https://en.wikipedia.org/wiki/Span_and_div) tags. Since the late 1990s when [Cascading Style Sheets](https://en.wikipedia.org/wiki/Cascading_Style_Sheets) were beginning to work in most browsers, web authors have been encouraged to avoid the use of presentational HTML markup with a view to the [separation of presentation and content](https://en.wikipedia.org/wiki/Separation_of_presentation_and_content).[\[77\]](https://en.wikipedia.org/wiki/HTML#cite_note-77)

In a 2001 discussion of the [Semantic Web](https://en.wikipedia.org/wiki/Semantic_Web),[Tim Berners-Lee](https://en.wikipedia.org/wiki/Tim_Berners-Lee) and others gave examples of ways in which intelligent software "agents" may one day automatically crawl the web and find, filter and correlate previously unrelated, published facts for the benefit of human users.[\[78\]](https://en.wikipedia.org/wiki/HTML#cite_note-78)Such agents are not commonplace even now, but some of the ideas of [Web 2.0](https://en.wikipedia.org/wiki/Web_2.0),[mashups](https://en.wikipedia.org/wiki/Mashup_%28web_application_hybrid%29) and [price comparison websites](https://en.wikipedia.org/wiki/Price_comparison_service) may be coming close. The main difference between these web application hybrids and Berners-Lee's semantic agents lies in the fact that the current [aggregation](https://en.wikipedia.org/wiki/Feed_aggregator) and hybridization of information is usually designed in by [web developers](https://en.wikipedia.org/wiki/Web_developer), who already know the web locations and the [API semantics](https://en.wikipedia.org/wiki/Application_programming_interface) of the specific data they wish to mash, compare and combine.

An important type of web agent that does crawl and read web pages automatically, without prior knowledge of what it might find, is the [web crawler](https://en.wikipedia.org/wiki/Web_crawler) or search-engine spider. These software agents are dependent on the semantic clarity of web pages they find as they use various techniques and [algorithms](https://en.wikipedia.org/wiki/Algorithm)to read and index millions of web pages a day and provide web users with [search facilities](https://en.wikipedia.org/wiki/Web_search_engine) without which the World Wide Web's usefulness would be greatly reduced.

In order for search-engine spiders to be able to rate the significance of pieces of text they find in HTML documents, and also for those creating mashups and other hybrids as well as for more automated agents as they are developed, the semantic structures that exist in HTML need to be widely and uniformly applied to bring out the meaning of published text.[\[79\]](https://en.wikipedia.org/wiki/HTML#cite_note-Semantic_Web_Revisted-79)

Presentational markup tags are [deprecated](https://en.wikipedia.org/wiki/Deprecation) in current HTML and[XHTML](https://en.wikipedia.org/wiki/XHTML)recommendationsand are illegal in HTML5\[[citation needed](https://en.wikipedia.org/wiki/Wikipedia:Citation_needed)\].

Good semantic HTML also improves the [accessibility](https://en.wikipedia.org/wiki/Accessibility)of web documents \(see also [Web Content Accessibility Guidelines](https://en.wikipedia.org/wiki/Web_Content_Accessibility_Guidelines)\). For example, when a screen reader or audio browser can correctly ascertain the structure of a document, it will not waste the visually impaired user's time by reading out repeated or irrelevant information when it has been marked up correctly.



