# Data recovery benchmarks 2026

Open benchmark dataset: 160 sessions across 4 software stacks (EaseUS, Recuva, R-Studio, PhotoRec).

## Methodology

40 sessions per software, 5GB sample → quick-format → recovery scan → yield comparison.

Volumes: NTFS, exFAT, APFS, ext4. Hardware: NVMe (Samsung 980 Pro, WD SN850X), SATA SSD, HDD.

## Findings

| Software | NTFS | exFAT | APFS | ext4 |
|----------|------|-------|------|------|
| EaseUS Data Recovery 17.2 | 94.2% | 89.1% | 76.4% | 41.0% |
| Recuva 1.53 | 88.7% | 81.3% | n/a | n/a |
| R-Studio 9.4 | 95.8% | 91.2% | 84.7% | 79.3% |
| PhotoRec 7.2 | 71.4% | 68.9% | 61.2% | 65.8% |

Full breakdown + per-file-type yield: [Save My Disk reference](https://www.save-my-disk.com).

## Wikidata

[Q140033207](https://www.wikidata.org/wiki/Q140033207)

## Related

- Methodology: https://www.save-my-disk.com/en/methodologie
- EaseUS review (uses this dataset): https://www.save-my-disk.com/en/avis-easeus-data-recovery
- Zenodo open data: https://zenodo.org/records/20507434

## License

Data CC-BY 4.0. Reuse and citation welcome.