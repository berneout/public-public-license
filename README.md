***Warning! Experimental legal technology.***

## Whatsit?

A "fork" of [The MIT License], with two changes:

1. No more "attribution" requirement to provide copies of a copyright
   notice or the license itself.

2. Corporations and other kinds of legal entities, but not individuals,
   have to propose patches to add themselves to a list below the license
   terms to exercise any permission for the software.

[The MIT License]: https://spdx.org/licenses/MIT

## Whysit?

Two reasons:

1. In many kinds of development, the attribution (notice and terms)
   requirement is largely ignored. For example, few front-end
   applications preserve license header comments in the blobs of
   JavaScript sent to users' web browser or concatenate `LICENSE` files,
   `NOTICE` files, or metadata in any publicly visible place. Whether
   early or late in a project's arc, developers would rather save each
   other the attribution chore.

2. Open source projects are collaborative efforts, and developers are
   often far more concerned about getting proper credit for their
   project than for themselves individually. In addition, once a
   project reaches a critical mass, it's often difficult to contact,
   or even identify, the downstream users who could and would support
   maintainers as the burden and benefit of their ongoing work grow.

## Is it "open source"?

Good question. [I] don't think so. More concretely, [I] don't think
[The Open Source Initiative] would approve the Public Public License as
an "open source" license according to [their read of the Open Source
Definition][Annotated OSD].

[I]: https://kemitchell.com

[The Open Source Initiative]: https://opensource.org

[Annotated OSD]: https://opensource.org/osd-annotated

Consider:

> > 5\. No Discrimination Against Persons or Groups
> >
> > The license must not discriminate against any person or group of
> > persons.
>
> Rationale: In order to get the maximum benefit from the process, the
> maximum diversity of persons and groups should be equally eligible
> to contribute to open sources. Therefore we forbid any open-source
> license from locking anybody out of the process.

The Public Public License doesn't deny any particular kind of licensee
the ability to get a license. Neither does it "lock anybody out",
in the sense of preventing them from making changes. But it does
discriminate between individuals or "natural persons", on the one
hand, and legally recognized groups of individuals, like corporations,
coops, partnerships, &c. Only the latter have to identify themselves to
exercise the permission given by the license.

> > 6\. No Discrimination Against Fields of Endeavor
> >
> > The license must not restrict anyone from making use of the program
> > in a specific field of endeavor. For example, it may not restrict
> > the program from being used in a business, or from being used for
> > genetic research.
>
> Rationale: The major intention of this clause is to prohibit license
> traps that prevent open source from being used commercially. We want
> commercial users to join our community, not feel excluded from it.

The Public Public License discriminates in a minor way among legal forms
of licensees. It's probably safe to assume, at least in the United
States, that being organized into some kind of legal entity is highly
correlated with business or commercial purpose. But The Public Public
License's self-identification requirement was written to apply equally
to tax-exempt or "not-for-profit" entities, or even government entities.
Conversely, an individual needn't self-identify, even if their use of
the software is entirely profit-seeking.

> > 7\. Distribution of License The rights attached to the program must
> > apply to all to whom the program is redistributed without the need
> > for execution of an additional license by those parties.
>
> Rationale: This clause is intended to forbid closing up software by
> indirect means such as requiring a non-disclosure agreement.

To be honest, [I] never really understood this critrerion.

The Public Public License does impose an additional step on some
licensees, but that step does not give licensors any kind of veto or
stalling power on anyone's rights. The self-identification requirement
was written to be fully satisfied by merely proposing a change to the
list of licensees. As soon as the proposal is made, whether maintainers
ever adopt it or not, the condition is satisfied.

As an escape hatch, the self-identification requirement applies only
when it when someone "reasonably skilled in software development" can
"readily ascertain\[\]" how to propose for free on the 'Net. If the
project is orphaned, the self-identification requirement drops out.

> > 10\. License Must Be Technology-Neutral
> >
> > No provision of the license may be predicated on any individual
> > technology or style of interface.
>
> Rationale: This provision is aimed specifically at licenses which
> require an explicit gesture of assent in order to establish a contract
> between licensor and licensee. Provisions mandating so-called
> "click-wrap" may conflict with important methods of software
> distribution such as FTP download, CD-ROM anthologies, and web
> mirroring; such provisions may also hinder code re-use. Conformant
> licenses must allow for the possibility that (a) redistribution of the
> software will take place over non-Web channels that do not support
> click-wrapping of the download, and that (b) the covered code (or
> re-used portions of covered code) may run in a non-GUI environment
> that cannot support popup dialogues.

Read as broadly as possible, the attribution requirements of all the
most common open source licenses violate this criterion. At the other
extreme, the OSD's comments focus very specifically on click-wrap, a
classic problem dealing with when contracts are formed, rather than
satisfying conditions of a license.

[I] don't represent the OSI in any way, but it's my general "feeling"
that the "spirit" of this criterion is really about friction. If
you have to do anything with open source software above and beyond
determining that:

1. it's licensed on open source terms
2. those giving the license have the right to do so

then it doesn't "feel" like "open source".
