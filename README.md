# CBT083
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. 
Due to amazing work by Alison Zhang and Jake Choi repos are no longer deleted.

```
//***FILE 083 is the IEHMAP program (with a lot of disassembled     *   FILE 083
//*           source that was updated by Guy Albertelli of          *   FILE 083
//*           Akron, Ohio.)  This file is in IEBUPDTE SYSIN         *   FILE 083
//*           format.  This file consists of the original IEHMAP    *   FILE 083
//*           program (object) and all the published zaps, plus     *   FILE 083
//*           some unpublished zaps.  It also updates IEHMAP so     *   FILE 083
//*           that it will work on either SP, XA, or ESA.  The      *   FILE 083
//*           library contains the original IEHMAP object deck      *   FILE 083
//*           in two members, an MVS/XA CSECT that was created      *   FILE 083
//*           via the disassembler and the necessary zaps in        *   FILE 083
//*           separate members.  See the members called $DOC390     *   FILE 083
//*           and $DOC370 for additional information.  $DOC390      *   FILE 083
//*           is for MVS/ESA.                                       *   FILE 083
//*                                                                 *   FILE 083
//*           Now fixed to recognize the res pack if it has a       *   FILE 083
//*           dynamic UCB.  Also includes disassemblies of the      *   FILE 083
//*           object decks, with appropriate zap fixes already      *   FILE 083
//*           applied.  (for reference only)  (S.Golob - Sep 95)    *   FILE 083
//*                                                                 *   FILE 083
//*           New assembly JCL for High Level Assembler.            *   FILE 083
//*                                                                 *   FILE 083
//*           A load library in TSO XMIT format has been included   *   FILE 083
//*           as member $LOADLIB.  This includes load modules for   *   FILE 083
//*           IEHMAP and IEHMAPIN.                                  *   FILE 083
//*                                                                 *   FILE 083
//*           Also tested on z/OS 1.4, and works as it did on       *   FILE 083
//*           OS/390 1.3.  Known bug about reporting "invalid       *   FILE 083
//*           extent" at the end of the track map.  The extent      *   FILE 083
//*           is not really invalid.                                *   FILE 083
//*                                                                 *   FILE 083
//*           email:  sbgolob@cbttape.org                           *   FILE 083
//*                   guy_albertelli@goodyear.com                   *   FILE 083
//*                                                                 *   FILE 083
```
