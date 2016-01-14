---
coding: utf-8

title: The Role of the IRTF Chair
docname: draft-iab-irtf-chair-description-latest
category: info
wg: Internet Architecture Board (IAB)
ipr: trust200902

stand_alone: yes
pi: [toc, sortrefs, symrefs, comments]

author:
  -
    ins: L. Eggert
    name: Lars Eggert
    org: NetApp
    street: Sonnenallee 1
    city: Kirchheim bei München
    code: 85551
    country: Germany
    phone: +49 151 120 55791
    email: lars@netapp.com


informative:
    RFC2014:
    RFC2850:
    RFC4440:
    RFC5742:
    RFC5743:
    IAB-EXP:
        title: "Desired Expertise: Member of the Internet Architecture Board"
        author:
            org: NomCom 2015
        date: 2015
        target: https://datatracker.ietf.org/nomcom/2015/requirements/#iab-member
    IESG-EXP:
        title: Generic IESG Member Expertise
        author:
            org: NomCom 2015
        date: 2015
        target: http://trac.tools.ietf.org/group/iesg/trac/wiki/GenericExpertise
    IETF-JOURNAL:
        title: The IETF Journal
        author:
            org: Internet Society
        target: http://www.internetsociety.org/publications/ietf-journal
    IRTF-WIKI:
        title: IRTF Wiki
        author:
            org: Internet Research Task Force
        target: http://trac.tools.ietf.org/group/irtf/trac/wiki
    ID-TEMPLATE:
        title: martinthomson/i-d-template
        author:
            ins: M. Thomson
        target: https://github.com/martinthomson/i-d-template
    REPO:
        title: larseggert/irtf-chair-description
        author:
            ins: L. Eggert
        target: https://github.com/larseggert/irtf-chair-description
    KRAMDOWN-RFC2629:
        title: cabo/kramdown-rfc2629
        author:
            ins: C. Bormann
        target: https://github.com/cabo/kramdown-rfc2629


--- abstract

This document briefly describes the role of the Chair of the Internet Research
Task Force (IRTF), discusses its duties and outlines the skill set a candidate
for the role should ideally have.

--- middle

# Introduction

The Internet Research Task Force (IRTF) focuses on longer term research issues
related to the Internet while the sister organization, the Internet Engineering
Task Force (IETF), focuses on the shorter term issues of engineering and
standards making.

The IRTF consists of a number of topical and long-term Research Groups (RGs).
These groups work on issues related to Internet protocols, applications,
architecture and technology. RGs have the stable long term membership which is
needed to promote the development of research collaboration and teamwork in
exploring research issues. Individual contributors participate in the IRTF,
rather than representatives of organizations.

{{RFC2014}} details the procedures by which RGs operate. {{RFC4440}} discusses a
view from the Internet Architecture Board (IAB) on the IRTF and its relationship
to the IETF. The RFC Editor publishes documents from the IRTF and its RGs on the
IRTF Stream {{RFC5743}}.

The IRTF Chair manages the IRTF in consultation with the Internet Research
Steering Group (IRSG). The IRSG membership includes the IRTF Chair, the chairs
of the various RGs and other individuals ("members at large") from the research
community selected by the IRTF Chair.


# Duties

This section discusses the various duties of the IRTF chair and outlines the
skill set a candidate for the role should ideally have.


## Strategic

Arguably the most important part of the duties of the IRTF Chair is strategic,
and concern shaping of the purpose and scope of the IRTF, by making decisions
about which RGs to charter, which RGs to terminate, and which other activities
or efforts the IRTF should organize or affiliate itself with in order to further
its charter and increase the interaction and collaboration between network
research, engineering, operations and standardization.

For some new RGs, the research and engineering community brings a proposal to
the IRTF Chair for discussion. However, it is common for the IRTF Chair to
identify a new area of research that is considered of importance to the
Internet, actively motivate people in the research and engineering community to
consider the formation of an RG, and help them navigate the process for doing
so.

In order to be able to fulfill this duty, it is important for the IRTF Chair to
be involved in both the academic research community as well as engineering or
operational communities. Without a demonstrated history of participation in
these often somewhat isolated communities it will be very difficult to identify
areas of academic research that are suitable for being brought into the IRTF. A
good network of contacts in these communities will be very helpful in
identifying and motivating potential RG chairs and participants.

Involvement in the academic research community can be demonstrated through a
publication record, membership in conference program and organizational
committees, participation in publicly funded collaborative research projects,
among others.

In addition to chartering new RGs, it is equally important for the IRTF to end
RGs that have run out of energy, are focused on issues no longer considered
important for the Internet, or are otherwise not operating well. Careful
communication and good people skills are essential in order to explain the
reasons for concluding an RG. The same skill set is also useful when explaining
to proponents of a new RG why their request is being denied.

The Applied Networking Research Prize (ANRP) is a joint award of the Internet
Society (ISOC) and an example of a strategic initiative that since its inception
in 2011 now turned into more of an administrative duty. The IRTF Chair and an
ISOC representative pick and chair the ANRP selection committee, which
advertises the ANRP, encourages community nominations for the prizes, and
reviews nominations and selects prize winners. The IRTF Chair and the ISOC
representative also mentor the ANRP winners, who are often IETF newcomers, and
introduce them to other attendees who may have an interest in their work.

Chairmanship of the ANRP selection committee also relies on strong ties to the
academic research community, to identify suitable selection committee members
and to encourage nominations for suitable work that is published in a given
year. The selection committee operates similar to a program committee for an
academic conference (more specifically, it performs a function similar to the
selection of a best paper award). It is therefore useful if the IRTF Chair has
firsthand experience serving on program committees, and ideally, chairing them.


## Administrative

A good fraction of the duties of the IRTF Chair are administrative. Some of them
may be permanently or temporarily delegated to other IRSG members, but they
ultimately always remain the IRTF Chair's responsibility.

Some of those related to publishing documents on the IRTF RFC Stream, such as
ensuring sufficient review, so that documents published are of good quality,
scheduling the required Internet Engineering Steering Group (IESG) review
{{RFC5742}}, and following up with the IESG, IANA and the RFC Editor during and
after the publication process.

Other administrative duties include reviewing and approving requests from the
RGs for time slots during IETF meetings or interim meetings elsewhere, ensuring
that meeting materials are submitted on schedule, maintaining the IRTF web site,
and -- in cooperation with the RG chairs -- ensuring that the IETF datatracker
correctly reflects the status of the various IRTF-related documents.

The IRTF Chair appoints, replaces and manages the RG chairs and the IRSG, and
follows the research work of the chartered and proposed RGs to a degree that is
sufficient to let them develop an understanding on whether they are generally
operating well.

The IRTF Chair also defines the operational procedures for the IRTF (in the
boundaries defined by {{RFC2014}}) and the IRSG. At the moment, these procedures
are captured as a set of [wiki pages](#IRTF-WIKI) and it is the duty of the IRTF
Chair to refine and update these descriptions as procedures evolve. When process
questions on the IRSG or in an RG arise (e.g., on IPR, liaison statements,
consensus procedures, copyright, plagiarism, document publication, etc.), the
IRTF Chair is frequently consulted and needs to have sufficient familiarity in
the area to provide a definitive answer, or at least be able to identify an
external party for further consultation.

The IRSG tries to schedule a working dinner during each IETF meeting, and the
IRTF Chair is responsible for organizing the agenda and a suitable venue.

The IRTF Chair provides a status report on the IRTF to the IAB on a monthly
basis, and also writes a regular column for the [IETF Journal](#IETF-JOURNAL) on
recent IRTF-related events.

During each IETF meeting, the IRTF Chair is responsible for organizing and
chairing the "IRTF Open Meeting", during which topics related to the IRTF are
being presented and discussed. This includes a report by the IRTF Chair on the
status of the IRTF and its RGs (an abbreviated version of this report is also
usually given during the IETF Technical Plenary) as well as other presentations
from RGs, ANRP prize winners, individuals wishing to propose new RGS, or others.

These administrative duties are very similar to part of the duties of an Area
Director (AD) in the IETF and require the same set of organizational and
communication skills {{IESG-EXP}}. They also require a regular time commitment
throughout the year, the ability to attend most of the IETF meetings in person,
as well as some other related travel.

The IRTF Chair regularly interacts with the ADs and the IESG for document
reviews, IETF meeting agenda planning, and often provides input on various IETF
efforts and topics. The IRTF Chair also regularly interacts with the IETF
Administrative Oversight Committee (IAOC) and the IETF Secretariat for meeting
planning, budgeting and other organizational purposes. In addition, the IRTF
Chair also interacts with the Tools Team to provide input on how IETF tools can
best support the operation of the IRTF. Finally, the IRTF Chair is the owner of
the IRTF RFC Stream and is hence part of the group that reviews the RFC Editor's
performance and operation; and engages with the Independent Stream Editor in
cases where submissions on that RFC Stream have relationships to the IRTF. A
good understanding of the purpose and procedures of these different bodies and a
good working relationship with the individuals serving on them is important.


## IAB Membership

The IRTF Chair serves as an "ex officio" member of the IAB {{RFC2850}}, and is
expected to participate in IAB discussions and activities alongside the
NomCom-appointed IAB members.

This duty benefits from expertise that is similar to those of full IAB members
{{IAB-EXP}}, and requires a similar time and travel commitment, for example, to
attend IAB retreats, relevant IAB workshops as well as other meetings the IAB is
participating in or organizing. Per {{IAB-EXP}}, "it is desirable for IAB members
to have technical leadership experience, operational management backgrounds,
research or academic backgrounds, implementation experience, and experience in
other bodies involved in Internet governance."

The IRTF Chair frequently provides input to "birds-of-a-feather" (BoF) sessions,
either as an ex officio IAB member (i.e., as a "BoF shepherd") or because it may
be unclear whether a proposed effort should be started as an IETF WG or an IRTF
RG.


# Security Considerations

This document raises no security considerations.


# IANA Considerations

This document has no IANA considerations.


# Acknowledgments

Robert Sparks, Brian Trammell, Stephen Farrell, Niels ten Oever, Dirk Kutscher,
Aaron Falk, Jana Iyengar and Mat Ford provided input to this document.

Lars Eggert has received funding from the European Union's Horizon 2020 research
and innovation program 2014-2018 under grant agreement No. 644866 ("SSICLOPS").
This document reflects only the authors' views and the European Commission is
not responsible for any use that may be made of the information it contains.

This document is being prepared in a [Github repository](#REPO) using Martin
Thomson's [I-D template](#ID-TEMPLATE) and Carsten Bormann's
[kramdown-rfc2629](#KRAMDOWN-RFC2629).
