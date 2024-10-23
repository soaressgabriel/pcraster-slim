> [!CAUTION]
> This repository is not affiliated with the official PCRaster project. **For official downloads, documentation, and support, please visit the original repository at [https://github.com/pcraster/pcraster.git](https://github.com/pcraster/pcraster.git)**.

# PCRaster-Slim

This repository aims to provide a workflow to compile the [PCRaster](https://github.com/pcraster/pcraster.git) library using a slim base image [`python:3.11-slim`](https://hub.docker.com/layers/library/python/3.11-slim/images/sha256-1591aa8c01b5b37ab31dbe5662c5bdcf40c2f1bce4ef1c1fd24802dae3d01052?context=explore) based on Debian 12. This allows for a lighter and more efficient compilation, facilitating the integration of PCRaster in minimalist environments that restrict the use of conda.

## Purpose

- Provide an automated workflow using GitHub Actions to compile specific versions of PCRaster;
- Ensure compatibility with Debian 12 (bookworm) by using the [`python:3.11-slim`](https://hub.docker.com/layers/library/python/3.11-slim/images/sha256-1591aa8c01b5b37ab31dbe5662c5bdcf40c2f1bce4ef1c1fd24802dae3d01052?context=explore) base image.

## Credits

All credit for the development of PCRaster goes to the maintainers of the original repository:

- **PCRaster Repository:** [https://github.com/pcraster/pcraster.git](https://github.com/pcraster/pcraster.git)

We thank the developers of PCRaster for making this software available to the community.

> [!IMPORTANT]  
> **We strongly recommend that you use the official releases available in the original PCRaster repository.**
>
> This repository is provided for demonstration purposes only. The builds generated here do not replace the official versions and may not have undergone all the tests and validations of the original maintainers.

## License

This project is licensed under the terms of the [MIT License](LICENSE).
