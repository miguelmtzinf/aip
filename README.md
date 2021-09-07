---
👋 Hey there! You're currently viewing this on Github, which isn't the intended experience.
For the full Aave AIP experience, go to the [AIPs website](https://aave.github.io/aip/)
---

## Contributing

1. Fork [this repository](https://github.com/aave/aip) by clicking 'Fork' in the top right.
2. Add your AIP to your fork of the repository in the `content/aips/` directory. Use the [AIP template](https://github.com/aave/aip/blob/master/aip-X.md).
3. Generate the AIP identifier using the following command: `npm run generate-filename '[title]' '[date]'`. Replace the `title` and `date` placeholders with the `title` and `created` tags of the AIP md file.
4. Use the generated identifier for the AIP filename. The final name of the AIP file should be: `AIP-[generated_identifier]-[title_abbrev].md`.
4. Submit a [Pull Request (PR)](https://github.com/aave/aip/pulls) to the [Pending AIPs branch](https://github.com/aave/aip/tree/Pending-AIPs).

Your first PR should be a draft of the final AIP. It must follow the formatting criteria enforced by the build, as detailed in the AIP template. Make sure you include a `discussions-to` header with the URL to a discussion forum or open GitHub issue where people can discuss the AIP as a whole.

If your AIP requires images, the image files should be included in a subdirectory of the `assets` folder for that AIP as follow: `assets/AIP-[generated_identifier]-[title_abbrev]` (for AIP **AIP-[generated_identifier]-[title_abbrev]**). When linking to an image in the AIP, use relative links such as `../assets/AIP-[generated_identifier]-[title_abbrev]/image.png`.

When you believe your AIP is mature and ready to progress past the WIP phase, you should ask to have your issue added to the governance discord where it can be discussed for inclusion in a future platform upgrade. If the community agrees to include it, the AIP editors will update the state of your AIP to 'Approved'.

## AIP Statuses

- **WIP** - an AIP that is still being developed.
- **Proposed** - an AIP that is ready to be proposed on-chain.
- **Approved** - an AIP that has been accepted for implementation by the Aave community.
- **Implemented** - an AIP that has been released to mainnet.
- **Rejected** - an AIP that has been rejected.
