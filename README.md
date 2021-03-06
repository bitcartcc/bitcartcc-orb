# BitcartCC Shared Orb

[![CircleCI Build Status](https://circleci.com/gh/bitcartcc/bitcartcc-orb.svg?style=svg)](https://circleci.com/gh/bitcartcc/bitcartcc-orb) [![CircleCI Orb Version](https://badges.circleci.com/orbs/bitcartcc/bitcartcc-shared.svg)](https://circleci.com/orbs/registry/orb/bitcartcc/bitcartcc-shared)

This orb is used across BitcartCC repositories to reduce duplication and improve maintenance

## Resources

[CircleCI Orb Registry Page](https://circleci.com/orbs/registry/orb/bitcartcc/bitcartcc-orb) - The official registry page of this orb for all versions, executors, commands, and jobs described.
[CircleCI Orb Docs](https://circleci.com/docs/2.0/orb-intro/#section=configuration) - Docs for using and creating CircleCI Orbs.

### How to Contribute

We welcome [issues](https://github.com/bitcartcc/bitcartcc-orb/issues) to and [pull requests](https://github.com/bitcartcc/bitcartcc-orb/pulls) against this repository!

### How to Publish

- Create and push a branch with your new features.
- When ready to publish a new production version, create a Pull Request from _feature branch_ to `master`.
- The title of the pull request must contain a special semver tag: `[semver:<segment>]` where `<segment>` is replaced by one of the following values.

| Increment | Description                       |
| --------- | --------------------------------- |
| major     | Issue a 1.0.0 incremented release |
| minor     | Issue a x.1.0 incremented release |
| patch     | Issue a x.x.1 incremented release |
| skip      | Do not issue a release            |

Example: `[semver:major]`

- Squash and merge. Ensure the semver tag is preserved and entered as a part of the commit message.
- On merge, after manual approval, the orb will automatically be published to the Orb Registry.

For further questions/comments about this or other orbs, visit the Orb Category of [CircleCI Discuss](https://discuss.circleci.com/c/orbs).
