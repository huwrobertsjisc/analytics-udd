# institution
* [TENANT_ID](#tenant_id) [1] **
* [TENANT_NAME](#tenant_name) [0..1]
* [UDD_VERSION](#udd_version) [1]

\** indicates that the property is the primary key for this entity.

## Description of institution entity
An institution is the overall provider of one or more courses.  Example: University of Gloucestershire.

## TENANT_ID
### Description
This field records the unique identifier for the University College concerned - using the UK Provider Reference Number (UKRPN) which is the unique identifier allocated to institutions by the UK Register of Learning Providers (UKRLP).

### Purpose
To identify the organisation.

### Derivation
UK Register of Learning Providers (UKRLP).

### References

### Format
String (8)

### Notes
Further information (on UKPRN) available at www.ukrlp.co.uk


## TENANT_NAME
### Description
Institution's official legal name. This should match the name indicated in the UKRLP database, as used for TENANT_ID

### Purpose
To identify the organisation.

### Derivation
Institution

### References

### Format
String (255)

### Notes
Omitting this property could impair the functionality of analytics applications such as student apps or dashboards.

## UDD_VERSION
### Description
Version number of this UDD specification.

### Purpose
Enables the UDD to be self-declaring of its version.

### Derivation
UDD specification in use by the institution

### References

### Format
String (8)

### Notes
Value will be the current version number of the UDD preceded by "v".  Example: if the data uses UDD v1.3.0, value will "v1.3.0".
