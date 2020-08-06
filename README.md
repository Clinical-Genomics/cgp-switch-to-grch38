# cgp-switch-to-grch38

## Project summary
| | |
|-|-|
| **Goal** | [Use Grch38 for bioinformatic workflows and tools](https://github.com/Clinical-Genomics/Goals/issues/67) |
| **Priority** | 1 or 2 |
| **Estimated duration** | 6 months |
| **Team Members** | HS, AJ, MM, PG, CH, HFA, VW |
| **Coordinator** | HS |
| **External Members** | DN, JE |

## Project description

Bioinformatic tools and workflows currently use grch37 as the default genome reference build and we should now use the updated and improved genome build grch38 instead.
All Clinical Genomics applications and databases handling bioinformatic workflows with a human reference need to be able to handle the new grch38 build and some databases need to be repopulated and/or migrated using data based on grch38. References used in the bioinformatic workflows need to be updated and the workflows re-validated.

### Aim(s)

The bioinformatic workflows and applications use grch38 as default in production

### Description

The grch38 genome build was released several years ago and it is business critical that Clinical Genomics analyses and applications used the most recent genome build. Many new tools only support grch38 and many new annotations and references are only available for grch38. The analysis will benefit from more complete and updated transcripts and improved alignment. Our customers request this and are dependent on us successfully doing this in the near future.
Bioinformatic tools and workflows currently use grch37 as the default genome reference build and we should now use the updated and improved genome build grch38 instead.
All Clinical Genomics applications and databases handling bioinformatic workflows with a human reference need to be able to handle the new grch38 build and some databases need to be repopulated and/or migrated using data based on grch38. References used in the bioinformatic workflows need to be updated and the workflows re-validated.

### Resources required

Teams: Bioinfo, IT, produktion bioinfo

### Milestones

1. Validate MIP rare disease workflow using new grch38 genome build
1. Validate Balsamic workflow using new grch38 genome build
1. Verify that Scout can handle MIP and Balsamic grch38 data
1. Devise a plan to migrate and/or repopulate Scout with new analysis data and current meta-data
1. Devise a plan to repopulate loqusDb with new MIP grch38 data
1. Update transcript db in Chanjo and verify that the application works with grch38 data
1. Devise a plan to migrate and/or repopulate MutAcc with causatives from grch38 coordinates
1. Verify that our Beacon handles grch38 datasets 
