1.9.0
=====

We're happy to announce the release of numpydoc 1.9.0!

Enhancements
------------

- ignore some errors at module level (`#593 <https://github.com/numpy/numpydoc/pull/593>`_).
- Rework hook output to remove the table (`#611 <https://github.com/numpy/numpydoc/pull/611>`_).
- Switch to storing AST nodes on the stack for more accurate method signature check and easy access to parent nodes (`#623 <https://github.com/numpy/numpydoc/pull/623>`_).

Bug Fixes
---------

- MAINT: Changed class constructor __init__ GL08 reporting (`#592 <https://github.com/numpy/numpydoc/pull/592>`_).
- BUG: Correct functionality of numpydoc SS05 (`#613 <https://github.com/numpy/numpydoc/pull/613>`_).
- Specity the types of ``numpydoc_xref_ignore`` option (`#631 <https://github.com/numpy/numpydoc/pull/631>`_).

Documentation
-------------

- DOC: Do not use types for ``*args``, ``**kwargs`` (`#585 <https://github.com/numpy/numpydoc/pull/585>`_).
- mention conda-forge in installation docs (`#595 <https://github.com/numpy/numpydoc/pull/595>`_).
- Fix typo in validation.rst (`#605 <https://github.com/numpy/numpydoc/pull/605>`_).
- Fix broken link in ``format.rst`` (`#628 <https://github.com/numpy/numpydoc/pull/628>`_).

Maintenance
-----------

- CI: use hashes for actions' versions in publishing job (`#579 <https://github.com/numpy/numpydoc/pull/579>`_).
- Bump the actions group with 2 updates (`#581 <https://github.com/numpy/numpydoc/pull/581>`_).
- Bump pypa/gh-action-pypi-publish from 1.10.0 to 1.10.2 in the actions group (`#582 <https://github.com/numpy/numpydoc/pull/582>`_).
- [pre-commit.ci] pre-commit autoupdate (`#583 <https://github.com/numpy/numpydoc/pull/583>`_).
- MAINT: Add _exception_on_warning to MockApp (`#586 <https://github.com/numpy/numpydoc/pull/586>`_).
- Bump the actions group across 1 directory with 2 updates (`#590 <https://github.com/numpy/numpydoc/pull/590>`_).
- don't pass maxsplit as positional arg (`#596 <https://github.com/numpy/numpydoc/pull/596>`_).
- [pre-commit.ci] pre-commit autoupdate (`#598 <https://github.com/numpy/numpydoc/pull/598>`_).
- Add Python 3.13 support (`#599 <https://github.com/numpy/numpydoc/pull/599>`_).
- Update readthedocs config (`#600 <https://github.com/numpy/numpydoc/pull/600>`_).
- Bump the actions group with 2 updates (`#603 <https://github.com/numpy/numpydoc/pull/603>`_).
- Bump the actions group with 3 updates (`#609 <https://github.com/numpy/numpydoc/pull/609>`_).
- [pre-commit.ci] pre-commit autoupdate (`#614 <https://github.com/numpy/numpydoc/pull/614>`_).
- Bump actions/download-artifact from 4.2.1 to 4.3.0 in the actions group (`#620 <https://github.com/numpy/numpydoc/pull/620>`_).
- Bump scientific-python/circleci-artifacts-redirector-action from 1.0.0 to 1.1.0 in the actions group (`#627 <https://github.com/numpy/numpydoc/pull/627>`_).
- Switch to dependency groups (`#626 <https://github.com/numpy/numpydoc/pull/626>`_).
- Fix pip setup command in github workflow (`#629 <https://github.com/numpy/numpydoc/pull/629>`_).

Contributors
------------

13 authors added to this release (alphabetically):

- Brigitta Sipőcz (`@bsipocz <https://github.com/bsipocz>`_)
- Daniel McCloy (`@drammock <https://github.com/drammock>`_)
- Eric Larson (`@larsoner <https://github.com/larsoner>`_)
- Gilles Peiffer (`@Peiffap <https://github.com/Peiffap>`_)
- Jarrod Millman (`@jarrodmillman <https://github.com/jarrodmillman>`_)
- Lucas Colley (`@lucascolley <https://github.com/lucascolley>`_)
- Matt Gebert (`@mattgebert <https://github.com/mattgebert>`_)
- Maxine Hartnett (`@maxinelasp <https://github.com/maxinelasp>`_)
- Ross Barnowski (`@rossbar <https://github.com/rossbar>`_)
- Stefan van der Walt (`@stefanv <https://github.com/stefanv>`_)
- Stefanie Molin (`@stefmolin <https://github.com/stefmolin>`_)
- Tim Hoffmann (`@timhoffm <https://github.com/timhoffm>`_)
- Yuki Kobayashi (`@koyuki7w <https://github.com/koyuki7w>`_)

7 reviewers added to this release (alphabetically):

- Charles Harris (`@charris <https://github.com/charris>`_)
- Eric Larson (`@larsoner <https://github.com/larsoner>`_)
- Jarrod Millman (`@jarrodmillman <https://github.com/jarrodmillman>`_)
- Lucas Colley (`@lucascolley <https://github.com/lucascolley>`_)
- Matt Gebert (`@mattgebert <https://github.com/mattgebert>`_)
- Ross Barnowski (`@rossbar <https://github.com/rossbar>`_)
- Stefan van der Walt (`@stefanv <https://github.com/stefanv>`_)

_These lists are automatically generated, and may not be complete or may contain duplicates._

1.8.0
=====

We're happy to announce the release of numpydoc 1.8.0!

Enhancements
------------

- Unify CLIs (`#537 <https://github.com/numpy/numpydoc/pull/537>`_).
- Move "Attributes" and "Methods" below "Parameters" (`#571 <https://github.com/numpy/numpydoc/pull/571>`_).

Bug Fixes
---------

- FIX: coroutines can have a return statement (`#542 <https://github.com/numpy/numpydoc/pull/542>`_).
- Unwrap decorated objects for YD01 validation check (`#541 <https://github.com/numpy/numpydoc/pull/541>`_).
- Fix bug with validation encoding (`#550 <https://github.com/numpy/numpydoc/pull/550>`_).

Documentation
-------------

- Classify development status as Production/Stable (`#548 <https://github.com/numpy/numpydoc/pull/548>`_).
- Add note about TOML regex; fix typo (`#552 <https://github.com/numpy/numpydoc/pull/552>`_).
- DOC: Clarify recommendations regarding use of backticks (`#525 <https://github.com/numpy/numpydoc/pull/525>`_).

Maintenance
-----------

- Fix typo in label-check.yml (`#538 <https://github.com/numpy/numpydoc/pull/538>`_).
- [pre-commit.ci] pre-commit autoupdate (`#539 <https://github.com/numpy/numpydoc/pull/539>`_).
- DEV: Rm xfails from pytest summary (`#540 <https://github.com/numpy/numpydoc/pull/540>`_).
- Drop Python 3.8 support (`#545 <https://github.com/numpy/numpydoc/pull/545>`_).
- Clean up old sphinx cruft (`#549 <https://github.com/numpy/numpydoc/pull/549>`_).
- Test on sphinx 7.3 (`#547 <https://github.com/numpy/numpydoc/pull/547>`_).
- Require GHA update grouping (`#553 <https://github.com/numpy/numpydoc/pull/553>`_).
- Update pre-commit config (`#554 <https://github.com/numpy/numpydoc/pull/554>`_).
- Use ruff for linting and formatting (`#555 <https://github.com/numpy/numpydoc/pull/555>`_).
- Use intersphinx registry to avoid out of date links (`#563 <https://github.com/numpy/numpydoc/pull/563>`_).
- Do not rely on requirements.txt in ci, use .[test,doc] (`#566 <https://github.com/numpy/numpydoc/pull/566>`_).
- CI: update action that got moved org (`#567 <https://github.com/numpy/numpydoc/pull/567>`_).
- Fix navbar for documentation pages (`#569 <https://github.com/numpy/numpydoc/pull/569>`_).
- [pre-commit.ci] pre-commit autoupdate (`#570 <https://github.com/numpy/numpydoc/pull/570>`_).
- docscrape: fixes from SciPy (`#576 <https://github.com/numpy/numpydoc/pull/576>`_).
- MAINT: Remove scale to work around PyPI bug (`#578 <https://github.com/numpy/numpydoc/pull/578>`_).

Contributors
------------

10 authors added to this release (alphabetically):

- Brigitta Sipőcz (`@bsipocz <https://github.com/bsipocz>`_)
- Eric Larson (`@larsoner <https://github.com/larsoner>`_)
- Jarrod Millman (`@jarrodmillman <https://github.com/jarrodmillman>`_)
- Lucas Colley (`@lucascolley <https://github.com/lucascolley>`_)
- M Bussonnier (`@Carreau <https://github.com/Carreau>`_)
- Matt Haberland (`@mdhaber <https://github.com/mdhaber>`_)
- Melissa Weber Mendonça (`@melissawm <https://github.com/melissawm>`_)
- Ross Barnowski (`@rossbar <https://github.com/rossbar>`_)
- Stefanie Molin (`@stefmolin <https://github.com/stefmolin>`_)
- Thomas A Caswell (`@tacaswell <https://github.com/tacaswell>`_)

7 reviewers added to this release (alphabetically):

- Eric Larson (`@larsoner <https://github.com/larsoner>`_)
- Jarrod Millman (`@jarrodmillman <https://github.com/jarrodmillman>`_)
- M Bussonnier (`@Carreau <https://github.com/Carreau>`_)
- Matt Haberland (`@mdhaber <https://github.com/mdhaber>`_)
- Ross Barnowski (`@rossbar <https://github.com/rossbar>`_)
- Stefan van der Walt (`@stefanv <https://github.com/stefanv>`_)
- Stefanie Molin (`@stefmolin <https://github.com/stefmolin>`_)

_These lists are automatically generated, and may not be complete or may contain duplicates._

1.7.0
=====

We're happy to announce the release of numpydoc 1.7.0!

Enhancements
------------

- PERF: wrap inspect.getsourcelines with cache (`#532 <https://github.com/numpy/numpydoc/pull/532>`_).

Bug Fixes
---------

- during tokenize, use UTF8 encoding on all platforms (`#510 <https://github.com/numpy/numpydoc/pull/510>`_).
- fix 'Alias for field number X' problem with NamedTuples (`#527 <https://github.com/numpy/numpydoc/pull/527>`_).

Documentation
-------------

- DOC: Fix typos found by codespell (`#514 <https://github.com/numpy/numpydoc/pull/514>`_).
- DOC: Update link to mailing list (`#518 <https://github.com/numpy/numpydoc/pull/518>`_).
- Add Python 3.12 to classifiers (`#529 <https://github.com/numpy/numpydoc/pull/529>`_).
- Update release process (`#534 <https://github.com/numpy/numpydoc/pull/534>`_).
- Update release process (`#535 <https://github.com/numpy/numpydoc/pull/535>`_).

Maintenance
-----------

- [pre-commit.ci] pre-commit autoupdate (`#508 <https://github.com/numpy/numpydoc/pull/508>`_).
- [pre-commit.ci] pre-commit autoupdate (`#513 <https://github.com/numpy/numpydoc/pull/513>`_).
- MAINT: apply refurb suggestion (`#515 <https://github.com/numpy/numpydoc/pull/515>`_).
- [pre-commit.ci] pre-commit autoupdate (`#516 <https://github.com/numpy/numpydoc/pull/516>`_).
- Bump actions/setup-python from 4 to 5 (`#520 <https://github.com/numpy/numpydoc/pull/520>`_).
- [pre-commit.ci] pre-commit autoupdate (`#521 <https://github.com/numpy/numpydoc/pull/521>`_).
- Filter ``DeprecationWarning`` in failing test for python 3.12 (`#523 <https://github.com/numpy/numpydoc/pull/523>`_).
- MAINT: Replace NameConstant with Constant (`#524 <https://github.com/numpy/numpydoc/pull/524>`_).
- [pre-commit.ci] pre-commit autoupdate (`#526 <https://github.com/numpy/numpydoc/pull/526>`_).
- Update precommit repos (`#531 <https://github.com/numpy/numpydoc/pull/531>`_).
- Require sphinx 6 (`#530 <https://github.com/numpy/numpydoc/pull/530>`_).
- Use trusted publisher (`#533 <https://github.com/numpy/numpydoc/pull/533>`_).

Contributors
------------

8 authors added to this release (alphabetically):

- Chiara Marmo (`@cmarmo <https://github.com/cmarmo>`_)
- Daniel McCloy (`@drammock <https://github.com/drammock>`_)
- Dimitri Papadopoulos Orfanos (`@DimitriPapadopoulos <https://github.com/DimitriPapadopoulos>`_)
- Eric Larson (`@larsoner <https://github.com/larsoner>`_)
- Jarrod Millman (`@jarrodmillman <https://github.com/jarrodmillman>`_)
- Niko Föhr (`@fohrloop <https://github.com/fohrloop>`_)
- Philipp Hoffmann (`@dontgoto <https://github.com/dontgoto>`_)
- Ross Barnowski (`@rossbar <https://github.com/rossbar>`_)

9 reviewers added to this release (alphabetically):

- Antoine Pitrou (`@pitrou <https://github.com/pitrou>`_)
- Charles Harris (`@charris <https://github.com/charris>`_)
- Daniel McCloy (`@drammock <https://github.com/drammock>`_)
- Eric Larson (`@larsoner <https://github.com/larsoner>`_)
- GitHub Web Flow (`@web-flow <https://github.com/web-flow>`_)
- Jarrod Millman (`@jarrodmillman <https://github.com/jarrodmillman>`_)
- Niko Föhr (`@fohrloop <https://github.com/fohrloop>`_)
- Ross Barnowski (`@rossbar <https://github.com/rossbar>`_)
- Stefan van der Walt (`@stefanv <https://github.com/stefanv>`_)

_These lists are automatically generated, and may not be complete or may contain duplicates._
