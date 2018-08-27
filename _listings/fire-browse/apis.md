---
name: Fire Browse
x-slug: fire-browse
description: A simple and elegant way to explore cancer data. Sitting above one of
  the deepest and most integratively characterized open cancer datasets in the world.
  Backed by a powerful computational infrastructure, application programming interface
  (API), graphical tools and online reports. With over 80K sample aliquots from 11,000+
  cancer patients, spanning 38 unique disease cohorts.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/firebrowse.png
x-kinRank: "7"
x-alexaRank: "0"
tags: Analysis
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/fire-browse/apis.md
specificationVersion: "0.14"
apis:
- name: Fire Browse Beta API - Retrieve all data by genes Gistic2 results.
  x-api-slug: analysescopynumbergenesall-get
  description: 'This service provides access to the Gistic2 all_data_by_genes.txt
    output data. This data is a gene-level table of copy number values for all samples.
    The returned copy number values are in units (copy number - 2) so that no amplification
    or deletion is 0, genes with amplifications have positive values, and genes with
    deletions are negative values. The data are converted from marker level to gene
    level using the extreme method: a gene is assigned the greatest amplification
    or the least deletion value among the markers it covers. Results may be filtered
    by cohort, gene, or barcode, but at least one gene or barcode must be supplied.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/firebrowse.png
  humanURL: http://firebrowse.org
  baseURL: https://firebrowse.org//api/v1
  tags: Cancer, API Provider, Data Provider, Profiles, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/fire-browse/analysescopynumbergenesall-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/fire-browse/analysescopynumbergenesall-get-openapi.md
- name: Fire Browse Beta API - Retrieve Gistic2 significantly amplified genes results.
  x-api-slug: analysescopynumbergenesamplified-get
  description: This service provides access to the Gistic2 amp_genes.conf_99.txt output
    data.  At least 1 gene or cohort must be supplied.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/firebrowse.png
  humanURL: http://firebrowse.org
  baseURL: https://firebrowse.org//api/v1
  tags: Cancer, API Provider, Data Provider, Profiles, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/fire-browse/analysescopynumbergenesamplified-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/fire-browse/analysescopynumbergenesamplified-get-openapi.md
- name: Fire Browse Beta API - Retrieve Gistic2 significantly deleted genes results.
  x-api-slug: analysescopynumbergenesdeleted-get
  description: This service provides access to the Gistic2 del_genes.conf_99.txt output
    data.  At least 1 gene or cohort must be supplied.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/firebrowse.png
  humanURL: http://firebrowse.org
  baseURL: https://firebrowse.org//api/v1
  tags: Cancer, API Provider, Data Provider, Profiles, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/fire-browse/analysescopynumbergenesdeleted-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/fire-browse/analysescopynumbergenesdeleted-get-openapi.md
- name: Fire Browse Beta API - Retrieve focal data by genes Gistic2 results.
  x-api-slug: analysescopynumbergenesfocal-get
  description: 'This service provides access to the Gistic2 focal_data_by_genes.txt
    output data. This output is similar to the all_data_by_genes.txt output, but using
    only focal events with lengths greater than the  focal length cutoff. This data
    is a gene-level table of copy number values for all samples. The returned copy
    number values are in units (copy number - 2) so that no amplification or deletion
    is 0, genes with amplifications have positive values, and genes with deletions
    are negative values. The data are converted from marker level to gene level using
    the extreme method: a gene is assigned the greatest amplification or the least
    deletion value among the markers it covers. Results may be filtered by cohort,
    gene, and/or barcode, but at least one gene or barcode must be supplied.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/firebrowse.png
  humanURL: http://firebrowse.org
  baseURL: https://firebrowse.org//api/v1
  tags: Cancer, API Provider, Data Provider, Profiles, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/fire-browse/analysescopynumbergenesfocal-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/fire-browse/analysescopynumbergenesfocal-get-openapi.md
- name: Fire Browse Beta API - Retrieve all thresholded by genes Gistic2 results.
  x-api-slug: analysescopynumbergenesthresholded-get
  description: 'This service provides access to the Gistic2 all_thresholded_by_genes.txt
    output data. A gene-level table of discrete amplification and deletion indicators
    for all samples. A table value of 0 means no amplification or deletion above the
    threshold. Amplifications are positive numbers: 1 means amplification above the
    amplification threshold; 2 means amplifications larger to the arm level amplifications
    observed for the sample. Deletions are represented by negative table values: -1
    represents deletion beyond the threshold; -2 means deletions greater than the
    minimum arm-level deletion observed for the sample. Results maybe filtered by
    cohort, gene or barcode, but at least one gene or barcode must be supplied.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/firebrowse.png
  humanURL: http://firebrowse.org
  baseURL: https://firebrowse.org//api/v1
  tags: Cancer, API Provider, Data Provider, Profiles, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/fire-browse/analysescopynumbergenesthresholded-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/fire-browse/analysescopynumbergenesthresholded-get-openapi.md
- name: Fire Browse Beta API - Retrieve aggregated analysis features table.
  x-api-slug: analysesfeaturetable-get
  description: This service returns part or all of the so-called feature table; which
    aggregates the most important findings across ALL pipelines in the GDAC Firehose
    analysis workflow into a single table for simple access.  One feature table is
    created per disease cohort.  Results may be filtered by date or cohort, but at
    least 1 cohort must be specified here. For more details please visit the online
    documentation.  Please note that the service is still undergoing experimental
    evaluation and does not return JSON format.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/firebrowse.png
  humanURL: http://firebrowse.org
  baseURL: https://firebrowse.org//api/v1
  tags: Cancer, API Provider, Data Provider, Profiles, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/fire-browse/analysesfeaturetable-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/fire-browse/analysesfeaturetable-get-openapi.md
- name: Fire Browse Beta API - Retrieve MutSig final analysis MAF.
  x-api-slug: analysesmutationmaf-get
  description: This service returns columns from the MAF generated by MutSig. Results
    may be filtered by gene, cohort, tool, or barcode, but at least one gene OR barcode
    OR cohort must be given.  By default a subset consisting of the most commonly
    used columns will be returned, but that can be modified with the column parameter.
    Specifying 'all' in this parameter is a convenient way to return every column
    of the respective MAF, and has precedence over any any other column selection
    expression.  The complete list of column names that may be specified is given
    here.  For more information on the mutation data, and how it is processed by Firehose,
    please consult the pipeline documentation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/firebrowse.png
  humanURL: http://firebrowse.org
  baseURL: https://firebrowse.org//api/v1
  tags: Cancer, API Provider, Data Provider, Profiles, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/fire-browse/analysesmutationmaf-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/fire-browse/analysesmutationmaf-get-openapi.md
- name: Fire Browse Beta API - Retrieve Significantly Mutated Genes (SMG).
  x-api-slug: analysesmutationsmg-get
  description: This service provides a list of significantly mutated genes, as scored
    by MutSig.  It may be filtered by cohort, rank, gene, tool and/or Q-value threshold,
    but at least one cohort or gene must be supplied.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/firebrowse.png
  humanURL: http://firebrowse.org
  baseURL: https://firebrowse.org//api/v1
  tags: Cancer, API Provider, Data Provider, Profiles, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/fire-browse/analysesmutationsmg-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/fire-browse/analysesmutationsmg-get-openapi.md
- name: Fire Browse Beta API - Retrieve links to summary reports from Firehose analysis
    runs.
  x-api-slug: analysesreports-get
  description: This service returns URLs to the analysis result reports for runs of
    the Broad Institute GDAC Firehose analysis pipeline. At least one year of run
    reports are maintained in the database, but the reports from the latest run will
    be returned by default. The set of Nozzle reports returned may be filtered by
    disease cohort, report type and report name.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/firebrowse.png
  humanURL: http://firebrowse.org
  baseURL: https://firebrowse.org//api/v1
  tags: Cancer, API Provider, Data Provider, Profiles, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/fire-browse/analysesreports-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/fire-browse/analysesreports-get-openapi.md
- name: Fire Browse Beta API - Returns RNASeq expression quartiles, e.g. suitable
    for drawing a boxplot.
  x-api-slug: analysesmrnaseqquartiles-get
  description: For a given gene compute quartiles and extrema, suitable e.g. for drawing
    a boxplot (Tukey 1977).  Results may be filtered by cohort, sample type, patient
    barcode  or characterization protocol, and are returned sorted by cohort.  Note
    that samples for which no expression value was recorded (e.g. the melanoma sample
    TCGA-GN-262) are removed prior to calculation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/firebrowse.png
  humanURL: http://firebrowse.org
  baseURL: https://firebrowse.org//api/v1
  tags: Cancer, API Provider, Data Provider, Profiles, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/fire-browse/analysesmrnaseqquartiles-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/fire-browse/analysesmrnaseqquartiles-get-openapi.md
- name: Fire Browse Beta API - Retrieve all data by genes Gistic2 results.
  x-api-slug: analysescopynumbergenesall-get
  description: 'This service provides access to the Gistic2 all_data_by_genes.txt
    output data. This data is a gene-level table of copy number values for all samples.
    The returned copy number values are in units (copy number - 2) so that no amplification
    or deletion is 0, genes with amplifications have positive values, and genes with
    deletions are negative values. The data are converted from marker level to gene
    level using the extreme method: a gene is assigned the greatest amplification
    or the least deletion value among the markers it covers. Results may be filtered
    by cohort, gene, or barcode, but at least one gene or barcode must be supplied.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/firebrowse.png
  humanURL: http://firebrowse.org
  baseURL: https://firebrowse.org//api/v1
  tags: Cancer, API Provider, Data Provider, Profiles, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/fire-browse/analysescopynumbergenesall-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/fire-browse/analysescopynumbergenesall-get-openapi.md
- name: Fire Browse Beta API - Retrieve Gistic2 significantly amplified genes results.
  x-api-slug: analysescopynumbergenesamplified-get
  description: This service provides access to the Gistic2 amp_genes.conf_99.txt output
    data.  At least 1 gene or cohort must be supplied.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/firebrowse.png
  humanURL: http://firebrowse.org
  baseURL: https://firebrowse.org//api/v1
  tags: Cancer, API Provider, Data Provider, Profiles, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/fire-browse/analysescopynumbergenesamplified-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/fire-browse/analysescopynumbergenesamplified-get-openapi.md
- name: Fire Browse Beta API - Retrieve Gistic2 significantly deleted genes results.
  x-api-slug: analysescopynumbergenesdeleted-get
  description: This service provides access to the Gistic2 del_genes.conf_99.txt output
    data.  At least 1 gene or cohort must be supplied.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/firebrowse.png
  humanURL: http://firebrowse.org
  baseURL: https://firebrowse.org//api/v1
  tags: Cancer, API Provider, Data Provider, Profiles, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/fire-browse/analysescopynumbergenesdeleted-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/fire-browse/analysescopynumbergenesdeleted-get-openapi.md
- name: Fire Browse Beta API - Retrieve focal data by genes Gistic2 results.
  x-api-slug: analysescopynumbergenesfocal-get
  description: 'This service provides access to the Gistic2 focal_data_by_genes.txt
    output data. This output is similar to the all_data_by_genes.txt output, but using
    only focal events with lengths greater than the  focal length cutoff. This data
    is a gene-level table of copy number values for all samples. The returned copy
    number values are in units (copy number - 2) so that no amplification or deletion
    is 0, genes with amplifications have positive values, and genes with deletions
    are negative values. The data are converted from marker level to gene level using
    the extreme method: a gene is assigned the greatest amplification or the least
    deletion value among the markers it covers. Results may be filtered by cohort,
    gene, and/or barcode, but at least one gene or barcode must be supplied.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/firebrowse.png
  humanURL: http://firebrowse.org
  baseURL: https://firebrowse.org//api/v1
  tags: Cancer, API Provider, Data Provider, Profiles, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/fire-browse/analysescopynumbergenesfocal-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/fire-browse/analysescopynumbergenesfocal-get-openapi.md
- name: Fire Browse Beta API - Retrieve all thresholded by genes Gistic2 results.
  x-api-slug: analysescopynumbergenesthresholded-get
  description: 'This service provides access to the Gistic2 all_thresholded_by_genes.txt
    output data. A gene-level table of discrete amplification and deletion indicators
    for all samples. A table value of 0 means no amplification or deletion above the
    threshold. Amplifications are positive numbers: 1 means amplification above the
    amplification threshold; 2 means amplifications larger to the arm level amplifications
    observed for the sample. Deletions are represented by negative table values: -1
    represents deletion beyond the threshold; -2 means deletions greater than the
    minimum arm-level deletion observed for the sample. Results maybe filtered by
    cohort, gene or barcode, but at least one gene or barcode must be supplied.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/firebrowse.png
  humanURL: http://firebrowse.org
  baseURL: https://firebrowse.org//api/v1
  tags: Cancer, API Provider, Data Provider, Profiles, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/fire-browse/analysescopynumbergenesthresholded-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/fire-browse/analysescopynumbergenesthresholded-get-openapi.md
- name: Fire Browse Beta API - Retrieve aggregated analysis features table.
  x-api-slug: analysesfeaturetable-get
  description: This service returns part or all of the so-called feature table; which
    aggregates the most important findings across ALL pipelines in the GDAC Firehose
    analysis workflow into a single table for simple access.  One feature table is
    created per disease cohort.  Results may be filtered by date or cohort, but at
    least 1 cohort must be specified here. For more details please visit the online
    documentation.  Please note that the service is still undergoing experimental
    evaluation and does not return JSON format.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/firebrowse.png
  humanURL: http://firebrowse.org
  baseURL: https://firebrowse.org//api/v1
  tags: Cancer, API Provider, Data Provider, Profiles, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/fire-browse/analysesfeaturetable-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/fire-browse/analysesfeaturetable-get-openapi.md
- name: Fire Browse Beta API - Retrieve MutSig final analysis MAF.
  x-api-slug: analysesmutationmaf-get
  description: This service returns columns from the MAF generated by MutSig. Results
    may be filtered by gene, cohort, tool, or barcode, but at least one gene OR barcode
    OR cohort must be given.  By default a subset consisting of the most commonly
    used columns will be returned, but that can be modified with the column parameter.
    Specifying 'all' in this parameter is a convenient way to return every column
    of the respective MAF, and has precedence over any any other column selection
    expression.  The complete list of column names that may be specified is given
    here.  For more information on the mutation data, and how it is processed by Firehose,
    please consult the pipeline documentation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/firebrowse.png
  humanURL: http://firebrowse.org
  baseURL: https://firebrowse.org//api/v1
  tags: Cancer, API Provider, Data Provider, Profiles, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/fire-browse/analysesmutationmaf-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/fire-browse/analysesmutationmaf-get-openapi.md
- name: Fire Browse Beta API - Retrieve Significantly Mutated Genes (SMG).
  x-api-slug: analysesmutationsmg-get
  description: This service provides a list of significantly mutated genes, as scored
    by MutSig.  It may be filtered by cohort, rank, gene, tool and/or Q-value threshold,
    but at least one cohort or gene must be supplied.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/firebrowse.png
  humanURL: http://firebrowse.org
  baseURL: https://firebrowse.org//api/v1
  tags: Cancer, API Provider, Data Provider, Profiles, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/fire-browse/analysesmutationsmg-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/fire-browse/analysesmutationsmg-get-openapi.md
- name: Fire Browse Beta API - Retrieve links to summary reports from Firehose analysis
    runs.
  x-api-slug: analysesreports-get
  description: This service returns URLs to the analysis result reports for runs of
    the Broad Institute GDAC Firehose analysis pipeline. At least one year of run
    reports are maintained in the database, but the reports from the latest run will
    be returned by default. The set of Nozzle reports returned may be filtered by
    disease cohort, report type and report name.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/firebrowse.png
  humanURL: http://firebrowse.org
  baseURL: https://firebrowse.org//api/v1
  tags: Cancer, API Provider, Data Provider, Profiles, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/fire-browse/analysesreports-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/fire-browse/analysesreports-get-openapi.md
- name: Fire Browse Beta API - Returns RNASeq expression quartiles, e.g. suitable
    for drawing a boxplot.
  x-api-slug: analysesmrnaseqquartiles-get
  description: For a given gene compute quartiles and extrema, suitable e.g. for drawing
    a boxplot (Tukey 1977).  Results may be filtered by cohort, sample type, patient
    barcode  or characterization protocol, and are returned sorted by cohort.  Note
    that samples for which no expression value was recorded (e.g. the melanoma sample
    TCGA-GN-262) are removed prior to calculation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/firebrowse.png
  humanURL: http://firebrowse.org
  baseURL: https://firebrowse.org//api/v1
  tags: Cancer, API Provider, Data Provider, Profiles, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/fire-browse/analysesmrnaseqquartiles-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/fire-browse/analysesmrnaseqquartiles-get-openapi.md
- name: Fire Browse Beta API - Returns RNASeq expression quartiles, e.g. suitable
    for drawing a boxplot.
  x-api-slug: analysesmrnaseqquartiles-get
  description: For a given gene compute quartiles and extrema, suitable e.g. for drawing
    a boxplot (Tukey 1977).  Results may be filtered by cohort, sample type, patient
    barcode  or characterization protocol, and are returned sorted by cohort.  Note
    that samples for which no expression value was recorded (e.g. the melanoma sample
    TCGA-GN-262) are removed prior to calculation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/firebrowse.png
  humanURL: http://firebrowse.org
  baseURL: https://firebrowse.org//api/v1
  tags: Cancer, API Provider, Data Provider, Profiles, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/fire-browse/analysesmrnaseqquartiles-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/fire-browse/analysesmrnaseqquartiles-get-openapi.md
- name: Fire Browse Beta API - Retrieve links to summary reports from Firehose analysis
    runs.
  x-api-slug: analysesreports-get
  description: This service returns URLs to the analysis result reports for runs of
    the Broad Institute GDAC Firehose analysis pipeline. At least one year of run
    reports are maintained in the database, but the reports from the latest run will
    be returned by default. The set of Nozzle reports returned may be filtered by
    disease cohort, report type and report name.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/firebrowse.png
  humanURL: http://firebrowse.org
  baseURL: https://firebrowse.org//api/v1
  tags: Cancer, API Provider, Data Provider, Profiles, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/fire-browse/analysesreports-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/fire-browse/analysesreports-get-openapi.md
- name: Fire Browse Beta API - Retrieve Significantly Mutated Genes (SMG).
  x-api-slug: analysesmutationsmg-get
  description: This service provides a list of significantly mutated genes, as scored
    by MutSig.  It may be filtered by cohort, rank, gene, tool and/or Q-value threshold,
    but at least one cohort or gene must be supplied.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/firebrowse.png
  humanURL: http://firebrowse.org
  baseURL: https://firebrowse.org//api/v1
  tags: Cancer, API Provider, Data Provider, Profiles, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/fire-browse/analysesmutationsmg-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/fire-browse/analysesmutationsmg-get-openapi.md
- name: Fire Browse Beta API - Retrieve MutSig final analysis MAF.
  x-api-slug: analysesmutationmaf-get
  description: This service returns columns from the MAF generated by MutSig. Results
    may be filtered by gene, cohort, tool, or barcode, but at least one gene OR barcode
    OR cohort must be given.  By default a subset consisting of the most commonly
    used columns will be returned, but that can be modified with the column parameter.
    Specifying 'all' in this parameter is a convenient way to return every column
    of the respective MAF, and has precedence over any any other column selection
    expression.  The complete list of column names that may be specified is given
    here.  For more information on the mutation data, and how it is processed by Firehose,
    please consult the pipeline documentation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/firebrowse.png
  humanURL: http://firebrowse.org
  baseURL: https://firebrowse.org//api/v1
  tags: Cancer, API Provider, Data Provider, Profiles, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/fire-browse/analysesmutationmaf-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/fire-browse/analysesmutationmaf-get-openapi.md
- name: Fire Browse Beta API - Retrieve aggregated analysis features table.
  x-api-slug: analysesfeaturetable-get
  description: This service returns part or all of the so-called feature table; which
    aggregates the most important findings across ALL pipelines in the GDAC Firehose
    analysis workflow into a single table for simple access.  One feature table is
    created per disease cohort.  Results may be filtered by date or cohort, but at
    least 1 cohort must be specified here. For more details please visit the online
    documentation.  Please note that the service is still undergoing experimental
    evaluation and does not return JSON format.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/firebrowse.png
  humanURL: http://firebrowse.org
  baseURL: https://firebrowse.org//api/v1
  tags: Cancer, API Provider, Data Provider, Profiles, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/fire-browse/analysesfeaturetable-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/fire-browse/analysesfeaturetable-get-openapi.md
- name: Fire Browse Beta API - Retrieve all thresholded by genes Gistic2 results.
  x-api-slug: analysescopynumbergenesthresholded-get
  description: 'This service provides access to the Gistic2 all_thresholded_by_genes.txt
    output data. A gene-level table of discrete amplification and deletion indicators
    for all samples. A table value of 0 means no amplification or deletion above the
    threshold. Amplifications are positive numbers: 1 means amplification above the
    amplification threshold; 2 means amplifications larger to the arm level amplifications
    observed for the sample. Deletions are represented by negative table values: -1
    represents deletion beyond the threshold; -2 means deletions greater than the
    minimum arm-level deletion observed for the sample. Results maybe filtered by
    cohort, gene or barcode, but at least one gene or barcode must be supplied.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/firebrowse.png
  humanURL: http://firebrowse.org
  baseURL: https://firebrowse.org//api/v1
  tags: Cancer, API Provider, Data Provider, Profiles, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/fire-browse/analysescopynumbergenesthresholded-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/fire-browse/analysescopynumbergenesthresholded-get-openapi.md
- name: Fire Browse Beta API - Retrieve focal data by genes Gistic2 results.
  x-api-slug: analysescopynumbergenesfocal-get
  description: 'This service provides access to the Gistic2 focal_data_by_genes.txt
    output data. This output is similar to the all_data_by_genes.txt output, but using
    only focal events with lengths greater than the  focal length cutoff. This data
    is a gene-level table of copy number values for all samples. The returned copy
    number values are in units (copy number - 2) so that no amplification or deletion
    is 0, genes with amplifications have positive values, and genes with deletions
    are negative values. The data are converted from marker level to gene level using
    the extreme method: a gene is assigned the greatest amplification or the least
    deletion value among the markers it covers. Results may be filtered by cohort,
    gene, and/or barcode, but at least one gene or barcode must be supplied.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/firebrowse.png
  humanURL: http://firebrowse.org
  baseURL: https://firebrowse.org//api/v1
  tags: Cancer, API Provider, Data Provider, Profiles, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/fire-browse/analysescopynumbergenesfocal-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/fire-browse/analysescopynumbergenesfocal-get-openapi.md
- name: Fire Browse Beta API - Retrieve Gistic2 significantly deleted genes results.
  x-api-slug: analysescopynumbergenesdeleted-get
  description: This service provides access to the Gistic2 del_genes.conf_99.txt output
    data.  At least 1 gene or cohort must be supplied.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/firebrowse.png
  humanURL: http://firebrowse.org
  baseURL: https://firebrowse.org//api/v1
  tags: Cancer, API Provider, Data Provider, Profiles, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/fire-browse/analysescopynumbergenesdeleted-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/fire-browse/analysescopynumbergenesdeleted-get-openapi.md
- name: Fire Browse Beta API - Retrieve Gistic2 significantly amplified genes results.
  x-api-slug: analysescopynumbergenesamplified-get
  description: This service provides access to the Gistic2 amp_genes.conf_99.txt output
    data.  At least 1 gene or cohort must be supplied.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/firebrowse.png
  humanURL: http://firebrowse.org
  baseURL: https://firebrowse.org//api/v1
  tags: Cancer, API Provider, Data Provider, Profiles, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/fire-browse/analysescopynumbergenesamplified-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/fire-browse/analysescopynumbergenesamplified-get-openapi.md
- name: Fire Browse Beta API - Retrieve all data by genes Gistic2 results.
  x-api-slug: analysescopynumbergenesall-get
  description: 'This service provides access to the Gistic2 all_data_by_genes.txt
    output data. This data is a gene-level table of copy number values for all samples.
    The returned copy number values are in units (copy number - 2) so that no amplification
    or deletion is 0, genes with amplifications have positive values, and genes with
    deletions are negative values. The data are converted from marker level to gene
    level using the extreme method: a gene is assigned the greatest amplification
    or the least deletion value among the markers it covers. Results may be filtered
    by cohort, gene, or barcode, but at least one gene or barcode must be supplied.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/firebrowse.png
  humanURL: http://firebrowse.org
  baseURL: https://firebrowse.org//api/v1
  tags: Cancer, API Provider, Data Provider, Profiles, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/fire-browse/analysescopynumbergenesall-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/fire-browse/analysescopynumbergenesall-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://factual.api.gallery.streamdata.io
- type: x-api-stack
  url: http://fire.browse.stack.network
- type: x-website
  url: http://firebrowse.org
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---