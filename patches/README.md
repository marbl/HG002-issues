# Patch directory

## Introduction
VCF files in these directories ("to_be_applied" and "already_applied") contain
changes to be applied to the assembly for the purposes of correcting errors.

*All VCF file names should explicitly contain the version of the assembly they are meant to correct.*

Once patches have been applied, they should be moved to the "already_applied" 
directory so we can keep a record of the changes that were incorporated in
each new released version.
