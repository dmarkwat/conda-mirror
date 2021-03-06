# Change Log

## [Unreleased](https://github.com/maxpoint/conda-mirror/tree/HEAD)

[Full Changelog](https://github.com/maxpoint/conda-mirror/compare/0.6.0...HEAD)

**Closed issues:**

- Validate that there is enough space to actually perform the mirror [\#19](https://github.com/maxpoint/conda-mirror/issues/19)

## [0.6.0](https://github.com/maxpoint/conda-mirror/tree/0.6.0) (2017-01-10)
[Full Changelog](https://github.com/maxpoint/conda-mirror/compare/0.5.1...0.6.0)

**Merged pull requests:**

- Implement optional cli flag for temp download directory [\#21](https://github.com/maxpoint/conda-mirror/pull/21) ([jneines](https://github.com/jneines))

## [0.5.1](https://github.com/maxpoint/conda-mirror/tree/0.5.1) (2017-01-03)
[Full Changelog](https://github.com/maxpoint/conda-mirror/compare/0.5.0...0.5.1)

**Merged pull requests:**

- Download repodata to temp dir first, then move it [\#20](https://github.com/maxpoint/conda-mirror/pull/20) ([ericdill](https://github.com/ericdill))

## [0.5.0](https://github.com/maxpoint/conda-mirror/tree/0.5.0) (2016-12-19)
[Full Changelog](https://github.com/maxpoint/conda-mirror/compare/0.4.6...0.5.0)

**Closed issues:**

- Remove conda\_build as a dependency [\#13](https://github.com/maxpoint/conda-mirror/issues/13)

**Merged pull requests:**

- Write repodata.json.bz2. libconda needs it. [\#18](https://github.com/maxpoint/conda-mirror/pull/18) ([ericdill](https://github.com/ericdill))
- Updated badges to point to new org. [\#17](https://github.com/maxpoint/conda-mirror/pull/17) ([mariusvniekerk](https://github.com/mariusvniekerk))

## [0.4.6](https://github.com/maxpoint/conda-mirror/tree/0.4.6) (2016-12-15)
[Full Changelog](https://github.com/maxpoint/conda-mirror/compare/0.4.5...0.4.6)

- Prune repodata.json of packages we do not have locally [957f662](https://github.com/maxpoint/conda-mirror/commit/957f66260a8e91c7217656ab721db52b9bc27aa1)

## [0.4.5](https://github.com/maxpoint/conda-mirror/tree/0.4.5) (2016-12-15)
[Full Changelog](https://github.com/maxpoint/conda-mirror/compare/0.4.4...0.4.5)

- (Performance) Short-circuit the validation if one of the checks fail [68ebd00](https://github.com/maxpoint/conda-mirror/commit/68ebd00e8747a504d00bfd4304e480afcbf7b24b)

## [0.4.4](https://github.com/maxpoint/conda-mirror/tree/0.4.4) (2016-12-15)
[Full Changelog](https://github.com/maxpoint/conda-mirror/compare/0.4.3...0.4.4)

- (Performance) Don't validate the entire repo every time (c811397)[https://github.com/maxpoint/conda-mirror/commit/c8113976b80af7e789814d8b9095ece8e5481879]

## [0.4.3](https://github.com/maxpoint/conda-mirror/tree/0.4.3) (2016-12-15)
[Full Changelog](https://github.com/maxpoint/conda-mirror/compare/0.4.2...0.4.3)

- Show output of subprocess calls on failure [e8ba6d4](https://github.com/maxpoint/conda-mirror/commit/e8ba6d4e01febaae5b08127ef71d36a3533b368b)

## [0.4.2](https://github.com/maxpoint/conda-mirror/tree/0.4.2) (2016-12-13)
[Full Changelog](https://github.com/maxpoint/conda-mirror/compare/0.4.1...0.4.2)

**Merged pull requests:**

- Remove packages that fail their assertion [\#16](https://github.com/maxpoint/conda-mirror/pull/16) ([ericdill](https://github.com/ericdill))

## [0.4.1](https://github.com/maxpoint/conda-mirror/tree/0.4.1) (2016-12-13)
[Full Changelog](https://github.com/maxpoint/conda-mirror/compare/0.4.0...0.4.1)

## [0.4.0](https://github.com/maxpoint/conda-mirror/tree/0.4.0) (2016-12-12)
[Full Changelog](https://github.com/maxpoint/conda-mirror/compare/0.3.0...0.4.0)

**Merged pull requests:**

- ENH: Rework conda mirror to not use conda-index [\#14](https://github.com/maxpoint/conda-mirror/pull/14) ([ericdill](https://github.com/ericdill))

## [0.3.0](https://github.com/maxpoint/conda-mirror/tree/0.3.0) (2016-12-07)
[Full Changelog](https://github.com/maxpoint/conda-mirror/compare/0.2.3...0.3.0)

**Merged pull requests:**

- ENH: Copy index from anaconda [\#12](https://github.com/maxpoint/conda-mirror/pull/12) ([ericdill](https://github.com/ericdill))

## [0.2.3](https://github.com/maxpoint/conda-mirror/tree/0.2.3) (2016-11-09)
[Full Changelog](https://github.com/maxpoint/conda-mirror/compare/0.2.2...0.2.3)

**Merged pull requests:**

- Disable tqdm by default [\#11](https://github.com/maxpoint/conda-mirror/pull/11) ([ericdill](https://github.com/ericdill))

## [0.2.2](https://github.com/maxpoint/conda-mirror/tree/0.2.2) (2016-11-09)
[Full Changelog](https://github.com/maxpoint/conda-mirror/compare/0.2.1...0.2.2)

**Merged pull requests:**

- Handle when the license is a literal value of None [\#10](https://github.com/maxpoint/conda-mirror/pull/10) ([ericdill](https://github.com/ericdill))

## [0.2.1](https://github.com/maxpoint/conda-mirror/tree/0.2.1) (2016-11-08)
[Full Changelog](https://github.com/maxpoint/conda-mirror/compare/0.2.0...0.2.1)

**Merged pull requests:**

- Remove bad packages instead of failing [\#9](https://github.com/maxpoint/conda-mirror/pull/9) ([ericdill](https://github.com/ericdill))

## [0.2.0](https://github.com/maxpoint/conda-mirror/tree/0.2.0) (2016-11-04)
[Full Changelog](https://github.com/maxpoint/conda-mirror/compare/0.1.0...0.2.0)

**Merged pull requests:**

- Call conda mirror directly [\#8](https://github.com/maxpoint/conda-mirror/pull/8) ([ericdill](https://github.com/ericdill))

## [0.1.0](https://github.com/maxpoint/conda-mirror/tree/0.1.0) (2016-11-02)
[Full Changelog](https://github.com/maxpoint/conda-mirror/compare/0.0.8...0.1.0)

**Merged pull requests:**

- ENH: Add license checks [\#7](https://github.com/maxpoint/conda-mirror/pull/7) ([ericdill](https://github.com/ericdill))

## [0.0.8](https://github.com/maxpoint/conda-mirror/tree/0.0.8) (2016-10-24)
[Full Changelog](https://github.com/maxpoint/conda-mirror/compare/0.0.7...0.0.8)

**Merged pull requests:**

- WIP: Intermittently run conda index when mirroring lots of packages [\#6](https://github.com/maxpoint/conda-mirror/pull/6) ([ericdill](https://github.com/ericdill))

## [0.0.7](https://github.com/maxpoint/conda-mirror/tree/0.0.7) (2016-10-24)
[Full Changelog](https://github.com/maxpoint/conda-mirror/compare/0.0.6...0.0.7)

**Merged pull requests:**

- WIP: entry\_points... [\#5](https://github.com/maxpoint/conda-mirror/pull/5) ([ericdill](https://github.com/ericdill))

## [0.0.6](https://github.com/maxpoint/conda-mirror/tree/0.0.6) (2016-10-24)
[Full Changelog](https://github.com/maxpoint/conda-mirror/compare/0.0.4...0.0.6)

**Merged pull requests:**

- WIP: add setup.py directive to make conda\_mirror.py a script [\#4](https://github.com/maxpoint/conda-mirror/pull/4) ([ericdill](https://github.com/ericdill))

## [0.0.4](https://github.com/maxpoint/conda-mirror/tree/0.0.4) (2016-10-24)
[Full Changelog](https://github.com/maxpoint/conda-mirror/compare/0.0.3...0.0.4)

**Merged pull requests:**

- WIP: Update travis yaml [\#3](https://github.com/maxpoint/conda-mirror/pull/3) ([ericdill](https://github.com/ericdill))

## [0.0.3](https://github.com/maxpoint/conda-mirror/tree/0.0.3) (2016-10-24)
[Full Changelog](https://github.com/maxpoint/conda-mirror/compare/0.0.2...0.0.3)

## [0.0.2](https://github.com/maxpoint/conda-mirror/tree/0.0.2) (2016-10-24)
[Full Changelog](https://github.com/maxpoint/conda-mirror/compare/0.0.1...0.0.2)

## [0.0.1](https://github.com/maxpoint/conda-mirror/tree/0.0.1) (2016-10-20)
**Merged pull requests:**

- test the cli too [\#2](https://github.com/maxpoint/conda-mirror/pull/2) ([ericdill](https://github.com/ericdill))
- Remove unused validator [\#1](https://github.com/maxpoint/conda-mirror/pull/1) ([ericdill](https://github.com/ericdill))



\* *This Change Log was automatically generated by [github_changelog_generator](https://github.com/skywinder/Github-Changelog-Generator)*
