# photoassistant

This is a playground. 

The goal is to simplify the process of sorting and culling of photos.
It shouldn't break lightroom catalogues.

## Scope
### Sorting
1. Create folders for years, months, days
2. Rename photos to the format "YYYYMMDD-hhmmss" based on the capture datetime.
3. Move photos to the correct folder.

### Culling
1. Find duplicate photos and keep only one of them.
2. Find similar photos and mark the best one.
3. Tag all photos with people.

## Status
### Implemented
- Create directories for YYYY, MM, DD (but so far always 31 days)
- test if creation of folders work and teardown

### Next
- create directories for each real calendar day
- test the function itself

