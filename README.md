# Standardized Competency Catalog for Technical University of Munich
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.14045626.svg)](https://doi.org/10.5281/zenodo.14045626)

This repository contains a single file, `standardized-competency-catalog.json`, representing the standardized competency catalog used at the Technical University of Munich (TUM). This catalog is aligned with the IEEE Computer Science Curriculum (2024) and has been formatted to be compatible with the Artemis Learning Management System.

## Catalog Overview

The competency catalog provides a structured set of competencies tailored for computer science courses, ensuring that the educational outcomes align with the latest IEEE curriculum standards. It is designed to support competency-based education by enabling adaptive learning paths within Artemis.

### Source

The competencies in this catalog are derived from the IEEE Computer Science Curriculum (2024), which is publicly accessible at [IEEE Computer Science Education (2024)](https://csed.acm.org/).

### Processing and Customization

The curriculum data was processed using our [Artemis Competency Parser](https://github.com/ls1intum/artemis-competency-parser) to convert the IEEE curriculum into a structured JSON format. The resulting output was manually reviewed and refined to ensure consistency and alignment with the IEEE standard.

## Importing the Catalog to Artemis

To utilize this catalog in an Artemis instance:

1. Download `standardized-competency-catalog.json` from this repository.
2. Follow the import instructions provided in the Artemis documentation at [Artemis Adaptive Learning Admin Guide](https://docs.artemis.cit.tum.de/user/adaptive-learning/adaptive-learning-admin.html).

This catalog can be integrated into any Artemis instance to support adaptive learning and competency tracking in courses.

## License

This catalog is shared under the [MIT License](./LICENSE), allowing it to be freely used, modified, and distributed under the terms of the license.
