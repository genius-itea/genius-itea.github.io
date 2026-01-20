---
# The title of the publication
title: '{{ replace .File.ContentBaseName "-" " " | title }}'
# The date of the publication. This defines the main sorting of the publication list but is not used otherwise
# Use format yyyy-mm-dd here.
date: '{{ .Date }}'
draft: false
params:
    # The kind of publication.
    # Possible values are within the set [ paper ]
    kind: paper
    authors:
        - Gröpler, R.
        # - Author 2
        # - Author 3
        # - Author 4
    
    # The date of the publication as printed out. This is an arbitrary string. Can be left unset.
    # publicationDate: 'Apr. 12–18, 2026'

    # The name of the book or conference, can be left unset.
    # booktitle: 'Proceedings of the 48th International Conference on Software Engineering (ICSE 2026)'

    publisher: 'IEEE'
    
    # The lcoation of the conference. Can be left unset.
    # location: 'Rio de Janeiro, Brazil'
    
    # The pages in the book or proceedings. Will be automaticall prepended by "pp". Can be left unset.
    # pages: '2-3'

    # The DOI of the publication. Please give only the pure DOI number, not the URL. Can be left unset.
    # doi: ''

    # An arbitrary URL for the publication in case no DOI is present yet. Please provide a full URL starting with http. Can be left unset.
    # url: ''

    # The name of an image file in the current folder to be used as teaser image. This will be scaled to 220x350 px max, so keep its details well visible.
    # If no image is given, an empty placeholder is presented instead.
    # image: ''

    # The name of the file to attach as download (in the same bundle). Can be left unset.
    # download: ''

    # A unique id for later referencing the publication. Can be left unset.
    # This should be a short and easy to type string, e.g. vision-paper.
    # id: ''
---

