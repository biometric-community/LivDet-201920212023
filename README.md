# LivDet (2019/2021/2023)

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-green?logo=creativecommons&logoColor=white)](https://creativecommons.org/licenses/by/4.0/)
[![GitHub](https://img.shields.io/badge/GitHub-biometric--community%2FLivDet--201920212023-181717?logo=github)](https://github.com/biometric-community/LivDet-201920212023)
[![Access: register](https://img.shields.io/badge/access-register-important.svg)](https://livdet.uniss.it/)

**LivDet (2019/2021/2023)** — tbiom catalog packaging for `livdet` (fingerprint-pad; access `register`). Docs/helpers only; obtain data via upstream registration.

- **Dataset repository**: https://github.com/biometric-community/LivDet-201920212023
- **Upstream source**: https://livdet.uniss.it/
- **License (helpers / docs)**: CC BY 4.0 (see [`LICENSE`](LICENSE))
- **License (data)**: upstream terms — this packaging does **not** relicense or redistribute gated data

| Field | Value |
|-------|-------|
| Catalog id (tbiom) | `livdet` |
| Category | `fingerprint-pad` |
| Access | `register` |
| Upstream homepage | https://livdet.uniss.it/ |

## TL;DR

- **Access**: **register** — obtain data from the upstream homepage / license process
- **This mirror**: documentation + download helpers only (no bulk payload in git)
- **Notes**: Liveness Detection competitions; request competition data.

## Download

### Clone this repository

```bash
git clone git@github.com:biometric-community/LivDet-201920212023.git
cd LivDet-201920212023
```

### tbiom monorepo helper

```bash
bash projects/datasets/scripts/download_livdet.sh
```

Place licensed archives under `projects/datasets/livdet/` (gitignored).

## Dataset structure

```text
LivDet-201920212023/
├── README.md
├── LICENSE
├── .gitignore
└── extracted/   # local only after you obtain upstream data
```

## License

Helpers/docs: CC BY 4.0. Dataset files: upstream license / registration agreement.

## Contact

- Upstream: https://livdet.uniss.it/
- Packaging: https://github.com/biometric-community/LivDet-201920212023/issues
