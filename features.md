#Working features as on 4/5/2013

# Introduction #

List of features that are either working fully or partially.

# Performance #

For a SSD with 160MBps aggr on a NTFS volume, REDFS can do about 80 Mbps. Remember that redfs sits on another filesystem. Reads are similar. However when reading sparse files, speeds can go upto 400 Mbps.

# Details #

  * Support for clones of volumes.
  * File cloning of any file within the same volume.
  * Cloning of a file across any volume.
  * Directory cloning, both within the same volume and cross-volume.
  * Deduplication (not really optimized)
  * FAT32/NTFS drives that can be mounted as virtual drives on windows. Use redfs initiator. Something like the iSCSI initiator to mount block storage devices.
  * Correct display of all stats such as physical data usage, logical data, dedupe savings, virtual drive sizes etc.
