# MiSeq Wet Lab SOP


|-------:|:--------|
**Detailed Title:** | 16S rRNA Sequencing with the Illumina MiSeq: Library Generation, QC, & Sequencing |
**Authors:**        | James Kozich, Patrick Schloss, Niel Baxter, & Matt Jenior |
**Original Date:**  | 25-March-2013 |
**Version:**        | 4.0 |
**Last Updated:**   | 9-March-2015 |
**Updated By:**     |  Niel Baxter |


  ------------------------------------
  **1.0) Introduction and Workflow**
  ------------------------------------

***1.1) Introduction***

-   The Illumina MiSeq Personal Sequencer can produce 2 x 250 paired-end
    reads and up to 8.5 Gb of data in a single run. Dual indexing of
    library samples allows up to 384 samples to be run simultaneously.
    The instrument is capable of producing in excess of 24 million
    reads, however, for low diversity runs about 12 million reads can be
    expected. A wide range of applications is possible including 16S
    analysis, metagenomics, genome sequencing, transcriptomics, and RNA
    sequencing.

-   There are several steps in preparing samples for sequencing on the
    MiSeq. Broadly, these include library generation and indexing,
    quality control, normalization and pooling, quantification,
    sequencing, run quality assessment, and data export.

***1.2) 16S Prep Workflow***

1.  Samples must be arrayed in 96 well plate format. If possible, leave
    two wells on each plate open for controls. Plate used should be
    compatible with Eppendorf epMotion 5075.

2.  The investigator will provide the technician with the names of the
    project, experiment, a one-sentence description of the experiment, a
    name for each plate submitted (up to 4 96 well plates per run), the
    names and groupings of each sample.

3.  A Sample Plate will then be created for each plate using Illumina
    Experiment Manager. Sample Plates will then be used to create a
    Sample Sheet. This sheet serves as the set of run parameters and
    indexing scheme used by the MiSeq for the run.

4.  PCR of 16S samples with Schloss lab indices (up to 94 samples can be
    processed per plate). Each plate will contain a negative control
    (water) and a positive control (mock community).

5.  A subset of 12 samples from each plate will undergo electrophoresis
    on a 1% agarose gel to ensure amplification proceeded normally.

6.  Library clean up and normalization performed using the Invitrogen
    [SequalPrep](http://products.invitrogen.com/ivgn/product/A1051001)
    Plate Normalization Kit.

7.  Samples from all plates are pooled.

8.  Library QC includes quantification using a KAPA Biosystems [Q-PCR
    kit](http://www.kapabiosystems.com/products/name/kapa-library-quant-kits)
    cat\# KK4824, and obtaining a Bioanalyzer trace using the [Agilent
    Technologies HS DNA
    kit](http://www.genomics.agilent.com/CollectionSubpage.aspx?PageType=Product&SubPageType=ProductDetail&PageID=1635)
    cat\# 5067-4626.

9.  Library enters the Sequencing Workflow.

***1.3) Sequencing Workflow***

1.  The technician will review all documentation including the sample
    sheet. The sample sheet will be transferred to the instrument. The
    Technician will consult with the investigator to choose an
    appropriate amount of DNA to load for optimal cluster density and
    ensure optimum data quality/quantity.

2.  The reagent cartridge will be thawed in a water bath per the [MiSeq
    User
    Guide](http://supportres.illumina.com/documents/documentation/system_documentation/miseq/miseq-system-user-guide-15027617-l.pdf).

3.  Unless otherwise specified, dilution and loading will follow the
    steps outlined in the document:

Preparing DNA Libraries for Sequencing on the MiSeq[ (15039740
C)](http://supportres.illumina.com/documents/documentation/system_documentation/miseq/preparing_libraries_for_miseq_15039740_c.pdf)

1.  Any custom primers required (including those for 16S) will be mixed
    with the native primers on the reagent cartridge.

2.  The technician will load the sample sheet, flow cell, reagent
    cartridge, PR2 bottle, and an empty waste bottle onto the MiSeq and
    start the run. A 500 cycle run takes approx. 44 hours.

3.  The technician will monitor the run using Illumina Sequence Analysis
    Viewer.

4.  The data will be stored on the Schloss Lab NAS drive and made
    available to the investigator following run completion. Unless
    otherwise requested, default output will be fastq files.

5.  Technician will perform a post run wash and any required maintenance
    of instrument.

  ------------------------------------
  **2.0) Safety and Waste Disposal**
  ------------------------------------

-   The Schloss Lab Chemical Hygiene Plan should be followed at all
    times.

-   Standard PPE (nitrile gloves, safety glasses, and lab coat) should
    be used at all times.

-   Each reagent cartridge contains a small amount of formamide and must
    be disposed of in an appropriate container following the run. Liquid
    waste from a run must also be disposed of as hazardous due to the
    formamide content.

-   All other safety concerns may be addressed to the lab chemical
    safety officer.

  ----------------------
  **3.0) Consumables**
  ----------------------

  Reagent/Kit                                             Catalog \#    Price
  ------------------------------------------------------- ------------- -----------
  MiSeq® Reagent Kit v2 (500 cycle)                       MS-102-2003   \$910.80
  PhiX Control Kit v3                                     FC-110-3001   \$132.00
  16s Index Primers (40 total)                            IDT           \$1180.00
  16s Sequencing Primers (Read 1, Index, Read 2)          IDT           \$41.71
  AccuPrime™ Pfx SuperMix 200rxns                         12344-040     \$331.28
  Agilent High Sensitivity DNA Kit                        5067-4626     \$434.70
  Library Quantification Kit - Illumina/Universal         KK4824        \$575.00
  SequalPrep™ Normalization Plate (96) Kit                A10510-01     \$453.60
  epT.I.P.S. Motion 1-50 uL Reloads 24 racks of 96 tips   30014421      \$190.00
  Tip One Refill Wafers 200uL elongated graduated         NC9549602     \$39.24
  Tip One Refill Wafers 1000uL graduated                  1111-2721     \$25.25
  Fisher 1N NaOH 1L                                       SS266-1       \$46.32
  TWIN.TEC 96 Well Plate Skirted Blue                     E951020460    \$99.23

  --------------------
  **4.0) Run Costs**
  --------------------

  For 384 sample run   PCR and Indexing   Cleanup Pooling & Normalization   Library QC   Sequencing   Totals   Total Cost with Man Hours   Duration (days)
  -------------------- ------------------ --------------------------------- ------------ ------------ -------- --------------------------- -----------------
  16S Reagents         \$588              \$265                             \$138        \$941        \$1932   \$2,232                     4.5 days
  16S Man hours        4                  3                                 4            4            15                                   

  --------------------
  **5.0) Method(s)**
  --------------------

***5.1) Published Protocols***

-   The following methods and references are used in the workflows
    above.

    -   [MiSeq User
        Guide](http://supportres.illumina.com/documents/documentation/system_documentation/miseq/miseq-system-user-guide-15027617-l.pdf)
        Rev. L

    -   Preparing DNA Libraries for Sequencing on the MiSeq[ (15039740
        C)](http://supportres.illumina.com/documents/documentation/system_documentation/miseq/preparing_libraries_for_miseq_15039740_c.pdf)

    -   Kapa Biosystems Q-PCR Library [Quantification
        Kit](http://www.kapabiosystems.com/public/pdfs/kapa-library-quant-kits/KAPA_Library_Quantification_Illumina_TDS.pdf)
        Illumina

    -   Accuprime Pfx [Super
        Mix](http://tools.invitrogen.com/content/sfs/manuals/accuprimepfxsupermix_man.pdf)

    -   Agilent High Sensitivity DNA Kit Guide

    -   SequalPrep Normalization Plate (96) Kit

***5.2) Working Protocols***

-   A Detailed protocol for the 16S workflow can be found in Appendix A.

  ------------------------
  **6.0) Data Analysis**
  ------------------------

***6.1) During Run***

-   The Technician will monitor the run using Illumina Sequence Analysis
    Viewer.

-   To asses run quality, the technician will review the following data:
    cluster density, clusters passing filter, data yield, Q30 Score,
    intensity, corrected intensity, % base composition, % aligned,
    reads, reads passing filter, and indices identified following index
    reads.

-   The tolerances for the preceding data are run type dependent. The
    investigator will consult the technician prior to the run to
    determine these values.

***6.2) Post Run***

-   The default repository for run data is the “runs” folder on the
    Schloss Lab NAS Drive.

-   Investigators wishing for personal copies of fastq files must
    provide the technician with storage media.

-   The investigator will determine whether sufficient coverage and
    quality have been achieved or if there is a need for re-sequencing,
    and notify the technician immediately.

-   It is recommended that investigators use
    [mothur](http://www.mothur.org/) for fastq analysis.

  Version   Date        Change                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               Reason
  --------- ----------- ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ ---------------------------------------------------------------
  1.0       3/18/2013   SOP Created                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          N/A
  2.0       5/16/2013   Note about software update added to Appendix B. Updated linked Illumina Documents to current versions section 2.3 and 6.1. Removed Ampure link section 6.1. Updated consumables to reflect new prices and added pcr plates section 4.0. Adjusted man-hours calculations and run cost section 5.0. Eliminate Hardcoding language section 2.3.5. Corrected nM to uM Appendix A Initial Set Up lines 1 and 2, added reference to Appendix B, and eliminated hardcoding language substituting with current guidelines line 7. Under Appendix A PCR Program changes penultimate step to 72C 10:00. Appendix A Sequencing removed former line 3, which was a check to ensure hardcoding was in use; line 9 edited to reflect current NaOH practice; line 11 edited to reflect changes resulting from software update. Section 7.1 bullet 2 added reads and reads passing filter. Section 7.2 bullet 3 added note about technician notification. Appendix A Cleanup Normalization and Pooling line 8 changed to create pool from each plate. Use 5ul instead of 3ul. Appendix A Library QC line 1 eliminated 1:20 and 1:40 dilutions, changed to “each” pool; line 2j adjusted to load 4 plate pools on Bioanalyzer chip, line 3ki added “from Bioanalyzer”, and added line 4. Appendix A Run Monitoring line 2 eliminated hardcoding language and adjusted expected parameters reflecting lower PhiX. Removed % base composition target.   MiSeq software update, general corrections, new price quotes.
  2.1       10/3/2013   Initial Setup 1 added “and sequencing primers”. 2 added “do not dilute seq. primers”. 6 added note on primer plate A. Sequencing 5 added “the 100 uM”.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               Clarity
  3.0       12/4/2013   Updated Illumina guides to current revision. Appendix A: Changed Sequencing 11 to show 4.0pM load. Added footnote about low concentration libraries Sequencing 9. Added info about v3 reagent kits to Sequencing 11 and Run Monitoring.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              v3 kit, change standard load conc.
  4.0       8/11/14     Deleted Appendix on Hardcoding for 1previous MiSeq software versions.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                

  -------------------------
  **8.0) Change Control**
  -------------------------

  --------------------------
  **9.0) Signature Block**
  --------------------------

Written
By:\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_
Date: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

Reviewed and Approved
By:\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_
Date: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

***Appendix A***

Detailed 16S Protocol

***Initial Set up***

1.  Reconstitute indexed primers and sequencing primers to 100 uM. See
    Appendix D for primer design.

2.  Prepare 100ul 10 uM aliquots of indexed primers. Do not dilute
    sequencing primers.

3.  Array aliquots into four 96 well plates. Use the following scheme:

    a.  A701 – A712 with A501 – A508

    b.  A701 – A712 with B501 – B508

    c.  B701 – B712 with B501 – B508

    d.  B701 – B712 with A501 – A508

4.  Extract template DNA and array in 96 well format leaving two wells
    open. (One for a negative water control and another for the positive
    Mock Community control)

5.  Using Illumina Experiment Manager, create a sample plate for each 96
    well plate of template. Choose indexes that correspond to one of the
    four index pair plates above. See Appendix C for instruction on
    creating a custom assay in IEM.

6.  Using Illumina Experiment Manager, create a sample sheet for the
    run. Ensure that index choices are compatible with one another and
    there is sufficient diversity in the index reads so as to activate
    both light channels every cycle. Note: Primer plate A has
    insufficient diversity to be run alone. If sequencing 96 or fewer
    samples, choose plate B, C, or D.

7.  The MiSeq requires base diversity on every cycle. 16S is a low
    diversity library. With MiSeq software v2.2, 16S libraries can be
    loaded with 5% PhiX. Additionally, other high diversity samples such
    as metagenomes can be run simultaneously. This requires manually
    editing the sample sheet. Older software versions required
    “hardcoding” the matrix and phasing/pre-phasing values. See Appendix
    B.

***PCR***

Note: These steps may be performed using an epMotion or similar
automated pipetting system.

1.  Dispense 17 ul of Accuprime Pfx Supermix into each well of a new 96
    well plate.

2.  Using a multichannel pipette, transfer 1 ul of template DNA per well
    to the corresponding well on the PCR plate.

3.  Using a multichannel pipette, transfer 2 ul of each paired set of
    index primers to the corresponding well on the PCR plate. Be sure to
    follow the layout chosen in the sample sheet.

4.  Add 1 ul of PCR grade dH~2~O to the negative control well, and 1 ul
    of Mock Community at a 1:3 dilution to the positive control well.

5.  Repeat for up to four 96 well plates. Seal plates, vortex briefly
    and spin down contents.

6.  Place in thermocycler.

***PCR Program***

Use the following program:

> 95C 2:00\
> --------30 cycles--------
>
> 95C 00:20\
> 55C 00:15\
> 72C 5:00
>
> ----------------------------
>
> 72C 10:00\
> 4C  end

***Gel Electrophoresis***

1.  A random row of 12 should be selected from each PCR plate and run on
    a gel to confirm success of the PCR.

2.  Use 2 ul of sample, 4 ul of loading dye in a 1% agarose gel.

3.  Run at 100v for 30 minutes alongside a standard ladder.

4.  Photograph gel under UV. Check to be sure there is a band for every
    well.

***Cleanup, Normalization, and Pooling***

Use the SequalPrep Normalization Plate Kit

1.  Transfer 18 ul of PCR product from PCR plate to corresponding well
    on the normalization plate.

2.  Add 18 ul of Binding Buffer. Mix by pipetting, sealing, vortexing,
    and spinning briefly.

3.  Incubate at room temperature for 60 minutes. Note: can incubate
    overnight if needed. Extra time does not improve results.

4.  Aspirate the liquid from the wells. Do not scrape the sides.

5.  Add 50 ul of Wash Buffer and pipette up and down twice, then
    aspirate immediately. Ensure there is no residual wash buffer in any
    wells.

6.  Add 20 ul of Elution Buffer. Mix by pipetting up and down 5 times.
    Seal, vortex, and spin briefly.

7.  Incubate at room temperature for 5 minutes.

8.  Create a pool from each plate. Take 5 ul of each well to pool. The
    use of an empty 96 well plate may facilitate the use of multichannel
    pipettes.

9.  Freeze the remaining sample for later use.

***Library QC***

1.  Prepare the following dilutions of each pooled library in PCR grade
    H~2~O:

    a.  1:1

    b.  1:10

    c.  1:1000 (dilute in several steps for better results)

    d.  1:2000

    e.  1:4000

2.  Agilent Bioanalyzer Trace

    a.  Prepare Gel-Dye mix if not already prepared.

    b.  Let reagents equilibrate to room temperature.

    c.  Turn Bioanalyzer on and load 350 ul of dH~2~O onto electrode
        cleanser and place in analyzer for 5 minutes.

    d.  Open a high sensitivity chip and place on the priming station.
        Base plate should be a position “C” and syringe clip should be
        at lowest position.

    e.  Load 9.0 ul of gel-dye mix to position 12 market with a large
        “G”. Ensure the syringe plunger is at 1.0 ml and close the
        station. Press plunger until it is held by clip.

    f.  Wait for exactly 60 seconds then release the plunger clip. Wait
        an additional 5 seconds, then slowly pull the plunger back to
        the 1.0 ml position.

    g.  Open the priming station. Pipette 9.0 ul of gel-dye mix into the
        other wells marked “G” in positions 4,8,and 16.

    h.  Pipette 5.0 ul of marker to all wells excluding the right
        column. (No marker positions 4,8,12, and 16)

    i.  Load 1 ul of ladder into position 15 marked by the ladder
        symbol.

    j.  Pipette 1 ul of each of dilutions a – b above. Top row Plate 1
        Pool 1:1 x 1, 1:10 x 2. Second row Plate 2 pool 1:1 x 1, 1:10 x
        2. Third row Plate 3 Pool 1:1 x 1, 1:10 x 2. Bottom row Plate 4
        Pool 1:1 x 1, 1:10 x 2.

    k.  Place chip in the designated vortex for 1 minute, then transfer
        chip to the Bioanalyzer.

    l.  Open the 2100 Expert software and select the HS DNA Assay. Enter
        sample names/dilutions for each of the test wells. Click Start.

    m.  Print .pdf when run finishes.

3.  Kapa Q-PCR Library Quantification

    a.  Before Q-PCR reaction setup, add 1 ml Primer Premix (10X) to the
        5 ml bottle of KAPA SYBR® FAST Q-PCR Master Mix (2X) and mix by
        vortexing for 10 sec. Record the date of Primer Premix addition
        on the KAPA SYBR® FAST Q-PCR Master Mix bottle.

    b.  Reaction can be either 10 ul or 20 ul. A 10 ul reaction volume
        is recommended.

    c.  Prepare a 96 well Q-PCR plate compatible with the real time
        thermocycler. There are six standards. Each should be run in
        triplicate. Each pool at each dilution should be run in
        triplicate.

    d.  For 10 ul reaction volume dispense 6 ul of master mix into each
        well needed.

    e.  Pipette 4 ul of standards and library dilutions into appropriate
        wells. Mix by pipetting. Vortex and spin optional.

    f.  Place plate in thermocycler. Start control software

    g.  Program the following cycle

        i.  Initial Activation 95 °C 5 minutes

        ii. 35 cycles

            1.  Denaturation 95 °C 30 seconds

            2.  Annealing 60 °C 45 seconds

            3.  If library fragment size exceeds 700bp, extend annealing
                step to 90 seconds.

        iii. Perform melt curve to check for primer/adaptor dimer

    h.  Assign wells and group replicates.

    i.  Enter values for standards

        i.  Std. 1 20pM

        ii. Std. 2 2pM

        iii. Std. 3 0.2pM

        iv. Std. 4 0.02pM

        v.  Std. 5 0.002pM

        vi. Std. 6 0.0002pM

        vii. Note: The concentrations provided here are for the DNA
            Standards as supplied in the kit, and are NOT the
            concentrations in the reactions. Provided that the volume of
            template added to each reaction is the same for Standards
            and for library samples (i.e. 4 ul in each case), there is
            no need to account for these volumes when calculating the
            concentrations of library samples, nor should one need to
            calculate the concentration of template in the reaction.

    j.  Run program

    k.  To calculate library concentration use the following formula:

        i.  Average x (452/Avg fragment length from bioanalyzer) x
            dilution factor

        ii. Use the average of the triplicate data points corresponding
            to the most concentrated library DNA dilution that falls
            within the dynamic range of the DNA Standards to calculate
            the concentration of the undiluted library.

        iii. Do not include outliers in calculation. If there is more
            than one outlier in a group, the assay must be repeated.

4.  Create normalized pools from each plate by diluting to the
    concentration of the least concentrated plate. Create a single final
    pool by adding equal amounts of each post qpcr normalized pool.
    Final pool must be \>10ul in total volume. 40-80ul is ideal.

***Sequencing***

1.  Remove a 500 cycle reagent cartridge from the -20 **°**C freezer.
    Place in room temperature water bath for one hour. Place HT1 buffer
    tube in 4 **°**C fridge.

2.  Copy sample sheet to sample sheet folder on MiSeq. Rename sample
    sheet to match barcode of reagent cartridge.

3.  When the reagent cartridge has thawed, dry bottom with paper towel.
    Invert the cartridge repeatedly to check each well is thawed. This
    also serves to mix the reagents. Place in hood.

4.  Thaw library, PhiX, and sequencing primers. Check to make sure HT1
    is thawed.

5.  Place 3 ul of the 100 uM Read 1 Sequencing Primer(s) into a clean
    PCR tube. Repeat in separate tubes for the Index Primer(s) and Read
    2 Sequencing Primer(s).

6.  Using a 1000 ul pipette tip, break the foil over wells 12, 13, 14,
    and 17.

7.  Use an extra long 100 ul tip with the pipettor set on 75 ul to
    transfer the 3 ul of Read 1 Sequencing Primer to the bottom of well
    12 and pipette 10X to mix. Repeat this process spiking the Index
    Primer into well 13 and the Read 2 Sequencing Primer into well 14.

8.  Prepare a fresh dilution of 0.2N NaOH.

9.  To a 1.5ml tube add 10 ul of library, and 10 ul of 0.2N NaOH. To a
    separate tube add 2 ul PhiX, 3 ul PCR grade water, and 5 ul of 0.2N
    NaOH. Vortex both tubes to mix and spin for 1 minute at 400rcf.
    Note: NaOH concentration on the flow cell must remain under 0.001N.
    Adjusting the concentration of the NaOH used to denature the DNA to
    0.1N may be necessary if library concentration is 1nM or below.[^1]

10. Allow the tubes to incubate at room temperature for 5 minutes.
    Immediately add 980 ul of HT1 to the library tube, and 990 ul HT1 to
    the PhiX tube.

11. Use HT1 to dilute both the library and PhiX to 4pM for a v2 kit. Can
    load up to 8pM for a v3 kit. For a 10% PhiX run, combine 900 ul of
    4.0pM Library and 100 ul PhiX in a final tube. Vortex. Load 600 ul
    of this solution into well 17 on the reagent cartridge. See example
    below:

    a.  (1.45 nM library x 10 ul) + (0.2N NaOH x 10 ul) + 980 ul HT1 =
        14.5pM Lib, 0.002N NaOH

    b.  (14.5pM lib x 275.86 ul) + 724.14 ul HT1 = 4.0pM lib, 0.00055N
        NaOH

    c.  [(10nM PhiX x 2 ul) + 3 ul H~2~O] + (0.2N NaOH x 5 ul) + 990 ul
        HT1 = 20pM PhiX, 0.001N NaOH

    d.  (20pM PhiX x 200 ul) + 800 ul HT1 = 4.0pM PhiX, 0.0002N NaOH

    e.  (4.0pM Lib x 900 ul) + (4.0pM PhiX x 100 ul) = solution loaded

    f.  Solution loaded is 4.0pM overall with a 3.6pM Library
        concentration, 0.4pM PhiX concentration, and 0.000515N NaOH

<!-- -->

13. Set reagent cartridge aside. Unbox flow cell and PR2 bottle.

14. Thoroughly rinse the flow cell with Milli-Q water. Carefully dry by
    blotting with lint free wipes (Kimwipes). Give special attention to
    the edges and points of intersection between the glass and plastic.

15. Wet a new wipe with 100% alcohol and wipe the glass on both sides
    avoiding the rubber intake ports.

16. Visually inspect the flow cell to ensure there are no blemishes,
    particles, or fibers on the glass.

17. Follow on screen instructions and load the flow cell, reagent
    cartridge, and PR2 bottle. Empty and replace the waste bottle.

18. Ensure the machine recognizes the correct sample sheet and the run
    parameters are correct.

19. Wait for the MiSeq to perform its pre-run checks, and press start.

***Run Monitoring***

1.  The run should be monitored periodically using Illumina Sequence
    Analysis Viewer.

2.  Ideal parameters for a 90% 16S run:

    a.  Cluster density 700-800k/mm2 for v2 kits

    b.  Cluster density 1000-1100k/mm2 for v3 kits

    c.  \>85% clusters passing filter

    d.  10% aligned (amount of PhiX)

    e.  No spikes in corrected intensity plot

    f.  All indices identified following index reads

    g.  Final \>Q30 score of \>70%

***Final Steps***

1.  Perform post run wash.

2.  Dispose of liquid waste in appropriate hazardous jug and reagent
    cartridge in hazardous bucket.

3.  When MiSeq Reporter finishes, copy the fastq files from the analysis
    folder to the run folder on the NAS drive.

4.  Perform maintenance wash if required.

5.  Confirm with investigator that data are of sufficient quality and
    quantity.

***Appendix B***

Adding An Assay To Illumina Experiment Manager

Introduction

Illumina Experiment Manager is used to generate sample plates and
sheets. A new assay must be added to the system to efficiently prepare
sample sheets for 16S sequencing. Not only does this eliminate the need
to manually assemble a sample sheet for 16S runs, but allows the user to
retain use of the IEM index analysis feature. This ensures the indices
selected for a particular run have sufficient diversity on a
cycle-by-cycle basis and will successfully demultiplex.

Procedure

1.  Open C:\\program files\\Illumina\\Illumina Experiment
    Manager\\Sample Prep Kits

2.  Copy the file Nextera.txt, and rename the file Schloss.txt

3.  Open in a text editor

4.  Under [Name] change to Schloss

5.  Under [PlateExtension] change to Schloss

6.  Under [I7], clear the Nextera indices and paste in the SA701 through
    SB712 index names, and the REVERSE COMPLIMENT of the primer index
    sequences.

7.  Under [I5], remove the Nextera indices and paste in the SA501
    through SB512 index names and index sequences with no alteration
    (NOT the reverse compliment).

8.  Under [DefaultLayout\_SingleIndex] and [DefaultLayout\_DualIndex]
    each well of a 96 well plate is listed with a corresponding Nextera
    index name. These must be replaced with Schloss index names. It is
    recommended that a text editor with column select capability be used
    to leave the index name number unchanged (i.e. 701, 702, etc.),
    while replacing the character ”N” for Nextera with “SA” for Schloss
    A.

9.  Save and close.

10. Return to the IEM folder and open the Applications folder. Open and
    edit the file GenerateFASTQ.txt.

11. Add a line at to the bottom with the text “Schloss”

***Appendix C***

Primer design

Overall design considerations

-   The sequencing primers must have a melting temperature near 65°C.
    This can be achieved by altering the pad sequence

-   The index sequences must balance the number of bases at each
    position. The index sequences listed here have a 25% ATGC
    composition at each site. If you are going to cherry pick indices
    from the list, make sure that you have even representation.

Generic PCR primer design:

AATGATACGGCGACCACCGAGATCTACAC \<i5\>\<pad\>\<link\>\<16Sf\> VX.N5??

CAAGCAGAAGACGGCATACGAGAT \<i7\>\<pad\>\<link\>\<16Sr\> VX.N7??

Generic read 1 primer design

\<pad\>\<link\>\<16Sf\> VX.read1

Generic read 2 primer design

\<pad\>\<link\>\<16Sr\> VX.read2

Generic index read primer design

Reverse complement of (\<pad\>\<link\>\<16Sr\>) VX.p7\_index

The listed sequences in the generic design, above, are the adapter
sequences to allow annealing of the amplicons to the flow cell. The i5
and i7 sequences are the 8-nt index sequences. The pad is a 10-nt
sequence to boost the sequencing primer melting temperatures. The link
is a 2-nt sequence that is anti-complementary to the known sequences.
The 16Sf and 16Sr are the gene specific primer sequences. Primers are
purchased from IDT with no special purification. This system should work
for any other region of the 16S rRNA gene or any other gene. The only
thing to change would be the 16Sf/16Sr sequences and confirm that when
combined with the pad sequence that the melting temperature is near
65°C.

16Sf

V3: CCTACGGGAGGCAGCAG

V4: GTGCCAGCMGCCGCGGTAA

16Sr

V4: GGACTACHVGGGTWTCTAAT

V5: CCCGTCAATTCMTTTRAGT

Link:

V4f: GT

V4r: CC

V3f: GG

V5r: GG

Pad:

Forward: TATGGTAATT

Reverse: AGTCAGTCAG

i5

SA501 ATCGTACG

SA502 ACTATCTG

SA503 TAGCGAGT

SA504 CTGCGTGT

SA505 TCATCGAG

SA506 CGTGAGTG

SA507 GGATATCT

SA508 GACACCGT

SB501 CTACTATA

SB502 CGTTACTA

SB503 AGAGTCAC

SB504 TACGAGAC

SB505 ACGTCTCG

SB506 TCGACGAG

SB507 GATCGTGT

SB508 GTCAGATA

SC501 ACGACGTG

SC502 ATATACAC

SC503 CGTCGCTA

SC504 CTAGAGCT

SC505 GCTCTAGT

SC506 GACACTGA

SC507 TGCGTACG

SC508 TAGTGTAG

SD501 AAGCAGCA

SD502 ACGCGTGA

SD503 CGATCTAC

SD504 TGCGTCAC

SD505 GTCTAGTG

SD506 CTAGTATG

SD507 GATAGCGT

SD508 TCTACACT

i7

SA701 AACTCTCG

SA702 ACTATGTC

SA703 AGTAGCGT

SA704 CAGTGAGT

SA705 CGTACTCA

SA706 CTACGCAG

SA707 GGAGACTA

SA708 GTCGCTCG

SA709 GTCGTAGT

SA710 TAGCAGAC

SA711 TCATAGAC

SA712 TCGCTATA

SB701 AAGTCGAG

SB702 ATACTTCG

SB703 AGCTGCTA

SB704 CATAGAGA

SB705 CGTAGATC

SB706 CTCGTTAC

SB707 GCGCACGT

SB708 GGTACTAT

SB709 GTATACGC

SB710 TACGAGCA

SB711 TCAGCGTT

SB712 TCGCTACG

SC701 ACCTACTG

SC702 AGCGCTAT

SC703 AGTCTAGA

SC704 CATGAGGA

SC705 CTAGCTCG

SC706 CTCTAGAG

SC707 GAGCTCAT

SC708 GGTATGCT

SC709 GTATGACG

SC710 TAGACTGA

SC711 TCACGATG

SC712 TCGAGCTC

SD701 ACCTAGTA

SD702 ACGTACGT

SD703 ATATCGCG

SD704 CACGATAG

SD705 CGTATCGC

SD706 CTGCGACT

SD707 GCTGTAAC

SD708 GGACGTTA

SD709 GGTCGTAG

SD710 TAAGTCTC

SD711 TACACAGT

SD712 TTGACGCA

Primers used to amplify 384 samples using the V4 region:

v4.SA501
AATGATACGGCGACCACCGAGATCTACACATCGTACGTATGGTAATTGTGTGCCAGCMGCCGCGGTAA

v4.SA502
AATGATACGGCGACCACCGAGATCTACACACTATCTGTATGGTAATTGTGTGCCAGCMGCCGCGGTAA

v4.SA503
AATGATACGGCGACCACCGAGATCTACACTAGCGAGTTATGGTAATTGTGTGCCAGCMGCCGCGGTAA

v4.SA504
AATGATACGGCGACCACCGAGATCTACACCTGCGTGTTATGGTAATTGTGTGCCAGCMGCCGCGGTAA

v4.SA505
AATGATACGGCGACCACCGAGATCTACACTCATCGAGTATGGTAATTGTGTGCCAGCMGCCGCGGTAA

v4.SA506
AATGATACGGCGACCACCGAGATCTACACCGTGAGTGTATGGTAATTGTGTGCCAGCMGCCGCGGTAA

v4.SA507
AATGATACGGCGACCACCGAGATCTACACGGATATCTTATGGTAATTGTGTGCCAGCMGCCGCGGTAA

v4.SA508
AATGATACGGCGACCACCGAGATCTACACGACACCGTTATGGTAATTGTGTGCCAGCMGCCGCGGTAA

v4.SB501
AATGATACGGCGACCACCGAGATCTACACCTACTATATATGGTAATTGTGTGCCAGCMGCCGCGGTAA

v4.SB502
AATGATACGGCGACCACCGAGATCTACACCGTTACTATATGGTAATTGTGTGCCAGCMGCCGCGGTAA

v4.SB503
AATGATACGGCGACCACCGAGATCTACACAGAGTCACTATGGTAATTGTGTGCCAGCMGCCGCGGTAA

v4.SB504
AATGATACGGCGACCACCGAGATCTACACTACGAGACTATGGTAATTGTGTGCCAGCMGCCGCGGTAA

v4.SB505
AATGATACGGCGACCACCGAGATCTACACACGTCTCGTATGGTAATTGTGTGCCAGCMGCCGCGGTAA

v4.SB506
AATGATACGGCGACCACCGAGATCTACACTCGACGAGTATGGTAATTGTGTGCCAGCMGCCGCGGTAA

v4.SB507
AATGATACGGCGACCACCGAGATCTACACGATCGTGTTATGGTAATTGTGTGCCAGCMGCCGCGGTAA

v4.SB508
AATGATACGGCGACCACCGAGATCTACACGTCAGATATATGGTAATTGTGTGCCAGCMGCCGCGGTAA

v4.SA701
CAAGCAGAAGACGGCATACGAGATAACTCTCGAGTCAGTCAGCCGGACTACHVGGGTWTCTAAT

v4.SA702
CAAGCAGAAGACGGCATACGAGATACTATGTCAGTCAGTCAGCCGGACTACHVGGGTWTCTAAT

v4.SA703
CAAGCAGAAGACGGCATACGAGATAGTAGCGTAGTCAGTCAGCCGGACTACHVGGGTWTCTAAT

v4.SA704
CAAGCAGAAGACGGCATACGAGATCAGTGAGTAGTCAGTCAGCCGGACTACHVGGGTWTCTAAT

v4.SA705
CAAGCAGAAGACGGCATACGAGATCGTACTCAAGTCAGTCAGCCGGACTACHVGGGTWTCTAAT

v4.SA706
CAAGCAGAAGACGGCATACGAGATCTACGCAGAGTCAGTCAGCCGGACTACHVGGGTWTCTAAT

v4.SA707
CAAGCAGAAGACGGCATACGAGATGGAGACTAAGTCAGTCAGCCGGACTACHVGGGTWTCTAAT

v4.SA708
CAAGCAGAAGACGGCATACGAGATGTCGCTCGAGTCAGTCAGCCGGACTACHVGGGTWTCTAAT

v4.SA709
CAAGCAGAAGACGGCATACGAGATGTCGTAGTAGTCAGTCAGCCGGACTACHVGGGTWTCTAAT

v4.SA710
CAAGCAGAAGACGGCATACGAGATTAGCAGACAGTCAGTCAGCCGGACTACHVGGGTWTCTAAT

v4.SA711
CAAGCAGAAGACGGCATACGAGATTCATAGACAGTCAGTCAGCCGGACTACHVGGGTWTCTAAT

v4.SA712
CAAGCAGAAGACGGCATACGAGATTCGCTATAAGTCAGTCAGCCGGACTACHVGGGTWTCTAAT

v4.SB701
CAAGCAGAAGACGGCATACGAGATAAGTCGAGAGTCAGTCAGCCGGACTACHVGGGTWTCTAAT

v4.SB702
CAAGCAGAAGACGGCATACGAGATATACTTCGAGTCAGTCAGCCGGACTACHVGGGTWTCTAAT

v4.SB703
CAAGCAGAAGACGGCATACGAGATAGCTGCTAAGTCAGTCAGCCGGACTACHVGGGTWTCTAAT

v4.SB704
CAAGCAGAAGACGGCATACGAGATCATAGAGAAGTCAGTCAGCCGGACTACHVGGGTWTCTAAT

v4.SB705
CAAGCAGAAGACGGCATACGAGATCGTAGATCAGTCAGTCAGCCGGACTACHVGGGTWTCTAAT

v4.SB706
CAAGCAGAAGACGGCATACGAGATCTCGTTACAGTCAGTCAGCCGGACTACHVGGGTWTCTAAT

v4.SB707
CAAGCAGAAGACGGCATACGAGATGCGCACGTAGTCAGTCAGCCGGACTACHVGGGTWTCTAAT

v4.SB708
CAAGCAGAAGACGGCATACGAGATGGTACTATAGTCAGTCAGCCGGACTACHVGGGTWTCTAAT

v4.SB709
CAAGCAGAAGACGGCATACGAGATGTATACGCAGTCAGTCAGCCGGACTACHVGGGTWTCTAAT

v4.SB710
CAAGCAGAAGACGGCATACGAGATTACGAGCAAGTCAGTCAGCCGGACTACHVGGGTWTCTAAT

v4.SB711
CAAGCAGAAGACGGCATACGAGATTCAGCGTTAGTCAGTCAGCCGGACTACHVGGGTWTCTAAT

v4.SB712
CAAGCAGAAGACGGCATACGAGATTCGCTACGAGTCAGTCAGCCGGACTACHVGGGTWTCTAAT

Read 1 primer for V4 region

TATGGTAATTGTGTGCCAGCMGCCGCGGTAA

Read 2 primer for V4 region

AGTCAGTCAGCCGGACTACHVGGGTWTCTAAT

Index primer for V4 region

ATTAGAWACCCBDGTAGTCCGGCTGACTGACT

[^1]: For extremely low concentration libraries we have adapted a method
    published by Quail et al.
    [http://www.nature.com/nmeth/journal/v5/n12/full/nmeth.1270.html](../customXml/item1.xml)

    Libraries as low as 0.1nM do not allow for sufficient dilution to
    reduce NaOH to 0.001N. It must be neutralized using 200mM Tris pH
    7.0. Example: 40 ul 0.1nM library + 40 ul 0.1N NaOH. Incubate for 5
    min. Add 80 ul 200mM Tris. Then add 840 ul HT1. This results in a
    4.0pM library.