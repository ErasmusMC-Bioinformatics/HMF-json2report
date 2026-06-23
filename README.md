# Changelog

## V1.1.1
- Change "UNKNOWN" values to 'N/A'

## V1.1.0
- Handle new "UNKNOWN" and null values with low tumor purity (<20%)

## V1.0.1
### Changed
- Bi-allelic inactivation message not shown for certain oncogenes

## v1.0.0
### Added
- Logic for failing WGS (JSON structure is different)
- Extra comment for tumor purity < 20%
- `somatische varianten` to `Tumor mutational load (TML)`

### Changed
- Summary now only contains 'driver: HIGH' variants
- Export name contains Sample_ID
- Textarea changed from readonly to read/write for manual edits
- Gains and Losses order -> `FULL_GAIN`, `PARTIAL_GAIN`, `FULL_LOSS`, `PARTUAL_LOSS`
- Word output font 'Times New Roman'
- Word list spacing

### Removed
- Template whitespace
